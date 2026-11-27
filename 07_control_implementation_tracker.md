
# 07 — Security Control Implementation Tracker

## Document Information

| Field | Details |
|---|---|
| Organisation | Nexora Solutions Pvt. Ltd. |
| Framework | ISO/IEC 27001:2022 |
| Document Type | Security Control Implementation Tracker |
| Related Document | 06 — Statement of Applicability |
| Version | 1.0 |
| Assessment Status | Proposed — Not Verified |

---

## 1. Purpose

This document tracks the proposed implementation of the information security controls selected in the Statement of Applicability (SoA).

It establishes:

- The security controls requiring implementation.
- The risks addressed by each control.
- Proposed responsible roles.
- Implementation priorities.
- Evidence required to verify implementation.
- Current implementation status.

This tracker supports the organisation's risk treatment activities and provides a structured method for monitoring security improvement.

**Important:** This is a proposed implementation tracker. It does not confirm that any control has been implemented, tested, or independently verified.

---

## 2. Implementation Status Definitions

The following status definitions are used throughout this tracker.

- **Proposed — Not Verified:** The control has been selected for implementation, but implementation has not been verified.
- **In Progress:** Implementation activities have started, but the control is not yet fully implemented.
- **Implemented — Pending Verification:** Implementation is reported as complete, but supporting evidence or effectiveness has not yet been verified.
- **Verified:** Sufficient evidence has been reviewed to confirm implementation.
- **Partially Implemented:** Some requirements are implemented, but gaps remain.
- **Not Started:** No implementation activity has begun.

All controls currently remain at **Proposed — Not Verified** because no implementation evidence has been provided for this assessment.

---

## 3. Implementation Tracker

### 3.1 Organisational Controls — Annex A.5

#### A.5.15 — Access Control

**Related Risks:** R01, R03, R04

**Objective:** Ensure that access to organisational information and systems is restricted according to business requirements and authorised responsibilities.

**Proposed Implementation Activities:**
- Establish an access control policy.
- Define user access levels based on job responsibilities.
- Apply least-privilege access principles.
- Review access permissions periodically.

**Proposed Owner:** IT Administrator / Security Officer

**Priority:** High

**Evidence Required:**
- Approved access control policy.
- User access matrix.
- Access review records.
- User account and permission records.

**Current Status:** Proposed — Not Verified

---

#### A.5.17 — Authentication Information

**Related Risks:** R01, R04

**Objective:** Protect authentication information, including passwords and other credentials, throughout its lifecycle.

**Proposed Implementation Activities:**
- Establish rules for secure credential handling.
- Prohibit credential sharing.
- Apply secure password storage practices.
- Define procedures for resetting compromised credentials.

**Proposed Owner:** IT Administrator

**Priority:** High

**Evidence Required:**
- Authentication and password policy.
- Credential management procedures.
- Password reset procedures.
- Relevant configuration records.

**Current Status:** Proposed — Not Verified

---

#### A.5.18 — Access Rights

**Related Risks:** R01, R03, R04

**Objective:** Ensure that access rights are granted, reviewed, modified, and removed in accordance with organisational requirements.

**Proposed Implementation Activities:**
- Establish formal access approval procedures.
- Review user permissions periodically.
- Remove access when employees leave or change roles.
- Maintain records of access modifications.

**Proposed Owner:** IT Administrator / HR Manager

**Priority:** High

**Evidence Required:**
- Access request and approval records.
- User access review reports.
- Employee onboarding and offboarding records.
- Access revocation records.

**Current Status:** Proposed — Not Verified

---

#### A.5.23 — Information Security for Use of Cloud Services

**Related Risks:** R04

**Objective:** Ensure that cloud services are selected, used, managed, and monitored securely.

**Proposed Implementation Activities:**
- Establish requirements for cloud service selection.
- Evaluate cloud providers before adoption.
- Define responsibilities between the organisation and service providers.
- Review cloud access permissions and security configurations.
- Establish cloud data protection requirements.

