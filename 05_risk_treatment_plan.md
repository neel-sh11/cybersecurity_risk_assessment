05 — Risk Treatment Plan & Security Controls

Organisation: Nexora Solutions Pvt. Ltd.
Assessment Type: Simulated Cybersecurity Risk Assessment
Framework: ISO/IEC 27001:2022
Document Status: Proposed Risk Treatment Plan

⸻

1. Objective

The purpose of this document is to define appropriate treatment strategies and security controls for the cybersecurity risks identified during the risk assessment.

The treatment plan aims to reduce the likelihood and/or impact of identified risks through appropriate organisational, people and technological security measures.

This document establishes proposed security improvements, relevant ISO/IEC 27001:2022 Annex A control references, preliminary responsibilities and implementation priorities.

2. Risk Treatment Strategies

The organisation considers four primary risk treatment strategies.

2.1 Risk Avoidance

Eliminating activities or processes that create unacceptable risks.

Example: Discontinuing an insecure application that cannot be adequately protected.

2.2 Risk Mitigation

Implementing security controls to reduce the likelihood or impact of a risk.

Example: Implementing Multi-Factor Authentication (MFA) to reduce the possibility of unauthorised account access.

2.3 Risk Transfer or Sharing

Sharing certain financial or operational consequences of a risk with another party.

Example: Purchasing cyber insurance to help manage eligible financial losses.

2.4 Risk Acceptance

Formally acknowledging a risk and deciding to retain it within the organisation’s approved risk tolerance.

Example: Accepting a low-impact risk with appropriate management approval and monitoring.

3. Risk Treatment Approach

Nexora Solutions will primarily use risk mitigation to address its identified Critical, High and Moderate risks.

All seven identified risks have been assigned a mitigation strategy based on their potential business impact and security requirements.

The proposed treatment approach focuses on:

* Strengthening identity and access management.
* Improving email security and employee awareness.
* Implementing formal vulnerability and patch management.
* Improving backup and recovery procedures.
* Strengthening cloud security configurations.
* Improving network monitoring and protection.
* Establishing appropriate business continuity measures.

The proposed controls will require management approval, resource allocation and implementation verification.

⸻

4. Proposed Security Controls

The following sections define the proposed treatment actions and relevant ISO/IEC 27001:2022 Annex A controls for each identified risk.

R01 — Phishing and Account Compromise

Initial Risk Score: 20
Initial Risk Rating: Critical
Treatment Strategy: Mitigate

Risk Treatment Actions:

1. Conduct regular employee phishing awareness and security training.
2. Implement Multi-Factor Authentication (MFA) for organisational user accounts.
3. Configure email filtering and malicious attachment protection.
4. Conduct periodic phishing simulation exercises.
5. Establish procedures for reporting suspicious emails and suspected account compromise.

Relevant ISO/IEC 27001:2022 Controls:

* A.6.3 — Information security awareness, education and training.
* A.8.5 — Secure authentication.
* A.5.17 — Authentication information.
* A.8.7 — Protection against malware.
* A.8.23 — Web filtering.
* A.5.24 — Information security incident management planning and preparation.
* A.8.16 — Monitoring activities.

Responsible Departments: IT and HR

R02 — Ransomware Infection

Initial Risk Score: 20
Initial Risk Rating: Critical
Treatment Strategy: Mitigate

Risk Treatment Actions:

1. Implement regular security updates and formal patch management.
2. Maintain secure and isolated backups of critical organisational information.
3. Conduct periodic data restoration and backup recovery tests.
4. Implement endpoint malware protection across organisational devices.
5. Monitor suspicious system activities and potential malware behaviour.
6. Establish an incident response procedure for ransomware-related incidents.

Relevant ISO/IEC 27001:2022 Controls:

* A.8.7 — Protection against malware.
* A.8.8 — Management of technical vulnerabilities.
* A.8.13 — Information backup.
* A.8.16 — Monitoring activities.
* A.5.24 — Information security incident management planning and preparation.
* A.5.30 — ICT readiness for business continuity.

Responsible Department: IT Department

R03 — Insider Data Misuse

Initial Risk Score: 15
Initial Risk Rating: High
Treatment Strategy: Mitigate

Risk Treatment Actions:

