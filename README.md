# 🔍 Network Forensics

## 📌 Overview

This project documents my practical work in **Network Forensics** using
**TCPDump** and **TShark** on Kali Linux.

The practical focuses on capturing, filtering, reading, and analyzing
network packets and PCAP files.

## 🎯 Objectives

- Understand basic network concepts and the OSI/TCP model
- Capture network packets using TCPDump
- Filter traffic based on IP, host, network, port, and protocol
- Save captured traffic into `.pcap` files
- Read and analyze PCAP files
- Analyze network traffic using TShark
- Extract IP addresses and network information
- Understand basic packet analysis and troubleshooting

## 🛠️ Tools Used

- Kali Linux
- TCPDump
- TShark
- PCAP
- Wireshark

## 🔬 Practical Work

### TCPDump

I practiced TCPDump commands for:

- Network interface discovery
- Live packet capture
- Host and IP-based filtering
- Source and destination filtering
- Port and protocol filtering
- IPv6 traffic capture
- Packet count limitation
- Saving packets to PCAP files
- Reading saved PCAP files
- Incoming and outgoing traffic analysis

Example:

```bash
tcpdump -D
tcpdump -i eth0
tcpdump -n
tcpdump -c 3
tcpdump -w my.pcap
tcpdump -r my.pcap
tshark -D
tshark -i eth0
tshark -r kinju.pcap
tshark -Y http
tshark -Y dns
tshark -Z endpoints,ip