**Proposed Owner:** IT Administrator / Security Officer

**Priority:** High

**Evidence Required:**
- Cloud security policy or procedure.
- Cloud service inventory.
- Provider security assessments.
- Cloud access and configuration review records.
- Relevant contractual security requirements.

**Current Status:** Proposed — Not Verified

---

#### A.5.24 — Information Security Incident Management Planning and Preparation

**Related Risks:** R01, R02, R03, R04, R05, R06, R07

**Objective:** Establish the organisational capability to prepare for, respond to, and manage information security incidents.

**Proposed Implementation Activities:**
- Develop an incident response plan.
- Define incident reporting and escalation procedures.
- Assign incident response responsibilities.
- Establish incident classification and documentation procedures.
- Conduct periodic incident response exercises.

**Proposed Owner:** Security Officer / IT Administrator

**Priority:** High

**Evidence Required:**
- Approved incident response plan.
- Incident reporting procedure.
- Incident register.
- Escalation matrix.
- Incident response exercise records.

**Current Status:** Proposed — Not Verified

---

#### A.5.30 — ICT Readiness for Business Continuity

**Related Risks:** R02, R06, R07

**Objective:** Ensure that information and communication technology systems can support business continuity requirements during disruptions.

**Proposed Implementation Activities:**
- Identify critical ICT systems and services.
- Define recovery time and recovery point objectives where appropriate.
- Establish ICT recovery procedures.
- Test backup restoration and recovery arrangements.
- Review continuity arrangements periodically.

**Proposed Owner:** IT Administrator / Management

**Priority:** High

**Evidence Required:**
- ICT business continuity plan.
- System recovery procedures.
- Recovery objectives and requirements.
- Backup restoration test reports.
- Business continuity test records.

**Current Status:** Proposed — Not Verified

---

### 3.2 People Controls — Annex A.6

#### A.6.3 — Information Security Awareness, Education and Training

**Related Risks:** R01, R02, R03

**Objective:** Ensure that personnel understand their information security responsibilities and recognise common security threats.

**Proposed Implementation Activities:**
- Conduct regular security awareness sessions.
- Provide phishing awareness training.
- Educate employees about password security and data handling.
- Maintain training completion records.
- Evaluate employee awareness periodically.

**Proposed Owner:** HR Manager / Security Officer

**Priority:** Medium

**Evidence Required:**
- Security awareness training materials.
- Training attendance records.
- Employee awareness acknowledgements.
- Phishing simulation or awareness assessment results.

**Current Status:** Proposed — Not Verified

---

### 3.3 Technological Controls — Annex A.8
A.8.14 — Redundancy of Information Processing Facilities

Related Risks: R07 — Hardware Failure and Data Loss

Objective: Ensure the availability of information processing facilities through appropriate redundancy measures.

Proposed Implementation Activities:

* Identify critical systems and infrastructure components.
* Evaluate single points of failure.
* Establish redundancy requirements for critical services.
* Consider redundant storage, network or processing components where appropriate.
* Test failover and recovery arrangements periodically.

Proposed Owner: IT Administrator / Infrastructure Manager

Priority: High

Evidence Required:

* Infrastructure redundancy documentation.
* System architecture or infrastructure diagrams.
* Failover test reports.
* Availability and recovery records.
* Maintenance and review records.

Current Status: Proposed — Not Verified

⸻

#### A.8.2 — Privileged Access Rights

**Related Risks:** R02, R03, R04, R05

**Objective:** Restrict and manage privileged access to systems and sensitive information.

**Proposed Implementation Activities:**
- Identify privileged accounts.
- Restrict administrative permissions.
- Require approval for privileged access.
- Review privileged accounts periodically.
- Monitor privileged activities.

**Proposed Owner:** IT Administrator

**Priority:** High

**Evidence Required:**
- Privileged account inventory.
- Administrative access approval records.
- Privileged access review reports.
- Relevant system audit logs.

**Current Status:** Proposed — Not Verified

---

#### A.8.3 — Information Access Restriction

