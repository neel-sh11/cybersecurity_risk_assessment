06 — Statement of Applicability (SoA)

Organisation: Nexora Solutions Pvt. Ltd.
Framework: ISO/IEC 27001:2022
Reference: Annex A
Document Type: Preliminary Statement of Applicability
Document Status: Draft — Proposed Control Selection
Assessment Type: Simulated Cybersecurity Risk Assessment

⸻

1. Objective

The purpose of this Statement of Applicability (SoA) is to identify information security controls considered relevant to Nexora Solutions, document their applicability, provide justification and record their current implementation status.

This document connects the organisation’s identified cybersecurity risks with selected ISO/IEC 27001:2022 Annex A controls.

This is a preliminary, risk-based control selection. It is not a complete assessment of all 93 Annex A controls and does not demonstrate ISO certification or compliance.

2. ISO/IEC 27001:2022 Annex A Structure

Annex A contains 93 reference controls divided into four categories:

* A.5 — Organisational Controls: 37 controls.
* A.6 — People Controls: 8 controls.
* A.7 — Physical Controls: 14 controls.
* A.8 — Technological Controls: 34 controls.

Total: 93 controls.

3. Applicability Assessment Criteria

Controls are selected based on:

1. Identified information security risks.
2. Organisational assets and business activities.
3. Legal, regulatory and contractual requirements.
4. Information security objectives.
5. Risk treatment decisions.
6. The organisation’s operating environment and security requirements.

A control is considered applicable when it supports the treatment of an identified risk or addresses a relevant information security requirement.

Controls not selected in this preliminary register must not automatically be interpreted as formally excluded or not applicable. A complete SoA requires an assessment and documented justification for all relevant Annex A controls.

4. Statement of Applicability Register

The following 22 controls are selected for this preliminary assessment.

All selected controls currently have the status Proposed — Not Verified. No implementation evidence has been supplied for this simulated organisation.

4.1 Organisational Controls — A.5

A.5.15 — Access Control

* Applicable: Yes
* Related Risk: R03 — Insider Data Misuse; R04 — Cloud Data Exposure
* Purpose: Establish rules to control access to information and associated assets.
* Status: Proposed — Not Verified
* Justification: Access to sensitive client information and cloud resources must be restricted according to authorised responsibilities.

A.5.17 — Authentication Information

* Applicable: Yes
* Related Risks: R01 — Phishing and Account Compromise; R04 — Cloud Data Exposure
* Purpose: Protect authentication information throughout its lifecycle.
* Status: Proposed — Not Verified
* Justification: Secure handling of passwords, credentials and authentication information helps reduce unauthorised account access.

A.5.18 — Access Rights

* Applicable: Yes
* Related Risk: R03 — Insider Data Misuse
* Purpose: Provision, review, modify and remove access rights according to organisational requirements.
* Status: Proposed — Not Verified
* Justification: Periodic access reviews and appropriate permission management help prevent excessive or inappropriate access.

A.5.23 — Information Security for Use of Cloud Services

* Applicable: Yes
* Related Risk: R04 — Cloud Data Exposure
* Purpose: Establish processes for acquiring, using, managing and exiting cloud services securely.
* Status: Proposed — Not Verified
* Justification: The organisation relies on cloud-based storage and services that require appropriate security oversight and configuration management.

A.5.24 — Information Security Incident Management Planning and Preparation

* Applicable: Yes
* Related Risks: R01, R02, R03, R04, R05, R06 and R07
* Purpose: Establish the organisation’s capability to prepare for and respond to information security incidents.
* Status: Proposed — Not Verified
* Justification: A documented incident response approach is required to support consistent reporting, escalation, response and recovery across the identified risk scenarios.

A.5.30 — ICT Readiness for Business Continuity

* Applicable: Yes
* Related Risks: R02 — Ransomware Infection; R07 — Hardware Failure and Data Loss
* Purpose: Ensure ICT readiness supports business continuity objectives.
* Status: Proposed — Not Verified
* Justification: Critical business operations depend on the availability and recovery of information systems and supporting infrastructure.

