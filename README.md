# 🛡️ 30-Day SOC Analyst Challenge – MyDFIR

![Platform](https://img.shields.io/badge/Platform-Azure-blue)
![OS](https://img.shields.io/badge/OS-Windows%20Server%202022%20%7C%20Ubuntu%2024.04-green)
![Elastic](https://img.shields.io/badge/Elastic-9.x-yellow)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📌 Overview

This repository documents my hands-on completion of the **30-Day SOC Analyst Challenge** created by **MyDFIR**.

The objective of this challenge was to build a practical Security Operations Center (SOC) lab from scratch and gain real-world experience with:

- Security Monitoring
- Log Collection
- SIEM Deployment
- Threat Detection
- Incident Investigation
- Ticketing Systems
- Endpoint Detection & Response (EDR)

Instead of only learning theory, I deployed and configured an end-to-end SOC environment using Microsoft Azure and Elastic Stack.

---

# 🏗️ SOC Lab Architecture

```
                    Internet
                        │
        ┌───────────────┴────────────────┐
        │                                │
        ▼                                ▼
 Ubuntu Server                     Windows Server 2022
(Fleet + Elasticsearch)          (Victim Machine)

        │                                │
        │ Elastic Agent                  │ Sysmon
        │                                │
        └──────────────┬─────────────────┘
                       │
                 Elasticsearch
                       │
                   Kibana SIEM
                       │
          Alerts • Dashboards • Detection Rules
                       │
                   Webhook Connector
                       │
                   osTicket Server
```

---

# 🎯 Objectives

- Deploy a cloud-based SOC lab
- Configure Elasticsearch and Kibana
- Deploy Fleet Server
- Install Elastic Agents
- Collect Windows and Linux logs
- Configure Sysmon
- Build SIEM dashboards
- Create Detection Rules
- Generate Security Alerts
- Integrate osTicket
- Investigate simulated attacks

---

# ☁️ Azure Infrastructure

| Component | Description |
|------------|-------------|
| Cloud Provider | Microsoft Azure |
| Ubuntu Server | Elasticsearch + Kibana + Fleet Server |
| Windows Server | Victim Machine |
| osTicket Server | Ticketing Platform |
| Networking | NSGs, Public IPs, Firewall Rules |

---

# 🛠️ Technologies Used

## SIEM

- Elasticsearch
- Kibana
- Fleet Server
- Elastic Agent

## Operating Systems

- Ubuntu Server 24.04
- Windows Server 2022

## Endpoint Monitoring

- Sysmon
- Elastic Defend

## Ticketing

- osTicket
- Webhook Connector

## Cloud

- Microsoft Azure

## Networking

- TCP/IP
- RDP
- SSH
- Windows Firewall
- Azure NSG

---

# 📅 Challenge Progress

| Day | Topic | Status |
|------|-------|--------|
| 1 | Logical Diagram | ✅ |
| 2 | ELK Stack Introduction | ✅ |
| 3 | Elasticsearch Setup | ✅ |
| 4 | Kibana Setup | ✅ |
| 5 | Windows Server Installation | ✅ |
| 6 | Fleet Server Introduction | ✅ |
| 7 | Fleet Server Deployment | ✅ |
| 8 | Sysmon Introduction | ✅ |
| 9 | Sysmon Installation | ✅ |
| 10 | Log Ingestion | ✅ |
| 11 | Brute Force Attack | ✅ |
| 12 | Ubuntu Server Installation | ✅ |
| 13 | Elastic Agent on Ubuntu | ✅ |
| 14 | Alerts & Dashboards | ✅ |
| 15 | RDP Introduction | ✅ |
| 16 | Detection Rules | ✅ |
| 17 | Dashboards | ✅ |
| 18 | Command & Control | ✅ |
| 19 | Attack Diagram | ✅ |
| 20 | Mythic Server Setup | ✅ |
| 21 | Mythic Agent Setup | ✅ |
| 22 | Advanced Dashboards | ✅ |
| 23 | Ticketing System | ✅ |
| 24 | osTicket Installation | ✅ |
| 25 | osTicket + ELK Integration | ✅ |
| 26 | SSH Brute Force Investigation | ✅ |
| 27 | RDP Brute Force Investigation | ✅ |
| 28 | Mythic Investigation | ✅ |
| 29 | Elastic Defend | ✅ |
| 30 | Troubleshooting | ✅ |

---

# 🔍 Skills Gained

- SIEM Administration
- Log Analysis
- Threat Hunting
- Incident Response
- SOC Operations
- Windows Event Logging
- Linux Log Analysis
- Elastic Stack Administration
- Fleet Management
- Sysmon Configuration
- Detection Engineering
- Dashboard Creation
- Azure Virtual Machines
- Network Security
- Ticketing Workflow
- Security Monitoring
- Endpoint Protection

---



# 📸 Screenshots

This repository includes screenshots of:

- Elasticsearch
- Kibana
- Fleet Server
- Elastic Agents
- Sysmon
- Detection Rules
- Dashboards
- Alerts
- osTicket Integration
- Incident Investigation
- Azure Infrastructure

---

# 🎓 Key Learning Outcomes

By completing this challenge, I learned how to:

- Build a SOC lab from scratch
- Deploy Elastic Stack
- Configure Fleet Server
- Monitor Windows and Linux endpoints
- Collect and analyze logs
- Detect brute-force attacks
- Investigate attacker activity
- Create SIEM dashboards
- Configure alerting rules
- Automate incident creation using osTicket
- Perform basic SOC investigations

---

# 📚 Credits

This project is based on the excellent **30-Day SOC Analyst Challenge** created by **MyDFIR**.

The repository contains **my own lab implementation, configurations, notes, and documentation** completed while following the challenge.

---



# 👨‍💻 Author

**Abdul Ahad Memon**

Computer Science Student | SOC Analyst Enthusiast | Cybersecurity Learner

- GitHub: https://github.com/ahadxdev
- LinkedIn: https://linkedin.com/in/abdul-ahad-memon-b27801332

---

## ⭐ If you found this repository useful, consider giving it a star!