**Related Risks:** R03, R04

**Objective:** Restrict access to information and associated assets according to the organisation's access control requirements.

**Proposed Implementation Activities:**
- Define information access restrictions.
- Apply role-based permissions.
- Restrict access to sensitive files and folders.
- Review access permissions regularly.

**Proposed Owner:** IT Administrator / Data Owner

**Priority:** High

**Evidence Required:**
- Information access policy.
- File and folder permission records.
- Role-based access matrix.
- Access review records.

**Current Status:** Proposed — Not Verified

---

#### A.8.5 — Secure Authentication

**Related Risks:** R01, R04

**Objective:** Implement secure authentication technologies and procedures to protect access to systems and applications.

**Proposed Implementation Activities:**
- Enable multi-factor authentication where supported.
- Apply secure authentication configurations.
- Implement account lockout or other appropriate protections.
- Review authentication settings periodically.

**Proposed Owner:** IT Administrator

**Priority:** High

**Evidence Required:**
- MFA configuration records.
- Authentication policy.
- System authentication settings.
- Relevant access and authentication logs.

**Current Status:** Proposed — Not Verified

---

#### A.8.6 — Capacity Management

**Related Risks:** R06

**Objective:** Monitor and manage system resource capacity to maintain the availability and performance of information processing facilities.

**Proposed Implementation Activities:**
- Identify critical system resources.
- Monitor CPU, memory, storage, and network utilisation.
- Establish capacity thresholds.
- Plan for resource expansion where necessary.
- Review capacity trends periodically.

**Proposed Owner:** IT Administrator

**Priority:** Medium

**Evidence Required:**
- Capacity monitoring reports.
- Resource utilisation records.
- Capacity planning documentation.
- System performance reports.

**Current Status:** Proposed — Not Verified

---

#### A.8.7 — Protection Against Malware

**Related Risks:** R02

**Objective:** Protect information and systems against malware and malicious software.

**Proposed Implementation Activities:**
- Deploy appropriate anti-malware protection.
- Enable real-time threat detection where available.
- Keep malware protection tools updated.
- Restrict execution of unauthorised software.
- Educate employees about malicious attachments and downloads.

**Proposed Owner:** IT Administrator

**Priority:** High

**Evidence Required:**
- Anti-malware configuration records.
- Endpoint protection reports.
- Malware detection logs.
- Security update records.

**Current Status:** Proposed — Not Verified

---

#### A.8.8 — Management of Technical Vulnerabilities

**Related Risks:** R05

**Objective:** Identify, assess, and address technical vulnerabilities affecting organisational systems.

**Proposed Implementation Activities:**
- Maintain an inventory of systems and software.
- Monitor relevant vulnerability information.
- Perform periodic vulnerability assessments.
- Prioritise remediation according to risk.
- Track patching and remediation activities.

**Proposed Owner:** IT Administrator / Security Officer

**Priority:** High

**Evidence Required:**
- Vulnerability assessment reports.
- Software and system inventory.
- Patch management records.
- Vulnerability remediation register.

**Current Status:** Proposed — Not Verified

---

#### A.8.9 — Configuration Management

**Related Risks:** R02, R05

**Objective:** Establish and maintain secure configurations for hardware, software, services, and networks.

**Proposed Implementation Activities:**
- Define secure configuration baselines.
- Disable unnecessary services and features.
- Change default credentials and insecure settings.
- Document configuration changes.
- Review system configurations periodically.

**Proposed Owner:** IT Administrator

**Priority:** High

**Evidence Required:**
- Secure configuration standards.
- System configuration records.
- Configuration change logs.
- Periodic configuration review reports.

**Current Status:** Proposed — Not Verified

---

#### A.8.13 — Information Backup

**Related Risks:** R02, R07

**Objective:** Protect organisational information against data loss through appropriate backup arrangements.

**Proposed Implementation Activities:**
- Establish a backup policy.
- Define backup frequency based on business requirements.
- Protect backup copies from unauthorised access.
- Maintain appropriate backup retention periods.
- Test restoration procedures periodically.

