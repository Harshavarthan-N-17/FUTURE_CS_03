# 🔥 Firewall Configuration & Testing Report

## 📌 1️⃣ Overview
This report documents the firewall setup and the results of various security tests.

---

## 📌 2️⃣ Firewall Rules Applied
The following rules were configured:
- **Default Policies**: Incoming denied, Outgoing allowed.
- **Allowed Services**: SSH (22), HTTP (80), HTTPS (443).
- **Blocked IPs**: Restricted SSH access from certain IPs.

### 🔗 Reference: [firewall_rules.md](firewall_rules.md) 

---

## 📌 3️⃣ Testing Results
The firewall was tested using **Nmap**. Below are the key findings:

| Test Scenario | Expected Result | Actual Result |
|--------------|----------------|--------------|
| SSH (Port 22) open for allowed IPs | ✅ Open | ✅ Open |
| HTTP (Port 80) open for all | ✅ Open | ✅ Open |
| HTTPS (Port 443) open for all | ✅ Open | ✅ Open |
| SSH blocked for denied IPs | ❌ Closed | ❌ Closed |

### 🔗 Reference: [test_results.md](test_results.md)  

---

## 📌 4️⃣ Final Conclusion
The firewall rules were applied **successfully**, and all tests produced the expected results.  
This confirms that the **UFW firewall is properly configured** and working as intended.

---

## 📌 5️⃣ Recommendations
- **Enable logging** (`sudo ufw logging on`) for monitoring.
- **Regularly audit rules** (`sudo ufw status numbered`).
- **Restrict SSH access** to trusted IPs only.

---

### ✅ **Prepared by: Harshavarthan N**  
🕒 **Date:** `16-03-2025`

