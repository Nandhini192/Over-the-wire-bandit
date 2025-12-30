## 🛰️ **Bandit Level 05 ➜ 06**

---

### **🎯 Challenge Overview**

Inside the `inhere` directory, there are many subdirectories containing multiple files.  
Only **one file** meets all the following conditions:

- Human-readable  
- Exactly **1033 bytes** in size  
- **Not executable**

The goal is to locate this file and retrieve the password for the next level.

---

### **🧠 Key Idea**

Manually checking each file is inefficient.  
The `find` command is used to search recursively and apply filters for file size, readability, and execution permissions.

---

### **🧭 Method Used**

- Navigate into the `inhere` directory  
- Use `find` with specific conditions  
- Read the matching file to get the password  

---

### **💻 Commands Executed**

```bash
ls
cd inhere
find . -type f -size 1033c -readable ! -executable
cat ./maybehere07/.file2
