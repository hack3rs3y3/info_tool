# Info Tool – HackersEye Privilege Escalation Scanner for Kali Linux

This is a **simple GUI tool** designed for educational purposes. It allows regular users to scan the system for basic privilege escalation vectors.

## 📋 What It Does

- Shows all system users (/etc/passwd)
- Lists writable files in /etc
- Displays the main crontab (/etc/crontab)
- Finds all files with the SETUID bit set

## 🔧 How to Install

1. **Clone the repository**:
```bash
git clone https://github.com/hack3rs3y3/info_tool.git
```

2. **Install it**:
```bash
cd info_tool
sudo dpkg -i info-tool.deb
```
3. **Run the tool**:
```bash
info_tool
```
## 🧪 Tested on:

- Kali Linux 2023+
- Works with normal users

## 📎 Author

Created by Tzahi Turgeman – for training and educational use.
