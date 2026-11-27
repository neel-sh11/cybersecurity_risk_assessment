06 — Statement of Applicability (SoA)

Organisation: Nexora Solutions Pvt. Ltd.
Framework: ISO/IEC 27001:2022
Reference: Annex A
Document Type: Preliminary Statement of Applicability
Document Status: Revised Draft

⸻

1. Objective

The purpose of this Statement of Applicability (SoA) is to identify relevant information security controls for Nexora Solutions and document their applicability, implementation status and justification.

The SoA connects the cybersecurity risks identified during the risk assessment with appropriate ISO/IEC 27001:2022 Annex A controls.

It provides a structured foundation for security control selection, implementation tracking and future compliance assessment.

2. ISO/IEC 27001:2022 Annex A Structure

Annex A contains 93 reference controls divided into four categories:

A.5 — Organisational Controls
37 controls covering security policies, access management, supplier relationships and information security governance.

A.6 — People Controls
8 controls covering employee responsibilities, awareness, training and personnel-related security requirements.

A.7 — Physical Controls
14 controls covering physical security, equipment protection and secure working environments.

A.8 — Technological Controls
34 controls covering authentication, network security, malware protection, backup and technical vulnerability management.

Total: 93 controls

3. Applicability Criteria

Controls are evaluated based on:

1. Identified cybersecurity risks.
2. Organisational information assets.
3. Business operations and security requirements.
4. Legal, regulatory and contractual obligations.
5. Risk treatment decisions.
6. Organisational security objectives.

A control is considered applicable when it is required to address an identified risk or other relevant information security requirement.

Controls that are excluded must have documented justifications.

4. Statement of Applicability Register

The following 21 controls have been selected for this preliminary assessment.

All selected controls are considered applicable to the simulated organisation.

4.1 Organisational Controls — A.5

A.5.15 — Access Control

* Applicable: Yes
* Related Risk: R03 — Insider Data Misuse
* Purpose: Establish rules for controlling access to information and associated assets.
* Status: Proposed — Not Implemented
* Justification: Sensitive organisational information requires controlled access.

A.5.17 — Authentication Information

* Applicable: Yes
* Related Risk: R01 — Phishing and Account Compromise
* Purpose: Protect authentication information throughout its lifecycle.
* Status: Proposed — Not Implemented
* Justification: Authentication credentials must be securely managed and protected against compromise.

A.5.18 — Access Rights

* Applicable: Yes
* Related Risk: R03 — Insider Data Misuse
* Purpose: Provision, review, modify and remove access rights according to organisational requirements.
* Status: Proposed — Not Implemented
* Justification: Periodic access reviews help prevent excessive user permissions.

A.5.23 — Information Security for Use of Cloud Services

* Applicable: Yes
* Related Risk: R04 — Cloud Data Exposure
* Purpose: Establish processes for acquiring, using, managing and exiting cloud services securely.
* Status: Proposed — Not Implemented
* Justification: The organisation relies on cloud-based infrastructure and storage.

A.5.30 — ICT Readiness for Business Continuity

* Applicable: Yes
* Related Risk: R07 — Hardware Failure and Data Loss
* Purpose: Ensure ICT readiness supports business continuity objectives.
* Status: Proposed — Not Implemented
* Justification: Critical business operations depend on IT system availability and recovery.

4.2 People Controls — A.6

A.6.3 — Information Security Awareness, Education and Training

* Applicable: Yes
* Related Risk: R01 — Phishing and Account Compromise
* Purpose: Provide employees with relevant information security awareness and training.
* Status: Proposed — Not Implemented
* Justification: Employees require awareness of phishing, credential theft and other security threats.

4.3 Physical Controls — A.7

Physical security controls require further assessment during a complete Statement of Applicability review.

* Assessment Status: Not Assessed
* Exclusion Decision: Not Determined

Physical controls are not automatically considered excluded or unnecessary.

A separate review of office facilities, equipment protection and physical access requirements would be required.

4.4 Technological Controls — A.8

A.8.2 — Privileged Access Rights

* Applicable: Yes
* Related Risk: R03 — Insider Data Misuse
* Purpose: Restrict and manage privileged access rights.
* Status: Proposed — Not Implemented
* Justification: Privileged accounts require stronger access restrictions and monitoring.

A.8.3 — Information Access Restriction

* Applicable: Yes
* Related Risk: R03 — Insider Data Misuse
* Purpose: Restrict access to information according to established access control policies.
* Status: Proposed — Not Implemented
* Justification: Sensitive information must only be accessible to authorised users.

A.8.5 — Secure Authentication

* Applicable: Yes
* Related Risk: R01 — Phishing and Account Compromise
* Purpose: Implement secure authentication technologies and procedures.
* Status: Proposed — Not Implemented
* Justification: Secure authentication, including MFA where appropriate, helps reduce unauthorised account access.

A.8.6 — Capacity Management

* Applicable: Yes
* Related Risk: R06 — DDoS Service Disruption
* Purpose: Monitor and manage resource utilisation to ensure adequate system capacity.
* Status: Proposed — Not Implemented
* Justification: Appropriate capacity management supports service availability and helps identify resource exhaustion.

