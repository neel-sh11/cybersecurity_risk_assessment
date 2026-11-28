# 06 — Statement of Applicability (SoA)

| Field | Details |
|---|---|
| Organisation | Nexora Solutions Pvt. Ltd. (fictional) |
| Document | 06 — Statement of Applicability |
| Framework | ISO/IEC 27001:2022, Annex A (93 controls) |
| Version | 2.0 |
| Status | Preliminary — Simulated |

---

## 1. Purpose

This document lists **all 93 Annex A controls** of ISO/IEC 27001:2022 and records a decision for each one. It links the 23 controls selected through risk treatment to the risks in `04_risk_assessment.md` and `05_risk_treatment_plan.md`.

---

## 2. Decision Categories

| Decision | Meaning |
|---|---|
| **Selected** | Chosen to treat one or more of the nine assessed risks. Tracked in `07_control_implementation_tracker.md`. |
| **Pending** | Presumed applicable to an IT services company, but not driven by the nine simulated risks. Needs a full applicability assessment in a real ISMS. |
| **Out of scope** | Outside this assessment's scope (physical security, see `01`). Applicable in reality, but not assessed here. |
| **Not applicable** | Not relevant to the organisation as described, with a stated reason. |

"Selected" does **not** mean implemented. Every control is currently unverified.

---

## 3. Summary

| Category | Total | Selected | Pending | Out of scope | Not applicable |
|---|---|---|---|---|---|
| A.5 Organisational | 37 | 6 | 31 | 0 | 0 |
| A.6 People | 8 | 1 | 7 | 0 | 0 |
| A.7 Physical | 14 | 0 | 0 | 14 | 0 |
| A.8 Technological | 34 | 16 | 17 | 0 | 1 |
| **Total** | **93** | **23** | **55** | **14** | **1** |

---

## 4. A.5 — Organisational Controls (37)

| ID | Control | Decision | Risks | Justification / note |
|---|---|---|---|---|
| A.5.1 | Policies for information security | Pending | — | Foundation of any ISMS; priority for the next iteration |
| A.5.2 | Information security roles and responsibilities | Pending | — | Proposed roles are in `01`; formal assignment not assessed |
| A.5.3 | Segregation of duties | Pending | — | — |
| A.5.4 | Management responsibilities | Pending | — | — |
| A.5.5 | Contact with authorities | Pending | — | — |
| A.5.6 | Contact with special interest groups | Pending | — | — |
| A.5.7 | Threat intelligence | Pending | — | — |
| A.5.8 | Information security in project management | Pending | — | — |
| A.5.9 | Inventory of information and other associated assets | Pending | — | Partly addressed by `02_asset_inventory.md` |
| A.5.10 | Acceptable use of information and other associated assets | Pending | — | — |
| A.5.11 | Return of assets | Pending | — | — |
| A.5.12 | Classification of information | Pending | — | Four levels defined in `02`; formal scheme not assessed |
| A.5.13 | Labelling of information | Pending | — | — |
| A.5.14 | Information transfer | Pending | — | — |
| A.5.15 | Access control | **Selected** | R03, R04, R08, R09 | Limits access to client, employee, source code and financial data |
| A.5.16 | Identity management | Pending | — | — |
| A.5.17 | Authentication information | **Selected** | R01 | Reduces credential theft and reuse |
| A.5.18 | Access rights | **Selected** | R03, R08, R09 | Controls joiner, mover and leaver access |
| A.5.19 | Information security in supplier relationships | Pending | — | Third-party risk is acknowledged but not yet assessed |
| A.5.20 | Addressing information security within supplier agreements | Pending | — | As above |
| A.5.21 | Managing information security in the ICT supply chain | Pending | — | As above |
| A.5.22 | Monitoring, review and change management of supplier services | Pending | — | As above |
| A.5.23 | Information security for use of cloud services | **Selected** | R04 | Addresses cloud exposure and shared responsibility |
| A.5.24 | Information security incident management planning and preparation | **Selected** | R01–R09 | Cross-cutting response capability |
| A.5.25 | Assessment and decision on information security events | Pending | — | — |
| A.5.26 | Response to information security incidents | Pending | — | — |
| A.5.27 | Learning from information security incidents | Pending | — | — |
| A.5.28 | Collection of evidence | Pending | — | — |
| A.5.29 | Information security during disruption | Pending | — | Related to A.5.30 |
| A.5.30 | ICT readiness for business continuity | **Selected** | R02, R07 | Supports recovery after ransomware or hardware failure |
| A.5.31 | Legal, statutory, regulatory and contractual requirements | Pending | — | Indian law and client contracts noted in `01` |
| A.5.32 | Intellectual property rights | Pending | — | — |
| A.5.33 | Protection of records | Pending | — | — |
| A.5.34 | Privacy and protection of PII | Pending | — | Relevant to client and employee personal data |
| A.5.35 | Independent review of information security | Pending | — | — |
| A.5.36 | Compliance with policies, rules and standards for information security | Pending | — | — |
| A.5.37 | Documented operating procedures | Pending | — | — |

---

## 5. A.6 — People Controls (8)

