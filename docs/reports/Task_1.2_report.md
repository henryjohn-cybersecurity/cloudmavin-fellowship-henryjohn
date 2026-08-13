# Task 1.2 Report

## Framework Mapping Exercise

## Executive Summary

This task demonstrates how a phishing attack can be analyzed using three industry-recognized cybersecurity frameworks: the NIST Cybersecurity Framework (CSF) 2.0, the NICE Workforce Framework for Cybersecurity, and the MITRE ATT&CK Framework. The exercise shows how governance, workforce responsibilities, and attacker behavior can all be viewed from a single cybersecurity incident.

---

## Objectives

- Understand the NIST Cybersecurity Framework (CSF) 2.0 functions.
- Identify cybersecurity work roles using the NICE Workforce Framework.
- Map attacker activities using the MITRE ATT&CK Framework.
- Demonstrate the relationship between these frameworks using one practical incident.

---

## Methodology

1. Selected a realistic phishing attack scenario.
2. Analyzed the incident using the six NIST CSF 2.0 functions.
3. Identified three NICE Workforce roles involved in the incident response.
4. Mapped the attacker's activities to the MITRE ATT&CK Framework.
5. Documented the results in a one-page framework mapping.

---

## Technical Report

### Incident Description

An employee receives a phishing email pretending to be from Microsoft 365. The employee clicks the malicious link and enters their login credentials. The attacker successfully logs into the employee's account and accesses confidential company documents.

---

### NIST Cybersecurity Framework (CSF) 2.0 Mapping

| CSF Function | Application to the Incident |
|--------------|-----------------------------|
| **Govern** | Establish cybersecurity policies, password policies, and employee awareness training. |
| **Identify** | Identify Microsoft 365 accounts, email systems, and sensitive company information as critical assets. |
| **Protect** | Use strong passwords, Multi-Factor Authentication (MFA), email filtering, and user awareness training. |
| **Detect** | Monitor login attempts, review security alerts, and identify suspicious account activity. |
| **Respond** | Disable compromised accounts, reset passwords, investigate the incident, and notify relevant stakeholders. |
| **Recover** | Restore normal operations, verify account security, and improve security controls based on lessons learned. |

---

### NICE Workforce Framework Roles

| Work Role | Responsibility |
|-----------|----------------|
| **Security Analyst** | Monitors systems, identifies suspicious activities, and analyzes security events. |
| **Incident Responder** | Investigates the phishing incident, contains the attack, and coordinates recovery activities. |
| **Security Administrator** | Resets compromised accounts, implements security controls, and strengthens system security. |

---

### MITRE ATT&CK Tactics

| Tactic | Description |
|--------|-------------|
| **Initial Access** | The attacker gains access through a phishing email. |
| **Credential Access** | The attacker steals the employee's login credentials. |
| **Persistence** | The attacker maintains unauthorized access to the compromised account. |
| **Collection** | The attacker accesses and collects confidential company documents. |

---

## Commands Used

No Linux commands were required for this task because it involved analytical mapping and documentation rather than system configuration.

---

## Findings

The exercise demonstrated that a single phishing incident can be analyzed from multiple cybersecurity perspectives. The NIST Cybersecurity Framework focuses on managing organizational cybersecurity risk, the NICE Workforce Framework identifies the cybersecurity professionals responsible for responding to the incident, and the MITRE ATT&CK Framework explains the attacker's tactics and techniques throughout the attack lifecycle.

---

## Risk Rating

**High**

**Reason:**

Phishing attacks present a high risk because they can result in credential theft, unauthorized access to systems, data breaches, financial losses, and reputational damage if effective security controls are not implemented.

---

## Recommendations

- Enforce Multi-Factor Authentication (MFA) for all user accounts.
- Conduct regular phishing awareness and cybersecurity training for employees.
- Continuously monitor user login activity for suspicious behavior.
- Implement advanced email filtering and anti-phishing solutions.
- Regularly review and update incident response procedures.
- Perform periodic phishing simulation exercises to assess user awareness.

---

## Lessons Learned

This task enhanced my understanding of three major cybersecurity frameworks and demonstrated how they complement one another in analyzing and responding to cybersecurity incidents. I also gained a better appreciation of the importance of governance, workforce responsibilities, and attacker behavior in effective cybersecurity risk management.

---

## References

- NIST Cybersecurity Framework (CSF) 2.0
- NICE Workforce Framework for Cybersecurity
- MITRE ATT&CK Framework

---

## AI Usage Declaration

Artificial Intelligence (ChatGPT by OpenAI) was used as a learning assistant to explain cybersecurity concepts, improve documentation quality, and review the report structure. All practical analysis, documentation, and final submissions were personally completed, reviewed, and understood by the student.
