10 — Methodology and References

Organisation: Nexora Solutions Pvt. Ltd.
Project: Cybersecurity Risk Assessment & ISO 27001 Case Study
Document Type: Methodology and References
Version: 2.0
Status: Revised Assessment Methodology

⸻

1. Purpose

This document describes the methodology, assessment principles, risk evaluation approach and reference materials used throughout the Cybersecurity GRC Risk Assessment Project.

The purpose is to maintain consistency, transparency and traceability across all project documents.

The assessment uses ISO/IEC 27001:2022 as its primary reference framework, supported by relevant information security risk management and cybersecurity guidance.

2. Assessment Approach

The project follows a structured risk-based information security assessment process.

The methodology connects the following activities:

1. Organisational context identification.
2. Information asset identification.
3. Threat and vulnerability identification.
4. Risk analysis and evaluation.
5. Risk treatment planning.
6. Security control applicability assessment.
7. Control implementation tracking.
8. Residual risk evaluation.
9. Documentation and management review.

Each stage provides information required for the subsequent assessment activities.

3. Assessment Methodology

Step 1 — Define the Organisational Context

Establish the fictional organisation’s business environment, operational activities, information security requirements and assessment boundaries.

The organisational profile provides the context for identifying relevant information assets and potential security risks.

Reference Document: 01 — Organisation Profile.

Step 2 — Identify and Classify Information Assets

Identify organisational assets that support business operations and information processing.

Examples include:

* Hardware and computing devices.
* Software and applications.
* Business information and databases.
* Network infrastructure.
* Cloud storage and services.
* User accounts and credentials.
* Backup infrastructure.

Assets are documented with their relevant identifiers, descriptions, classifications and ownership information.

Reference Document: 02 — Asset Inventory.

Step 3 — Identify Threats and Vulnerabilities

Identify potential threat events and vulnerabilities that could affect organisational assets.

Threats represent potential sources of harm, while vulnerabilities represent weaknesses that could be exploited.

The assessment establishes relationships between relevant threats and vulnerabilities.

Reference Document: 03 — Threat and Vulnerability Assessment.

Step 4 — Analyse and Evaluate Risks

Evaluate the potential cybersecurity risks associated with identified assets, threats and vulnerabilities.

Each risk is assessed using two primary factors:

Likelihood: The estimated probability of a risk event occurring.

Impact: The potential consequences if the risk event occurs.

The resulting risk score determines the corresponding risk classification and treatment priority.

Reference Document: 04 — Cybersecurity Risk Assessment.

Step 5 — Determine Risk Treatment

Select an appropriate risk treatment strategy for each identified risk.

The assessment considers four general treatment approaches:

Risk Modification

Implementing security measures to reduce the likelihood or impact of a risk. This includes risk mitigation.

Risk Avoidance

Discontinuing an activity or process that creates an unacceptable risk.

Risk Sharing

Sharing certain risk consequences with another party through appropriate contractual arrangements, insurance or other mechanisms.

Risk Retention

Formally retaining a risk through an authorised and documented management decision.

All seven identified risks in this project have been assigned a mitigation strategy.

Reference Document: 05 — Risk Treatment Plan.

Step 6 — Assess Control Applicability

Review relevant ISO/IEC 27001:2022 Annex A controls and determine their applicability to the identified organisational risks and requirements.

Document:

* Selected security controls.
* Applicability decisions.
* Justification for control selection.
* Related risk identifiers.
* Implementation status.
* Exclusion decisions where applicable.

This project selects 21 controls for its preliminary Statement of Applicability.

The remaining Annex A controls have not undergone a complete individual applicability assessment.

Reference Document: 06 — Statement of Applicability.

Step 7 — Track Control Implementation

Establish a structured process for monitoring proposed security control implementation.

The tracking process records:

* Control identifiers.
* Responsible departments.
* Implementation priorities.
* Proposed timelines.
* Implementation status.
* Required supporting evidence.
* Verification requirements.

Control implementation claims must be supported by appropriate evidence.

Reference Document: 07 — Control Implementation Tracker.

Step 8 — Evaluate Residual Risk

Reassess identified risks after the relevant security controls have been implemented and their effectiveness has been evaluated.

The reassessment considers whether the likelihood and/or impact of each risk has changed.

Residual risk ratings must be supported by implementation evidence, control effectiveness testing and appropriate risk owner review.

