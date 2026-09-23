# Incident Response Journal: Ransomware Attack Investigation

## Overview

This project documents the investigation of a ransomware attack against a healthcare clinic. The incident was analyzed using the incident response process and the 5 W's framework to identify what happened, how the attackers gained access, the business impact, and the actions required to contain and remediate the threat. The exercise demonstrates fundamental security operations, incident handling, and ransomware investigation skills. 【1-66aa4f】

## Scenario

A small U.S. healthcare clinic experienced a ransomware attack on a Tuesday morning at approximately 9:00 AM. Multiple employees reported that they were unable to access patient records and other critical business files. Attackers successfully compromised the organization through phishing emails containing malicious attachments. Once executed, the malware encrypted critical files across multiple systems and displayed a ransom note demanding payment in exchange for a decryption key.

As a result, business operations were disrupted, employees were unable to perform their duties, and the clinic was forced to shut down affected systems while seeking technical assistance and reporting the incident to appropriate organizations.

## Objectives

- Investigate the ransomware incident
- Apply the 5 W's incident analysis methodology
- Identify the attack vector and root cause
- Assess the impact on business operations
- Recommend containment and recovery actions
- Document findings in an incident handler's journal

## Tools Used

- Splunk
- System and security log analysis
- Incident response procedures 【1-66aa4f】

## Incident Summary

### Attack Vector
The attackers used targeted phishing emails containing malicious attachments. Employees downloaded the files, which installed ransomware on their systems and encrypted critical organizational data. 【1-66aa4f】

### Impact

- Loss of access to medical records
- Disruption of healthcare services
- Multiple affected workstations
- Shutdown of business operations
- Potential regulatory and compliance concerns
- Financial and reputational risk

## The 5 W's Analysis

### Who?
Employees who interacted with the phishing emails inadvertently initiated the infection process. The ransomware was deployed by an organized cybercriminal group known for targeting healthcare organizations. 【1-66aa4f】

### What?
Ransomware encrypted critical files and systems, preventing employees from accessing applications and patient records. A ransom note was displayed demanding payment for file recovery. 【1-66aa4f】

### When?
Tuesday at approximately 9:00 AM. 【1-66aa4f】

### Where?
Multiple employee workstations throughout the healthcare clinic were affected. 【1-66aa4f】

### Why?
Employees were targeted through phishing emails that contained malicious files. After the files were downloaded and executed, the ransomware spread and encrypted data across affected systems. 【1-66aa4f】

## Findings

### Security Weaknesses Identified

- Users were susceptible to phishing attacks.
- Malicious attachments were successfully executed.
- Endpoint protections did not prevent ransomware execution.
- Critical business systems became unavailable after encryption.

### Potential Risks

- Exposure of patient information
- Regulatory penalties
- Data loss
- Extended downtime
- Financial losses
- Reputational damage

## Recommendations

### Immediate Actions

- Isolate infected systems from the network.
- Preserve logs and forensic evidence.
- Determine whether data exfiltration occurred prior to encryption.
- Restore systems using clean backups when available.

### Long-Term Improvements

- Conduct phishing awareness training.
- Deploy email filtering and attachment scanning.
- Implement Endpoint Detection and Response (EDR).
- Apply the principle of least privilege.
- Enable regular backup testing and recovery procedures.
- Establish a formal incident response plan.

## Skills Demonstrated

- Incident Response
- Security Monitoring
- Log Analysis
- Phishing Investigation
- Malware Analysis
- Ransomware Response
- Threat Identification
- Documentation and Reporting

## Outcome

This project demonstrates the ability to investigate and document a ransomware incident, identify the root cause, evaluate business impact, and recommend practical security controls. These skills are essential for cybersecurity analysts responsible for detecting, responding to, and recovering from security incidents in real-world environments.
