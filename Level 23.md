## Bandit Level 22 → Level 23

### Objective
Find the password for Bandit Level 23 by analyzing a cron job that generates a file name using an MD5 hash.

### Commands Executed
- `ls /etc/cron.d`
- `cat /etc/cron.d/cronjob_bandit23`
- `cat /usr/bin/cronjob_bandit23.sh`
- `echo I am user bandit23 | md5sum | cut -d ' ' -f 1`
- `cat /tmp/8ca319486bfbc3663ea0fbe81326349`

### Explanation
- Listed cron jobs to locate the one for Bandit Level 23.
- Read the cron job configuration to identify the script being executed.
- Inspected the script to understand how the password file name is generated.
- Reproduced the MD5 hash used by the script to determine the filename.
- Read the corresponding file in `/tmp` to obtain the password.

### Password

`0Zf11ioIjMVN551jX3CmStKLYqjk54Ga`




<img width="968" height="208" alt="image" src="https://github.com/user-attachments/assets/86f334b5-be34-4b85-a495-564dd57361b8" />
