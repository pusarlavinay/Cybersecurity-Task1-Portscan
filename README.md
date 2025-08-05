# Cybersecurity-Task1-Portscan
# 🔐 Cybersecurity Internship Task 1 – Nmap Network Scan

## 🧠 Objective

The goal of this task is to understand how to perform **network reconnaissance** using the Nmap tool. Specifically, this task focused on scanning a local network to identify **live hosts**, **open ports**, and **potentially vulnerable services** running on them.

---

## 🛠 Tools Used

- **Nmap** – for scanning IP ranges and detecting open ports
- *(Optional)* **Wireshark** – for packet-level network analysis

---

## 🖥️ Task Performed

### 1. **Identified my local IP range**  
Used the `ip a` command to find my IP and subnet (e.g., `192.168.1.0/24`).

### 2. **Performed a TCP SYN Scan**
Ran the following Nmap command with root privileges:
```bash
sudo nmap -sS 192.168.1.0/24 -oN scan_output.txt

