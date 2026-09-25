# Phishing Incident Investigation and Escalation

## Overview

This project documents the investigation of a phishing-related security alert as a Level 1 Security Operations Center (SOC) analyst. Using an incident response playbook and an incident handler's journal, I analyzed a suspicious email, identified Indicators of Compromise (IoCs), validated a malicious file hash through threat intelligence, and determined the appropriate escalation path for the incident.

## Scenario

A phishing alert was generated after a user received a suspicious email containing a malicious attachment. The email attempted to masquerade as a job application and used social engineering techniques, including a password-protected attachment. When the attachment was opened, a malicious payload was executed, resulting in a potential compromise of organizational systems. 【1-4b0f8d】

## Alert Information

- **Ticket ID:** A-2703
- **Alert:** SERVER-MAIL Phishing attempt possible download of malware
- **Severity:** Medium
- **Status:** Escalated to L2 SOC Analyst 【1-4b0f8d】

## Investigation Process

The investigation followed a phishing incident response playbook and included:

- Reviewing the alert details
- Analyzing the email message
- Identifying phishing indicators
- Collecting Indicators of Compromise (IoCs)
- Investigating the malicious attachment
- Validating the file hash using threat intelligence
- Documenting findings in the incident handler's journal
- Escalating the incident according to SOC procedures

## Indicators of Compromise (IoCs)

### Malicious File Hash

```text
54e6ea47eb04634d3e87fd7787e2136ccfbcc80ade34f246a12cf93bab527f6b
