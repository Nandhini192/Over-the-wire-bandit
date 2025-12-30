## Bandit Level 12 → Level 13

### Objective
Find the password for Bandit Level 13. The file `data.txt` contains multiple layers of compression and encoding that must be identified and extracted step by step.

### Commands Executed
- `mkdir /tmp/ctf`
- `cp data.txt /tmp/ctf`
- `cd /tmp/ctf`
- `file data.txt`
- `xxd -r data.txt > data`
- `file data`
- `mv data data.gz`
- `gzip -d data.gz`
- `file data`
- `mv data data.bz2`
- `bzip2 -d data.bz2`
- `file data`
- `mv data data.tar`
- `tar -xvf data.tar`
- `file data5.bin`
- `mv data5.bin a.tar`
- `tar -xvf a.tar`
- `file data6.bin`
- `mv data6.bin ak.bz2`
- `bzip2 -d ak.bz2`
- `file ak`
- `mv ak ak.tar`
- `tar -xvf ak.tar`
- `file data8.bin`
- `mv data8.bin ak.gz`
- `gzip -d ak.gz`
- `file ak`
- `cat ak`

### Explanation
- Created a temporary working directory to safely extract files.
- Used the `file` command repeatedly to identify each encoding or compression format.
- Renamed files with correct extensions and decompressed them step by step.
- Continued this process until reaching the final readable file.
- Displayed the contents using `cat` to reveal the password.

### Password
🔐 **Password Retrieved (For Level 13)**  
`F05dwFsc0cbaIiH0h8J2euks2vdTDwAn`




<img width="1203" height="509" alt="image" src="https://github.com/user-attachments/assets/72784649-9818-4c2e-856b-7d089cace441" />




<img width="620" height="271" alt="image" src="https://github.com/user-attachments/assets/0ed4a986-c667-4bbe-bdf9-8d5fbb10a529" />




<img width="1269" height="155" alt="image" src="https://github.com/user-attachments/assets/b00690f4-12b8-466a-a362-4158b8255e97" />



