# 🔍 Nmap (Network Mapper)

## ✅ What is Nmap?
**Nmap** is an open-source tool used for **network discovery** and **security auditing**.  
It helps identify devices, open ports, and running services on a network.

---

## 🎯 Why use Nmap?
- Discover live hosts in a network
- Identify open TCP/UDP ports
- Detect running services and versions
- Basic OS detection (when possible)
- Useful for reconnaissance (Recon)

---

## ⚠️ Ethical Notice
Use Nmap **only** on systems you own or have **explicit permission** to scan.

---

## 🧠 Key Concepts
- **Port**: A communication endpoint (e.g., 22 SSH, 80 HTTP)
- **Service**: Application running on a port (e.g., Apache, SSH)
- **Reconnaissance**: Gathering information before security testing

---

## ⚙️ Common Commands

### ✅ 1) Scan a single host (basic)
```bash
nmap 192.168.1.10

