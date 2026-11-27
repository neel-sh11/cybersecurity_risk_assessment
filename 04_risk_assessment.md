04 — Cybersecurity Risk Assessment

Organisation: Nexora Solutions Pvt. Ltd.
Assessment Type: Simulated Cybersecurity Risk Assessment
Framework Reference: ISO/IEC 27001:2022
Document Status: Revised Initial Risk Evaluation

⸻

1. Objective

The objective of this assessment is to identify, analyse and evaluate cybersecurity risks that could affect the organisation’s information assets, business operations and overall security posture.

The assessment uses the asset inventory and threat-vulnerability assessment as its foundation.

Each identified risk is evaluated using two factors:

* Likelihood: The estimated probability of a risk event occurring.
* Impact: The potential severity of consequences if the risk event occurs.

The resulting risk scores help determine treatment priorities and support informed security decisions.

⸻

2. Risk Assessment Methodology

The organisation uses a qualitative 5×5 risk assessment matrix.

The risk score is calculated using the following formula:

Risk Score = Likelihood × Impact

Both likelihood and impact are assigned values between 1 and 5.

2.1 Likelihood Scale

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

2.2 Impact Scale

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

⸻

3. Risk Rating Categories

The calculated risk score determines the corresponding risk classification and treatment priority.

Risk Score	Risk Rating	Treatment Priority
1–4	Low	Routine Monitoring
5–9	Moderate	Planned Improvement
10–16	High	Priority Treatment
17–25	Critical	Immediate Attention

The classification provides a consistent approach for comparing and prioritising identified risks.

⸻

4. Inherent Risk Assessment

Inherent risk represents the level of risk before considering the effectiveness of existing security controls.

The following assessments are preliminary estimates based on the assumed operating environment of Nexora Solutions.

R01 — Phishing and Account Compromise

Affected Asset: A05 — Corporate Email

Threat: T01 — Phishing

Vulnerability: V03 — Poor Email Security

Risk Description:

An employee may interact with a fraudulent email containing malicious links or attachments, allowing attackers to steal credentials and gain unauthorised access to organisational accounts.

Risk Evaluation:

* Likelihood: 4 — Likely
* Impact: 5 — Severe
* Risk Score: 20
* Risk Rating: Critical

Treatment Priority: Immediate Attention

R02 — Ransomware Infection

Affected Asset: A01 — Client Database

Threat: T02 — Ransomware

Vulnerabilities:

* V04 — Unpatched Systems
* V06 — Inadequate Backup Practices

Risk Description:

Ransomware may exploit weaknesses in organisational systems and encrypt critical business information, disrupting operations and preventing access to important client records.

Inadequate backup practices may further increase the impact by making data recovery difficult.

Risk Evaluation:

* Likelihood: 4 — Likely
* Impact: 5 — Severe
* Risk Score: 20
* Risk Rating: Critical

Treatment Priority: Immediate Attention

R03 — Insider Data Misuse

Affected Asset: A01 — Client Database

Threat: T03 — Insider Threat

Vulnerability: V05 — Excessive User Permissions

Risk Description:

An employee with excessive access privileges may intentionally or accidentally access, disclose or modify confidential client information beyond their authorised job responsibilities.

Risk Evaluation:

* Likelihood: 3 — Possible
* Impact: 5 — Severe
* Risk Score: 15
* Risk Rating: High

Treatment Priority: Priority Treatment

R04 — Cloud Data Exposure

Affected Asset: A04 — Cloud Storage

Threat: T08 — Cloud Misconfiguration

Vulnerability: V08 — Cloud Security Gaps

Risk Description:

Incorrect cloud storage permissions or insecure configurations may expose confidential organisational information to unauthorised individuals.

Risk Evaluation:

* Likelihood: 3 — Possible
* Impact: 5 — Severe
* Risk Score: 15
* Risk Rating: High

Treatment Priority: Priority Treatment

R05 — Exploitation of Unpatched Software

Affected Asset: A07 — Employee Laptops

Threat: T09 — Exploitation of Known Software Vulnerabilities

Vulnerability: V04 — Unpatched Systems

Risk Description:

Attackers may exploit known vulnerabilities in outdated operating systems or applications running on employee devices.

Successful exploitation could allow unauthorised system access, malware installation, compromise of organisational resources or further attacks against internal systems.

