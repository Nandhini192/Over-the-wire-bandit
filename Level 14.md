## Bandit Level 13 → Level 14

### Objective
Log in to Bandit Level 14 using an SSH private key and retrieve the password.

### Commands Executed
- `scp -P 2220 bandit13@bandit.labs.overthewire.org:sshkey.private .`
- `chmod 600 sshkey.private`
- `ssh -i sshkey.private bandit14@bandit.labs.overthewire.org -p 2220`
- `cat /etc/bandit_pass/bandit14`

### Explanation
- Used `scp` to securely copy the private SSH key from the remote server.
- Updated file permissions with `chmod 600` to secure the private key.
- Logged in to Bandit Level 14 using SSH key authentication.
- Read the password file for the next level.

### Password

`MU4WeTyJk8R0of1qqmcBPaLh7lDCPvS`



<img width="987" height="385" alt="image" src="https://github.com/user-attachments/assets/096a2e3b-3b0b-4261-8eb0-60abb8ee9dbc" />





<img width="997" height="726" alt="image" src="https://github.com/user-attachments/assets/b1817234-6a3e-405c-bd20-36f35630499f" />




<img width="715" height="337" alt="image" src="https://github.com/user-attachments/assets/a1933dae-9fdc-46ef-b1c3-5a878dddebb8" />

