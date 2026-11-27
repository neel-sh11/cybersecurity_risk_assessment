10 — Methodology and References

Organisation: Nexora Solutions Pvt. Ltd.
Assessment: Cybersecurity Risk Assessment and Treatment
Framework: ISO/IEC 27001:2022
Assessment Type: Simulated GRC Case Study
Document Status: Final Methodology Documentation

⸻

1. Introduction

This document explains the methodology, assessment approach, risk evaluation criteria and reference materials used throughout the Nexora Solutions cybersecurity risk assessment project.

The project demonstrates a structured approach to identifying information security risks, evaluating their potential impact, selecting appropriate security controls and planning risk treatment activities.

The assessment is based on a fictional organisation and is intended for educational and portfolio demonstration purposes.

It does not represent an official ISO/IEC 27001 certification audit or an assessment of a real organisation.

2. Assessment Objectives

The primary objectives are to:

* Establish a simulated organisational information security context.
* Identify important information assets.
* Identify relevant threats and vulnerabilities.
* Evaluate cybersecurity risks using a consistent risk rating methodology.
* Recommend appropriate risk treatment measures.
* Map selected security controls to ISO/IEC 27001:2022 Annex A.
* Establish a preliminary Statement of Applicability.
* Define proposed control implementation activities.
* Evaluate residual risk requirements.
* Communicate findings through an executive summary.

3. Assessment Scope

The assessment covers the simulated information security environment of Nexora Solutions Pvt. Ltd.

The scope includes:

* Organisational information assets.
* Information systems and supporting technology.
* User access and authentication.
* Cloud-based services and information storage.
* Network and service availability.
* Software vulnerabilities and malware exposure.
* Data protection and recovery requirements.
* Information security incident management.

The assessment focuses on seven identified cybersecurity risks.

Physical security controls under ISO/IEC 27001:2022 Annex A.7 have not been assessed in this preliminary exercise.

The selected Annex A controls represent a preliminary risk-based selection and not a complete applicability assessment of all 93 controls.

4. Assessment Methodology

The assessment follows a structured risk management process.

4.1 Organisational Context

The organisation profile establishes the simulated business environment, its activities, information assets and security requirements.

This provides the foundation for identifying potential information security risks.

Reference Document: 01_organisation_profile.md

4.2 Asset Identification

Relevant information assets are identified and documented.

Assets are considered according to their business importance, information sensitivity and potential consequences of compromise.

Examples include:

* Business information and records.
* Client and employee information.
* Information systems.
* Cloud platforms and storage.
* Network infrastructure.
* End-user devices.

Reference Document: 02_asset_inventory.md

4.3 Threat and Vulnerability Assessment

Potential threats and vulnerabilities are identified for the organisation’s information assets.

Threats represent potential causes of security incidents, while vulnerabilities represent weaknesses that could be exploited.

The assessment considers scenarios such as phishing, ransomware, unauthorised access, cloud exposure, software vulnerabilities, service disruption and hardware failure.

Reference Document: 03_threat_vulnerability_assessment.md

4.4 Risk Identification and Assessment

Identified threats and vulnerabilities are evaluated to determine their potential information security risks.

The assessment considers:

* Likelihood of occurrence.
* Potential business impact.
* Confidentiality, integrity and availability consequences.
* Existing security considerations.
* Overall risk priority.

A consistent scoring approach is used to support risk prioritisation.

Reference Document: 04_risk_assessment.md

4.5 Risk Treatment

Risk treatment options are considered according to the nature and priority of each identified risk.

The treatment approach includes:

* Risk Mitigation: Reducing the likelihood or impact of a risk through security measures.
* Risk Avoidance: Discontinuing an activity that creates unacceptable risk.
* Risk Transfer or Sharing: Sharing or transferring certain financial or operational consequences through appropriate arrangements.
* Risk Acceptance: Formally accepting a risk within approved organisational tolerance.

The project primarily focuses on proposed risk mitigation activities.

Relevant ISO/IEC 27001:2022 Annex A controls are identified for each risk.

Reference Document: 05_risk_treatment_plan.md

4.6 Statement of Applicability

A preliminary Statement of Applicability is developed using a risk-based selection of ISO/IEC 27001:2022 Annex A controls.

The current selection contains:

Control Category	Selected Controls
A.5 — Organisational	6
A.6 — People	1
A.7 — Physical	Not Assessed
A.8 — Technological	15
Total Selected	22

The selected controls are documented with applicability decisions, related risks, purpose and current status.

The remaining Annex A controls have not undergone a complete applicability and exclusion assessment.

Reference Document: 06_statement_of_applicability.md

4.7 Control Implementation Planning

A control implementation tracker is prepared to define proposed implementation activities.

Each selected control includes relevant information such as:

* Control objective.
* Related risk.
* Proposed implementation activities.
* Proposed responsibility.
* Priority.
* Evidence requirements.
* Current implementation status.

All 22 selected controls are currently classified as:

Proposed — Not Verified

No implementation evidence has been supplied or independently verified.

Reference Document: 07_control_implementation_tracker.md

4.8 Residual Risk Assessment

Residual risk represents the risk remaining after selected treatment measures have been implemented and their effectiveness has been evaluated.

