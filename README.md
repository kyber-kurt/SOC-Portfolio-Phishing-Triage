# SOC Portfolio Project #2  
## Phishing Email Triage – Login Theft Attempt


### Project Overview

This project simulates the triage and investigation of a phishing email reported by a user.  
It walks through a complete Tier 1 SOC response workflow, including header analysis, link reputation checking, user behavior review, and response actions.


### Alert Summary

**Alert Name:** Reported Suspicious Email – Possible Phishing  
**Source:** User-reported (via Outlook Report Phishing)  
**Severity:** High  
**Timestamp:** July 6, 2025 – 09:11 AM  

**Description:**  
User `s.parker@acmeinc.com` reported an email with the subject:  
**"[ACTION REQUIRED] Password Expiration Notice – Click to Keep Access"**  
The message impersonated Microsoft and included a suspicious login link. DKIM and DMARC failed, and the return-path domain mismatched.


### Triage Process

**1. Acknowledge and Assign Alert**  
**2. Review Email Metadata and Headers**  
**3. Analyze Link or Attachment**  
**4. Investigate User Behavior**  
**5. Scan for Lateral Spread or Other Targets**  
**6. Contain and Prevent**



### Findings and Analyst Decision

- Confirmed phishing attack impersonating Microsoft  
- Credential harvesting domain identified and blocked  
- User clicked but no data submitted  
- SOC response contained the threat  
- Preventative actions applied across the environment


### Skills Demonstrated

- Phishing triage and user reporting workflows  
- Email header analysis (SPF, DKIM, DMARC)  
- Malicious link investigation with VirusTotal and URLscan.io  
- Containment steps and communication  
- Clear documentation and escalation decisions

  (See PDF report for full details)