4.2 People Controls — A.6

A.6.3 — Information Security Awareness, Education and Training

* Applicable: Yes
* Related Risks: R01 — Phishing and Account Compromise; R02 — Ransomware Infection; R03 — Insider Data Misuse
* Purpose: Provide personnel with relevant information security awareness and training.
* Status: Proposed — Not Verified
* Justification: Employees need to understand phishing, credential protection, safe information handling and their security responsibilities.

4.3 Physical Controls — A.7

Physical security controls have not been assessed in this preliminary register.

Status: Not Assessed.

This is a limitation of the current educational case study. It does not mean that physical controls are excluded or not applicable. A complete organisational SoA would need to evaluate relevant physical security requirements.

4.4 Technological Controls — A.8

A.8.2 — Privileged Access Rights

* Applicable: Yes
* Related Risk: R03 — Insider Data Misuse
* Purpose: Restrict and manage privileged access rights.
* Status: Proposed — Not Verified
* Justification: Privileged accounts require stronger access restrictions and appropriate oversight to reduce misuse.

A.8.3 — Information Access Restriction

* Applicable: Yes
* Related Risks: R03 — Insider Data Misuse; R04 — Cloud Data Exposure
* Purpose: Restrict access to information according to established access control requirements.
* Status: Proposed — Not Verified
* Justification: Sensitive client and business information should only be accessible to authorised users with a legitimate business requirement.

A.8.5 — Secure Authentication

* Applicable: Yes
* Related Risks: R01 — Phishing and Account Compromise; R04 — Cloud Data Exposure
* Purpose: Implement secure authentication technologies and procedures.
* Status: Proposed — Not Verified
* Justification: Strong authentication measures, including multi-factor authentication where appropriate, help reduce the risk of unauthorised account access.

A.8.6 — Capacity Management

* Applicable: Yes
* Related Risk: R06 — DDoS Service Disruption
* Purpose: Monitor and manage the capacity of information processing facilities.
* Status: Proposed — Not Verified
* Justification: Capacity monitoring and planning support service availability and help identify resource constraints during abnormal traffic conditions.

A.8.7 — Protection Against Malware

* Applicable: Yes
* Related Risks: R01 — Phishing and Account Compromise; R02 — Ransomware Infection
* Purpose: Protect information and systems against malware.
* Status: Proposed — Not Verified
* Justification: Malicious attachments, downloads and ransomware may compromise organisational devices and information.

A.8.8 — Management of Technical Vulnerabilities

* Applicable: Yes
* Related Risks: R02 — Ransomware Infection; R05 — Exploitation of Unpatched Software
* Purpose: Identify, evaluate and address technical vulnerabilities.
* Status: Proposed — Not Verified
* Justification: Timely vulnerability identification and remediation help reduce exposure to known software weaknesses.

A.8.9 — Configuration Management

* Applicable: Yes
* Related Risks: R04 — Cloud Data Exposure; R05 — Exploitation of Unpatched Software
* Purpose: Establish and monitor secure configurations for systems and services.
* Status: Proposed — Not Verified
* Justification: Secure and controlled configurations help reduce cloud misconfiguration and weaknesses in system settings.

A.8.13 — Information Backup

* Applicable: Yes
* Related Risks: R02 — Ransomware Infection; R07 — Hardware Failure and Data Loss
* Purpose: Maintain and protect backup copies of information.
* Status: Proposed — Not Verified
* Justification: Secure backups and tested restoration procedures support data recovery following ransomware incidents or hardware failure.

A.8.14 — Redundancy of Information Processing Facilities

* Applicable: Yes
* Related Risk: R07 — Hardware Failure and Data Loss
* Purpose: Implement redundancy to meet availability requirements.
* Status: Proposed — Not Verified
* Justification: Redundant information processing capabilities can reduce service disruption when critical hardware or infrastructure components fail.

