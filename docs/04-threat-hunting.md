# Chapter 4 - Threat Hunting

## Objective

The objective of this chapter is to perform threat hunting using the Wazuh Dashboard. Security events collected from the Windows endpoint were analyzed to identify suspicious activities and understand the details of generated alerts.

---

## Step 1 - Threat Hunting Dashboard

The Threat Hunting module in the Wazuh Dashboard was used to search, filter, and analyze security events collected from the Windows endpoint.

### Screenshot

![Threat Hunting Dashboard](../screenshots/8_threat%20hunting%20page.png)

*Figure 10: Threat Hunting page in the Wazuh Dashboard.*

---

## Step 2 - Rule Details

Each generated alert was examined to view the associated Wazuh rule, severity level, MITRE ATT&CK mapping, and event information.

### Screenshot

![Rule Details](../screenshots/9_rule%20details.png)

*Figure 11: Detailed information of a Wazuh detection rule.*

---

## Step 3 - Failed Login Detection

A failed Windows logon attempt was simulated to verify that Wazuh correctly detected the event and generated a corresponding security alert.

### Screenshot

![Failed Login Detection](../screenshots/10_failed%20login%20detection.png)

*Figure 12: Detection of a failed Windows logon attempt.*

---

## Outcome

At the end of this chapter:

- Threat hunting features of Wazuh were successfully explored.
- Alert details and MITRE ATT&CK mappings were analyzed.
- Failed login attempts were detected and recorded for investigation.
