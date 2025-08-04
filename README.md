# 🔍 Task 1: Port Scanning on Local Network

## 🧾 Objective
Scan the local network to find open ports and understand which services are running using Nmap.

## 🛠 Tools Used
- Nmap (TCP SYN Scan)
- Command Prompt (Windows)

## 📡 Steps For Example
1. Found IP range using `ipconfig` (e.g., 192.168.1.0/24)
2. Run scan using:
   ```bash
   nmap -sS 192.168.1.0/24 -oN task.txt
   Saved results in task.txt

Identified open ports and common services
