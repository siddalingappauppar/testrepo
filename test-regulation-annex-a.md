# Annex A — Technical Standards for Data Storage and Security

**Parent Regulation:** EU Data Act EDGB/2026/003
**Effective Date:** 2026-03-01

---

## A.1 Encryption Requirements

All employee personal data at rest must be encrypted using a minimum of **AES-256** standard. Data in transit must use **TLS 1.3** or higher.

## A.2 Data Centre Certification

Approved data centres must hold at least one of the following certifications:

- ISO/IEC 27001:2022
- SOC 2 Type II
- EU Cloud Code of Conduct (EU Cloud CoC) Level 3

## A.3 Backup and Recovery

Employers must maintain automated backups with the following parameters:

- Backup frequency: at least every **24 hours**
- Recovery Point Objective (RPO): maximum **4 hours**
- Recovery Time Objective (RTO): maximum **8 hours**
- Backup retention period: minimum **3 years**

## A.4 Access Controls

- Multi-factor authentication (MFA) is mandatory for all systems processing personal data
- Access logs must be retained for a minimum of **2 years**
- Privileged access reviews must be conducted every **6 months**

## A.5 Audit Requirements

An independent security audit must be performed annually by a certified third-party auditor. Audit reports must be submitted to the relevant supervisory authority within **60 days** of completion.
