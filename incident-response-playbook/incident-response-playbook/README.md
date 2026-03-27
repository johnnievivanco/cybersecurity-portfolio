## Incident Response Playbook: Phishing Attack Scenario

### Overview
Created a simulated incident response playbook for handling a phishing-based security incident. This project demonstrates how a security team detects, contains, eradicates, and recovers from an attack while minimizing business impact.

---

### Scenario
An employee receives a phishing email impersonating a trusted service. The email contains a malicious link designed to capture login credentials. The user reports the email to the security team before interacting with it.

---

### Objective
To document a structured incident response process for handling phishing attacks and demonstrate understanding of real-world SOC workflows.

---

### Incident Type
Phishing / Social Engineering Attack

---

### Response Workflow
1. User reports suspicious email to IT/security team  
2. Security analyst reviews email content and sender domain  
3. Malicious indicators are confirmed (spoofed domain, suspicious link)  
4. Email is blocked and removed from user inboxes  
5. Potentially affected accounts are secured  
6. Systems and logs are reviewed for signs of compromise  
7. Incident is documented and prevention measures are updated  

---

### Detection and Analysis
- Reviewed email content and identified spoofed sender address  
- Observed urgency-based language and impersonation tactics  
- Analyzed embedded link for malicious behavior  
- Determined risk of credential theft  

---

### Supporting Evidence
This scenario is based on phishing indicators analyzed in prior projects, including spoofed domains, malicious links, and social engineering techniques commonly used in credential theft attacks.

---

### Indicators of Compromise (IOCs)
- Spoofed sender domain (e.g., paypa1-support.com)
- Suspicious login URL embedded in email
- Urgent language prompting immediate action
- Generic greeting (“Dear Customer”)

---

### Containment
- Blocked malicious domain and sender  
- Prevented further email delivery  
- Instructed user not to interact with the email  
- Disabled account if compromise was suspected  

---

### Eradication
- Removed phishing emails from inboxes  
- Reset potentially compromised credentials  
- Scanned systems for malware or persistence mechanisms  
- Verified no unauthorized email forwarding rules were created  

---

### Recovery
- Restored secure user access  
- Re-enabled systems after validation  
- Monitored logs for suspicious login attempts  
- Confirmed normal operations resumed  

---

### Lessons Learned
- Users are primary targets for phishing attacks  
- Security awareness training is critical  
- Email filtering controls should be improved  
- Early reporting significantly reduces risk  

---

### Tools Used
- Email analysis techniques  
- Splunk (log monitoring concepts)  
- Endpoint protection tools  
- Account access controls  

---

### Business Impact
A successful phishing attack could result in credential theft, unauthorized access, data breaches, financial loss, and reputational damage. Effective incident response minimizes downtime and reduces overall risk.

---

### Key Takeaways
- Learned the full lifecycle of incident response  
- Practiced documenting a real-world security incident  
- Improved understanding of containment, eradication, and recovery  
- Strengthened ability to communicate incidents clearly  

---

### Key Skills Demonstrated
- Incident response  
- Threat analysis  
- Security documentation  
- Risk mitigation  
- Business impact analysis  