A.8.7 — Protection Against Malware

* Applicable: Yes
* Related Risks: R01 and R02
* Purpose: Implement protection against malware.
* Status: Proposed — Not Implemented
* Justification: Malware and ransomware may compromise organisational systems and information.

A.8.8 — Management of Technical Vulnerabilities

* Applicable: Yes
* Related Risk: R05 — Exploitation of Unpatched Software
* Purpose: Identify, evaluate and address technical vulnerabilities.
* Status: Proposed — Not Implemented
* Justification: Timely vulnerability management reduces exposure to known software weaknesses.

A.8.9 — Configuration Management

* Applicable: Yes
* Related Risk: R04 — Cloud Data Exposure
* Purpose: Establish and monitor secure configurations for systems and services.
* Status: Proposed — Not Implemented
* Justification: Secure configuration management helps prevent cloud and infrastructure misconfiguration.

A.8.13 — Information Backup

* Applicable: Yes
* Related Risks: R02 and R07
* Purpose: Maintain backup copies of information, software and systems.
* Status: Proposed — Not Implemented
* Justification: Reliable backups support recovery from ransomware incidents and hardware failures.

A.8.14 — Redundancy of Information Processing Facilities

* Applicable: Yes
* Related Risk: R07 — Hardware Failure and Data Loss
* Purpose: Implement redundancy sufficient to meet availability requirements.
* Status: Proposed — Not Implemented
* Justification: Redundancy can reduce dependence on individual hardware components and support service continuity.

A.8.16 — Monitoring Activities

* Applicable: Yes
* Related Risks: R02, R03 and R04
* Purpose: Monitor networks, systems and applications for anomalous behaviour.
* Status: Proposed — Not Implemented
* Justification: Monitoring helps identify suspicious activities and potential security incidents.

A.8.19 — Installation of Software on Operational Systems

* Applicable: Yes
* Related Risk: R05 — Exploitation of Unpatched Software
* Purpose: Control software installation on operational systems securely.
* Status: Proposed — Not Implemented
* Justification: Controlled software installation helps reduce exposure to unauthorised or insecure software.

A.8.20 — Networks Security

* Applicable: Yes
* Related Risk: R06 — DDoS Service Disruption
* Purpose: Protect networks, network devices and information transmitted through them.
* Status: Proposed — Not Implemented
* Justification: Network security measures help protect online services and organisational infrastructure.

A.8.21 — Security of Network Services

* Applicable: Yes
* Related Risk: R06 — DDoS Service Disruption
* Purpose: Identify and implement security mechanisms and service requirements for network services.
* Status: Proposed — Not Implemented
* Justification: Network services require appropriate security and availability protections.

A.8.23 — Web Filtering

* Applicable: Yes
* Related Risk: R01 — Phishing and Account Compromise
* Purpose: Manage access to external websites to reduce exposure to malicious content.
* Status: Proposed — Not Implemented
* Justification: Web filtering can help prevent access to known malicious websites.

A.8.24 — Use of Cryptography

* Applicable: Yes
* Related Risk: R04 — Cloud Data Exposure
* Purpose: Establish rules for effective use of cryptography and encryption.
* Status: Proposed — Not Implemented
* Justification: Cryptographic protections help safeguard sensitive information against unauthorised disclosure.

5. SoA Summary

The preliminary register contains the following selected controls:

* Organisational Controls (A.5): 5
* People Controls (A.6): 1
* Physical Controls (A.7): Not Assessed
* Technological Controls (A.8): 15

Total Selected and Documented Controls: 21

All 21 selected controls are considered applicable to the preliminary assessment.

No selected control has been verified as implemented.

6. Implementation Status Definitions

Not Implemented: The required control has not been implemented.

Partially Implemented: Some elements of the control are implemented, but gaps remain.

Implemented: The control has been deployed and supporting evidence is available.

Not Verified: Implementation status has not been established through assessment evidence.

For this simulated case study, all selected controls remain proposed and not implemented.

7. Exclusions and Limitations

This document represents a preliminary selection of 21 applicable controls from the 93 ISO/IEC 27001:2022 Annex A reference controls.

It is not a complete Statement of Applicability for ISO/IEC 27001 certification purposes.

The remaining controls have not yet undergone individual applicability and exclusion assessment.

A complete SoA must consider all 93 controls, document applicability decisions, justify exclusions and record implementation status.

Physical security requirements and additional organisational requirements require further assessment.

8. Assessment Conclusion

The preliminary Statement of Applicability connects 21 selected ISO/IEC 27001:2022 Annex A controls with the seven cybersecurity risks identified during the assessment.

It establishes a foundation for control implementation tracking, evidence collection and future risk reassessment.

The selected controls require implementation, verification and periodic review before their effectiveness can be established.

⸻

Project: Cybersecurity Risk Assessment & ISO 27001 Case Study
Organisation: Nexora Solutions Pvt. Ltd.
Document: 06 — Statement of Applicability
Status: Preliminary Draft — 21 Selected Controls

Disclaimer: This is a simulated educational assessment. Control applicability and implementation status have not been independently verified.
