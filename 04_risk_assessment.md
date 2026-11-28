# 04 — Cybersecurity Risk Assessment

| Field | Details |
|---|---|
| Organisation | Nexora Solutions Pvt. Ltd. (fictional) |
| Document | 04 — Cybersecurity Risk Assessment |
| Framework | ISO/IEC 27001:2022 (risk method informed by ISO/IEC 27005 and ISO 31000) |
| Version | 2.0 |
| Status | Final — Initial Risk Evaluation (Simulated) |

---

## 1. Objective

Identify, analyse and evaluate the cybersecurity risks that could affect Nexora's information assets and operations.

The asset inventory (`02`) and the threat and vulnerability assessment (`03`) are the foundation. Each risk is rated on two factors:

- **Likelihood** — how probable the event is
- **Impact** — how severe the consequences would be

---

## 2. Risk Assessment Methodology

A qualitative 5×5 matrix is used.

**Risk Score = Likelihood × Impact**

### 2.1 Likelihood scale

| Score | Rating | Description |
|---|---|---|
| 1 | Rare | Highly unlikely under normal circumstances |
| 2 | Unlikely | Could occur but is not expected |
| 3 | Possible | Could reasonably occur during normal operations |
| 4 | Likely | Expected to occur under certain circumstances |
| 5 | Almost certain | Expected to occur frequently |

### 2.2 Impact scale

| Score | Rating | Description |
|---|---|---|
| 1 | Insignificant | Negligible financial or operational consequences |
| 2 | Minor | Limited disruption, small financial consequences |
| 3 | Moderate | Noticeable disruption or moderate financial consequences |
| 4 | Major | Serious disruption, significant loss or exposure of sensitive information |
| 5 | Severe | Critical disruption, major financial loss, substantial data compromise or serious reputational damage |

---

## 3. Risk Rating and Treatment Priority

| Score | Rating | Treatment priority |
|---|---|---|
| 1–4 | Low | Routine monitoring |
| 5–9 | Moderate | Planned improvement |
| 10–16 | High | Priority treatment |
| 17–25 | Critical | Immediate attention |

These bands are this project's own criteria. They are not thresholds prescribed by ISO/IEC 27001.

---

## 4. Initial Risk Assessment

**Initial risk** is the risk *before proposed treatment*. No existing control is assumed to be verified (see `10_methodology_and_references.md`). All ratings are estimates for this simulation.

### R01 — Phishing and Account Compromise

| Item | Details |
|---|---|
| Affected asset | A05 Corporate Email |
| Threats | T01 Phishing, T06 Credential theft |
| Vulnerabilities | V01 Weak authentication, V02 No MFA, V03 Poor email security |
| Risk owner | IT Manager |
| Description | An employee interacts with a fraudulent email; attackers steal credentials and, without MFA, gain access to email and connected systems. |
| Likelihood / Impact | 4 Likely / 5 Severe |
| **Score / Rating** | **20 — Critical** |

### R02 — Ransomware Infection

| Item | Details |
|---|---|
| Affected asset | A01 Client Database |
| Threat | T02 Ransomware |
| Vulnerabilities | V04 Unpatched systems, V06 Inadequate backup practices |
| Risk owner | IT Manager |
| Description | Ransomware exploits system weaknesses and encrypts critical business information. Weak backups make recovery difficult. |
| Likelihood / Impact | 4 Likely / 5 Severe |
| **Score / Rating** | **20 — Critical** |

### R03 — Insider Data Misuse

| Item | Details |
|---|---|
| Affected assets | A01 Client Database, A02 Employee Records |
| Threats | T03 Insider threat, T04 Data breach |
| Vulnerability | V05 Excessive user permissions |
| Risk owner | IT Manager (with HR Manager) |
| Description | An employee with excessive privileges accesses, discloses or modifies client or employee information beyond their job responsibilities. |
| Likelihood / Impact | 3 Possible / 5 Severe |
| **Score / Rating** | **15 — High** |

### R04 — Cloud Data Exposure

| Item | Details |
|---|---|
| Affected asset | A04 Cloud Storage |
| Threats | T08 Cloud misconfiguration, T04 Data breach |
| Vulnerabilities | V08 Cloud security gaps, V02 No MFA |
| Risk owner | IT Manager |
| Description | Incorrect cloud permissions or weakly protected cloud accounts expose confidential information to unauthorised people. |
| Likelihood / Impact | 3 Possible / 5 Severe |
| **Score / Rating** | **15 — High** |

### R05 — Exploitation of Unpatched Software

| Item | Details |
|---|---|
| Affected asset | A07 Employee Laptops |
| Threat | T09 Exploitation of known software vulnerabilities |
| Vulnerability | V04 Unpatched systems |
| Risk owner | IT Manager |
| Description | Attackers exploit known flaws in outdated operating systems or applications, allowing system access, malware installation or attacks on internal systems. |
| Likelihood / Impact | 4 Likely / 4 Major |
| **Score / Rating** | **16 — High** |

### R06 — DDoS Service Disruption

| Item | Details |
|---|---|
| Affected assets | A09 Company Website (supported by A08 Network Infrastructure) |
| Threat | T05 DDoS |
| Vulnerability | V07 Weak network security |
| Risk owner | IT Manager |
| Description | Excessive malicious traffic makes the public website unavailable to customers and visitors. |
| Likelihood / Impact | 3 Possible / 3 Moderate |
| **Score / Rating** | **9 — Moderate** |

