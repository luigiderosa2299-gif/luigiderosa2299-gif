# Hi, I'm Luigi De Rosa 👋

**Aspiring Cybersecurity Professional** — focus su detection engineering, SIEM, cloud security (Azure) e Active Directory, in preparazione per CompTIA Security+ (SY0-701).

## 🎯 Current Focus
- Detection Engineering & SIEM (Splunk, Microsoft Sentinel)
- Cloud Security (Microsoft Azure, Defender for Cloud/Endpoint)
- Incident Response & Threat Hunting
- Network Security & Secure Architecture Design
- CompTIA Security+ (SY0-701) — in preparazione

## 📜 Certifications
- ✅ CompTIA Network+
- 🔄 CompTIA Security+ — *in preparazione*
- 🔄 HTB CPTS — *in progress*

## 🛠 Projects

### Detection Engineering & SIEM
| Progetto | Descrizione | Stack / Focus |
|---|---|---|
| [SSH Brute Force Detection Lab](https://github.com/luigiderosa2299-gif/ssh-brute-force-detection-lab) | SIEM lab con Splunk: dashboard a 4 pannelli, kill chain completa simulata (recon → exploitation → post-exploitation → exfiltration → cleanup), query SPL scritte da zero | Splunk, SPL, Linux (Kali), Python/paramiko |
| [Honeypot Incident Response Lab](https://github.com/luigiderosa2299-gif/honeypot-incident-response-lab) | Honeypot Azure (VM + MySQL con dati fittizi) attaccato end-to-end da me stesso, rilevato in tempo reale da 3 regole di detection custom su Microsoft Sentinel, ciclo completo di incident response (detection → analisi → contenimento → eradicazione) | Azure, Microsoft Sentinel, Defender for Cloud, KQL, MySQL |
| [Threat Hunt TOR Lab](https://github.com/luigiderosa2299-gif/threat-hunt-tor-lab) | Threat hunting su uso non autorizzato di TOR Browser, basato sullo scenario ufficiale di The Cyber Range: indagine manuale su schema EDR Microsoft Defender for Endpoint, timeline forense e report finale | Microsoft Defender for Endpoint, KQL Advanced Hunting, Azure |

### Hardening & Vulnerability Management
| Progetto | Descrizione | Stack / Focus |
|---|---|---|
| [Linux Security Audit — Lynis](https://github.com/luigiderosa2299-gif/linux-security-audit-lynis) | Audit di sicurezza Linux con Lynis: baseline, remediation mirata (fail2ban, PAM password quality), confronto misurabile dell'hardening index prima/dopo | Lynis, Linux (Kali), CIS Benchmarks |

### Fondamenta: Networking, Malware Analysis, Lab Environment
| Progetto | Descrizione | Stack / Focus |
|---|---|---|
| [Trading Floor Support Center — Secure & Redundant Network Infrastructure](https://github.com/luigiderosa2299-gif/Trading-Floor-Support-Center-Secure-Redundant-Network-Infrastructure) | Progettazione di una rete enterprise sicura e ridondata (600 utenti, 6 dipartimenti) con Cisco Packet Tracer: VLAN segmentation, port security, ACL, OSPF, dual-ISP redundancy, SSHv2 | Cisco Packet Tracer, VLAN, OSPF, ACL, Port Security |
| [Home Lab — Cybersecurity Practice Environment](https://github.com/luigiderosa2299-gif/home-lab-cybersecurity) | Lab personale virtualizzato (Kali Linux + DVWA su UTM) per network scanning e vulnerability assessment, documentato con architettura, evidenze e troubleshooting reale | UTM/QEMU, Kali Linux, Nmap |
| [Python Keylogger — Malware Analysis & Detection](https://github.com/luigiderosa2299-gif/python-keylogger-lab) | Keylogger didattico scritto da zero in Python, affiancato da una regola YARA e uno script di detection comportamentale, entrambi testati con risultati reali | Python, pynput, YARA, psutil |

> Altri progetti in arrivo mano a mano che completo i laboratori pratici del percorso Security+.

## 📐 Come documento i progetti
Ogni progetto ha un proprio repository con README strutturato: obiettivo, contesto, tecnologie usate, steps/configurazione, risultati, evidenza tecnica per ogni fase (comandi reali, output, screenshot), e — quando applicabile — un confronto misurabile prima/dopo.

## 📫 Contatti
- GitHub: [@luigiderosa2299-gif](https://github.com/luigiderosa2299-gif)
