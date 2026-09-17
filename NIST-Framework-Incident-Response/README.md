# Incident Report Analysis: ICMP Flood DoS Attack

## Overview
This project analyzes a Denial-of-Service (DoS) attack that disrupted access to internal network resources for approximately two hours. The investigation determined that the network experienced an ICMP flood attack, resulting in degraded performance and service availability.

## Incident Summary
- Internal users were unable to access critical network resources.
- Network performance was significantly degraded.
- The outage lasted approximately two hours.
- Analysis revealed excessive ICMP traffic consistent with a DoS attack.
- An unconfigured firewall contributed to the success of the attack.

## NIST Cybersecurity Framework Application

### Identify
- Conducted an incident investigation and security audit.
- Determined that an improperly configured firewall allowed malicious traffic to reach the network.

### Protect
Implemented the following security controls:
- ICMP rate limiting via firewall rules.
- Source IP address verification to detect spoofed traffic.
- Network monitoring software.
- Intrusion Detection and Prevention System (IDS/IPS).

### Detect
Improved detection capabilities through:
- Network monitoring tools.
- IDS/IPS deployment.
- Source IP verification processes.

### Respond
- Blocked malicious ICMP traffic.
- Isolated non-critical services during the incident.
- Contained the attack to restore network stability.

### Recover
- Restored critical services.
- Returned systems to normal operation.
- Resumed business activities following validation of service availability.

## Security Concepts
- Denial-of-Service (DoS)
- ICMP Flood Attacks
- Firewall Configuration
- Network Monitoring
- Intrusion Detection and Prevention
- Incident Response
- NIST Cybersecurity Framework

## Skills Demonstrated
- Incident analysis
- Network security investigation
- Firewall hardening
- Threat detection
- Security monitoring
- Incident response documentation

## Project Outcome
The analysis identified an ICMP flood attack enabled by insufficient firewall protections. By implementing rate limiting, traffic filtering, monitoring, and IDS/IPS controls, the organization improved its ability to prevent, detect, and respond to future denial-of-service attacks.

---

*This project was completed as part of my cybersecurity portfolio and demonstrates foundational incident response, network defense, and security operations skills.*
