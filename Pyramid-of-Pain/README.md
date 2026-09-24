# Pyramid of Pain: Malware Investigation Using VirusTotal

## Overview

This project documents the investigation of a malicious file identified during a Security Operations Center (SOC) alert. As a Level 1 SOC analyst, I analyzed a suspicious file downloaded by an employee after they opened a password-protected spreadsheet attachment received through a phishing email. The investigation focused on identifying Indicators of Compromise (IoCs), Threat Tactics, Techniques, and Procedures (TTPs), and other artifacts using VirusTotal and threat intelligence analysis. 【1-823bb7】

## Scenario

A financial services employee received an email containing a password-protected spreadsheet attachment. The password was included in the email. After downloading and opening the file, a malicious payload was executed on the employee's workstation.

To investigate the incident, a SHA-256 hash of the malicious file was generated and submitted to VirusTotal. The resulting analysis provided information about the malware's behavior, associated IoCs, and threat intelligence indicators. 【1-823bb7】

## Objectives

- Analyze a malicious file using VirusTotal
- Identify Indicators of Compromise (IoCs)
- Discover associated network artifacts
- Identify attacker TTPs
- Understand how threat intelligence supports incident response
- Apply the Pyramid of Pain framework

## Malware Analysis Results

### File Classification

The file was identified as malicious and classified as a Trojan. Multiple antivirus vendors detected the file as malicious, indicating a high confidence malware identification. 【1-823bb7】

### File Hashes

**MD5**
```text
287d612e29b71c90aa54947313810a25
```

**SHA-1**
```text
8f35a9e70dbec8f1904991773f394cd4f9a07f5e
```

**SHA-256**
```text
54e6ea47eb04634d3e87fd7787e2136ccfbcc80ade34f246a12cf93bab527f6b
```
【1-823bb7】

## Indicators of Compromise (IoCs)

### Network Artifacts

#### URL

```text
http://org.misecure.com/index.html
```

#### Domain

```text
a-0003.a-msedge.net
```

#### Network Connection

```text
TCP 142.251.188.94:443 (www.gstatic.com)
```
【1-823bb7】

### IP Address

```text
104.115.151.81
```
【1-823bb7】

## Tactics, Techniques, and Procedures (TTPs)

### MITRE ATT&CK Technique

**T1539 - Steal Web Session Cookie**

This technique is used by threat actors to steal session cookies and potentially gain unauthorized access to authenticated web sessions. 【1-823bb7】

## Tools Observed

The VirusTotal analysis identified behavior associated with:

```text
service-scan
```

This behavior may indicate reconnaissance or service discovery activity on compromised systems or networks. 【1-823bb7】

## Pyramid of Pain Analysis

This project demonstrates several levels of the Pyramid of Pain:

### Hash Values
- MD5
- SHA-1
- SHA-256

### IP Addresses
- 104.115.151.81

### Domain Names
- a-0003.a-msedge.net

### Network Artifacts
- http://org.misecure.com/index.html

### TTPs
- T1539: Steal Web Session Cookie

As organizations move higher in the Pyramid of Pain, detections become more effective because attackers must significantly modify their infrastructure and behavior to evade detection.

## Skills Demonstrated

- Malware Analysis
- Threat Intelligence
- Indicator of Compromise (IoC) Analysis
- VirusTotal Investigation
- MITRE ATT&CK Mapping
- Security Operations Center (SOC) Procedures
- Incident Investigation
- Pyramid of Pain Methodology

## Outcome

This investigation demonstrated how threat intelligence platforms such as VirusTotal can be used to analyze malicious files, identify attacker infrastructure, and collect actionable Indicators of Compromise. By mapping findings to the Pyramid of Pain, security analysts can improve detection capabilities and develop more resilient defensive strategies against future attacks.
