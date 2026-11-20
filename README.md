# Hi, I'm Luigi De Rosa 👋

**Aspiring Cybersecurity Professional** — focused on detection engineering, SIEM, cloud security (Azure) and Active Directory, preparing for CompTIA Security+ (SY0-701).

## 🎯 Current Focus
- Detection Engineering & SIEM (Splunk, Microsoft Sentinel)
- Cloud Security (Microsoft Azure, Defender for Cloud/Endpoint)
- Incident Response & Threat Hunting
- Network Security & Secure Architecture Design
- CompTIA Security+ (SY0-701) — in preparation

## 📜 Certifications
- ✅ CompTIA Network+
- 🔄 CompTIA Security+ — *in preparation*
- 🔄 HTB CPTS — *in progress*

## 🛠 Projects

### Detection Engineering & SIEM
| Project | Description | Stack / Focus |
|---|---|---|
| [SSH Brute Force Detection Lab](https://github.com/luigiderosa2299-gif/ssh-brute-force-detection-lab) | SIEM lab with Splunk: 4-panel dashboard, full simulated kill chain (recon → exploitation → post-exploitation → exfiltration → cleanup), SPL queries written from scratch | Splunk, SPL, Linux (Kali), Python/paramiko |
| [Honeypot Incident Response Lab](https://github.com/luigiderosa2299-gif/honeypot-incident-response-lab) | Azure honeypot (VM + MySQL with fictitious data) attacked end-to-end by myself and detected in real time by 3 custom detection rules in Microsoft Sentinel, with the full incident response cycle (detection → analysis → containment → eradication) | Azure, Microsoft Sentinel, Defender for Cloud, KQL, MySQL |
| [Threat Hunt TOR Lab](https://github.com/luigiderosa2299-gif/threat-hunt-tor-lab) | Threat hunting for unauthorized TOR Browser use, based on the official The Cyber Range scenario: manual investigation on the Microsoft Defender for Endpoint EDR schema, forensic timeline and final report | Microsoft Defender for Endpoint, KQL Advanced Hunting, Azure |

### Cyber Threat Intelligence & Compliance
| Project | Description | Stack / Focus |
|---|---|---|
| [CTI Report — Campagna StreamRat/XWorm](https://github.com/luigiderosa2299-gif/cti-ssn-streamrat-xworm) | Full CTI analysis of a real malicious campaign (fake Italian National Health Service site): source evaluation with the Admiralty Code, IOC collection and enrichment, OSINT infrastructure pivoting (discovery of multi-country reuse), MITRE ATT&CK Enterprise + Mobile mapping, link to NIS2 measures (D.Lgs. 138/2024, the Italian transposition) | OSINT, VirusTotal, ThreatFox, Censys/Certificate Transparency, MITRE ATT&CK Navigator, NIS2 |

### Networking & Scripting
| Project | Description | Stack / Focus |
|---|---|---|
| [TCP Port Scanner & Banner Grabber](https://github.com/luigiderosa2299-gif/tcp-port-scanner) | TCP port scanner written from scratch in Python with banner grabbing (SSH + HTTP) and multithreading, behavior verified with a real packet capture (tcpdump) | Python, socket, argparse, concurrent.futures |

### Hardening & Vulnerability Management
| Project | Description | Stack / Focus |
|---|---|---|
| [Linux Security Audit — Lynis](https://github.com/luigiderosa2299-gif/linux-security-audit-lynis) | Linux security audit with Lynis: baseline, targeted remediation (fail2ban, PAM password quality), measurable before/after comparison of the hardening index | Lynis, Linux (Kali), CIS Benchmarks |

### Foundations: Networking, Malware Analysis, Lab Environment
| Project | Description | Stack / Focus |
|---|---|---|
| [Trading Floor Support Center — Secure & Redundant Network Infrastructure](https://github.com/luigiderosa2299-gif/Trading-Floor-Support-Center-Secure-Redundant-Network-Infrastructure) | Design of a secure, redundant enterprise network (600 users, 6 departments) with Cisco Packet Tracer: VLAN segmentation, port security, ACLs, OSPF, dual-ISP redundancy, SSHv2 | Cisco Packet Tracer, VLAN, OSPF, ACL, Port Security |
| [Home Lab — Cybersecurity Practice Environment](https://github.com/luigiderosa2299-gif/home-lab-cybersecurity) | Personal virtualized lab (Kali Linux + DVWA on UTM) for network scanning and vulnerability assessment, documented with architecture, evidence and real troubleshooting | UTM/QEMU, Kali Linux, Nmap |
| [Python Keylogger — Malware Analysis & Detection](https://github.com/luigiderosa2299-gif/python-keylogger-lab) | Educational keylogger written from scratch in Python, paired with a YARA rule and a behavioral detection script, both tested with real results | Python, pynput, YARA, psutil |

## 📐 How I Document My Projects
Each project has its own repository with a structured README: objective, context, technologies used, steps/configuration, results, technical evidence for each phase (real commands, output, screenshots) and, where applicable, a measurable before/after comparison.

## 📫 Contact
- GitHub: [@luigiderosa2299-gif](https://github.com/luigiderosa2299-gif)