1. Apply the principle of least privilege to organisational accounts.
2. Review user access permissions periodically.
3. Restrict access to sensitive client information based on job responsibilities.
4. Monitor privileged user activities and access to critical information.
5. Remove or modify access permissions promptly when employees leave the organisation or change roles.
6. Establish formal access approval procedures.

Relevant ISO/IEC 27001:2022 Controls:

* A.5.15 — Access control.
* A.5.18 — Access rights.
* A.8.2 — Privileged access rights.
* A.8.3 — Information access restriction.
* A.8.16 — Monitoring activities.
  
Responsible Departments: IT and HR

R04 — Cloud Data Exposure

Initial Risk Score: 15
Initial Risk Rating: High
Treatment Strategy: Mitigate

Risk Treatment Actions:

1. Review cloud storage permissions regularly.
2. Restrict public access to sensitive cloud storage resources.
3. Implement strong authentication for cloud accounts.
4. Monitor cloud configuration changes and unauthorised access attempts.
5. Apply appropriate encryption to sensitive organisational information.
6. Establish procedures for reviewing cloud security configurations.

Relevant ISO/IEC 27001:2022 Controls:

* A.5.23 — Information security for use of cloud services.
* A.5.15 — Access control.
* A.8.9 — Configuration management.
* A.8.24 — Use of cryptography.
* A.8.5 — Secure authentication.
* A.8.16 — Monitoring activities.

Responsible Department: IT Department

R05 — Exploitation of Unpatched Software

Initial Risk Score: 16
Initial Risk Rating: High
Treatment Strategy: Mitigate

Risk Treatment Actions:

1. Establish a formal vulnerability and patch management process.
2. Maintain an updated inventory of organisational software and systems.
3. Prioritise security updates based on vulnerability severity and potential business impact.
4. Conduct periodic vulnerability assessments.
5. Verify that critical security updates have been successfully installed.
6. Document identified vulnerabilities, remediation activities and outstanding issues.

Relevant ISO/IEC 27001:2022 Controls:


Relevant ISO/IEC 27001:2022 Controls:

* A.6.3 — Information security awareness, education and training.
* A.5.17 — Authentication information.
* A.8.5 — Secure authentication.
* A.8.7 — Protection against malware.
* A.8.23 — Web filtering.
* A.8.8 — Management of technical vulnerabilities.
* A.8.9 — Configuration management.
* A.8.19 — Installation of software on operational systems.
 
Responsible Department: IT Department

R06 — DDoS Service Disruption

Initial Risk Score: 9
Initial Risk Rating: Moderate
Treatment Strategy: Mitigate

Risk Treatment Actions:

1. Implement appropriate Distributed Denial of Service (DDoS) protection services.
2. Monitor unusual network traffic and potential traffic-based attacks.
3. Review network security configurations periodically.
4. Evaluate service capacity and availability requirements.
5. Establish procedures for responding to website and service disruptions.
6. Coordinate with relevant service providers for incident mitigation where required.

Relevant ISO/IEC 27001:2022 Controls:

* A.8.6 — Capacity management.
* A.8.20 — Network security.
* A.8.21 — Security of network services.
* A.8.16 — Monitoring activities. 

Responsible Department: IT Department

R07 — Hardware Failure and Data Loss

Initial Risk Score: 12
Initial Risk Rating: High
Treatment Strategy: Mitigate

Risk Treatment Actions:

1. Schedule regular backups of critical organisational information.
2. Maintain separate backup copies to reduce dependence on primary systems.
3. Conduct periodic data restoration and recovery tests.
4. Monitor hardware health and identify potential equipment failures.
5. Establish business continuity and disaster recovery procedures.
6. Evaluate redundancy options for critical information processing infrastructure.

  ### Cross-Cutting Incident Management Control

A.5.24 — Information security incident management planning and preparation is a cross-cutting control relevant to all seven identified risks.

The organisation should establish incident reporting, escalation, response and documentation procedures that can support the management of different security incidents. 

Relevant ISO/IEC 27001:2022 Controls:

* A.8.13 — Information backup.
* A.8.14 — Redundancy of information processing facilities.
* A.5.30 — ICT readiness for business continuity.

Responsible Department: IT Department

⸻

5. Risk Treatment Summary

The following summary presents the selected treatment strategy for all seven identified risks.

R01 — Phishing and Account Compromise

