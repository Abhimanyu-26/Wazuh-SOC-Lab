# Chapter 6 - Project Summary

## Project Overview

This project demonstrated the deployment of a Security Operations Center (SOC) lab using Wazuh SIEM, Ubuntu Server, Windows 11, and Sysmon. The environment was configured to collect endpoint telemetry, monitor security events, and detect common attack techniques through practical simulations.

---

## Technologies Used

| Component | Purpose |
|-----------|---------|
| Ubuntu Server | Hosts the Wazuh platform |
| Wazuh SIEM | Security monitoring and log analysis |
| Windows 11 | Endpoint for attack simulation |
| Wazuh Agent | Sends endpoint logs to the server |
| Sysmon | Advanced Windows event logging |
| MITRE ATT&CK | Attack technique mapping |

---

## Project Workflow

The overall workflow of the project was:

1. Ubuntu Server was installed.
2. Wazuh platform was deployed.
3. Windows endpoint was connected using the Wazuh Agent.
4. Sysmon was installed to collect detailed event logs.
5. Security events were monitored through the Wazuh Dashboard.
6. Multiple attack simulations were performed.
7. Wazuh detected the attacks and generated alerts for investigation.

---

## Key Achievements

- Successfully deployed a functional Wazuh SOC lab.
- Configured Windows endpoint monitoring.
- Integrated Sysmon with Wazuh.
- Performed threat hunting using the Wazuh Dashboard.
- Simulated multiple attack scenarios.
- Verified Wazuh alert generation and MITRE ATT&CK mapping.

---

## Conclusion

The Wazuh SOC Lab successfully demonstrated how a SIEM platform can collect endpoint logs, monitor security events, and detect suspicious activities in real time. This project provided practical experience in SOC operations, threat hunting, endpoint monitoring, and security event analysis using open-source technologies.

The knowledge gained from this project forms a strong foundation for understanding modern Security Operations Center workflows and incident detection techniques.
