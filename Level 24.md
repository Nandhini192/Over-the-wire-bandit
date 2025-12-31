## Bandit Level 23 → Level 24

### Objective
Retrieve the password for Bandit Level 24 by exploiting a writable cron job script location.

### Commands Executed
- `ls /etc/cron.d`
- `cat /etc/cron.d/cronjob_bandit24`
- `cat /usr/bin/cronjob_bandit24.sh`
- `cd /tmp`
- `rm myscript`
- `mkdir myscript`
- `cd myscript`
- `nano getpass.sh`
- `chmod +x getpass.sh`
- `cat /tmp/bandit24_pass`

### Explanation
- Identified the cron job running as Bandit Level 24.
- Reviewed the script executed by cron to find an exploitable path.
- Created a custom script in `/tmp` to capture the password.
- Made the script executable so cron could run it.
- Read the output file containing the password.

### Password

`gb8KRRCsshuZXI0tUuR6ypOFjiZbf3G8`



<img width="970" height="486" alt="image" src="https://github.com/user-attachments/assets/7a3f9f69-65b3-4858-afae-81587d5be516" />