* Initial Score: 20
* Initial Rating: Critical
* Treatment: Mitigate

R02 — Ransomware Infection

* Initial Score: 20
* Initial Rating: Critical
* Treatment: Mitigate

R03 — Insider Data Misuse

* Initial Score: 15
* Initial Rating: High
* Treatment: Mitigate

R04 — Cloud Data Exposure

* Initial Score: 15
* Initial Rating: High
* Treatment: Mitigate

R05 — Exploitation of Unpatched Software

* Initial Score: 16
* Initial Rating: High
* Treatment: Mitigate

R06 — DDoS Service Disruption

* Initial Score: 9
* Initial Rating: Moderate
* Treatment: Mitigate

R07 — Hardware Failure and Data Loss

* Initial Score: 12
* Initial Rating: High
* Treatment: Mitigate

All seven risks have been assigned a mitigation strategy. The initial risk ratings remain unchanged until treatment implementation and effectiveness have been evaluated.

⸻

6. Implementation Responsibilities

The following responsibilities are proposed for coordinating and overseeing risk treatment activities.

IT Manager

* Coordinate technical security improvements.
* Manage access controls and patch management activities.
* Oversee backup and recovery procedures.
* Monitor infrastructure security.
* Coordinate vulnerability remediation.

HR Manager

* Coordinate employee security awareness training.
* Support employee onboarding and offboarding procedures.
* Assist with periodic employee security awareness activities.

Development Manager

* Support secure software development practices.
* Coordinate software vulnerability remediation.
* Assist with identifying and addressing software security weaknesses.

Senior Management

* Review and approve risk treatment decisions.
* Allocate appropriate resources for security improvements.
* Review significant residual risks.
* Provide management approval for formally accepted risks.

These responsibilities are proposed assignments and do not represent verified organisational appointments.

⸻

7. Implementation Phases

The proposed implementation activities will be organised into three phases.

Phase 1 — Immediate Priorities

* Strengthen authentication mechanisms.
* Improve email security and phishing protection.
* Review critical cloud access permissions.
* Establish secure backup practices.
* Improve protection against ransomware.

Phase 2 — Security Improvements

* Establish formal patch management procedures.
* Review user access privileges.
* Improve network monitoring and protection.
* Conduct employee security awareness training.
* Implement vulnerability assessment procedures.

Phase 3 — Continuous Improvement

* Conduct periodic vulnerability assessments.
* Test incident response and recovery procedures.
* Review security control effectiveness.
* Evaluate infrastructure redundancy.
* Reassess remaining cybersecurity risks.

The implementation phases represent proposed priorities rather than confirmed completion dates.

⸻

8. Residual Risk Considerations

Residual risk refers to the level of risk remaining after security controls have been implemented and their effectiveness has been evaluated.

The organisation should reassess each identified risk after implementing the proposed treatment actions.

The reassessment should consider:

* Whether the proposed controls have been implemented.
* Whether implementation evidence is available.
* Whether the controls operate effectively.
* Whether the likelihood or impact of the risk has changed.
* Whether the remaining risk is within the organisation’s acceptable risk tolerance.

A risk must not be considered reduced merely because a security control has been proposed.

Residual risk ratings should only be assigned after implementation evidence and control effectiveness have been evaluated.

Formal management approval should be obtained for risks that are accepted.

⸻

9. Assessment Conclusion

This risk treatment plan establishes proposed security actions for all seven cybersecurity risks identified during the assessment.

Each risk has been assigned a mitigation strategy, relevant ISO/IEC 27001:2022 Annex A control references and preliminary implementation responsibilities.

The proposed treatment activities focus on improving organisational security across identity and access management, malware protection, vulnerability management, cloud security, network protection, backup and business continuity.

The treatment plan provides the foundation for the subsequent Statement of Applicability, control implementation tracking and residual risk assessment.

The effectiveness of these proposed controls must be evaluated before any reduction in risk ratings can be justified.

⸻

Project: Cybersecurity Risk Assessment & ISO 27001 Case Study
Organisation: Nexora Solutions Pvt. Ltd.
Document: 05 — Risk Treatment Plan & Security Controls
Status: Proposed — Not Yet Implemented

Disclaimer: This is a simulated educational assessment. The proposed security controls and treatment activities have not been implemented or independently verified.
