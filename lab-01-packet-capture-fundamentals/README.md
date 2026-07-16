# Lab 01 - Packet Capture Fundamentals

> **Building the foundation for packet-level network analysis with Wireshark.**

## Overview

This lab introduces packet-level network analysis by capturing and examining traffic generated using common networking tools such as `ping`, `dig`, and `curl`. Protocols including ICMP, DNS, TCP, and TLS are analyzed using Wireshark and `tshark`, with all findings supported by preserved packet captures and documented evidence.

## Learning Objectives

- Capture network traffic using Wireshark
- Analyze ICMP, DNS, TCP, and TLS traffic
- Apply display filters for protocol-specific analysis
- Inspect packet headers and protocol fields
- Reconstruct TCP conversations
- Preserve packet-level evidence

## Tools

- Kali Linux
- VirtualBox
- Wireshark
- tshark
- ping
- dig
- curl

## Repository Structure

```text
lab-01-packet-capture-fundamentals/
│
├── README.md
├── packet_capture_fundamentals.pdf
│
├── screenshots/
│   ├── 01-interface-selection/
│   ├── 02-idle-capture/
│   ├── 03-traffic-generation/
│   ├── 04-icmp-filtering/
│   ├── 05-dns-analysis/
│   ├── 06-https-tls/
│   ├── 07-packet-inspection/
│   ├── 08-tcp-stream/
│   └── 09-evidence-export/
│
├── pcap/
│   ├── lab01-task3-traffic-generation.pcapng
│   ├── lab01-task5-dns.pcapng
│   └── lab01-task6-http.pcapng
│
└── tshark/
    ├── lab01-task3-traffic-generation.txt
    ├── lab01-task4-icmp-only.txt
    ├── lab01-task5-dns.txt
    └── lab01-task6-http.txt
```

## Skills Gained

- Packet capture
- Packet inspection
- Protocol analysis
- Display filtering
- TCP stream reconstruction
- Evidence preservation
- Network troubleshooting fundamentals
