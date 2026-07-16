# Chapter 6 – Project Summary

## Project Overview

This project demonstrates the deployment of a Security Information and Event Management (SIEM) environment using Wazuh on Ubuntu Server. A Windows endpoint was connected using the Wazuh Agent and Sysmon to collect detailed system events. The collected logs were analyzed through the Wazuh Dashboard to detect and investigate simulated attack activities.

---

## Skills Demonstrated

During this project, the following practical skills were developed:

- Ubuntu Server administration
- Basic Linux command-line operations
- Wazuh SIEM installation and configuration
- Windows endpoint onboarding
- Sysmon deployment and configuration
- Threat hunting using the Wazuh Dashboard
- Windows Event Log analysis
- Security alert investigation
- Basic incident analysis
- MITRE ATT&CK framework interpretation

---

## MITRE ATT&CK Techniques Observed

| Technique ID | Technique |
|--------------|-------------------------------|
| T1059.001 | PowerShell |
| T1059.003 | Windows Command Shell |
| T1105 | Ingress Tool Transfer |
| T1087 | Account Discovery |
| T1110 | Brute Force (Multiple Failed Logons) |

---

## Key Outcomes

- Successfully deployed the Wazuh platform on Ubuntu Server.
- Connected a Windows endpoint using the Wazuh Agent.
- Configured Sysmon to generate detailed Windows events.
- Performed threat hunting using the Wazuh Dashboard.
- Simulated multiple attack techniques and verified successful detection.
- Investigated alerts mapped to the MITRE ATT&CK framework.

---

## Future Improvements

This lab can be further expanded by:

- Monitoring multiple endpoints
- Integrating Sigma detection rules
- Creating custom Wazuh detection rules
- Building automated incident response workflows
- Integrating email or Slack alert notifications
- Visualizing security metrics with dashboards

---

## Conclusion

This project provided practical experience in deploying, configuring, and using Wazuh as a SIEM platform for endpoint monitoring and threat detection. It also strengthened my understanding of SOC workflows, Windows event analysis, and attack detection using the MITRE ATT&CK framework.
