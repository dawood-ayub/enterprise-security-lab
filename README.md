# Enterprise Security Lab

## Overview
This project documents the design and implementation of an enterprise-style cybersecurity lab built to simulate real-world attack, detection, and incident response scenarios.

The lab is designed to reflect how security operations teams work in corporate environments, focusing on visibility, logging, and detection rather than isolated tool usage.

## Lab Architecture
The environment consists of the following systems:

- **DC01** – Windows Server 2019 (Active Directory Domain Controller)
- **WS01** – Windows 10 (Employee Workstation)
- **WEB01** – Ubuntu Server (Web Application + Linux Logs)
- **SIEM01** – Wazuh SIEM (Centralized Logging & Detection)
- **ATTACK01** – Kali Linux (External Attacker)

A segmented internal corporate network is used to simulate enterprise infrastructure with an external attacker interacting through defined attack paths.

## Objectives
- Simulate realistic enterprise attacks (AD, web, credential-based)
- Detect malicious activity using centralized logging
- Perform incident response and forensic analysis
- Map attacks to MITRE ATT&CK framework
- Document findings in a professional, interview-ready format

## Tools & Technologies
- Kali Linux
- Windows Server 2019
- Windows 10
- Ubuntu Server
- Wazuh SIEM
- Wireshark
- Nmap
- Metasploit
- Elastic Stack

## Status
Lab environment is currently under active development.
Daily progress, configurations, and reports will be added incrementally.
