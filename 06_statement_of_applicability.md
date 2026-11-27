
# 06 — Statement of Applicability (SoA)

**Organisation:** Nexora Solutions Pvt. Ltd.  
**Framework:** ISO/IEC 27001:2022  
**Document Type:** Statement of Applicability  
**Assessment Scope:** Preliminary Risk-Based Control Selection  
**Selected Controls:** 21  
**Status:** Draft

---

## 1. Purpose

The Statement of Applicability (SoA) identifies the information security controls selected to address the risks associated with Nexora Solutions.

It establishes a connection between the cybersecurity risk assessment, risk treatment plan and the ISO/IEC 27001:2022 Annex A control framework.

This document records:

- Selected applicable controls.
- Reasons for selecting each control.
- Related risk references.
- Intended security objectives.
- Current implementation status.

The SoA serves as a reference for control implementation and future security reviews.

## 2. ISO/IEC 27001:2022 Annex A Structure

ISO/IEC 27001:2022 Annex A contains 93 reference controls divided into four categories.

- A.5 — Organisational Controls: 37 controls.
- A.6 — People Controls: 8 controls.
- A.7 — Physical Controls: 14 controls.
- A.8 — Technological Controls: 34 controls.

The present assessment selects 21 controls based on identified organisational risks and security requirements.

This is a risk-based preliminary selection, not a complete assessment of all 93 controls.

## 3. Control Selection Criteria

Controls were selected by considering:

1. Identified cybersecurity risks.
2. Potential impact on organisational information assets.
3. Likelihood of security incidents.
4. Business continuity requirements.
5. Access management and data protection requirements.
6. Applicable security objectives.
7. Risk treatment priorities.

The selected controls are intended to reduce the likelihood or impact of identified security incidents.

---

## 4. Selected Annex A Controls

### 4.1 Organisational Controls — A.5

#### A.5.15 — Access Control

- Applicability: Applicable
- Related Risks: R03, R04
- Objective: Establish rules for controlling access to information and associated assets.
- Justification: Organisational and client information must only be accessible to authorised individuals.
- Implementation Status: Proposed — Not Verified

#### A.5.17 — Authentication Information

- Applicability: Applicable
- Related Risk: R01
- Objective: Protect authentication information throughout its lifecycle.
- Justification: Authentication credentials must be protected against theft, disclosure and unauthorised use.
- Implementation Status: Proposed — Not Verified

#### A.5.18 — Access Rights

- Applicability: Applicable
- Related Risk: R03
- Objective: Provision, review, modify and remove access rights according to organisational requirements.
- Justification: Regular access reviews help prevent excessive privileges and unauthorised access.
- Implementation Status: Proposed — Not Verified

#### A.5.23 — Information Security for Use of Cloud Services

- Applicability: Applicable
- Related Risk: R04
- Objective: Establish processes for acquiring, using, managing and exiting cloud services securely.
- Justification: Cloud-based infrastructure and storage require appropriate security management.
- Implementation Status: Proposed — Not Verified

#### A.5.24 — Information Security Incident Management Planning and Preparation

- Applicability: Applicable
- Related Risks: R01, R02
- Objective: Plan and prepare for the management of information security incidents.
- Justification: Phishing, malware and ransomware incidents require coordinated response procedures.
- Implementation Status: Proposed — Not Verified

#### A.5.30 — ICT Readiness for Business Continuity

- Applicability: Applicable
- Related Risk: R07
- Objective: Ensure ICT readiness supports business continuity requirements.
- Justification: Critical business operations depend on the availability and recovery of IT systems.
- Implementation Status: Proposed — Not Verified

### 4.2 People Controls — A.6

#### A.6.3 — Information Security Awareness, Education and Training

- Applicability: Applicable
- Related Risk: R01
- Objective: Provide employees with appropriate information security awareness and training.
- Justification: Employee awareness helps reduce phishing susceptibility and credential-related security incidents.
- Implementation Status: Proposed — Not Verified

### 4.3 Physical Controls — A.7

Physical controls have not been individually assessed within this preliminary risk-based selection.

- Applicability: Not Assessed
- Related Risks: Requires further assessment
- Justification: Physical security requirements must be evaluated against organisational facilities, equipment and operational arrangements.

This category is not declared unnecessary or excluded from a complete ISO/IEC 27001 assessment.

### 4.4 Technological Controls — A.8

#### A.8.2 — Privileged Access Rights

- Applicability: Applicable
- Related Risk: R03
- Objective: Restrict and manage privileged access rights.
- Justification: Administrative accounts require stronger access restrictions and monitoring.
- Implementation Status: Proposed — Not Verified

#### A.8.3 — Information Access Restriction

- Applicability: Applicable
- Related Risk: R03
- Objective: Restrict access to information according to established access control requirements.
- Justification: Sensitive organisational information must only be accessible to authorised users.
- Implementation Status: Proposed — Not Verified

#### A.8.5 — Secure Authentication

- Applicability: Applicable
- Related Risks: R01, R04
- Objective: Implement secure authentication technologies and procedures.
- Justification: Multi-Factor Authentication (MFA) and secure authentication mechanisms help reduce unauthorised account access.
- Implementation Status: Proposed — Not Verified

#### A.8.6 — Capacity Management

- Applicability: Applicable
- Related Risk: R06
- Objective: Monitor and adjust resource capacity to meet current and expected requirements.
- Justification: Capacity planning helps maintain service availability and manage resource exhaustion.
- Implementation Status: Proposed — Not Verified

