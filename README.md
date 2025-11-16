# Network and Security Fundamentals  

This repository contains my hands-on practical work in networking, cyber security, and defensive operations, completed as part of my BSc in Cyber Security at ECU.

It serves as a collection of technical labs, write-ups, and configurations demonstrating my skills in:

- Network scanning & enumeration
- Firewall configuration
- Secure remote access
- Traffic capture & protocol analysis
- Honeypot deployment and log investigation
- Encryption, hashing, and key management

These labs build my foundation for future work in SOC analysis, blue teaming, and network defense.

## Tools & Technologies  
- **Ubuntu / Kali Linux** – primary environments for configuration and testing  
- **Nmap** – network and service scanning  
- **Wireshark** – packet capture and protocol inspection  
- **Linux Firewalls (iptables / nftables)** – packet filtering, NAT, and custom rule sets  
- **OpenSSH (with Google Authenticator MFA)** – secure remote access and multi-factor authentication setup
- **Cowrie Honeypot** – simulating SSH attacks and analyzing malicious activity  
- **Encryption Methods** – symmetric & asymmetric cryptography (AES, RSA)  
- **Log Analysis** – reviewing system, firewall, and honeypot logs for anomalies

## Repository Structure
```
network-security-labs/
│
│
├── network-protocol-analysis/   # TCP, packet capture, Wireshark, Nmap
│     ├── tcp-handshake.md
│     ├── nmap-scanning.md
│
├── firewall-configuration/      # iptables & nftables labs
│     ├── iptables-basics.md
│
├── ssh-security/                # OpenSSH + MFA
│     ├── openssh-and-MFA-setup.md
│
├── honeypot-analysis/           # Cowrie deployment & attacker behaviour
│     ├── cowrie-setup-and-log-analysis
│
└── encryption-practice/
      ├── encryption-practice.md
```

## What I’ve Learned
- Practical understanding of TCP/IP, ports, protocols, and packet flows
- Experience performing network reconnaissance using Nmap
- Ability to configure Linux firewalls for secure access control
- Hands-on experience securing SSH with public keys + MFA
- Exposure to real attacker behaviour using a Cowrie honeypot
- Understanding of encryption, hashing, and key generation
- Stronger command-line, investigation, and analysis skills