A.8.16 — Monitoring Activities

* Applicable: Yes
* Related Risks: R01, R02, R03, R04, R06
* Purpose: Monitor networks, systems and applications for anomalous behaviour.
* Status: Proposed — Not Verified
* Justification: Monitoring activities can help identify suspicious access, malware behaviour, cloud configuration changes and abnormal network traffic.

A.8.19 — Installation of Software on Operational Systems

* Applicable: Yes
* Related Risk: R05 — Exploitation of Unpatched Software
* Purpose: Control software installation on operational systems securely.
* Status: Proposed — Not Verified
* Justification: Controlled software installation helps reduce exposure to unauthorised, outdated or insecure software.

A.8.20 — Network Security

* Applicable: Yes
* Related Risk: R06 — DDoS Service Disruption
* Purpose: Secure and protect networks and network devices.
* Status: Proposed — Not Verified
* Justification: Network security measures help protect the organisation’s public-facing services and supporting infrastructure.

A.8.21 — Security of Network Services

* Applicable: Yes
* Related Risk: R06 — DDoS Service Disruption
* Purpose: Identify and implement security mechanisms and requirements for network services.
* Status: Proposed — Not Verified
* Justification: Network services require appropriate security and availability protections to support reliable business operations.

A.8.23 — Web Filtering

* Applicable: Yes
* Related Risk: R01 — Phishing and Account Compromise
* Purpose: Manage access to external websites to reduce exposure to malicious content.
* Status: Proposed — Not Verified
* Justification: Web filtering can help prevent users from accessing known malicious or phishing websites.

A.8.24 — Use of Cryptography

* Applicable: Yes
* Related Risk: R04 — Cloud Data Exposure
* Purpose: Establish rules for effective use of cryptography and encryption.
* Status: Proposed — Not Verified
* Justification: Appropriate cryptographic protections help safeguard sensitive information against unauthorised disclosure.

5. SoA Summary

Control Category	Selected Controls
A.5 — Organisational	6
A.6 — People	1
A.7 — Physical	Not Assessed
A.8 — Technological	15
Total Selected Controls	22

All 22 selected controls are considered applicable to this preliminary risk-based assessment.

Their implementation has not been independently verified. Selection and applicability do not demonstrate that a control is implemented or operating effectively.

6. Implementation Status Definitions

The following status terminology is used throughout this project:

* Proposed — Not Verified: A control has been selected or recommended, but implementation has not been established through evidence.
* In Progress: Implementation activities have started, but the control is not yet fully implemented.
* Implemented — Pending Verification: The control has reportedly been deployed, but its operation and effectiveness have not yet been verified.
* Partially Implemented: Some control requirements are in place, but gaps remain.
* Verified: Implementation and operating effectiveness have been assessed and supported by appropriate evidence.

The current status of all selected controls is Proposed — Not Verified.

7. Limitations

This document represents a preliminary Statement of Applicability for a fictional organisation.

The following limitations apply:

1. The organisation and its operating environment are simulated.
2. Only 22 selected Annex A controls are documented in this preliminary register.
3. Physical controls under A.7 have not been assessed.
4. The remaining Annex A controls have not undergone a complete applicability and exclusion assessment.
5. No control implementation evidence has been supplied or independently verified.
6. The document does not represent an official ISO/IEC 27001 certification or compliance audit.

8. Conclusion

This preliminary SoA establishes a risk-based selection of 22 ISO/IEC 27001:2022 Annex A controls for Nexora Solutions Pvt. Ltd.

The selected controls are mapped to the cybersecurity risks documented in the Risk Assessment and Risk Treatment Plan.

Further assessment is required to complete the applicability review, evaluate physical security requirements, implement the proposed controls and collect evidence of their effectiveness.

The SoA should be reviewed and updated as the organisation’s risks, requirements and control implementation status change.
