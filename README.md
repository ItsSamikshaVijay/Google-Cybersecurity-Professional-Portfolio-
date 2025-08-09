
# Cybersecurity Reports – README

## Overview

This repository contains five security-related reports covering different aspects of cybersecurity practices, incidents, and assessments. These documents detail vulnerabilities, risk assessments, incident responses, and security news analyses, along with recommended solutions and mitigation strategies.

---

## **1. Penetration Testing Mini-Report**

**Summary:**
This report focuses on a penetration test targeting **Vsftpd v2.3.4** on a Metasploitable 2 environment using Kali Linux. The identified vulnerability is a **backdoor** within this version of Vsftpd, allowing an attacker to gain a root shell by logging in with a specially crafted username.
**Key Points:**

* **Vulnerability:** Built-in backdoor allowing remote shell access.
* **Impact:** Potential for data theft, defacement, server hijacking, DDoS launching, and persistent malware.
* **Mitigation:** Use firewalls, antivirus with RAT/Trojan detection, and network monitoring tools.
* **Conclusion:** Organizations should regularly reassess risks and close such critical vulnerabilities immediately.

---

## **2. Security Risk Assessment Report**

**Summary:**
A security assessment for a social media company after a **major data breach** revealed four major vulnerabilities: password sharing, default admin credentials, lack of firewall traffic filtering, and absence of MFA.
**Key Points:**

* **Risks:** Increased chance of repeated breaches without remediation.
* **Recommendations:**

  1. **Implement MFA** to restrict access to authorized users only.
  2. **Revise baseline configurations** to eliminate default passwords and enforce password policies.
  3. **Apply port filtering** to reduce attack surface.
* **Approach:** Regular policy reviews and patch updates.

---

## **3. Incident Report Analysis**

**Summary:**
Documents the response to an **ICMP flood (DDoS) attack** that rendered company network services inaccessible. The cause was an **unconfigured firewall** that allowed the malicious traffic.
**Key Points:**

* **Incident Type:** DDoS via ICMP flood.
* **Response:** Blocking ICMP traffic, isolating affected networks, restoring critical services first.
* **Mitigation Measures:** Network segmentation, firewall rules limiting ICMP, IP spoofing checks, IDS/IPS deployment, and traffic monitoring.
* **Recovery Steps:** Gradual service restoration after attack subsides.

---

## **4. Security News Research Exercise**

**Summary:**
A research-based report summarizing three current cybersecurity threats and breaches with recommended mitigation strategies:

1. **Phishing Trends (2025):** Surge in AI-driven phishing attacks, QR code phishing, BEC scams, and deepfake-based social engineering.

   * *Solution:* AI-based email filtering, behavior-driven phishing awareness training.
2. **Access Control Weakness – Life Insurance Company Breach:** Compromised sensitive data including SSNs and medical claim details.

   * *Solution:* Zero Trust model, SIEM, SOAR, XDR technologies, continuous monitoring.
3. **Third-Party Vendor Breach – Grubhub:** Data stolen via compromised vendor account.

   * *Solution:* Thorough vendor risk assessments, continuous monitoring, stronger contractual security requirements.

---

## **5. Vulnerability Assessment Report**

**Summary:**
Evaluates the access control security of a Linux-based MySQL database server with 128GB memory and IPv4 networking.
**Key Points:**

* **Value of Asset:** Stores critical business data including employee, customer, and confidential records.
* **Risks Identified:**

  * External hacking attempts.
  * Dependency on other public servers increasing attack vectors.
* **Risk Scoring:** Based on likelihood and severity using NIST SP 800-30 methodology.
* **Remediation:** Strong authentication and authorization, role-based access controls, MFA, TLS encryption, IP allow-listing.

---

## Suggested Usage

These documents can serve as:

* Training resources for new cybersecurity team members.
* Reference material for penetration testers and risk assessors.
* Evidence for security compliance documentation.
* Case studies in academic or corporate cybersecurity training.

---

Do you want me to also create a **table at the top of the README** that quickly compares the **type of report, threat type, and mitigation focus** for all five documents? That would make it easier for someone scanning the README to find what they need fast.
