# 🔐 Cybersecurity Home Lab

**Attacker:** Kali Linux | **Targets:** Metasploitable 2, Ubuntu | **SIEM:** Splunk (Windows 11) | **Platform:** VirtualBox


## Writeups
| # | Attack | Writeup |
|---|--------|---------|
| 1 | MySQL Unauthenticated Access & Credential Harvesting | [View PDF](./Lab1_MySQL_Unauthenticated_Access_&_Credential_Harvesting) |
| 2 | ARP Poisoning & Man-in-the-Middle Attack | [View PDF](./Lab2_ARP_Poisoning_&_Man_In_The_Middle(MITM)_Attack) |
| 3 | SSH Brute Force Detection Using Splunk SIEM | [View PDF](./Lab3_SSH_Brute_Force_Detection_Using_Splunk_SIEM.pdf) |


## Lab Environment
- Kali Linux (Attacker) — 192.168.56.101
- Metasploitable 2 (Target) — 192.168.56.103
- Ubuntu (Victim/Log Source) — 192.168.56.102
- Windows 11 Host (Splunk SIEM) — 192.168.56.1
- Network: VirtualBox Host-Only Adapter

## Tools Used
- Nmap, MySQL Client,
- arpspoof, Wireshark, dsniff
- Splunk Enterprise, Splunk Universal Forwarder, Hydra, OpenSSH

## Skills Demonstrated
### Lab 1 — MySQL Unauthenticated Access & Credential Harvesting
- Network Reconnaissance
- Service Enumeration
- Database Exploitation
- Credential Harvesting

### Lab 2 — ARP Poisoning & Man-in-the-Middle Attack
- ARP Cache Poisoning
- Man-in-the-Middle Attack
- Network Traffic Interception
- Plaintext Credential Sniffing
- Wireshark Packet Analysis

### Lab 3 — SSH Brute Force Detection Using Splunk SIEM
- SIEM Deployment & Configuration (Splunk Enterprise)
- Log Forwarding & Aggregation (Splunk Universal Forwarder)
- SSH Brute Force Simulation (Hydra)
- SPL Query Writing & Log Analysis
- Threat Detection & Alerting
- Blue Team / SOC L1 Detection Workflow
- MITRE ATT&CK Mapping (T1110.001)


