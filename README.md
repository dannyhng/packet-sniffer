# Packet Sniffer

A simple packet sniffer built in Python using Scapy. This project helps reinforce basic network packet analysis skills, aligned with CCNA learning objectives.
Created for learning purposes. Part of my networking and CCNA study journey.

## 🛠 Features

- Captures live network packets
- Displays packet summaries
- Easy to expand for protocol-specific filtering

## 🧠 Educational Value (CCNA)

This tool helps you understand:
- OSI model in action (especially Layer 2 and Layer 3)
- Packet structure and headers
- Real-time network monitoring
- Protocol identification (e.g., TCP, UDP, ICMP)

## 🚀 How to Run (Basic)

You must have Python and [Scapy](https://scapy.net/) installed.

```bash
pip install scapy
python packet_sniffer.py
```

## 📄 Example Output

```bash
Ether / IP / TCP 192.168.1.2:54321 > 142.250.64.78:https S
Ether / IP / UDP 192.168.1.3:68 > 192.168.1.1:67 BOOTP/DHCP
```

## 📚 Future Additions
- Save captured packets to a .pcap file
- Add filters (e.g., only capture DNS, ICMP, or ARP)
- GUI with protocol breakdown
