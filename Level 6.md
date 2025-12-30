## 🛰️ **Bandit Level 05 ➜ 06**

### **🎯 Challenge Overview**
Inside the `inhere` directory, there are many subdirectories with multiple files.  
Only one file matches these conditions:
- Human-readable  
- Exactly **1033 bytes**  
- **Not executable**

---

### **🧭 Steps to Solve**
- Navigate into the `inhere` directory  
- Use the `find` command with required filters  
- Read the correct file to get the password  

---

### **💻 Commands Executed**
```bash
ls
cd inhere
find . -type f -size 1033c -readable ! -executable
cat ./maybehere07/.file2

HWasnPhtq9AVKe0dmk45nxy20cvUa6EG

### **📘 Explanation**

- **`ls`**  
  Lists the contents of the current directory.

- **`cd inhere`**  
  Moves into the directory containing many subfolders.

- **`find . -type f -size 1033c -readable ! -executable`**  
  Searches all subdirectories for a readable file of exactly **1033 bytes** that is **not executable**.

- **Matching File**  
  The correct file is located at:  

