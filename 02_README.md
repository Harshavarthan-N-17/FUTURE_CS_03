# 🛡️ Firewall Setup & Testing Report 🚀  

This repository contains the **Firewall Setup & Testing Report**, which documents the process of configuring and testing a firewall using **UFW (Uncomplicated Firewall)** on Ubuntu 22.04. The primary goal is to restrict unauthorized access while allowing essential network services.  

---

## 📌 Tools Used  
- **UFW (Uncomplicated Firewall)** – For managing firewall rules.  
- **Nmap** – For scanning open ports before and after firewall setup.  

---

## 📂 Files & Structure  
01_LICENSE → The license information for this project.  
02_README.md → This file, providing an overview of the repository.  
03_ufw_installation.md → Instructions for checking and installing UFW.  
04_firewall_rules.md → Contains the firewall setup commands with explanations.  
05_test_results.md → Documents the Nmap scan results before and after firewall setup.  
06_firewall_report.md → The complete firewall setup & testing report.  
screenshots/ → Folder containing relevant screenshots of scan results and firewall status.  
 
---

## 📋 Firewall Configuration Overview  
- **Default Deny Policy:** All incoming traffic is blocked by default.  
- **Essential Ports Allowed:**  
  - ✅ **SSH (22)** – Allowed only from a specific IP.  
  - ✅ **HTTP (80)** & **HTTPS (443)** – Allowed for web access.  
- **Testing:** Conducted with **Nmap** before and after applying UFW rules.  

---

## 🔥 Security Impact  
- **Before Firewall Setup:** All ports were open and accessible.  
- **After Firewall Setup:** Only **essential services (22, 80, 443)** remained accessible, reducing attack surface.  

---

## 📢 Recommendations  
Refer to **06_firewall_report.md** for detailed security recommendations on improving firewall configurations.  

---

## 🔗 References  
- **UFW Documentation:** [https://help.ubuntu.com/community/UFW](https://help.ubuntu.com/community/UFW)  
- **Nmap Documentation:** [https://nmap.org/book/man.html](https://nmap.org/book/man.html)  

---

🛡️ **Disclaimer:** This report is for educational purposes only. Always follow cybersecurity best practices when configuring firewalls.  
