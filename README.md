## Networkwalks Cybersecurity Internship — Week 2 ##
Penetration Testing: Footprinting, Reconnaissance & Network Scanning
This repository contains the work completed during Week 2 of the Networkwalks Cybersecurity Internship.
The practical work focused on two areas:
PM1 — Footprinting with Multiple Kali Linux Tools
PM5 — Network Scanning with Zenmap
The activities provided hands-on experience with information gathering, DNS enumeration, web technology identification, HTTP response analysis, WAF identification, and network host discovery.

The objectives of Week 2 were to:
Perform basic footprinting and reconnaissance of a target domain.
Identify publicly available domain and DNS information.
Identify web technologies and application components.
Inspect HTTP response headers.
Identify the presence of a Web Application Firewall.
Perform DNS enumeration.
Discover active hosts on a local network using Zenmap.
Document observations and supporting evidence.

PM1 — Footprinting & Reconnaissance
The following Kali Linux tools were used against networkwalks.com:
Tool
Purpose
WHOIS : Gathered domain registration and registrar information.
WhatWeb: Identified web technologies and application components.
Nslookup : Resolved the domain to its associated IP address.
Curl: Inspected HTTP response headers.
Wafw00f :Identified the Web Application Firewall.
DNSRecon :Enumerated publicly available DNS records.

PM1 Evidence
The PM1-FOOTPRINTING directory contains:
Screenshots of each tool execution.
Text files containing the corresponding command output.

PM5 — Network Scanning with Zenmap
Zenmap was used to perform a Ping Scan of the local network: 192.168.1.0/24
The scan identified the following live hosts:
192.168.1.1
192.168.1.2
192.168.1.4
192.168.1.5
Additional host information was examined for 192.168.1.1, and a network topology view was generated.

PM5 Evidence
The PM5-ZENMAP/screenshots directory contains:
Local network configuration evidence.
Zenmap Ping Scan results.
Host details for 192.168.1.1.
Zenmap network topology.
Report

The complete Week 2 report is available in:
REPORT/W2-PM-FINAL-Srushti-Networkwalks.docx
The report contains:
Liability Disclaimer
Introduction
Tools Used
Activities Performed
Risk Analysis / Impact
Recommendations
Conclusion
Evidences Collected
Tools & Technologies:
Kali Linux
WHOIS
WhatWeb
Nslookup
Curl
Wafw00f
DNSRecon
Zenmap / Nmap
Microsoft Word
GitHub

Key Learning Outcomes:
Through these activities, I gained practical experience in:
Domain and infrastructure reconnaissance
DNS enumeration
Web technology fingerprinting
HTTP header analysis
WAF identification
Network host discovery
Basic network topology visualization
Evidence collection and security documentation

Disclaimer:
All activities documented in this repository were performed as part of the authorized cybersecurity internship practical exercises.
The footprinting and scanning activities were conducted for educational and authorized purposes. No exploitation, unauthorized access, or vulnerability validation was performed as part of these exercises.
