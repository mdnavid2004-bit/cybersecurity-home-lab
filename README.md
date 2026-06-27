# 🔐 Cybersecurity Home Lab

**Attacker:** Kali Linux | **Target:** Metasploitable 2 | **Platform:** VirtualBox

## Writeups
| # | Attack | Writeup |
|---|--------|---------|
| 1 | MySQL Unauthenticated Access & Credential Harvesting | [View PDF](./Lab_Writeup_MySQL_Attack_Navid_Final.pdf) |
| 2 | ARP Poisoning & Man-in-the-Middle Attack | [View PDF](./ARP%20Poisoning%20MITM%20Lab%20Writeup.pdf) |
| 3 | SSH Brute Force Detection Using Splunk SIEM | [View PDF](./SSH_BruteForce_Splunk_Detection.pdf) |


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
- Network Reconnaissance
- Service Enumeration
- Database Exploitation
- Credential Harvesting
- ARP Cache Poisoning
- Man-in-the-Middle Attack
- Network Traffic Interception
- Plaintext Credential Sniffing

