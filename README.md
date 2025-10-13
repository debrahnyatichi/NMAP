# NMAP COURSE CONTENT

## Introduction
- Nmap Introduction
- Port Scanning and Its Techniques
- OSI Model and its Layers
- Analyzing Network Layer using Wireshark

## TCP / UDP Basics
- Scanning TCP & UDP Models
- TCP Headers and 3-way Handshake
- Network Discovery

## Nmap Scans & Techniques
- Nmap SYN, ACK, UDP, ARP Scan (Bypass Firewall)
- Nmap ICMP Timestamp
- Traceroute
- DNS Resolution
- Scanning Linux-based machines
- Port specification and Scan Order
- Scan Techniques:
  - `-sS` (SYN scan)
  - `-sT` (TCP connect)
  - `-sW` (window scan)
  - `-sM` (Maimon scan)
- OS and Service Detection
- Aggressive Scan
- UDP Range Scan
- Result Diagnosis
- Output and Verbosity

## Nmap IDS Evasion
- Null scan
- Packet fragmentation
- FIN scan
- XMAS scan
- IP Spoofing (Decoy)
- How to detect Firewalls
- MAC Spoofing, IP Spoofing, Proxies, etc.

## Timing & Performance
- Nmap Timing templates: T0, T1, T2, T3, T4, T5
- Scan delay and host timeout

## Advanced Nmap Features
- Script scanning (NSE)
- Banner Grabbing
- `whois` lookup
- Subdomain brute-force
- Finding Hidden Directories
- How to detect web firewalls
- MySQL Enumeration

## Vulnerability Scanning / Reporting
- Vulnerability Scanning using Nmap
- Installing webmap
- Nmap scanning and generating a report

## Service Enumeration & Exploitation
*(Enumeration and exploitation techniques for each service)*
- FTP enumeration and exploitation
- SSH enumeration and exploitation using Metasploit (`msfconsole`) and Hydra
- Telnet enumeration and exploitation
- SMTP enumeration and exploitation
- HTTP / Port 80 enumeration and exploitation
- NetBIOS enumeration and exploitation
- Rexec enumeration and exploitation
- Java RMI enumeration and exploitation
- MySQL enumeration and exploitation
- PostgreSQL enumeration and exploitation
- VNC enumeration and exploitation
- X11 enumeration and exploitation
- Apache Tomcat enumeration and exploitation
- Exploiting Ruby DRB vulnerability