### R07 — Hardware Failure and Data Loss

| Item | Details |
|---|---|
| Affected asset | A10 Backup Systems |
| Threat | T07 Hardware failure |
| Vulnerability | V06 Inadequate backup practices |
| Risk owner | IT Manager |
| Description | Failure of backup hardware, combined with weak backup and recovery practice, causes permanent data loss or prolonged disruption. |
| Likelihood / Impact | 3 Possible / 4 Major |
| **Score / Rating** | **12 — High** |

### R08 — Source Code Compromise

| Item | Details |
|---|---|
| Affected asset | A03 Source Code Repository |
| Threats | T03 Insider threat, T06 Credential theft |
| Vulnerabilities | V01 Weak authentication, V02 No MFA, V05 Excessive user permissions |
| Risk owner | Development Manager |
| Description | Stolen developer credentials or excessive repository permissions allow source code to be copied, altered or deleted, or malicious code to be inserted. |
| Likelihood / Impact | 3 Possible / 4 Major |
| **Score / Rating** | **12 — High** |

### R09 — Financial Records Compromise or Tampering

| Item | Details |
|---|---|
| Affected asset | A06 Financial Records |
| Threats | T03 Insider threat, T06 Credential theft |
| Vulnerabilities | V01 Weak authentication, V02 No MFA, V05 Excessive user permissions |
| Risk owner | Finance Manager |
| Description | A compromised or over-privileged finance account leads to disclosure or alteration of invoices and payment records, causing fraud or financial loss. |
| Likelihood / Impact | 3 Possible / 4 Major |
| **Score / Rating** | **12 — High** |

---

## 5. Risk Register Summary

| ID | Risk | Asset | Likelihood | Impact | Score | Rating | Owner |
|---|---|---|---|---|---|---|---|
| R01 | Phishing and Account Compromise | A05 | 4 | 5 | 20 | Critical | IT Manager |
| R02 | Ransomware Infection | A01 | 4 | 5 | 20 | Critical | IT Manager |
| R03 | Insider Data Misuse | A01, A02 | 3 | 5 | 15 | High | IT Manager |
| R04 | Cloud Data Exposure | A04 | 3 | 5 | 15 | High | IT Manager |
| R05 | Exploitation of Unpatched Software | A07 | 4 | 4 | 16 | High | IT Manager |
| R06 | DDoS Service Disruption | A09 | 3 | 3 | 9 | Moderate | IT Manager |
| R07 | Hardware Failure and Data Loss | A10 | 3 | 4 | 12 | High | IT Manager |
| R08 | Source Code Compromise | A03 | 3 | 4 | 12 | High | Development Manager |
| R09 | Financial Records Compromise or Tampering | A06 | 3 | 4 | 12 | High | Finance Manager |

**Distribution:** Critical 2 · High 6 · Moderate 1 · Low 0 · **Total 9**

---

## 6. Risk Heat Map (Initial Risk)

| Likelihood ↓ / Impact → | 1 Insignificant | 2 Minor | 3 Moderate | 4 Major | 5 Severe |
|---|---|---|---|---|---|
| **5 Almost certain** | 🟨 5 | 🟧 10 | 🟧 15 | 🟥 20 | 🟥 25 |
| **4 Likely** | 🟩 4 | 🟨 8 | 🟧 12 | 🟧 16<br>**R05** | 🟥 20<br>**R01, R02** |
| **3 Possible** | 🟩 3 | 🟨 6 | 🟨 9<br>**R06** | 🟧 12<br>**R07, R08, R09** | 🟧 15<br>**R03, R04** |
| **2 Unlikely** | 🟩 2 | 🟩 4 | 🟨 6 | 🟨 8 | 🟧 10 |
| **1 Rare** | 🟩 1 | 🟩 2 | 🟩 3 | 🟩 4 | 🟨 5 |

🟥 Critical · 🟧 High · 🟨 Moderate · 🟩 Low

---

## 7. Risk Prioritisation

**Critical — immediate attention:** R01 Phishing and Account Compromise, R02 Ransomware Infection.

**High — priority treatment (highest score first):** R05, R03, R04, R07, R08, R09.

**Moderate — planned improvement:** R06 DDoS Service Disruption.

---

## 8. Assumptions and Limitations

- Likelihood and impact ratings are hypothetical estimates for this educational case study.
- They are not measurements of a real organisation's security posture.
- A real assessment would need incident history, technical vulnerability assessments, interviews with asset owners, reviews of existing controls and business impact analysis.
- Scores may change as evidence becomes available.

---

## 9. Assessment Conclusion

Nine cybersecurity risks were evaluated: two Critical, six High and one Moderate. Each is linked to an asset, one or more threats and vulnerabilities, and a risk owner.

Initial ratings stay unchanged until proposed controls are implemented and their effectiveness is verified. Treatment is planned in `05_risk_treatment_plan.md`.

---

**Project:** Cybersecurity Risk Assessment & ISO 27001 Case Study
**Document:** 04 — Cybersecurity Risk Assessment
**Disclaimer:** This is a simulated educational assessment. All risk scenarios and ratings are hypothetical and not independently verified.
