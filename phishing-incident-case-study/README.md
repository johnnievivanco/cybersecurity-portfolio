# Phishing Attack → Credential Compromise

> This project is part of my cybersecurity portfolio focused on incident response and threat detection.

---

## Overview

This case study simulates a phishing attack resulting in credential compromise and demonstrates a structured incident response workflow aligned with real-world security operations.

---

## Scenario

A user unknowingly submitted credentials to a malicious phishing site. Shortly after, an unauthorized login was detected from a foreign IP address.

---

## Detection

- Anomalous login activity from an unfamiliar geographic location  
- User-reported suspicious activity  
- Authentication behavior inconsistent with normal usage  

---

## Triage

- Correlated login activity with user-reported phishing interaction  
- Validated foreign IP access with no expected travel or VPN usage  
- Confirmed unauthorized access as a credential compromise  

---

## Investigation

- Reviewed authentication logs for additional suspicious activity  
- Checked for repeated login attempts or session persistence  
- Verified no lateral movement or additional account compromise  

---

## Containment

- Disabled the compromised account  
- Forced password reset to invalidate credentials  
- Revoked active sessions and authentication tokens  
- Blocked the originating malicious IP  

---

## Outcome

- Threat successfully contained  
- No evidence of lateral movement  
- Account access restored securely  

---

## Skills Demonstrated

- Incident response workflow  
- Threat validation and triage  
- Security event investigation  
- Containment strategy and communication  
