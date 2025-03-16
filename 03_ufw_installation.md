# 🔥 UFW Installation & Setup Guide

This document provides step-by-step instructions to **check, install, and enable UFW (Uncomplicated Firewall)** on Ubuntu.

---

## 📌 Step 1: Check if UFW is Installed

Before installing, check if UFW is already installed by running:

sudo ufw --version
📌 If UFW is installed, this command will display the version number.
📌 If you see "command not found", UFW is not installed. Proceed with the installation in Step 2.

---

## 📌 Step 2: Install UFW (If Not Installed)
If UFW is missing, install it using the following command:

---

sudo apt update && sudo apt install ufw -y
📌 Explanation:

sudo apt update → Updates package lists.
sudo apt install ufw -y → Installs UFW automatically.
📌 This ensures the firewall package is installed on your system.