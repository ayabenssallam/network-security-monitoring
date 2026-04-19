#🔐 Network Security Monitoring & Intrusion Detection System

##📌 Description

This project is a lightweight Network Security Monitoring and Intrusion Detection System (IDS) designed to analyze local network traffic and detect suspicious activities in real time.

It leverages tools like Nmap and Wireshark to identify active hosts, monitor connectivity, and detect potential anomalies within a network.

---

##🎯 Objectives

- Monitor local network activity
- Detect suspicious or unknown devices
- Identify active hosts (IP & MAC addresses)
- Improve overall network security posture

---

##🛠️ Technologies Used

- Kali Linux
- Nmap
- Wireshark (optional)
- Python / Bash

---

##⚙️ Features

- 🔎 Network scanning using Nmap
- 🌐 Active host discovery
- 🧾 IP & MAC address extraction
- 📡 Connectivity testing (Ping)
- 🚨 Basic anomaly detection (new/unknown devices)

---

##🚀 Usage

###1. Network Scan

nmap -sn 192.168.128.0/24

###2. Run Python Script

python3 network_monitor.py

---

##🧠 How It Works

1. The system scans the local network using Nmap
2. Extracts active devices (IP & MAC)
3. Verifies connectivity using ping
4. Compares detected devices with a known list
5. Generates alerts for unknown or suspicious devices

---

##📁 Project Structure

project/
│── network_monitor.py
│── scan_results.txt
│── known_devices.txt
│── README.md

---

##🚨 Future Improvements

- Real-time monitoring (continuous scanning loop)
- Logging system for detected events
- Web dashboard for visualization
- Integration with alert systems (email/notifications)
- Advanced packet analysis

---

##⚠️ Disclaimer

This project is for educational and ethical purposes only. Do not use it on networks without permission.

---

##👨‍💻 Author

Aya BENSSALLAM