Risk Evaluation:

* Likelihood: 4 — Likely
* Impact: 4 — Major
* Risk Score: 16
* Risk Rating: High

Treatment Priority: Priority Treatment

R06 — DDoS Service Disruption

Affected Asset: A09 — Company Website

Threat: T05 — Distributed Denial of Service (DDoS)

Vulnerability: V07 — Weak Network Security

Risk Description:

Attackers may overwhelm the company’s public website with excessive malicious network traffic, making online services unavailable to customers and visitors.

Risk Evaluation:

* Likelihood: 3 — Possible
* Impact: 3 — Moderate
* Risk Score: 9
* Risk Rating: Moderate

Treatment Priority: Planned Improvement

R07 — Hardware Failure and Data Loss

Affected Asset: A10 — Backup Systems

Threat: T07 — Hardware Failure

Vulnerability: V06 — Inadequate Backup Practices

Risk Description:

Hardware failure affecting backup infrastructure, combined with inadequate backup and recovery practices, may result in permanent data loss or prolonged service disruption.

Risk Evaluation:

* Likelihood: 3 — Possible
* Impact: 4 — Major
* Risk Score: 12
* Risk Rating: High

Treatment Priority: Priority Treatment

⸻

5. Risk Register Summary

The following register provides a consolidated overview of the seven identified cybersecurity risks.

Risk ID	Risk Description	Likelihood	Impact	Score	Rating
R01	Phishing and Account Compromise	4	5	20	Critical
R02	Ransomware Infection	4	5	20	Critical
R03	Insider Data Misuse	3	5	15	High
R04	Cloud Data Exposure	3	5	15	High
R05	Unpatched Software Exploitation	4	4	16	High
R06	DDoS Service Disruption	3	3	9	Moderate
R07	Hardware Failure and Data Loss	3	4	12	High

Total Identified Risks: 7

Risk Distribution:

* Critical: 2
* High: 4
* Moderate: 1
* Low: 0

⸻

6. Risk Prioritisation

Based on the calculated risk scores, the identified risks are grouped into three treatment priority categories.

6.1 Critical Risks

R01 — Phishing and Account Compromise

R02 — Ransomware Infection

These risks require immediate attention because of their potential to compromise sensitive organisational information, disrupt business operations and cause significant financial or reputational damage.

6.2 High Risks

R03 — Insider Data Misuse

R04 — Cloud Data Exposure

R05 — Exploitation of Unpatched Software

R07 — Hardware Failure and Data Loss

These risks require priority treatment through appropriate access management, cloud security, vulnerability management and business continuity measures.

6.3 Moderate Risks

R06 — DDoS Service Disruption

This risk requires planned security improvements, appropriate network protection and continuous monitoring to maintain service availability.

⸻

7. Assessment Assumptions and Limitations

The likelihood and impact ratings are hypothetical estimates developed for this educational case study.

The assessment does not represent verified measurements of an actual organisation’s cybersecurity posture.

A real-world assessment would require:

* Historical cybersecurity incident records.
* Technical vulnerability assessments.
* Interviews with asset owners and relevant departments.
* Existing security control reviews.
* Business impact analysis.
* Validation of identified threats and vulnerabilities.
* Review of organisational infrastructure and security configurations.

The risk scores may change when additional evidence becomes available or when the organisation’s operating environment changes.

⸻

8. Assessment Conclusion

Seven cybersecurity risks have been evaluated using a qualitative 5×5 risk assessment methodology.

The assessment identified:

* Two Critical risks requiring immediate attention.
* Four High risks requiring priority treatment.
* One Moderate risk requiring planned improvement.

Each risk has been associated with an organisational asset, an identified threat and one or more relevant vulnerabilities.

The assessment establishes the foundation for the subsequent risk treatment plan, security control selection and residual risk evaluation.

The initial risk ratings will remain unchanged until proposed security controls have been implemented and their effectiveness has been assessed.

⸻

Project: Cybersecurity Risk Assessment & ISO 27001 Case Study
Organisation: Nexora Solutions Pvt. Ltd.
Document: 04 — Cybersecurity Risk Assessment
Status: Revised Initial Risk Evaluation

Disclaimer: This is a simulated educational assessment. All risk scenarios, likelihood ratings and impact ratings are hypothetical and have not been independently verified.