**Proposed Owner:** IT Administrator

**Priority:** High

**Evidence Required:**
- Backup policy and schedule.
- Backup completion logs.
- Backup retention records.
- Backup access restrictions.
- Restoration test reports.

**Current Status:** Proposed — Not Verified

---

#### A.8.16 — Monitoring Activities

**Related Risks:** R01, R02, R03, R04, R05, R06

**Objective:** Monitor networks, systems, and applications to identify unusual behaviour and potential security incidents.

**Proposed Implementation Activities:**
- Enable appropriate system and security logging.
- Monitor critical system activities.
- Establish procedures for reviewing security alerts.
- Investigate suspicious activities.
- Retain logs according to organisational requirements.

**Proposed Owner:** IT Administrator / Security Officer

**Priority:** High

**Evidence Required:**
- Logging and monitoring procedures.
- System and security logs.
- Monitoring reports.
- Security alert records.
- Incident investigation records.

**Current Status:** Proposed — Not Verified

---

#### A.8.19 — Installation of Software on Operational Systems

**Related Risks:** R02, R05

**Objective:** Control software installation on operational systems to reduce the risk of unauthorised or malicious software.

**Proposed Implementation Activities:**
- Restrict software installation permissions.
- Require approval for software installation.
- Maintain an approved software list.
- Remove unauthorised applications.
- Review installed software periodically.

**Proposed Owner:** IT Administrator

**Priority:** Medium

**Evidence Required:**
- Software installation policy.
- Approved software inventory.
- Installation approval records.
- Software inventory and review reports.

**Current Status:** Proposed — Not Verified

---

#### A.8.20 — Network Security

**Related Risks:** R04, R05, R06

**Objective:** Protect networks and network devices against unauthorised access, misuse, and security threats.

**Proposed Implementation Activities:**
- Establish network security requirements.
- Configure firewalls and network access restrictions.
- Secure network devices.
- Separate networks where appropriate.
- Review network security configurations periodically.

**Proposed Owner:** Network Administrator / IT Administrator

**Priority:** High

**Evidence Required:**
- Network security policy.
- Network architecture documentation.
- Firewall configuration records.
- Network access control records.
- Network security review reports.

**Current Status:** Proposed — Not Verified

---

#### A.8.21 — Security of Network Services

**Related Risks:** R04, R06

**Objective:** Ensure that security requirements are identified and implemented for network services used by the organisation.

**Proposed Implementation Activities:**
- Identify network services in use.
- Define security requirements for each service.
- Review service provider security arrangements.
- Monitor network service performance and availability.
- Review service security requirements periodically.

**Proposed Owner:** IT Administrator / Network Administrator

**Priority:** Medium

**Evidence Required:**
- Network service inventory.
- Network service security requirements.
- Service provider agreements.
- Service monitoring records.
- Periodic service review reports.

**Current Status:** Proposed — Not Verified

---

#### A.8.23 — Web Filtering

**Related Risks:** R01, R02, R05

**Objective:** Reduce exposure to malicious and inappropriate websites through appropriate web access controls.

**Proposed Implementation Activities:**
- Implement web filtering where technically supported.
- Block known malicious and phishing websites.
- Restrict access to high-risk website categories where appropriate.
- Review filtering rules periodically.
- Monitor web access alerts.

**Proposed Owner:** IT Administrator

**Priority:** Medium

**Evidence Required:**
- Web filtering configuration.
- Approved filtering rules.
- Blocked website logs.
- Web access monitoring reports.

**Current Status:** Proposed — Not Verified

---

#### A.8.24 — Use of Cryptography

**Related Risks:** R04

**Objective:** Ensure the appropriate use of cryptography to protect the confidentiality, integrity, and authenticity of information.

**Proposed Implementation Activities:**
- Establish cryptographic requirements.
- Use appropriate encryption for sensitive data.
- Protect cryptographic keys.
- Apply secure communication protocols.
- Review encryption configurations periodically.

