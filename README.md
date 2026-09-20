# Cybersecurity-reconnaissance-lab
A hands-on cybersecurity reconnaissance lab covering information gathering, domain reconnaissance, technology fingerprinting, WAF detection, and network discovery using Kali Linux, WHOIS, WhatWeb, WAFW00F, and Zenmap/Nmap.
# 🔐 Cybersecurity Reconnaissance Lab

A hands-on cybersecurity reconnaissance and information-gathering project developed as part of my **Cybersecurity & Ethical Hacking Internship at NETWORKWALKS**.

This project focuses on understanding how security professionals collect publicly available information, identify technologies, analyze web security mechanisms, and perform network reconnaissance in an authorized lab environment.

---

## 👨‍💻 About the Project

Reconnaissance is one of the fundamental stages of a cybersecurity assessment.

Before performing deeper security testing, it is important to understand the target's digital footprint, technologies, network exposure, and publicly available information.

During this project, I explored several reconnaissance and information-gathering techniques using **Kali Linux** and industry-standard security tools.

---

## 🎯 Objectives

The main objectives of this project were:

- Understand the fundamentals of cybersecurity reconnaissance
- Perform domain and information gathering
- Identify technologies used by web applications
- Detect Web Application Firewalls (WAF)
- Discover live hosts and open ports
- Identify running network services
- Understand basic network enumeration
- Gain practical experience with Kali Linux security tools
- Document reconnaissance findings in a structured manner

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| 🐉 Kali Linux | Cybersecurity testing environment |
| 🔎 WHOIS | Domain and registration information |
| 🌐 WhatWeb | Web technology fingerprinting |
| 🛡️ WAFW00F | Web Application Firewall detection |
| 🗺️ Zenmap | Graphical network scanning and visualization |
| ⚡ Nmap | Network discovery and port scanning |

---

## 🔍 Topics Covered

### 1. WHOIS Reconnaissance

WHOIS was used to understand publicly available domain-related information such as:

- Domain registration details
- Registrar information
- Nameservers
- Domain status
- Registration and expiration information where available

> Note: WHOIS information varies depending on the domain registrar and privacy settings.

---

### 2. WhatWeb

**WhatWeb** was used for web technology fingerprinting.

The tool can help identify technologies associated with a website, such as:

- Web servers
- Content Management Systems
- JavaScript frameworks
- Web technologies
- Plugins and libraries
- Server-side technologies

This helps build an initial understanding of a web application's technology stack.

---

### 3. WAFW00F

**WAFW00F** was explored to understand Web Application Firewall detection.

A WAF can act as a security layer between users and a web application and may help detect or filter potentially malicious traffic.

WAFW00F can be used to identify whether a web application appears to be protected by a known WAF.

---

### 4. Zenmap / Nmap

**Nmap** is widely used for network discovery and security auditing.

During the project, I explored concepts including:

- Host discovery
- Port scanning
- Open ports
- Service identification
- Network enumeration

**Zenmap** provides a graphical interface for Nmap, making scan results easier to visualize and understand.

---

## 🧪 Lab Environment

### Operating System

- Kali Linux

### Environment

- Virtual Machine / Authorized Lab Environment

### Purpose

All activities documented in this repository are intended for:

- Educational purposes
- Authorized security testing
- Personal labs
- Cybersecurity learning environments

---

## 📚 What I Learned

Through this project, I developed a better understanding of:

- The importance of reconnaissance in cybersecurity
- Passive and active information gathering
- Domain intelligence
- Web technology fingerprinting
- WAF identification
- Network discovery
- Port and service enumeration
- Basic security assessment methodology
- Using Kali Linux reconnaissance tools
- Documenting technical findings

---

## 🔐 Ethical & Legal Disclaimer

This repository is created for **educational and authorized cybersecurity purposes only**.

The tools and techniques demonstrated here should only be used against:

- Systems you own
- Your own virtual machines
- Intentionally vulnerable lab environments
- Systems where you have explicit permission to perform security testing

Unauthorized scanning, enumeration, or security testing of systems and networks may violate laws, policies, or terms of service.

**Always obtain proper authorization before performing security testing.**

---

## 📂 Project Structure

```text
cybersecurity-reconnaissance-lab/
│
├── README.md
│
├── screenshots/
│   ├── whois/
│   ├── whatweb/
│   ├── wafw00f/
│   └── nmap/
│
├── notes/
│   ├── information-gathering.md
│   ├── web-reconnaissance.md
│   └── network-reconnaissance.md
│
└── reports/
    └── reconnaissance-report.md
