# 🔐 Cybersecurity Home Lab

**Attacker:** Kali Linux | **Targets:** Metasploitable 2, Ubuntu | **SIEM:** Splunk (Windows 11) | **Platform:** VirtualBox


## Writeups
| # | Attack | Writeup |
|---|--------|---------|
| 1 | MySQL Unauthenticated Access & Credential Harvesting | [View PDF](./Lab1_MySQL_Unauthenticated_Access_&_Credential_Harvesting.pdf) |
| 2 | ARP Poisoning & Man-in-the-Middle Attack | [View PDF](./Lab2_ARP_Poisoning_&_Man_In_The_Middle(MITM)_Attack.pdf) |
| 3 | SSH Brute Force Detection Using Splunk SIEM | [View PDF](./Lab3_SSH_Brute_Force_Detection_Using_Splunk_SIEM.pdf) |
| 4 | Windows Event Log Detection – RDP Brute Force via Splunk SIEM | [View PDF](./Lab4_Windows_Event_Log_Detection%2–%2RDP_Brute_Force_via_Splunk_SIEM.pdf) |



## Lab Environment
- Kali Linux (Attacker) — 192.168.56.101
- Metasploitable 2 (Target) — 192.168.56.103
- Ubuntu (Victim/Log Source) — 192.168.56.102
- Windows 11 Host (Splunk SIEM) — 192.168.56.1
- Network: VirtualBox Host-Only Adapter

## Tools Used
- Lab1:Nmap, MySQL Client,
- Lab2:Arpspoof, Wireshark, Dsniff
- Lab3:Splunk Enterprise, Splunk Universal Forwarder, Hydra, OpenSSH
- Lab4:Splunk Enterprise, Hydra, Nmap, Windows Audit Policy

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

### Lab 4 – Windows Event Log Detection – RDP Brute Force via Splunk SIEM
- Windows Audit Policy Configuration (secpol.msc)
- Windows Security Event Log Analysis (Event ID 4624/4625)
- Splunk Local Event Log Ingestion & SPL Querying
- RDP Brute Force Simulation (Hydra)
- Network Reconnaissance (Nmap)
- SIEM Alert Creation & Threshold-Based Detection
- MITRE ATT&CK Mapping (T1110, T1021.001, T1046, T1078)