**Proposed Owner:** IT Administrator / Security Officer

**Priority:** High

**Evidence Required:**
- Cryptographic policy or procedure.
- Encryption configuration records.
- Secure communication settings.
- Key management procedures.
- Relevant security review records.

**Current Status:** Proposed — Not Verified

---## 4. Implementation Summary

| Control Category | Selected Controls |
|---|---:|
| Organisational Controls — A.5 | 6 |
| People Controls — A.6 | 1 |
| Technological Controls — A.8 | 15 |
| **Total Selected Controls** | **22** |

All 22 controls remain at Proposed — Not Verified.

No control implementation or effectiveness evidence has been supplied for this simulated assessment.

## 5. Implementation and Verification Requirements

Implementation should follow a controlled process:

1. Assign responsibility for each selected control.
2. Approve the required policies and procedures.
3. Implement the necessary technical and organisational measures.
4. Collect supporting implementation evidence.
5. Review the evidence against the control objective.
6. Update the implementation status.
7. Record unresolved gaps and corrective actions.
8. Conduct periodic reviews to confirm continued effectiveness.

A control should not be marked as Verified solely because a policy or procedure exists. Evidence of actual implementation and operation should also be considered.

---

## 6. Evidence Management

Evidence should be maintained in a structured manner to support internal reviews and future audits.

Examples of evidence include:

- Approved policies and procedures.
- System configuration records.
- Access review reports.
- Security monitoring logs.
- Vulnerability assessment reports.
- Backup and restoration test results.
- Employee training records.
- Incident response documentation.

Evidence should be dated, attributable to a responsible person or role, and retained according to organisational requirements.

Sensitive evidence must be protected against unauthorised disclosure.

---

## 7. Relationship with Other Documents

This tracker should be reviewed alongside the following project documents:

- **01 — Organisation Profile:** Defines organisational context and assessment scope.
- **02 — Asset Inventory:** Identifies information assets requiring protection.
- **03 — Threat and Vulnerability Assessment:** Identifies potential threats and vulnerabilities.
- **04 — Risk Assessment:** Evaluates and prioritises identified cybersecurity risks.
- **05 — Risk Treatment Plan:** Defines proposed treatment actions and relevant security controls.
- **06 — Statement of Applicability:** Records selected Annex A controls and their applicability.
- **08 — Residual Risk Assessment:** Defines the process for evaluating remaining risks after treatment.
- **09 — Executive Summary:** Communicates consolidated assessment findings.
- **10 — Methodology and References:** Explains the assessment approach and supporting references.

Control IDs, names, applicability decisions and risk mappings should remain consistent across the relevant documents.

## 8. Limitations

This tracker represents a proposed implementation plan rather than evidence of an operational Information Security Management System (ISMS).

The following limitations apply:

- Actual implementation has not been independently verified.
- Evidence has not been collected or reviewed for this assessment.
- Responsible roles are proposed assignments, not confirmed employee appointments.
- Implementation priorities may change following management review.
- The selected controls represent a risk-based selection and do not constitute a complete assessment of all ISO/IEC 27001:2022 Annex A controls.
- Physical controls under Annex A.7 are outside the selected control set and have not been assessed in this tracker.

---

## 9. Review and Maintenance

This tracker should be reviewed:

- When new information security risks are identified.
- When significant changes occur in systems, processes, or business operations.
- Following security incidents.
- When control implementation activities are completed.
- During periodic ISMS reviews.
- When relevant legal, regulatory, or contractual requirements change.

All changes should be documented to maintain traceability and accountability.

---

## 10. Conclusion

This Security Control Implementation Tracker establishes a structured approach for monitoring the 21 controls selected in the Statement of Applicability.

It connects risk treatment activities with proposed implementation responsibilities and evidence requirements.

Successful implementation will require management support, assigned ownership, appropriate resources, documented procedures, and ongoing verification.

The current status remains **Proposed — Not Verified** until implementation activities are completed and supported by sufficient evidence.
