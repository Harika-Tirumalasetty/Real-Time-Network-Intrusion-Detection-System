# Real-Time-Network-Intrusion-Detection-System
**Project Overview
**
This project is a real-time network intrusion detection system built using Python, Scapy, and Npcap (Windows).
It monitors live network traffic on your computer, detects suspicious activity like flood attacks or port scans, and alerts you with reasons.
It also visualizes network traffic patterns for analysis.

**Features**
Capture live packets from your computer’s network adapter
Detect anomalies:
Flood detection – excessive requests from a single IP
Port scanning – multiple ports targeted by the same IP
Provide alerts with details (IP, protocol, number of packets/ports, reason)
Store and analyze packets using pandas
Visualize:
Top talkers (IPs with highest traffic)
Traffic over time
Installation
Install Python (≥3.9 recommended)
Install necessary libraries:
pip install scapy pandas matplotlib
Install Npcap (required for Windows to capture packets)
Download: https://nmap.org/npcap/
Choose default options
Check WinPcap API-compatible Mode
Restart your computer if prompted
Usage
Open Jupyter Notebook or Python IDE
Run the script nids.py (or your notebook)
The system starts capturing packets in real-time
Alerts will be printed for suspicious activity
At the end of capture, visualizations will be displayed
**Example Alert**
⚠️ ALERT: Suspicious Activity Detected (Flood)
Source IP: 192.152.26.4
Packets: 12 in 5 sec
Protocol: TCP → Destination: 13.71.55.58
How it Works
Packet Capture: Uses Scapy to sniff live packets
Activity Tracking: Keeps timestamps of packet activity per IP
Anomaly Detection:
Flood detection: triggers if too many packets from one IP in a short time
Port scanning: triggers if one IP targets multiple ports
Alerting: Prints source IP, protocol, reason, and packet count
Analysis & Visualization: Uses pandas & matplotlib to show traffic patterns
Skills Demonstrated
Python programming and libraries (Scapy, pandas, matplotlib)
Network traffic analysis & monitoring
Real-time anomaly detection
Data visualization
Security & intrusion detection concepts

**Project Goal**
To create a hands-on system that demonstrates understanding of:

Network security
Real-time monitoring
Data-driven decision making
Detecting malicious activity in practical scenarios
Screenshot / Visualization

<img width="1075" height="699" alt="image" src="https://github.com/user-attachments/assets/aabff4b6-1cc0-4686-b568-365053ecafe4" />
<img width="1056" height="581" alt="image" src="https://github.com/user-attachments/assets/439b402f-fc5f-4fa3-a044-8b5ff7430ebf" />