#### A.8.7 — Protection Against Malware

- Applicability: Applicable
- Related Risks: R01, R02
- Objective: Implement protection against malware.
- Justification: Malware and ransomware may compromise organisational systems and information.
- Implementation Status: Proposed — Not Verified

#### A.8.8 — Management of Technical Vulnerabilities

- Applicability: Applicable
- Related Risk: R05
- Objective: Identify, evaluate and address technical vulnerabilities.
- Justification: Timely vulnerability management reduces exposure to known software weaknesses.
- Implementation Status: Proposed — Not Verified

#### A.8.9 — Configuration Management

- Applicability: Applicable
- Related Risks: R04, R05
- Objective: Establish and monitor secure configurations for systems and services.
- Justification: Secure configurations help prevent infrastructure and cloud misconfigurations.
- Implementation Status: Proposed — Not Verified

#### A.8.13 — Information Backup

- Applicability: Applicable
- Related Risks: R02, R07
- Objective: Maintain backup copies of information, software and systems.
- Justification: Reliable backups support recovery from ransomware incidents and hardware failures.
- Implementation Status: Proposed — Not Verified

#### A.8.16 — Monitoring Activities

- Applicability: Applicable
- Related Risks: R02, R03, R04
- Objective: Monitor networks, systems and applications for anomalous behaviour.
- Justification: Monitoring helps identify suspicious activities and potential security incidents.
- Implementation Status: Proposed — Not Verified

#### A.8.19 — Installation of Software on Operational Systems

- Applicability: Applicable
- Related Risk: R05
- Objective: Control software installation on operational systems.
- Justification: Unauthorised or insecure software installations may introduce security vulnerabilities.
- Implementation Status: Proposed — Not Verified

#### A.8.20 — Network Security

- Applicability: Applicable
- Related Risk: R06
- Objective: Secure and protect networks and network devices.
- Justification: Network security measures help protect organisational infrastructure and online services.
- Implementation Status: Proposed — Not Verified

#### A.8.21 — Security of Network Services

- Applicability: Applicable
- Related Risk: R06
- Objective: Identify and implement security mechanisms and service requirements for network services.
- Justification: Network services require appropriate security and availability protections.
- Implementation Status: Proposed — Not Verified

#### A.8.23 — Web Filtering

- Applicability: Applicable
- Related Risk: R01
- Objective: Manage access to external websites to reduce exposure to malicious content.
- Justification: Web filtering helps reduce access to known malicious websites.
- Implementation Status: Proposed — Not Verified

#### A.8.24 — Use of Cryptography

- Applicability: Applicable
- Related Risk: R04
- Objective: Establish rules for the effective use of cryptography and encryption.
- Justification: Cryptographic protections help safeguard sensitive information against unauthorised disclosure.
- Implementation Status: Proposed — Not Verified

---

## 5. Control Selection Summary

The preliminary assessment selects 21 Annex A controls.

- Organisational Controls (A.5): 6
- People Controls (A.6): 1
- Physical Controls (A.7): Not Assessed
- Technological Controls (A.8): 14

**Total Selected Controls: 21**

The selection prioritises access management, authentication, cloud security, malware protection, vulnerability management, monitoring, network security and business continuity.

## 6. Implementation Status Definitions

The following status definitions will be used in the control implementation tracker.

**Not Started:** Implementation activities have not begun.

**In Progress:** Implementation activities are currently underway.

**Implemented:** The control has been implemented and supporting evidence is available.

**Partially Implemented:** Some requirements are implemented, but outstanding gaps remain.

**Not Verified:** Implementation status has not been established through sufficient assessment evidence.

For this preliminary assessment, all 21 selected controls are classified as:

**Proposed — Not Verified**

This classification does not imply that the controls are already operational.

## 7. Exclusions and Assessment Limitations

This document represents a preliminary selection of 21 controls from ISO/IEC 27001:2022 Annex A.

The remaining controls have not been individually evaluated in this case study.

Physical security requirements and additional organisational requirements require further assessment.

A complete organisational SoA must evaluate all 93 Annex A controls, document applicability decisions, justify exclusions and establish implementation status.

The current selection may be revised following changes in organisational context, risk assessment results or management requirements.

## 8. Relationship with Other Project Documents

This document is connected to the following project records:

- File 02 — Asset Inventory: Identifies organisational information assets.
- File 03 — Risk Assessment: Identifies and evaluates cybersecurity risks.
- File 04 — Risk Evaluation: Establishes risk prioritisation.
- File 05 — Risk Treatment Plan: Defines proposed risk treatment actions.
- File 07 — Control Implementation Tracker: Tracks implementation responsibilities, activities and evidence.
- File 08 — Residual Risk Assessment: Records residual risk evaluation following treatment.

These documents collectively establish traceability between assets, risks, treatment decisions and selected security controls.

## 9. Assessment Conclusion

The preliminary Statement of Applicability establishes a structured relationship between identified cybersecurity risks and 21 selected ISO/IEC 27001:2022 Annex A controls.

The selected controls provide a foundation for security implementation planning, responsibility assignment, evidence collection and future effectiveness reviews.

The next stage is to track the selected controls through the Control Implementation Tracker and evaluate their implementation using appropriate evidence.

---

**Project:** Cybersecurity Risk Assessment & ISO 27001 Case Study  
**Organisation:** Nexora Solutions Pvt. Ltd.  
**Document:** 06 — Statement of Applicability  
**Framework:** ISO/IEC 27001:2022  
**Selected Controls:** 21  
**Status:** Preliminary Draft
