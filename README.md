# Boost Mobile GRC Risk Assessment (Field Report)

Author: Abinav Joshi  
Date of Visit: July 11, 2025  
Location: Boost Mobile Franchise (WIT LLC), Florissant, MO  
Role: GRC (Field Assessment)

---

##  Project Overview

This project documents a real-world Governance, Risk, and Compliance (GRC) field assessment conducted at a Boost Mobile retail store operated by WIT LLC. The objective was to evaluate the security posture, identify compliance gaps, and map observed risks to industry-standard frameworks including:

- NIST Cybersecurity Framework (CSF)
- ISO/IEC 27001
- SOC 2 Trust Services Criteria
- GDPR (due to EU customer presence)

---

## Key Areas Assessed

- Endpoint security on outdated Windows 10 system (Pentium CPU, 4GB RAM)
- Software usage (Elevate, ePay WebPOS, Clover POS)
- Access control and credential handling
- Data privacy and retention
- Physical and operational security

---

## Summary of Observations

| Risk Area            | Observation                                                           | Risk Level |
|----------------------|------------------------------------------------------------------------|------------|
| Plaintext Credentials| Sticky notes and local Word file containing passwords                | High       |
| Unchanged PINs       | Devices sold with default factory PINs (e.g., 1010)                   | Medium     |
| Outdated System      | No antivirus, no patching, slow performance                           | Medium     |
| POS Access           | Clover POS allows guest login with no restrictions                    | High       |
| GDPR Exposure        | EU customer data stored with no deletion/retention policy             | High       |

---

## Framework Mapping

| Control | Description                                  | Framework Reference          |
|---------|----------------------------------------------|------------------------------|
| PR.AC-1 | Limit access to authorized users             | NIST CSF                     |
| A.9.2.1 | User access provisioning                     | ISO/IEC 27001                |
| A.12.6.1| Technical vulnerability management           | ISO/IEC 27001                |
| DE.CM-7 | Monitor for unauthorized access              | NIST CSF                     |
| PI-1    | Data retention and disposal rules            | SOC 2 (Privacy), GDPR        |

---

##  Recommendations

- Implement unique logins and remove guest POS access  
- Encrypt sensitive files and use password vaults  
- Install antivirus and regularly patch OS  
- Define formal data retention policy for PII  
- Train employees on basic cybersecurity hygiene  
- Draft internal IT and access control policies

---

## Full Report

Read the full assessment report that is posted as a PDF in the same repo folder.

---

## Interview Talking Point

> I performed a live GRC field assessment for a retail Boost Mobile store. I identified critical compliance issues related to endpoint protection, access control, and GDPR exposure, and mapped my findings to NIST CSF and ISO 27001. I provided actionable recommendations in a structured report, now published on GitHub.

---

##  Frameworks Used

- [NIST Cybersecurity Framework](https://www.nist.gov/cyberframework)
- [ISO/IEC 27001:2022](https://www.iso.org/isoiec-27001-information-security.html)
- [SOC 2 Trust Services Criteria](https://www.aicpa.org/resources/article/trust-services-criteria)
- [GDPR Key Principles](https://gdpr.eu)

