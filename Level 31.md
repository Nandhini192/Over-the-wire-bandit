## Bandit Level 30 → Level 31

### Objective
Retrieve the password for Bandit Level 31 by inspecting Git tags.

### Commands Executed
- `cd /tmp`
- `git clone ssh://bandit30-git@bandit.labs.overthewire.org:2220/home/bandit30-git/repo`
- `cd repo`
- `ls`
- `git tag`
- `git show secret`

### Explanation
- Cloned the Git repository for Bandit Level 30.
- Listed available Git tags.
- Inspected the `secret` tag.
- The tag content revealed the password.

### Password

`fb5S2xb7bRyFmAvQYQGEqsbhVyJqhnDy`





<img width="724" height="659" alt="image" src="https://github.com/user-attachments/assets/fb9a45f6-10d7-4932-b407-4f41855b23b3" />
