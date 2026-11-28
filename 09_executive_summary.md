# 09 — Executive Summary

| Field | Details |
|---|---|
| Organisation | Nexora Solutions Pvt. Ltd. (fictional) |
| Project | Cybersecurity Risk Assessment & ISO 27001 Case Study |
| Framework | ISO/IEC 27001:2022 |
| Document | 09 — Executive Summary |
| Version | 3.0 |
| Status | Final Portfolio Summary — Simulated Assessment |

---

## 1. Overview

This simulated Governance, Risk and Compliance (GRC) case study assesses the information security risks of a fictional 85-person IT services company, Nexora Solutions Pvt. Ltd.

It identifies assets, threats and vulnerabilities, rates nine risks, plans treatment, selects ISO/IEC 27001:2022 Annex A controls and sets out how residual risk will be reassessed.

---

## 2. Headline Findings

- **Nine risks** were assessed: **2 Critical, 6 High, 1 Moderate**.
- The two Critical risks are **phishing and account compromise (R01)** and **ransomware (R02)**, both scoring 20 out of 25.
- Weak authentication, missing MFA, patching gaps and untested backups drive most of the exposure.
- **23 of 93** Annex A controls are selected for treatment. None is implemented or verified, so no risk reduction is claimed.
- If every proposed control works as planned, the target profile is **8 Moderate and 1 High** (R01).

---

## 3. Risk Register

| ID | Risk | Score | Rating | Owner |
|---|---|---|---|---|
| R01 | Phishing and Account Compromise | 20 | Critical | IT Manager |
| R02 | Ransomware Infection | 20 | Critical | IT Manager |
| R05 | Exploitation of Unpatched Software | 16 | High | IT Manager |
| R03 | Insider Data Misuse | 15 | High | IT Manager |
| R04 | Cloud Data Exposure | 15 | High | IT Manager |
| R07 | Hardware Failure and Data Loss | 12 | High | IT Manager |
| R08 | Source Code Compromise | 12 | High | Development Manager |
| R09 | Financial Records Compromise or Tampering | 12 | High | Finance Manager |
| R06 | DDoS Service Disruption | 9 | Moderate | IT Manager |

Scores use Likelihood × Impact on a 5×5 scale. Bands: 1–4 Low, 5–9 Moderate, 10–16 High, 17–25 Critical.

---

## 4. Treatment Strategy

All nine risks are treated by **mitigation**; cyber insurance (transfer) is noted as an option for ransomware.

| Phase | Timeframe (indicative) | Focus |
|---|---|---|
| 1 | 0–3 months | MFA and credential rules, email and web filtering, malware protection, backups, cloud permissions, privileged access, incident plan |
| 2 | 3–6 months | Patching, access control and reviews, monitoring, network protection, training, continuity, encryption |
| 3 | 6–12 months | Capacity, redundancy, periodic testing and reassessment |

---

## 5. Control Position

| Measure | Value |
|---|---|
| Annex A controls reviewed in the SoA | 93 |
| Selected for risk treatment | 23 |
| Pending full applicability assessment | 55 |
| Physical controls (out of scope) | 14 |
| Not applicable | 1 |
| Implemented or verified | 0 |

---

## 6. Planned Outcome (Target, Not Achieved)

| Rating | Initial | Target residual |
|---|---|---|
| Critical | 2 | 0 |
| High | 6 | 1 (R01) |
| Moderate | 1 | 8 |
| Low | 0 | 0 |

R01 stays High because the impact of a compromised account remains severe. It would need further treatment or formal acceptance by senior management.

---

## 7. Decisions Required from Management

In a real engagement, management would be asked to:

1. Approve the treatment plan and fund Phase 1.
2. Confirm risk owners and the proposed Security Officer role.
3. Approve the risk acceptance criteria.
4. Decide whether to pursue cyber insurance for ransomware.
5. Agree to a full applicability assessment of the remaining Annex A controls.

---

## 8. Key Recommendations

1. Treat the Critical risks (phishing and ransomware) first.
2. Enforce MFA on email, cloud, repository and finance systems.
3. Establish tested, isolated backups.
4. Create a formal patch and vulnerability management process.
5. Review cloud and privileged access, and restrict source code and finance access by role.
6. Run security awareness training with phishing simulations.
7. Prepare and test an incident response plan.
8. Complete the assessment of the pending Annex A controls, including physical security.
9. Review risks and control effectiveness regularly.

---

## 9. Limitations

This is an educational portfolio project. It does not represent:

- A real security audit, penetration test or vulnerability assessment
- An independently verified compliance assessment
- An implemented Information Security Management System
- ISO/IEC 27001 certification
- Verified control effectiveness or residual risk reduction

All organisational details, risk scenarios and ratings are illustrative.

---

## 10. Conclusion

The project shows the core GRC workflow: context, assets, threats, risk rating, treatment, control selection, implementation tracking and residual risk planning, with each risk traceable to assets, threats, vulnerabilities and controls. It deliberately separates proposed improvements from verified implementation.

---

**Project:** Cybersecurity Risk Assessment & ISO 27001 Case Study
**Document:** 09 — Executive Summary
**Disclaimer:** This is a hypothetical educational project. All details are illustrative and not independently verified.
