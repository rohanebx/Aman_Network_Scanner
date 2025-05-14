# OS-Aware Nmap Scanner

A lightweight Python tool that uses Nmap to scan specific ports based on the target operating system (Android or Windows). This scanner helps identify open services on a given IP address using customized port sets and options tailored for each OS type.

> ⚠️ **Ethical Use Only:** This tool is intended for use in educational environments, penetration testing (with permission), or private networks. Unauthorized scanning of devices or networks may violate laws or terms of service.

---

## 🚀 Features

- Detects if Nmap is installed
- Scans a user-specified IP address
- Lets the user choose between Android or Windows as the target OS
- Uses a tailored list of ports depending on the chosen OS
- Runs an `nmap` scan with service detection and stealthy options

---

## 🛠️ Prerequisites (Linux)

Make sure your system meets the following requirements:

### 🔹 Python 3
```bash
sudo apt update
sudo apt install python3
