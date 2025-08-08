# Principles-of-Security-TryHackMe-Writeup
This writeup covers the key lessons from the "Principles of Security" room on TryHackMe, highlighting the foundational concepts of information security and defense in depth strategies.

---

## Overview

The "Principles of Security" room introduces critical frameworks and models used to protect systems, networks, and data in cybersecurity. It covers the **CIA Triad**, **privilege management**, **security models**, **threat modeling**, and **incident response**, with a focus on applying layered defenses.

---

## Key Concepts Learned

### Defense in Depth

- A security strategy involving multiple layers of security controls across the system stack.
- Helps reduce risk by adding redundancy—if one layer fails, others still protect the system.

### The CIA Triad

1. **Confidentiality**
   - Prevents unauthorized data access.
   - Real-world example: HR records only accessible to HR admins.
   - Techniques: Access controls, encryption, classification systems.

2. **Integrity**
   - Ensures data is accurate and unmodified unless authorized.
   - Examples: Checksums, digital signatures, strict access control.
   - Key concern in systems like software repositories and financial records.

3. **Availability**
   - Ensures systems and data are accessible when needed.
   - Measures: Redundant infrastructure, backups, DDoS protection.

---

## Privilege Management

- **PIM (Privileged Identity Management)**: Maps user roles to access roles.
- **PAM (Privileged Access Management)**: Manages and enforces those access roles, password policies, audit logging, and more.
- **Least Privilege Principle**: Users should only have the minimum necessary access to perform their duties.

---

## Security Models

### Bell-LaPadula (Confidentiality-Focused)
- "No read up, no write down."
- Used by military and government organizations.
- Trust-based access, assumes vetted users.

### Biba Model (Integrity-Focused)
- "No write up, no read down."
- Used in environments where data integrity is more important than secrecy.
- Example: Developers only modify specific source code components.

---

## Threat Modeling

- Threat modeling helps proactively assess risks to a system or application.
- Steps include:
  - Preparation
  - Identification
  - Mitigation
  - Review

### STRIDE Model (by Microsoft)
| Principle         | Description |
|------------------|-------------|
| **Spoofing**      | Faking identity. Solved by authentication and keys. |
| **Tampering**     | Altering data. Solved with anti-tampering controls. |
| **Repudiation**   | Denying actions. Solved with logging and monitoring. |
| **Information Disclosure** | Leaking data. Prevent with proper access control. |
| **Denial of Service (DoS)** | Crashing or overloading a service. Solved with rate-limiting, redundancy. |
| **Elevation of Privilege** | Gaining unauthorized privileges. Solved with role-based access control. |

---

## Incident Response

When breaches occur, a **Computer Security Incident Response Team (CSIRT)** handles the situation using a 6-phase process:

1. **Preparation** – Establish policies, tools, and training.
2. **Identification** – Detect and assess the incident.
3. **Containment** – Limit damage and prevent spread.
4. **Eradication** – Remove the threat actor or malware.
5. **Recovery** – Restore normal operations.
6. **Lessons Learned** – Post-incident analysis and improvement.

---

## Summary

This room emphasized the importance of layered defenses and holistic security frameworks. The foundational concepts of **confidentiality, integrity, and availability** were tied to real-world implementations through privilege management, threat modeling, and structured response plans. These principles form the backbone of modern cybersecurity operations and align closely with SOC practices.

---

## Use in Cybersecurity Career

This knowledge is foundational for roles such as:

- Security Analyst (SOC Level 1)
- Governance, Risk, and Compliance (GRC) Specialist
- Incident Responder
- Security Engineer
