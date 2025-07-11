# NMAP-Project

🛰️ Nmap – Network Scanning & Security Auditing Project
This is a hands-on cybersecurity project performed using Nmap as part of my internship training. The goal was to understand and apply various network scanning techniques to enumerate services, detect vulnerabilities, and map open ports on a target system using Kali Linux and Metasploitable 2.

🧰 Lab Setup
Component	Configuration
Attacker Machine	Kali Linux (IP)
Target Machine	Metasploitable 2 (IP)
Tool Used	Nmap

🔎 Scan Types Performed
Ping Scan (nmap -sn)
To check if the target host is live.

Basic TCP Scan (nmap)
Default top 1000 TCP ports scan.

TCP Connect Scan (nmap -sT)
Full 3-way handshake for open ports.

Stealth SYN Scan (nmap -sS)
Half-open scan to avoid detection.

Version Detection (nmap -sV)
Grabs service banners and version info.

Top Port Scan (nmap --top-ports 100)
Fast scan of most common 100 ports.

Fast Scan (nmap -F)
Quick scan using internal Nmap port list.

Full Port Scan (nmap -p-)
Scans all 65535 TCP ports.

Aggressive Scan (nmap -A)
Combines OS detection, versioning, traceroute, and scripts.

OS Detection (nmap -O)
Identifies OS fingerprints using TCP/IP responses.

Port Range Scan (nmap -p 1-1000)
Sequential scan of ports 1 to 1000.

XMAS Scan (nmap -sX)
Stealth scan using TCP FIN, PSH, URG flags.

FIN Scan (nmap -sF)
Uses only FIN flag to detect open ports.

NULL Scan (nmap -sN)
Sends packets with no flags for stealth discovery.

UDP Scan (nmap -sU --top-ports 50)
Scans top 50 common UDP ports using aggressive timing.

Vulnerability Scan (nmap -sV --script vuln)
Uses NSE scripts to detect known CVEs and misconfigurations.

🧠 What I Learned
How to detect live hosts and exposed services

Port scanning techniques for stealth, speed, and depth

Banner grabbing and version detection

How to use OS fingerprinting and scripting to detect vulnerabilities

Real-world use of Nmap for penetration testing and internal audits

⚠ Disclaimer
This project was done on a local virtual lab using Metasploitable 2, a legal vulnerable machine.
No unauthorized systems were scanned. This was purely for educational and ethical learning.

