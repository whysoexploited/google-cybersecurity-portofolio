# TCP SYN Flood Incident Analysis

## Overview
This project investigates a website outage caused by a suspected Denial-of-Service (DoS) attack. By analyzing network logs and connection attempts, I identified signs of a TCP SYN flood targeting the web server.

## Key Findings
- Analyzed failed HTTPS connections to the web server (port 443).
- Observed repeated SYN requests originating from a single source IP address.
- Identified indicators consistent with a TCP SYN flood attack.
- Investigated the impact of excessive connection requests on server availability.
- Determined that legitimate users experienced connection timeouts due to resource exhaustion.

## Technical Concepts
- TCP Three-Way Handshake
- SYN, SYN-ACK, and ACK communication
- HTTPS (Port 443)
- Denial-of-Service (DoS) attacks
- TCP SYN Flood attacks
- Network log analysis

## Skills Demonstrated
- Incident analysis
- Network traffic investigation
- Attack identification
- TCP/IP fundamentals
- Cybersecurity reporting and documentation

## Tools Used
- Log analysis
- Packet and traffic inspection
- Incident response methodology

## Project Outcome
The analysis concluded that the website outage was consistent with a TCP SYN flood attack, where a large number of connection requests exhausted server resources and prevented legitimate users from accessing the website.

---

*This project was completed as part of my cybersecurity portfolio and demonstrates foundational incident response and network traffic analysis skills.*
