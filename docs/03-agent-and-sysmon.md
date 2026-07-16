# Chapter 3 - Windows Agent and Sysmon

## Objective

The objective of this chapter is to connect the Windows endpoint to the Wazuh server and configure Sysmon for advanced Windows event logging. This enables Wazuh to collect detailed endpoint telemetry for threat detection.

---

## Step 1 - Windows Agent Connected

The Wazuh agent was installed on the Windows 11 endpoint and successfully connected to the Wazuh Manager running on the Ubuntu Server. The endpoint status was displayed as active in the Wazuh Dashboard.

### Screenshot

![Windows Agent Connected](../screenshots/7_windows%20agent%20connected%20active.png)

*Figure 7: Windows endpoint successfully connected to Wazuh.*

---

## Step 2 - Sysmon Installation

Sysmon was installed on the Windows endpoint to provide detailed monitoring of process creation, network connections, file creation, and other security-related events.

### Screenshot

![Sysmon Installation](../screenshots/11_sysmon%20installation%20success.png)

*Figure 8: Successful Sysmon installation.*

---

## Step 3 - Sysmon Events in Wazuh

After installation, Sysmon events were forwarded to the Wazuh Manager and displayed in the Wazuh Dashboard. These logs provide detailed visibility into endpoint activities for security monitoring.

### Screenshot

![Sysmon Events](../screenshots/12_sysmon%20events%20in%20wazuh.png)

*Figure 9: Sysmon events collected and displayed in Wazuh.*

---

## Outcome

At the end of this chapter:

- The Windows endpoint was successfully enrolled in Wazuh.
- Sysmon was installed and configured successfully.
- Windows event logs were forwarded to Wazuh for continuous monitoring.