Reference Document: 08 — Residual Risk Assessment.

Step 9 — Consolidate Assessment Findings

Summarise the assessment scope, key findings, risk distribution, proposed treatments, selected controls and outstanding assessment limitations.

Reference Document: 09 — Executive Summary.

⸻

4. Risk Scoring Methodology

The project uses a qualitative 5×5 risk assessment matrix.

The risk score is calculated using:

Risk Score = Likelihood × Impact

Both factors are assigned values between 1 and 5.

The maximum possible risk score is 25.

4.1 Likelihood Scale

1 — Rare

The event is highly unlikely to occur under normal circumstances.

2 — Unlikely

The event could occur but is not expected in most circumstances.

3 — Possible

The event could reasonably occur during normal business operations.

4 — Likely

The event is expected to occur under certain circumstances.

5 — Almost Certain

The event is highly probable or expected to occur frequently.

4.2 Impact Scale

1 — Insignificant

Minimal disruption with negligible financial or operational consequences.

2 — Minor

Limited operational disruption with relatively small financial consequences.

3 — Moderate

Noticeable business disruption, service interruption or moderate financial consequences.

4 — Major

Serious operational disruption, significant financial loss or exposure of sensitive information.

5 — Severe

Critical business disruption, major financial loss, substantial data compromise or serious reputational damage.

4.3 Risk Classification

Risk Score	Classification
1–4	Low
5–9	Moderate
10–16	High
17–25	Critical

4.4 Risk Evaluation Principles

The same scoring model is used for initial and residual risk assessments.

Initial risk scores represent the estimated exposure before considering the effectiveness of security controls.

Residual risk scores represent the remaining exposure after implemented controls have been evaluated.

A proposed control alone does not justify a reduction in risk score.

The likelihood and impact ratings must be reassessed using available evidence and documented assessment judgement.

⸻

5. Risk Treatment and Control Selection Principles

The assessment uses a risk-based approach to selecting security controls.

Control selection considers:

1. The nature of the identified cybersecurity risk.
2. The affected organisational asset.
3. The associated threat and vulnerability.
4. Potential business consequences.
5. The proposed risk treatment strategy.
6. Relevant ISO/IEC 27001:2022 Annex A controls.
7. Organisational requirements and available resources.

A security control may support the treatment of more than one risk.

Similarly, a single risk may require multiple security controls.

Control applicability does not automatically establish implementation or effectiveness.

⸻

6. Statement of Applicability Methodology

ISO/IEC 27001:2022 Annex A contains 93 reference controls across four categories.

Control Category	Number of Controls
Organisational (A.5)	37
People (A.6)	8
Physical (A.7)	14
Technological (A.8)	34
Total	93

The preliminary Statement of Applicability in this project documents 21 selected controls.

The selected controls are:

* Organisational Controls: 5.
* People Controls: 1.
* Technological Controls: 15.

Physical controls have not yet undergone a separate applicability assessment.

The remaining reference controls also require further review before a complete SoA can be established.

Control exclusions must be justified according to organisational requirements and the assessment context.

The preliminary selection of 21 controls must not be interpreted as a complete ISO/IEC 27001 control applicability assessment.

⸻

7. Residual Risk Evaluation Principles

Residual risk evaluation is performed only after proposed controls have been implemented and their effectiveness assessed.

The assessment requires:

* Implementation evidence.
* Control configuration or deployment records.
* Testing and verification results.
* Updated threat and vulnerability information.
* Revised likelihood and impact assessments.
* Risk owner review.
* Management approval where required.

The risk reduction calculation is:

Risk Reduction = Initial Risk Score − Residual Risk Score

A positive value indicates a reduction in the assessed risk score.

A negative value indicates an increase.

Where implementation evidence is unavailable, residual risk values must remain pending.

Risk acceptance must be documented and authorised by the appropriate management authority.

⸻

8. Information Security Principles

The assessment considers the CIA Triad, a fundamental information security model.

Confidentiality

Ensuring that information is accessible only to authorised individuals and systems.

Examples include access control, authentication and encryption.

Integrity

Ensuring that information remains accurate, complete and protected against unauthorised modification.

Examples include access restrictions, integrity monitoring and controlled change management.

Availability

Ensuring that information and systems remain accessible when required by authorised users.

Examples include backups, redundancy, capacity management and business continuity planning.

These principles help evaluate the potential consequences of cybersecurity risks.

