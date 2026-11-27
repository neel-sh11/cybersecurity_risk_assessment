04 — Cybersecurity Risk Assessment

Organisation: Nexora Solutions Pvt. Ltd.
Assessment Type: Simulated Cybersecurity Risk Assessment
Framework Reference: ISO/IEC 27001:2022
Document Status: Initial Risk Evaluation

⸻

1. Objective

The objective of this assessment is to evaluate the cybersecurity risks identified during the asset identification and threat assessment stages.

Each risk is evaluated using two factors:

* Likelihood: Probability of the risk event occurring.
* Impact: Severity of the consequences if the event occurs.

The resulting risk scores help prioritise security improvements.

⸻

2. Risk Calculation Methodology

The assessment uses the following formula:

Risk Score = Likelihood × Impact

Both factors are assigned scores from 1 to 5.

2.1 Likelihood Scale

1 — Rare: Very unlikely to occur.

2 — Unlikely: Could occur, but is not expected.

3 — Possible: Could reasonably occur.

4 — Likely: Expected to occur in certain circumstances.

5 — Almost Certain: Highly probable or expected to occur frequently.

2.2 Impact Scale

1 — Insignificant: Minimal disruption or loss.

2 — Minor: Limited operational impact.

3 — Moderate: Noticeable disruption or financial consequences.

4 — Major: Serious business disruption or sensitive information exposure.

5 — Severe: Critical operational disruption, major financial loss or significant reputational damage.

⸻

3. Risk Rating Categories

Risk     Score	     Rating_Priority
1–4	     Low	       Routine Monitoring
5–9	     Moderate	   Planned Improvement
10–16	   High	       Priority Treatment
17–25	   Critical	   Immediate Attention

⸻

4. Inherent Risk Assessment

Inherent risk represents the level of risk before considering the effect of security controls.

The following scores are preliminary estimates based on the fictional organisation’s assumed operating environment.

R01 — Phishing and Account Compromise

* Affected Asset: A05 — Corporate Email
* Threat: T01 — Phishing
* Vulnerability: V03 — Poor Email Security
* Risk Description: An employee may interact with a fraudulent email, allowing attackers to steal credentials and access company accounts.
* Likelihood: 4 — Likely
* Impact: 5 — Severe
* Risk Score: 20
* Risk Rating: Critical

R02 — Ransomware Infection

* Affected Asset: A01 — Client Database
* Threat: T02 — Ransomware
* Vulnerability: V04 — Unpatched Systems; V06 — Inadequate Backup Practices
* Risk Description: Ransomware may encrypt critical business information, disrupting operations and preventing access to client records.
* Likelihood: 4 — Likely
* Impact: 5 — Severe
* Risk Score: 20
* Risk Rating: Critical

R03 — Insider Data Misuse

* Affected Asset: A01 — Client Database
* Threat: T03 — Insider Threat
* Vulnerability: V05 — Excessive User Permissions
* Risk Description: An employee with excessive privileges may access, disclose or modify information beyond their job responsibilities.
* Likelihood: 3 — Possible
* Impact: 5 — Severe
* Risk Score: 15
* Risk Rating: High

R04 — Cloud Data Exposure

* Affected Asset: A04 — Cloud Storage
* Threat: T08 — Cloud Misconfiguration
* Vulnerability: V08 — Cloud Security Gaps
* Risk Description: Incorrect cloud storage permissions may expose confidential organisational information to unauthorised parties.
* Likelihood: 3 — Possible
* Impact: 5 — Severe
* Risk Score: 15
* Risk Rating: High

R05 — Exploitation of Unpatched Software

* Affected Asset: A07 — Employee Laptops
* Threat: T02 — Ransomware
* Vulnerability: V04 — Unpatched Systems
* Risk Description: Attackers may exploit known software vulnerabilities to compromise employee devices and gain access to organisational resources.
* Likelihood: 4 — Likely
* Impact: 4 — Major
* Risk Score: 16
* Risk Rating: High

R06 — DDoS Service Disruption

* Affected Asset: A09 — Company Website
* Threat: T05 — Distributed Denial of Service
* Vulnerability: V07 — Weak Network Security
* Risk Description: Excessive malicious network traffic may make the company’s public website unavailable to customers and visitors.
* Likelihood: 3 — Possible
* Impact: 3 — Moderate
* Risk Score: 9
* Risk Rating: Moderate

R07 — Hardware Failure and Data Loss

* Affected Asset: A10 — Backup Systems
* Threat: T07 — Hardware Failure
* Vulnerability: V06 — Inadequate Backup Practices
* Risk Description: Hardware failure combined with inadequate backup and recovery practices may result in permanent data loss or prolonged service disruption.
* Likelihood: 3 — Possible
* Impact: 4 — Major
* Risk Score: 12
* Risk Rating: High

⸻

5. Risk Register Summary

RiskID	  Risk_Description	    Likelihood	Impact	Score	 Rating
R01	      Phishing	            4	          5	      20	   Critical
R02	      Ransomware	          4	          5	      20	   Critical
R03	      Insider Data Misuse	  3	          5	      15	   High
R04	      Cloud Data Exposure	  3	          5	      15	   High
R05	      Unpatched Software	  4	          4	      16	   High
R06	      DDoS Disruption	      3	          3	      9	     Moderate
R07	      Hardware Failure	    3	          4	      12	   High

⸻

6. Risk Prioritisation

Based on the preliminary assessment:

Critical Risks

* R01 — Phishing and Account Compromise
* R02 — Ransomware Infection

These risks require immediate attention because of their potential to compromise critical information and disrupt business operations.

High Risks

* R03 — Insider Data Misuse
* R04 — Cloud Data Exposure
* R05 — Exploitation of Unpatched Software
* R07 — Hardware Failure and Data Loss

These risks require priority treatment and appropriate security controls.

Moderate Risks

* R06 — DDoS Service Disruption

This risk requires planned improvements and continued monitoring.

⸻

7. Assessment Limitations

The likelihood and impact ratings are hypothetical estimates for an educational case study.

A real assessment would require:

* Historical security incident records
* Technical vulnerability assessments
* Interviews with asset owners
* Existing security control reviews
* Business impact analysis
* Validation of threat exposure

The scores should therefore not be interpreted as verified measurements of an actual organisation’s security posture.

⸻

8. Assessment Conclusion

Seven cybersecurity risks have been evaluated using a 5×5 risk assessment methodology.

The assessment identified two Critical risks, four High risks and one Moderate risk.

These findings provide a basis for developing a risk treatment plan, selecting appropriate security controls and determining residual risk.

⸻

Project: Cybersecurity Risk Assessment & ISO 27001 Case Study
Organisation: Nexora Solutions Pvt. Ltd.
Document: 04 — Cybersecurity Risk Assessment
Status: Initial Risk Evaluation Completed
