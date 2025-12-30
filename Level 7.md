## 🛰️ Bandit Level 6 ➜ Level 7

---

## 🎯 Goal
Find the password for **bandit7**.

The password is in a file that:
- Is a **normal file**  
- Owned by **bandit7**  
- Group is **bandit6**  
- File size is **33 bytes**

---

## 💡 Key Ideas
1. The file can be **anywhere** on the system.  
2. Use the `find` command to search by **owner, group, and size**.  
3. Some folders are protected, so **ignore errors**.  
4. Use `cat` to read the file and get the password.

---

## 📘 Explanation
- Go to the root directory `/` to search the whole system.  
- Use `find` to look for the file with the right owner, group, and size.  
- Hide any "permission denied" errors.  
- Once found, read the file with `cat` to see the password.

---

## 🔧 Commands

```bash
cd /
find . -type f -user bandit7 -group bandit6 -size 33c 2>/dev/null
cat ./var/lib/dpkg/info/bandit7.password

morbNTDkSW6jILUOYmdoMaLNOIFVAaj
