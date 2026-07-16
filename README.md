# Wazuh SOC Lab – Security Monitoring and Threat Detection

A hands-on Security Operations Center (SOC) lab built using **Wazuh SIEM**, **Ubuntu Server**, **Windows 11**, and **Sysmon**. This project demonstrates the deployment of a centralized security monitoring environment capable of collecting Windows event logs, performing threat hunting, and detecting common attack techniques.

---

## Project Overview

The primary objective of this project was to gain practical experience with Security Operations Center (SOC) workflows by building a Wazuh-based SIEM environment from scratch.

The project demonstrates:

- Deployment of the Wazuh platform on Ubuntu Server
- Windows endpoint monitoring using the Wazuh Agent
- Sysmon integration for detailed endpoint telemetry
- Windows Event Log collection and analysis
- Threat hunting using the Wazuh Dashboard
- Detection of common attack techniques
- MITRE ATT&CK mapping for detected events

---

## Features

- Wazuh SIEM deployment on Ubuntu Server
- Windows endpoint monitoring
- Sysmon integration
- Real-time security event collection
- Threat hunting using the Wazuh Dashboard
- Detection of PowerShell, Command Prompt, executable drop, and brute-force attacks
- MITRE ATT&CK technique mapping

---

## Lab Architecture

The lab consists of an Ubuntu Server hosting the Wazuh platform and a Windows 11 endpoint configured with the Wazuh Agent and Sysmon. Security events generated on the Windows endpoint are forwarded to the Wazuh Server, where they are analyzed and displayed through the Wazuh Dashboard.

```text
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

---

## Technologies Used

| Component | Purpose |
|-----------|---------|
| Ubuntu Server | Hosts the Wazuh platform |
| Wazuh SIEM | Security monitoring and log analysis |
| Windows 11 | Endpoint for attack simulation |
| Sysmon | Advanced Windows event logging |
| Wazuh Agent | Endpoint log collection |
| MITRE ATT&CK | Attack technique mapping |

---

## Repository Structure

```text
Wazuh-SOC-Lab/
├── README.md
├── LICENSE
├── docs/
│   ├── 01-lab-setup.md
│   ├── 02-wazuh-installation.md
│   ├── 03-agent-and-sysmon.md
│   ├── 04-threat-hunting.md
│   ├── 05-attack-simulation.md
│   └── 06-summary.md
├── screenshots/
└── LICENSE
```

---

## Documentation

Detailed documentation is available in the **docs** folder.

- [Chapter 1 – Lab Setup](docs/01-lab-setup.md)
- [Chapter 2 – Wazuh Installation](docs/02-wazuh-installation.md)
- [Chapter 3 – Windows Agent and Sysmon](docs/03-agent-and-sysmon.md)
- [Chapter 4 – Threat Hunting](docs/04-threat-hunting.md)
- [Chapter 5 – Attack Simulations](docs/05-attack-simulation.md)
- [Chapter 6 – Project Summary](docs/06-summary.md)

---

## Disclaimer

All attack simulations were performed in a controlled laboratory environment for educational purposes only.