⸻

9. Documentation and Evidence Management

All assessment documents should follow consistent documentation and evidence management practices.

The project follows these principles:

1. Maintain consistent asset and risk identifiers.
2. Use clear and specific risk descriptions.
3. Maintain traceability between threats, vulnerabilities and risks.
4. Document the justification for control applicability.
5. Distinguish proposed controls from implemented controls.
6. Maintain evidence supporting implementation claims.
7. Record risk treatment and acceptance decisions.
8. Document assessment assumptions and limitations.
9. Review documentation when significant changes occur.
10. Protect sensitive information and avoid publishing confidential evidence.

Evidence should be dated, traceable and reviewed by authorised personnel.

⸻

10. Framework and Reference Materials

The following standards and frameworks inform the assessment methodology.

10.1 Primary Framework

ISO/IEC 27001:2022 — Information Security Management Systems

Provides requirements for establishing, implementing, maintaining and continually improving an Information Security Management System (ISMS).

It is the primary framework reference for this project.

Official reference:

https://www.iso.org/standard/27001

10.2 Risk Management Guidance

ISO/IEC 27005:2022 — Guidance on Managing Information Security Risks

Provides guidance for identifying, assessing, treating, communicating and monitoring information security risks.

It supports the risk management approach used throughout the assessment.

Official reference:

https://www.iso.org/standard/80585.html

10.3 Information Security Control Guidance

ISO/IEC 27002:2022 — Information Security Controls

Provides guidance on information security controls and their implementation.

It supports the interpretation and selection of relevant security controls.

Official reference:

https://www.iso.org/standard/75652.html

10.4 Additional Cybersecurity Framework

NIST Cybersecurity Framework 2.0

Provides guidance for understanding, assessing, prioritising and communicating cybersecurity risks.

Its six core functions are:

* Govern.
* Identify.
* Protect.
* Detect.
* Respond.
* Recover.

The framework provides additional context for organisational cybersecurity risk management.

Official reference:

https://www.nist.gov/cyberframework

⸻

11. Assumptions and Limitations

The following assumptions and limitations apply to this project:

1. Nexora Solutions Pvt. Ltd. is a fictional organisation created for educational and portfolio purposes.
2. Organisational assets and business operations are illustrative.
3. Threats and vulnerabilities are hypothetical assessment scenarios.
4. Risk scores are preliminary estimates based on the defined methodology.
5. The assessment does not include actual technical vulnerability scanning.
6. Proposed security controls do not indicate actual implementation.
7. Control effectiveness requires supporting evidence and validation.
8. Residual risk ratings remain pending until appropriate assessment activities are completed.
9. Risk acceptance requires documented management authorisation.
10. The 21 selected controls do not represent a complete assessment of all 93 Annex A controls.
11. This project does not constitute an official ISO certification or independent compliance audit.

⸻

12. Document Traceability

The following documents form the complete assessment structure.

File	Document	Purpose
01	Organisation Profile	Defines organisational context
02	Asset Inventory	Identifies organisational assets
03	Threat & Vulnerability Assessment	Identifies threats and weaknesses
04	Risk Assessment	Evaluates and prioritises risks
05	Risk Treatment Plan	Defines proposed treatment actions
06	Statement of Applicability	Documents selected security controls
07	Control Implementation Tracker	Tracks proposed implementation
08	Residual Risk Assessment	Establishes future residual risk evaluation
09	Executive Summary	Consolidates assessment findings
10	Methodology and References	Documents methodology and reference sources

The documents should be reviewed together to maintain consistency across risk identifiers, treatment decisions and control references.

⸻

13. Conclusion

This document establishes the methodology and reference materials supporting the Cybersecurity GRC Risk Assessment Project.

It defines the assessment process, risk scoring approach, treatment principles, control selection methodology, evidence requirements and residual risk evaluation process.

By maintaining consistent documentation and traceability, the project demonstrates a structured approach to information security risk management.

The methodology provides a foundation for future assessment improvements, control implementation and continuous security review.

⸻

Project: Cybersecurity Risk Assessment & ISO 27001 Case Study
Organisation: Nexora Solutions Pvt. Ltd.
Document: 10 — Methodology and References
Status: Revised Assessment Methodology

Disclaimer: This is a simulated educational assessment. The methodology and references support a portfolio case study and do not constitute an independently verified organisational assessment or ISO certification.
