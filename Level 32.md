## Bandit Level 31 → Level 32

### Objective
Retrieve the password for Bandit Level 32 by modifying a Git repository and pushing changes to the remote server.

### Commands Executed
- `cd /tmp`
- `mkdir bandit31`
- `cd bandit31`
- `git clone ssh://bandit31-git@bandit.labs.overthewire.org:2220/home/bandit31-git/repo`
- `cd repo`
- `ls`
- `cat README.md`
- `echo "May I come in?" > key.txt`
- `git add .`
- `git config --global user.name "bandit"`
- `git config --global user.email "bandit@localhost"`
- `git commit -m "add key"`
- `git push origin master`

### Explanation
- Cloned the repository for Bandit Level 31.
- Read the instructions in the README file.
- Created the required `key.txt` file with the specified content.
- Configured Git user details.
- Committed the changes and pushed them to the remote repository.
- The server responded with the password.

### Password
 
`309RfhqyALVBEZpvb6LYStshZoqo5sK`



<img width="729" height="757" alt="image" src="https://github.com/user-attachments/assets/1a8255a6-1bf1-4812-b8e7-c9f46d6ba5d0" />





<img width="625" height="575" alt="image" src="https://github.com/user-attachments/assets/bec71d2f-c429-436e-8d3c-fed25be78a61" />





<img width="804" height="646" alt="image" src="https://github.com/user-attachments/assets/7ef4e6ae-976c-413b-976e-c4c6b874acf1" />

