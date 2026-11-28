# 08 — Residual Risk Assessment

| Field | Details |
|---|---|
| Organisation | Nexora Solutions Pvt. Ltd. (fictional) |
| Document | 08 — Residual Risk Assessment |
| Framework | ISO/IEC 27001:2022 |
| Version | 3.0 |
| Status | Targets set — Actual residual risk pending implementation and validation |

---

## 1. Objective

Set out how risk will be reassessed after the proposed controls are implemented, and show the **target** risk levels the plan is designed to reach.

Three different values are used in this project:

| Term | Meaning | Status |
|---|---|---|
| **Initial risk** | Risk before proposed treatment | Assessed in `04` |
| **Target residual risk** | Planned level *if* controls are implemented and work as intended | Set here — a planning target, **not a result** |
| **Actual residual risk** | Risk measured after implementation and effectiveness testing | **Pending** |

---

## 2. Methodology

Residual risk uses the same 5×5 method as the initial assessment.

**Risk Score = Likelihood × Impact** (each scored 1–5)

A proposed control must not be treated as an implemented control. Actual residual ratings need:

1. Evidence that controls are implemented
2. Evidence that they operate effectively
3. Updated threat and vulnerability information
4. Reassessed likelihood and impact
5. Review by the risk owner and management

---

## 3. Risk Acceptance Criteria

| Residual rating | Required action | Approver |
|---|---|---|
| Low (1–4) | Accept with routine monitoring | Risk owner |
| Moderate (5–9) | Accept with documented periodic review | Risk owner |
| High (10–16) | Further treatment, or formal acceptance with documented justification | Senior Management |
| Critical (17–25) | Not acceptable; must be treated further | Senior Management |

Risk acceptance does not remove the need for ongoing monitoring.

---

## 4. Initial and Target Residual Risk

| ID | Risk | Initial L × I | Initial score | Target L × I | Target score | Target rating | Planned reduction |
|---|---|---|---|---|---|---|---|
| R01 | Phishing and Account Compromise | 4 × 5 | 20 Critical | 2 × 5 | 10 | High | 10 |
| R02 | Ransomware Infection | 4 × 5 | 20 Critical | 2 × 4 | 8 | Moderate | 12 |
| R03 | Insider Data Misuse | 3 × 5 | 15 High | 2 × 4 | 8 | Moderate | 7 |
| R04 | Cloud Data Exposure | 3 × 5 | 15 High | 2 × 4 | 8 | Moderate | 7 |
| R05 | Exploitation of Unpatched Software | 4 × 4 | 16 High | 2 × 4 | 8 | Moderate | 8 |
| R06 | DDoS Service Disruption | 3 × 3 | 9 Moderate | 2 × 3 | 6 | Moderate | 3 |
| R07 | Hardware Failure and Data Loss | 3 × 4 | 12 High | 2 × 3 | 6 | Moderate | 6 |
| R08 | Source Code Compromise | 3 × 4 | 12 High | 2 × 4 | 8 | Moderate | 4 |
| R09 | Financial Records Compromise or Tampering | 3 × 4 | 12 High | 2 × 4 | 8 | Moderate | 4 |

**Planned reduction = Initial score − Target score.** Targets assume every proposed control is implemented and effective.

### Target heat map

| Likelihood ↓ / Impact → | 1 | 2 | 3 | 4 | 5 |
|---|---|---|---|---|---|
| **5** | 🟨 5 | 🟧 10 | 🟧 15 | 🟥 20 | 🟥 25 |
| **4** | 🟩 4 | 🟨 8 | 🟧 12 | 🟧 16 | 🟥 20 |
| **3** | 🟩 3 | 🟨 6 | 🟨 9 | 🟧 12 | 🟧 15 |
| **2** | 🟩 2 | 🟩 4 | 🟨 6<br>**R06, R07** | 🟨 8<br>**R02, R03, R04, R05, R08, R09** | 🟧 10<br>**R01** |
| **1** | 🟩 1 | 🟩 2 | 🟩 3 | 🟩 4 | 🟨 5 |

**Outcome if targets are met:** eight risks Moderate and one (R01) High. R01 stays High because the impact of a successful account compromise remains severe even when likelihood falls. It would need formal acceptance by senior management or further treatment.

---

## 5. Rationale and Evidence Required per Risk

