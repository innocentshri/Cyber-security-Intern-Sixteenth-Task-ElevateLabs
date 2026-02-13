# Task 16 – Incident Response & Security Breach Simulation

## Objective
The objective of this task is to simulate a basic security incident, analyze system logs to detect suspicious activity, perform incident response steps, and document incident handling and recovery actions.

---

## Tools Used
- Linux Authentication Logs
- Windows Event Viewer
- TheHive 

---

## What is Incident Response?
Incident response is the process of detecting, analyzing, containing, and recovering from security incidents.

It helps organizations minimize damage and restore normal operations quickly.

---

## Incident Simulation Scenario

Simulated Incident:
Repeated failed login attempts detected on the system.

Possible Attack Type:
Brute-force login attempt or unauthorized access attempt.

---

## Incident Response Methodology

### 1. Incident Detection
Detected suspicious activity through:
- Multiple failed login attempts
- Unusual login time
- Repeated access attempts

---

### 2. Log Analysis
Analyzed:
- Authentication logs
- System logs
- Security events

Purpose:
Identify attack source and behavior pattern.

---

### 3. Incident Classification
Classified as:
Unauthorized Access Attempt (Brute Force Attack)

Severity Level:
Medium to High depending on frequency and success.

---

### 4. Incident Containment
Actions Taken:
- Locked affected user account
- Blocked suspicious IP address
- Restricted login attempts

Purpose:
Stop ongoing attack.

---

### 5. Threat Removal & Root Cause Fix
Actions:
- Reset compromised passwords
- Enforced stronger password policy
- Enabled account lockout rules

---

### 6. System Recovery
Actions:
- Verified system integrity
- Restored normal user access
- Confirmed no malware or persistence mechanisms

---

## Incident Timeline

| Time | Event |
|---|---|
| 10:00 AM | Multiple failed logins detected |
| 10:05 AM | Logs analyzed |
| 10:10 AM | Attack source identified |
| 10:15 AM | Account locked |
| 10:20 AM | IP blocked |
| 10:30 AM | Password reset |
| 10:45 AM | System verified secure |

---

## Security Improvements Recommended
- Implement Multi-Factor Authentication (MFA)
- Enforce strong password policy
- Enable account lockout
- Continuous log monitoring
- Intrusion detection system deployment

---

## Security Benefits
- Faster incident detection
- Reduced attack impact
- Improved monitoring capability
- Stronger authentication security

---

## Ethical Considerations
All simulations performed:
- In lab or authorized environment
- For educational purposes only
- Without impacting real users or production systems

---

## Summary
This task improved understanding of:
- Incident handling workflow
- Log-based attack detection
- Incident containment strategies
- Root cause analysis
- Security recovery process

---

## Final Outcome
Developed practical understanding of incident response lifecycle and breach handling process.

---

## Sources & References

1. NIST Incident Response Guide  
https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-61r2.pdf  

2. SANS Incident Response Process  
https://www.sans.org/white-papers/incident-handlers-handbook/  

3. OWASP Incident Response  
https://owasp.org/www-community/Incident_Response  

4. Microsoft Security Incident Response  
https://learn.microsoft.com/en-us/security/operations/incident-response-overview  

5. TheHive Project  
https://thehive-project.org/
