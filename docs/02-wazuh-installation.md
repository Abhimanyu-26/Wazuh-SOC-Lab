# Chapter 2 - Wazuh Installation

## Objective

The objective of this chapter is to install the Wazuh platform on the Ubuntu Server and verify that the installation completed successfully. The Wazuh Dashboard provides the interface used for monitoring security events and alerts.

---

## Step 1 - Downloading the Wazuh Installer

The official Wazuh installation script was downloaded from the Wazuh website. This script automates the installation of the Wazuh Indexer, Manager, and Dashboard.

### Screenshot

![Wazuh Installer Download](../screenshots/4_Wazuh%20installer%20download%20verified.png)

*Figure 4: Verification of the downloaded Wazuh installer.*

---

## Step 2 - Wazuh Installation Completed

The installation script completed successfully, installing all required Wazuh components on the Ubuntu Server.

### Screenshot

![Wazuh Installation Success](../screenshots/5_wazuh%20installation%20success.png)

*Figure 5: Successful Wazuh installation.*

---

## Step 3 - Accessing the Wazuh Dashboard

The Wazuh Dashboard was accessed securely through HTTPS on port 443 using a web browser running on the Windows host machine.

URL used:

```text
https://<Ubuntu_Server_IP>
```

### Screenshot

![Wazuh Dashboard](../screenshots/6_dashboard%20https%20port%20443.png)

*Figure 6: Wazuh Dashboard accessed through HTTPS.*

---

## Outcome

At the end of this chapter:

- Wazuh components were installed successfully.
- The Wazuh Dashboard was accessible through HTTPS.
- The SOC environment was ready for endpoint integration.
