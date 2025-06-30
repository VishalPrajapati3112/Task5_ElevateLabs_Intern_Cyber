# Task 5 – Packet Capture and Analysis using Wireshark

## 📌 Description

In this task, live network traffic was captured and analyzed using Wireshark on a Linux system (dual-boot setup). The objective was to understand how different types of network packets behave, and to get hands-on experience with protocol analysis and network troubleshooting.

Various types of packets were intentionally generated using terminal commands and browser activities to ensure a broad protocol coverage. Wireshark's filtering and inspection features were used to explore the packet contents, understand communication patterns, and note any security-relevant behaviors.

## 📦 Activities Performed

- Captured live network traffic on the active interface using Wireshark.
- Manually generated traffic to trigger multiple protocols:
  - `ping` for ICMP
  - `dig` for DNS
  - `curl` and HTTP websites for HTTP traffic
  - Browsed HTTPS websites for TLS packets
  - Used tools like `arping`, `ftp`, `traceroute`, `ssh` to trigger ARP, FTP, UDP traffic
- Applied protocol filters in Wireshark including:
  - `icmp`, `dns`, `http`, `tcp`, `tls`, `ftp`, `arp`, `ocsp`, etc.
- Analyzed packets by observing fields like headers, IPs, request/response content, handshake patterns, and encryption behavior.
- Identified response headers such as `X-XSS-Protection: 0` indicating potential XSS risk.
- Observed OCSP request packets showing SHA-1 usage, highlighting outdated hashing in certificate status checks.



## 🎯 Outcome

- Learned how to generate and capture various types of network traffic.
- Gained experience in filtering and inspecting specific protocols in Wireshark.
- Developed a better understanding of how protocols like DNS, HTTP, ICMP, TCP, and TLS operate on the network.
- Identified security-relevant indicators such as weak headers and outdated hashing algorithms.
- Strengthened hands-on skills in network troubleshooting and protocol-level inspection.

