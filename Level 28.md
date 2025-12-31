## Bandit Level 27 → Level 28

### Objective
Retrieve the password for Bandit Level 28 by cloning a remote Git repository.

### Commands Executed
- `cd /tmp`
- `git clone ssh://bandit27-git@bandit.labs.overthewire.org:2220/home/bandit27-git/repo`
- `cd repo`
- `cat README`

### Explanation
- Moved to the `/tmp` directory to avoid permission issues.
- Cloned the Git repository using SSH on port `2220`.
- Navigated into the cloned repository.
- Read the `README` file to obtain the password.

### Password

`Yz9IpL0sBcCeuG7m9uQFt8ZNpS4HZRcN`



<img width="783" height="500" alt="image" src="https://github.com/user-attachments/assets/3c7254db-565b-4ccb-b57e-f0111261f829" />

