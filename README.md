# 📦 Smart Backup System

## 🚀 Overview
Smart Backup System is a Python-based automated backup solution that efficiently copies only new or modified files and creates compressed archives. It ensures secure, fast, and reliable data backup with minimal storage usage.

---

## ✨ Features
- 🔄 Incremental Backup – Copies only new or changed files using hashing  
- 🗜️ ZIP Compression – Creates timestamped backup archives  
- ⏱️ Automation – Runs periodically using scheduling  
- 📧 Email Notification – Sends backup reports and files automatically  
- 📝 Logging System – Maintains logs and backup history  

---

## 🛠️ Technologies Used
- Python  
- File Handling  
- Hashing (MD5)  
- OS & Scheduling  
- ZIP Compression  
- SMTP (Email Automation)  

---

## ⚙️ How It Works
1. Scans the source directory  
2. Detects file changes using MD5 hashing  
3. Copies only modified/new files  
4. Stores them in a backup folder  
5. Creates a ZIP archive with timestamp  
6. Sends backup report via email  

---

## ▶️ Usage

### Run the script
```bash
python ScriptName.py <TimeInterval> <DirectoryName>
