## Bandit Level 26 → Level 27

### Objective
Retrieve the password for Bandit Level 27 using a setuid executable after escaping the restricted shell.

### Commands Executed
- `ssh -i bandit26.sshkey bandit26@bandit.labs.overthewire.org -p 2220`
- `:set shell=/bin/bash`
- `:shell`
- `ls`
- `./bandit27-do`
- `./bandit27-do cat /etc/bandit_pass/bandit27`

### Explanation
- Logged in as `bandit26` using the SSH key.
- Escaped the restricted shell to obtain a normal Bash shell.
- Listed files to locate the `bandit27-do` setuid executable.
- Used the executable to run a command as user `bandit27`.
- Read the password file for the next level.

### Password

`upsNCc7vzaRDx6oZC6GiR6ERwe1MowGB`




<img width="340" height="101" alt="image" src="https://github.com/user-attachments/assets/8cf37c84-1b63-43c3-9e76-8934e36dac6f" />





<img width="447" height="181" alt="image" src="https://github.com/user-attachments/assets/94d30476-08cf-4ad2-9221-03b8368dc7ce" />



