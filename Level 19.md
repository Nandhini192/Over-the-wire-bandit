## Bandit Level 18 → Level 19

### Objective
Retrieve the password for Bandit Level 19 by executing a command directly over SSH.

### Commands Executed
- `ssh bandit18@bandit.labs.overthewire.org -p 2220 cat readme`

### Explanation
- Used SSH to connect to the server and immediately execute `cat readme`.
- This bypassed the restricted shell that logs the user out on login.
- The command output revealed the password.

### Password

`cGWpMaKXVwDUNgPAVJbWYuGHVn9zl3j8`




<img width="608" height="258" alt="image" src="https://github.com/user-attachments/assets/e63f1d5d-c602-43dd-bf60-e87ef059db2e" />