Residual risk should not be assumed to be lower merely because a control has been recommended.

For this project, residual risk scores remain pending reassessment because the proposed controls have not been implemented and verified.

Reference Document: 08_residual_risk_assessment.md

4.9 Executive Reporting

The assessment findings are consolidated into an executive summary.

The summary communicates the overall risk position, selected controls, proposed treatment approach, implementation status and limitations.

Reference Document: 09_executive_summary.md

5. Risk Scoring Methodology

The project uses a qualitative risk assessment supported by a numerical scoring model.

Risk scores are calculated using:

Risk Score = Likelihood × Impact

Both likelihood and impact are rated on a five-point scale.

5.1 Likelihood Scale

Score	Rating	Description
1	Rare	Highly unlikely to occur
2	Unlikely	Could occur, but not expected frequently
3	Possible	May occur under certain circumstances
4	Likely	Expected to occur in relevant circumstances
5	Almost Certain	Expected to occur frequently or repeatedly

5.2 Impact Scale

Score	Rating	Description
1	Insignificant	Minimal operational or information impact
2	Minor	Limited disruption or loss
3	Moderate	Noticeable operational or information impact
4	Major	Significant business disruption or information compromise
5	Severe	Critical business, financial, legal or reputational consequences

5.3 Risk Rating Classification

The calculated risk score is classified using the following bands:

Risk Score	Rating
1–4	Low
5–9	Moderate
10–16	High
17–25	Critical

These rating bands are the project’s defined assessment criteria. They are not presented as mandatory numerical thresholds prescribed by ISO/IEC 27001.

6. Risk Treatment and Control Selection Principles

The project uses a risk-based approach when selecting security controls.

Control selection considers:

1. The nature of the identified risk.
2. The assets affected by the risk.
3. The likelihood and potential impact.
4. The proposed risk treatment strategy.
5. The relevance of ISO/IEC 27001:2022 Annex A controls.
6. The need for appropriate implementation evidence.

A control being selected does not mean that it has been implemented.

Control implementation must be supported by evidence, and operating effectiveness must be assessed before a control can be considered verified.

7. Control Implementation Status Definitions

The following status definitions are used throughout the project:

* Proposed — Not Verified: A control has been selected or recommended, but implementation has not been established through evidence.
* In Progress: Implementation activities have started, but the control is not yet fully implemented.
* Implemented — Pending Verification: The control has reportedly been deployed, but its operation and effectiveness have not been verified.
* Partially Implemented: Some requirements are in place, but implementation gaps remain.
* Verified: Implementation and operating effectiveness have been assessed and supported by appropriate evidence.

The current baseline for all 22 selected controls is Proposed — Not Verified.

8. Residual Risk Evaluation Principles

Residual risk evaluation should take place after risk treatment activities have been completed or sufficiently implemented.

The evaluation should consider:

* Whether the proposed control has been implemented.
* Whether sufficient implementation evidence exists.
* Whether the control operates as intended.
* Whether the original likelihood has changed.
* Whether the original impact has changed.
* Whether additional treatment is required.
* Whether the remaining risk is within the organisation’s acceptance criteria.

Residual risk scores must be recalculated using the same likelihood and impact methodology applied during the initial assessment.

No residual risk reduction is assumed in this project.

9. Assumptions and Limitations

This project has the following limitations:

1. Nexora Solutions Pvt. Ltd. is a fictional organisation.
2. The organisational profile and assessment environment are simulated.
3. The identified assets, threats, vulnerabilities and risk scenarios are illustrative.
4. Risk scores are based on the project’s defined assessment assumptions.
5. No production infrastructure or real organisational systems were accessed or tested.
6. No vulnerability scanning, penetration testing or technical validation was performed as part of this documented assessment.
7. The 22 selected Annex A controls represent a preliminary selection, not a complete assessment of all 93 controls.
8. Physical controls under Annex A.7 have not been assessed.
9. No control implementation evidence has been supplied or independently verified.
10. Residual risk scores remain pending implementation and effectiveness assessment.

These limitations should be considered when interpreting the assessment findings.

10. References

The following publications and frameworks provide the reference basis for this project:

1. ISO/IEC 27001:2022 — Information security, cybersecurity and privacy protection — Information security management systems — Requirements.
2. ISO/IEC 27002:2022 — Information security, cybersecurity and privacy protection — Information security controls.
3. ISO 31000:2018 — Risk management — Guidelines.
4. NIST Cybersecurity Framework 2.0 — A framework for managing cybersecurity risks.

Official reference resources:

* ISO: https://www.iso.org/
* NIST Cybersecurity Framework: https://www.nist.gov/cyberframework

These references support the general principles and control concepts used in the case study. The project does not claim formal conformity or certification against these standards.

11. Conclusion

This methodology establishes a consistent approach to the simulated cybersecurity risk assessment of Nexora Solutions Pvt. Ltd.

It connects organisational context, asset identification, threat and vulnerability analysis, risk evaluation, treatment planning, control selection and residual risk assessment.

The resulting documentation provides a structured demonstration of foundational Governance, Risk and Compliance (GRC) practices.

Further work would include completing the full Annex A applicability assessment, evaluating physical security requirements, implementing proposed controls, collecting evidence, validating control effectiveness and reassessing residual risks.
