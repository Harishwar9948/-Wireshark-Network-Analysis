#  Wireshark Network Analysis Lab

This repository showcases hands-on network traffic analysis using **Wireshark**. As part of my cybersecurity learning path, I captured and inspected real traffic in a virtual lab environment to understand protocols, anomalies, and common patterns.

---

## Objectives

- Learn how to use Wireshark for deep packet inspection (DPI)
- Understand the structure of common network protocols (TCP, DNS, ARP, HTTP, etc.)
- Analyze traffic behavior using filters and visualizations
- Detect unusual patterns (e.g., SYN Flood, malformed packets)

---

##  Tools Used

- Kali Linux (Wireshark)
- Virtual lab (attacker/victim systems)
- Browser-based traffic
- Simulated malicious activity

---

## Contents

-  `Wireshark Packet Analysis Report.pdf`
-  Screenshots: Packet capture sessions, protocol breakdowns (optional)

---

## Key Topics Covered

- TCP 3-Way Handshake
- DNS Resolution
- ARP Requests & Replies
- HTTP GET/POST
- ICMP Echo Requests
- SYN Flood pattern recognition

---

## How I Practiced

- Captured traffic between two VMs
- Used browser and terminal-based commands (ping, curl, dig)
- Applied display filters (`http`, `tcp.flags.syn==1 && tcp.flags.ack==0`, `icmp`, etc.)
- Interpreted results using protocol hierarchy, flow graphs, and packet details

---

## What I Learned

- How protocols work at different OSI layers
- How to identify suspicious traffic patterns
- Why packet analysis is critical for incident response, threat hunting, and pentesting

---

> ⚠️ **Disclaimer:**  
All traffic captured was from safe, simulated environments. This report is strictly for educational and ethical learning purposes.
