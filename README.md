# Network-scan-


This repository contains my **Task 1** submission for the cybersecurity internship.
The objective of this task is to perform a network scan, identify active hosts, detect open ports, and analyze potential security risks.

---

## 🛠 Tools Used
- **Nmap**

- **Kali Linux**

---

## 📌 Step-by-Step Commands Used

### 1️⃣ Check Network Interface & IP
```bash
ip anmap -sS --min-rate 10000 -T4 <your-IP-range> -oN scans/fast_scan.txt
nmap -sV <your-IP-range> -oN scans/service_scan.txt
nmap <your-IP-range> > scans/scan_summary.txt