| ID | Why the target is plausible | Controls | Evidence needed before reassessment |
|---|---|---|---|
| R01 | MFA, email and web filtering and training lower the chance a phish succeeds; impact stays severe | A.5.17, A.6.3, A.8.5, A.8.7, A.8.16, A.8.23 | MFA coverage report; phishing simulation results; email filtering logs |
| R02 | Patching and malware protection lower likelihood; tested isolated backups lower impact | A.5.30, A.6.3, A.8.7, A.8.8, A.8.13, A.8.16, A.8.19 | Restoration test report; patch compliance report; endpoint protection coverage |
| R03 | Least privilege and monitoring lower likelihood and limit the data an insider can reach | A.5.15, A.5.18, A.6.3, A.8.2, A.8.3, A.8.16 | Access review reports; privileged account review; monitoring alerts |
| R04 | Permission reviews, MFA and encryption lower likelihood and limit exposure impact | A.5.15, A.5.23, A.8.5, A.8.9, A.8.16, A.8.24 | Cloud configuration review; public access check; encryption configuration |
| R05 | Formal patching removes known weaknesses | A.8.8, A.8.9, A.8.19 | Vulnerability trend report; patch timelines; software inventory |
| R06 | DDoS protection and capacity planning lower likelihood of an outage | A.8.6, A.8.16, A.8.20, A.8.21 | Provider DDoS service configuration; capacity reports; response test |
| R07 | Tested backups and redundancy limit the effect of hardware failure | A.5.30, A.8.13, A.8.14 | Restoration test; failover test report |
| R08 | Role-based access, MFA and branch protection lower likelihood of compromise | A.5.15, A.5.18, A.8.2, A.8.4, A.8.5, A.8.13, A.8.16 | Repository access review; branch protection settings; audit logs |
| R09 | Restricted access, MFA and monitoring lower likelihood of misuse | A.5.15, A.5.18, A.8.3, A.8.5, A.8.13, A.8.16 | Finance access review; MFA coverage; log review |

A.5.24 (incident management) supports all nine risks.

---

## 6. Actual Residual Risk — Current Status

| ID | Initial score | Target score | Actual residual L | Actual residual I | Actual score | Control implementation | Validation |
|---|---|---|---|---|---|---|---|
| R01 | 20 | 10 | Pending | Pending | Pending | Proposed — Not Verified | Pending |
| R02 | 20 | 8 | Pending | Pending | Pending | Proposed — Not Verified | Pending |
| R03 | 15 | 8 | Pending | Pending | Pending | Proposed — Not Verified | Pending |
| R04 | 15 | 8 | Pending | Pending | Pending | Proposed — Not Verified | Pending |
| R05 | 16 | 8 | Pending | Pending | Pending | Proposed — Not Verified | Pending |
| R06 | 9 | 6 | Pending | Pending | Pending | Proposed — Not Verified | Pending |
| R07 | 12 | 6 | Pending | Pending | Pending | Proposed — Not Verified | Pending |
| R08 | 12 | 8 | Pending | Pending | Pending | Proposed — Not Verified | Pending |
| R09 | 12 | 8 | Pending | Pending | Pending | Proposed — Not Verified | Pending |

Actual residual scores cannot be calculated because no control has been implemented or verified. **No risk reduction is claimed.**

---

## 7. Monitoring and Review

Nexora should:

1. Reassess risks periodically and after incidents or major changes.
2. Review control effectiveness.
3. Monitor emerging threats and vulnerabilities.
4. Update the risk register when circumstances change.
5. Record changes in residual ratings.
6. Obtain management approval for accepted residual risks.
7. Keep evidence for every effectiveness assessment.

---

## 8. Limitations

- Target scores are planning judgements for a simulated organisation, not measurements.
- Controls have not been implemented or independently verified.
- Actual residual ratings, risk reduction figures and formal risk acceptance remain outstanding.

---

## 9. Conclusion

All nine risks have an initial score, a planned target and a list of evidence needed to confirm the result. If every control works as planned, the profile improves from two Critical and six High risks to eight Moderate and one High. That improvement is a plan, not an achievement, and no reduction is claimed until evidence supports it.

---

**Project:** Cybersecurity Risk Assessment & ISO 27001 Case Study
**Document:** 08 — Residual Risk Assessment
**Disclaimer:** This is a simulated educational assessment. Targets are hypothetical and require implementation evidence and effectiveness evaluation.
