# 🔥 Python Personal Firewall (GUI + iptables)

A lightweight, Python-based personal firewall that provides **real-time network monitoring**, **rule-based blocking**, and **system-level packet filtering** using `iptables`. Built with **Scapy**, **Tkinter**, and standard Python modules, this tool offers both a GUI and CLI interface for managing and securing your local network traffic.

---

## 💡 Features

- 🧠 **Custom Rule Engine**  
  Block IPs, ports, and protocols using simple JSON rules.

- 📦 **Scapy-Powered Packet Sniffer**  
  Detects TCP, UDP, and ICMP traffic in real-time.

- 🛡️ **GUI Control Panel**  
  Start, pause, and stop the firewall using a user-friendly Tkinter interface.

- 🔥 **iptables Integration**  
  Automatically applies and manages `iptables` rules at the system level.

- 🧾 **Traffic Logging**  
  Logs all blocked or suspicious packets to `logs/blocked.log`.

---

## 📁 Project Structure

<details> <summary>Click to expand</summary>
yaml
Copy
Edit
personal_firewall/
├── firewall.py             # Core sniffer and filtering logic
├── firewall_gui.py         # Tkinter-based GUI control panel
├── iptables_blocker.py     # CLI utility for managing iptables rules
├── rules.json              # JSON file for user-defined block rules
├── logs/
│   └── blocked.log         # Log file for blocked packets
├── requirements.txt        # Required Python libraries
└── Readme.md               # Project documentation (this file)
</details>
