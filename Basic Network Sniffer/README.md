# 🕵️ Basic Network Sniffer (Python)

A lightweight network packet sniffer built using Python that captures and analyzes network traffic in real-time. This project demonstrates fundamental concepts of network monitoring and packet inspection used in cybersecurity and network analysis.

---

## 🚀 Overview

The Basic Network Sniffer is a command-line tool designed to capture live network packets and display useful information such as source/destination IP addresses, protocols, and payload data.

It helps in understanding how data flows through a network and is commonly used in **ethical hacking, network troubleshooting, and cybersecurity learning**.

---

## 🎯 Features

- 📡 Capture live network packets
- 🌐 Display source and destination IP addresses
- 🔍 Protocol identification (TCP, UDP, ICMP)
- 📦 Packet payload inspection
- ⚡ Real-time packet monitoring
- 🧪 Lightweight and easy to use

---

## 🏗️ Tech Stack

- Python 3
- Socket Programming

---

## 📁 Project Structure
packet-sniffer/
│
├── backend/
│   ├── main.py                # FastAPI server (API + WebSocket)
│   ├── sniffer.py            # Scapy packet capture logic
│   ├── parser.py             # Packet parsing (TCP/UDP/ICMP/HTTP)
│   ├── requirements.txt      # Python dependencies
│   └── utils/
│        └── helpers.py       # optional helper functions
│
├── frontend/
│   ├── index.html            # Root HTML
│   ├── package.json          # Node dependencies
│   ├── vite.config.js        # Vite config
│   ├── tailwind.config.js    # Tailwind setup
│   └── src/
│        ├── main.jsx         # Entry point
│        ├── App.jsx          # Main layout
│        ├── styles/
│        │     └── index.css
│        ├── components/
│        │     ├── Navbar.jsx
│        │     ├── Controls.jsx
│        │     ├── PacketTable.jsx
│        │     ├── PacketDetails.jsx
│        │     ├── Charts.jsx
│        │     └── Filters.jsx
│        └── services/
│              └── socket.js  # WebSocket connection
│
├── data/
│   └── captures/             # Saved PCAP/JSON files
│
├── README.md
└── .gitignore
