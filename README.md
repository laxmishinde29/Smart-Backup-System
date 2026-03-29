# 🚀 Smart Backup System

A Python-based automated backup solution that intelligently copies only new or modified files and creates compressed archives for efficient and secure data protection.

---

## 📌 Key Features
- Incremental backup using MD5 hashing  
- Automatic file backup with scheduling  
- Timestamped ZIP archive creation  
- Email notification with backup reports  
- Logging and backup history tracking  

---

## 🧠 Core Idea
Instead of copying all files every time, the system:
- Detects file changes using hashing  
- Copies only updated or new files  
- Saves time and storage  

---

## ⚙️ How It Works
1. Scans the source directory  
2. Compares file hashes (MD5)  
3. Copies only changed files  
4. Stores them in backup folder  
5. Creates a compressed ZIP archive  
6. Sends backup report via email  

---

## 🛠️ Tech Stack
- Python  
- OS & File Handling  
- Hashlib (MD5)  
- Schedule Library  
- Zipfile Module  
- SMTP (Email Automation)  

---

## 👩‍💻 Author
Laxmi Shinde

---

## ▶️ Run the Project
```bash
python ScriptName.py <TimeInterval> <DirectoryName>
