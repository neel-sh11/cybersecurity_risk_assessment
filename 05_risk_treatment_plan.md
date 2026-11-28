# 05 — Risk Treatment Plan and Security Controls

| Field | Details |
|---|---|
| Organisation | Nexora Solutions Pvt. Ltd. (fictional) |
| Document | 05 — Risk Treatment Plan and Security Controls |
| Framework | ISO/IEC 27001:2022 |
| Version | 2.0 |
| Status | Proposed — Not Yet Implemented |

---

## 1. Objective

Define treatment strategies and security controls for the nine risks identified in `04_risk_assessment.md`.

The plan proposes security improvements, the relevant ISO/IEC 27001:2022 Annex A controls, responsible roles and implementation priorities. Nothing in this document confirms that a control exists.

---

## 2. Risk Treatment Options

| Option | Meaning | Example |
|---|---|---|
| Avoid | Stop the activity that creates unacceptable risk | Retire an insecure application that cannot be protected |
| Mitigate | Reduce likelihood and/or impact with controls | Enforce multi-factor authentication |
| Transfer or share | Share the financial or operational consequences | Cyber insurance |
| Accept | Formally retain a risk within approved tolerance | Accept a low-impact risk with management approval |

---

## 3. Treatment Approach

All nine risks are assigned **Mitigate** as the primary strategy. For R02 (ransomware), **Transfer** (cyber insurance) is noted as a possible secondary option, to be decided by senior management.

The plan focuses on:

- Strengthening identity and access management
- Improving email security and employee awareness
- Formal vulnerability and patch management
- Improved backup and recovery
- Stronger cloud security configuration
- Network monitoring and protection
- Business continuity and incident response

---

## 4. Proposed Treatment by Risk

### R01 — Phishing and Account Compromise
**Initial score:** 20 (Critical) · **Strategy:** Mitigate · **Owner:** IT Manager

Actions:
1. Run regular phishing awareness and security training.
2. Enforce multi-factor authentication (MFA) on organisational accounts.
3. Configure email filtering and malicious attachment protection.
4. Filter access to malicious websites.
5. Run periodic phishing simulations.
6. Set up a procedure to report suspicious emails and suspected account compromise.

Annex A controls: A.5.17, A.6.3, A.8.5, A.8.7, A.8.16, A.8.23
Responsible: IT Manager, HR Manager

### R02 — Ransomware Infection
**Initial score:** 20 (Critical) · **Strategy:** Mitigate (secondary option: Transfer) · **Owner:** IT Manager

Actions:
1. Apply security updates through formal patch management.
2. Keep secure, isolated backups of critical information.
3. Test data restoration periodically.
4. Deploy endpoint malware protection.
5. Restrict installation of unapproved software.
6. Monitor for suspicious activity and malware behaviour.
7. Prepare a ransomware incident response procedure.

Annex A controls: A.5.30, A.6.3, A.8.7, A.8.8, A.8.13, A.8.16, A.8.19
Responsible: IT Manager

### R03 — Insider Data Misuse
**Initial score:** 15 (High) · **Strategy:** Mitigate · **Owner:** IT Manager

Actions:
1. Apply least privilege to accounts.
2. Review access permissions periodically.
3. Restrict access to sensitive client and employee data by job role.
4. Monitor privileged activity and access to critical information.
5. Remove or change access promptly when staff leave or change roles.
6. Establish formal access approval.
7. Train staff on data handling.

Annex A controls: A.5.15, A.5.18, A.6.3, A.8.2, A.8.3, A.8.16
Responsible: IT Manager, HR Manager

### R04 — Cloud Data Exposure
**Initial score:** 15 (High) · **Strategy:** Mitigate · **Owner:** IT Manager

Actions:
1. Review cloud storage permissions regularly.
2. Block public access to sensitive cloud storage.
3. Require strong authentication, including MFA, for cloud accounts.
4. Monitor cloud configuration changes and unauthorised access attempts.
5. Encrypt sensitive information.
6. Establish a cloud configuration review procedure.

Annex A controls: A.5.15, A.5.23, A.8.5, A.8.9, A.8.16, A.8.24
Responsible: IT Manager

### R05 — Exploitation of Unpatched Software
**Initial score:** 16 (High) · **Strategy:** Mitigate · **Owner:** IT Manager

Actions:
1. Establish a formal vulnerability and patch management process.
2. Maintain an inventory of software and systems.
3. Prioritise updates by severity and business impact.
4. Run periodic vulnerability assessments.
5. Verify that critical updates are installed.
6. Document vulnerabilities, remediation and outstanding issues.

Annex A controls: A.8.8, A.8.9, A.8.19
Responsible: IT Manager (supported by the Development Manager)

### R06 — DDoS Service Disruption
**Initial score:** 9 (Moderate) · **Strategy:** Mitigate · **Owner:** IT Manager

Actions:
1. Use DDoS protection services for the public website.
2. Monitor unusual network traffic.
3. Review network security configuration periodically.
4. Assess service capacity and availability needs.
5. Prepare a website disruption response procedure.
6. Coordinate with service providers during incidents.

Annex A controls: A.8.6, A.8.16, A.8.20, A.8.21
Responsible: IT Manager, Network Administrator

### R07 — Hardware Failure and Data Loss
**Initial score:** 12 (High) · **Strategy:** Mitigate · **Owner:** IT Manager

Actions:
1. Schedule regular backups of critical information.
2. Keep separate backup copies.
3. Test restoration and recovery periodically.
4. Monitor hardware health.
5. Establish business continuity and disaster recovery procedures.
6. Evaluate redundancy for critical infrastructure.

