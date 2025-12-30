## Bandit Level 9 → Level 10

### Objective
Find the password for Bandit Level 10. The password is hidden in a human-readable string within `data.txt` and contains an `=` character.

### Commands Executed
- `ls`
- `strings data.txt | grep "="`

### Explanation
- Used `ls` to list files in the directory.
- Used `strings` to extract readable text from `data.txt`.
- Piped the output to `grep "="` to filter lines containing the `=` character.
- The resulting output revealed the password.

### Password

`FGUW5ilLVJrxX9kMYMmN4MgbpfMiqey`



<img width="599" height="403" alt="image" src="https://github.com/user-attachments/assets/f41b415b-d4e6-4650-824a-e81bf3c65122" />