| ID | Control | Decision | Risks | Justification / note |
|---|---|---|---|---|
| A.6.1 | Screening | Pending | — | — |
| A.6.2 | Terms and conditions of employment | Pending | — | — |
| A.6.3 | Information security awareness, education and training | **Selected** | R01, R02, R03 | Reduces phishing success and data misuse |
| A.6.4 | Disciplinary process | Pending | — | — |
| A.6.5 | Responsibilities after termination or change of employment | Pending | — | Related to A.5.18 |
| A.6.6 | Confidentiality or non-disclosure agreements | Pending | — | — |
| A.6.7 | Remote working | Pending | — | Remote access is part of the IT environment in `01` |
| A.6.8 | Information security event reporting | Pending | — | Related to A.5.24 |

---

## 6. A.7 — Physical Controls (14)

Physical security is outside the scope of this assessment (see `01_organisation_profile.md`). These controls are presumed applicable in a real organisation but have not been assessed.

| ID | Control | Decision | Risks | Justification / note |
|---|---|---|---|---|
| A.7.1 | Physical security perimeters | Out of scope | — | Physical security not assessed |
| A.7.2 | Physical entry | Out of scope | — | As above |
| A.7.3 | Securing offices, rooms and facilities | Out of scope | — | As above |
| A.7.4 | Physical security monitoring | Out of scope | — | As above |
| A.7.5 | Protecting against physical and environmental threats | Out of scope | — | As above |
| A.7.6 | Working in secure areas | Out of scope | — | As above |
| A.7.7 | Clear desk and clear screen | Out of scope | — | As above |
| A.7.8 | Equipment siting and protection | Out of scope | — | As above |
| A.7.9 | Security of assets off-premises | Out of scope | — | As above |
| A.7.10 | Storage media | Out of scope | — | As above |
| A.7.11 | Supporting utilities | Out of scope | — | As above |
| A.7.12 | Cabling security | Out of scope | — | As above |
| A.7.13 | Equipment maintenance | Out of scope | — | As above |
| A.7.14 | Secure disposal or re-use of equipment | Out of scope | — | As above |

---

## 7. A.8 — Technological Controls (34)

| ID | Control | Decision | Risks | Justification / note |
|---|---|---|---|---|
| A.8.1 | User endpoint devices | Pending | — | Related to R05 |
| A.8.2 | Privileged access rights | **Selected** | R03, R08 | Limits misuse of administrator accounts |
| A.8.3 | Information access restriction | **Selected** | R03, R09 | Restricts access to sensitive information |
| A.8.4 | Access to source code | **Selected** | R08 | Protects the source code repository |
| A.8.5 | Secure authentication | **Selected** | R01, R04, R08, R09 | MFA and secure login for critical systems |
| A.8.6 | Capacity management | **Selected** | R06 | Supports website availability under heavy traffic |
| A.8.7 | Protection against malware | **Selected** | R01, R02 | Endpoint protection against malware and ransomware |
| A.8.8 | Management of technical vulnerabilities | **Selected** | R02, R05 | Patching and vulnerability management |
| A.8.9 | Configuration management | **Selected** | R04, R05 | Secure baselines for cloud and endpoints |
| A.8.10 | Information deletion | Pending | — | — |
| A.8.11 | Data masking | Pending | — | — |
| A.8.12 | Data leakage prevention | Pending | — | Relevant to R03 |
| A.8.13 | Information backup | **Selected** | R02, R07, R08, R09 | Recovery from ransomware, failure and tampering |
| A.8.14 | Redundancy of information processing facilities | **Selected** | R07 | Reduces single points of failure |
| A.8.15 | Logging | Pending | — | Assess together with A.8.16 |
| A.8.16 | Monitoring activities | **Selected** | R01, R02, R03, R04, R06, R08, R09 | Detects suspicious activity |
| A.8.17 | Clock synchronization | Pending | — | — |
| A.8.18 | Use of privileged utility programs | Pending | — | — |
| A.8.19 | Installation of software on operational systems | **Selected** | R02, R05 | Prevents unauthorised software installation |
| A.8.20 | Networks security | **Selected** | R06 | Protects network and website infrastructure |
| A.8.21 | Security of network services | **Selected** | R06 | Security requirements for network service providers |
| A.8.22 | Segregation of networks | Pending | — | Assess together with A.8.20 |
| A.8.23 | Web filtering | **Selected** | R01 | Blocks malicious websites used in phishing |
| A.8.24 | Use of cryptography | **Selected** | R04 | Encrypts sensitive cloud and stored data |
| A.8.25 | Secure development life cycle | Pending | — | Relevant if R08 is expanded to secure development |
| A.8.26 | Application security requirements | Pending | — | As above |
| A.8.27 | Secure system architecture and engineering principles | Pending | — | As above |
| A.8.28 | Secure coding | Pending | — | As above |
| A.8.29 | Security testing in development and acceptance | Pending | — | As above |
| A.8.30 | Outsourced development | Not applicable | — | No outsourced development is described in the profile; revisit if introduced |
| A.8.31 | Separation of development, test and production environments | Pending | — | Relevant if R08 is expanded |
| A.8.32 | Change management | Pending | — | As above |
| A.8.33 | Test information | Pending | — | — |
| A.8.34 | Protection of information systems during audit testing | Pending | — | — |

---

## 8. Limitations

- This is a **preliminary** SoA for a simulated organisation.
- "Pending" decisions are presumptions, not completed applicability assessments.
- No control has been implemented or verified.
- A real SoA is approved by management and kept under document control.
- Further iterations would assess the 55 Pending controls and the 14 physical controls.

---

**Project:** Cybersecurity Risk Assessment & ISO 27001 Case Study
**Document:** 06 — Statement of Applicability
**Disclaimer:** This is a simulated educational document. It does not represent ISO/IEC 27001 certification or conformity.