Annex A controls: A.5.30, A.8.13, A.8.14
Responsible: IT Manager

### R08 — Source Code Compromise
**Initial score:** 12 (High) · **Strategy:** Mitigate · **Owner:** Development Manager

Actions:
1. Restrict repository access by role.
2. Enforce MFA on repository accounts.
3. Require branch protection and peer review for changes.
4. Limit and review administrator rights.
5. Back up repositories and test restoration.
6. Monitor repository access and changes.

Annex A controls: A.5.15, A.5.18, A.8.2, A.8.4, A.8.5, A.8.13, A.8.16
Responsible: Development Manager, IT Manager

### R09 — Financial Records Compromise or Tampering
**Initial score:** 12 (High) · **Strategy:** Mitigate · **Owner:** Finance Manager

Actions:
1. Restrict finance system access by role.
2. Enforce MFA on finance accounts.
3. Review finance permissions when roles change.
4. Back up financial records and test restoration.
5. Monitor access to financial records.

Annex A controls: A.5.15, A.5.18, A.8.3, A.8.5, A.8.13, A.8.16
Responsible: Finance Manager, IT Manager

### Cross-cutting control — A.5.24

**A.5.24 — Information security incident management planning and preparation** applies to all nine risks. Nexora should define incident reporting, escalation, response and documentation procedures that support any type of incident.

---

## 5. Risk Treatment Summary

| ID | Risk | Initial score | Rating | Strategy | Annex A controls (plus A.5.24) |
|---|---|---|---|---|---|
| R01 | Phishing and Account Compromise | 20 | Critical | Mitigate | A.5.17, A.6.3, A.8.5, A.8.7, A.8.16, A.8.23 |
| R02 | Ransomware Infection | 20 | Critical | Mitigate | A.5.30, A.6.3, A.8.7, A.8.8, A.8.13, A.8.16, A.8.19 |
| R03 | Insider Data Misuse | 15 | High | Mitigate | A.5.15, A.5.18, A.6.3, A.8.2, A.8.3, A.8.16 |
| R04 | Cloud Data Exposure | 15 | High | Mitigate | A.5.15, A.5.23, A.8.5, A.8.9, A.8.16, A.8.24 |
| R05 | Exploitation of Unpatched Software | 16 | High | Mitigate | A.8.8, A.8.9, A.8.19 |
| R06 | DDoS Service Disruption | 9 | Moderate | Mitigate | A.8.6, A.8.16, A.8.20, A.8.21 |
| R07 | Hardware Failure and Data Loss | 12 | High | Mitigate | A.5.30, A.8.13, A.8.14 |
| R08 | Source Code Compromise | 12 | High | Mitigate | A.5.15, A.5.18, A.8.2, A.8.4, A.8.5, A.8.13, A.8.16 |
| R09 | Financial Records Compromise or Tampering | 12 | High | Mitigate | A.5.15, A.5.18, A.8.3, A.8.5, A.8.13, A.8.16 |

Together these use **23 distinct Annex A controls**. Initial ratings remain unchanged until implementation and effectiveness have been evaluated.

---

## 6. Proposed Responsibilities

These are proposed assignments, not verified appointments.

| Role | Proposed responsibility |
|---|---|
| IT Manager | Technical security improvements, access, patching, backup and recovery, infrastructure monitoring |
| Security Officer (proposed) | Coordinate the ISMS, incident response and control reviews |
| HR Manager | Security awareness training, onboarding and offboarding |
| Development Manager | Source code protection and vulnerability remediation in software |
| Finance Manager | Access and review for financial records |
| Senior Management | Approve treatment, allocate resources, review high residual risks, approve risk acceptance |

---

## 7. Implementation Phases

Timeframes are **indicative planning assumptions**, not confirmed dates.

| Phase | Indicative timeframe | Focus | Controls |
|---|---|---|---|
| 1 — Immediate priorities | 0–3 months | Authentication, email and web protection, backups, cloud permissions, privileged access, incident plan | A.5.17, A.5.23, A.5.24, A.8.2, A.8.5, A.8.7, A.8.13, A.8.23 |
| 2 — Security improvements | 3–6 months | Patching, access control, monitoring, network, training, continuity, encryption | A.5.15, A.5.18, A.5.30, A.6.3, A.8.3, A.8.4, A.8.8, A.8.9, A.8.16, A.8.19, A.8.20, A.8.21, A.8.24 |
| 3 — Continuous improvement | 6–12 months | Capacity, redundancy, periodic testing and reassessment | A.8.6, A.8.14 |

Phase 3 also covers periodic vulnerability assessments, incident response and recovery tests, control effectiveness reviews and risk reassessment.

---

## 8. Residual Risk Considerations

- A risk is **not** reduced merely because a control has been proposed.
- Residual ratings are assigned only after implementation evidence and effectiveness testing.
- Risks accepted by management need formal approval.
- Planned target residual levels are in `08_residual_risk_assessment.md` and are clearly marked as targets, not results.

---

## 9. Assessment Conclusion

All nine risks have a treatment strategy, Annex A control references, owners and proposed priorities. The plan feeds the Statement of Applicability (`06`), the control implementation tracker (`07`) and the residual risk assessment (`08`).

---

**Project:** Cybersecurity Risk Assessment & ISO 27001 Case Study
**Document:** 05 — Risk Treatment Plan and Security Controls
**Status:** Proposed — Not Yet Implemented
**Disclaimer:** This is a simulated educational assessment. The proposed controls have not been implemented or independently verified.
