# Nmap Port Scanning Lab

## Overview

This project demonstrates the use of Nmap for network reconnaissance, host discovery, port scanning, and service enumeration in a controlled lab environment.

The objective is to understand how security professionals identify active hosts, open ports, and running services during security assessments.

---

## Disclaimer

This project was conducted in a controlled lab environment for educational and authorized testing purposes only.

Do not perform network scanning on systems without proper authorization.

---

## Tools Used

- Nmap
- Linux
- Command Line Interface (CLI)

---

## Learning Objectives

- Understand network reconnaissance techniques
- Perform host discovery
- Identify open ports
- Detect running services
- Interpret scan results
- Develop foundational security assessment skills

---

## Lab Environment

Target Environment:
- Local Lab Machine
- Virtual Machine
- Authorized Test Systems

Operating System:
- Linux

---

## Nmap Commands Used

### Host Discovery

```bash
nmap -sn 192.168.1.0/24
```

Purpose:
Identify active hosts within a network.

---

### Basic Port Scan

```bash
nmap 192.168.1.10
```

Purpose:
Discover open ports on the target system.

---

### Service Version Detection

```bash
nmap -sV 192.168.1.10
```

Purpose:
Identify services and software versions running on open ports.

---

### Operating System Detection

```bash
nmap -O 192.168.1.10
```

Purpose:
Attempt to identify the operating system.

---

### Aggressive Scan

```bash
nmap -A 192.168.1.10
```

Purpose:
Gather comprehensive information including:

- OS Detection
- Version Detection
- Script Scanning
- Traceroute

---

## Sample Findings

| Port | Service | State |
|--------|---------|---------|
| 22 | SSH | Open |
| 80 | HTTP | Open |
| 443 | HTTPS | Open |

---

## Security Analysis

Open ports increase the attack surface of a system.

Security teams should:

- Disable unnecessary services
- Patch vulnerable software
- Restrict access using firewalls
- Continuously monitor exposed services

---

## Skills Demonstrated

- Network Reconnaissance
- Port Scanning
- Service Enumeration
- Security Documentation
- Linux Command Line
- Cybersecurity Fundamentals

---

## Future Improvements

- NSE Script Scanning
- Vulnerability Enumeration
- Network Mapping
- Service Analysis
- Reporting Automation

---

## Author

Muzammil Rana

Aspiring Cybersecurity Professional
