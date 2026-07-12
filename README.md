# Wazuh SOC Lab

A hands-on Security Operations Center (SOC) lab built using Wazuh SIEM, Sysmon, Ubuntu Server, and Windows. This project demonstrates how to deploy a monitoring environment, collect Windows event logs, and detect common attack techniques through real-world simulations.

## Project Overview

The goal of this lab was to gain practical experience with SOC operations by building a small detection environment from scratch. The lab focuses on log collection, threat hunting, and identifying suspicious Windows activity using Wazuh and Sysmon.

The project includes:

- Wazuh Server installation on Ubuntu
- Windows agent deployment
- Sysmon configuration
- Windows Event Log monitoring
- Threat hunting using the Wazuh Dashboard
- Detection of multiple attack techniques
- MITRE ATT&CK mapping

> This project was created as a practical learning lab to strengthen SOC Analyst skills and understand how endpoint telemetry can be used to detect malicious activit


## Lab Architecture

The lab consists of a Wazuh server running on Ubuntu Server and a Windows endpoint configured with Sysmon. Windows event logs are collected by the Wazuh agent and forwarded to the Wazuh manager for analysis. The Wazuh Dashboard is then used to perform threat hunting, investigate alerts, and review MITRE ATT&CK mappings.

```
Ubuntu Server
├── Wazuh Manager
├── Wazuh Indexer
└── Wazuh Dashboard
        │
        │
Windows 11 Endpoint
├── Wazuh Agent
├── Sysmon
└── Windows Event Logs
        │
        ▼
Threat Detection & Alert Analysis
```

## Technologies Used

| Component | Purpose |
|----------|---------|
| Ubuntu Server | Hosts the Wazuh platform |
| Wazuh SIEM | Log collection and threat detection |
| Windows 11 | Endpoint for attack simulation |
| Sysmon | Advanced Windows event logging |
| Windows Event Logs | Security monitoring |
| MITRE ATT&CK | Attack technique mapping |
