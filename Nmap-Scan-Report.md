# 🔍 Nmap Scan Report

## 🎯 Objective
Perform a basic port scan and OS detection on a test machine using Nmap.

## 🧰 Tools Used
- Nmap
- Kali Linux
- Metasploitable2 VM (target)

## 🛠️ Commands Used
```bash
nmap -sS -A -T4 192.168.1.10
```

### Breakdown:
- `-sS`: SYN Scan
- `-A`: OS + service detection
- `-T4`: Faster scan

## 📊 Results
- Open Ports: 22 (SSH), 80 (HTTP), 3306 (MySQL)
- OS Detected: Linux 2.6.X to 3.X
- Services: Apache 2.2.8, OpenSSH 4.7, MySQL 5.0

## 🧠 What I Learned
- How to find open ports and fingerprint OS/services
- Basics of stealthy scanning (SYN scan)
- Identifying vulnerable services


