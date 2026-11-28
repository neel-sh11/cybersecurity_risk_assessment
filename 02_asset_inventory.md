# 02 — Asset Identification and Classification

| Field | Details |
|---|---|
| Organisation | Nexora Solutions Pvt. Ltd. (fictional) |
| Document | 02 — Asset Identification and Classification |
| Framework | ISO/IEC 27001:2022 |
| Version | 2.0 |
| Status | Final — Simulated Assessment |

---

## 1. Objective

Identify the information, systems and resources that support Nexora's business operations. Each asset is given:

- A unique asset ID
- A category and an owner
- A classification level
- A CIA (Confidentiality, Integrity, Availability) rating

---

## 2. Classification Levels

| Level | Description | Example |
|---|---|---|
| Public | Approved for public distribution | Company website content |
| Internal | Intended for employees and authorised personnel | Internal business communications |
| Confidential | Sensitive business or personal information requiring restricted access | Employee records, source code |
| Restricted | Highest sensitivity; strict access controls required | Client databases, financial records |

---

## 3. Asset Inventory

| ID | Asset | Category | Owner | Classification | Description |
|---|---|---|---|---|---|
| A01 | Client Database | Data | IT Manager | Restricted | Client information, contact details and business records |
| A02 | Employee Records | Data | HR Manager | Confidential | Employee personal information and employment records |
| A03 | Source Code Repository | Application / Data | Development Manager | Confidential | Application source code and development projects |
| A04 | Cloud Storage | Infrastructure | IT Manager | Restricted | Organisational documents, business data and project files |
| A05 | Corporate Email | Application | IT Manager | Internal | Internal communication and external business correspondence |
| A06 | Financial Records | Data | Finance Manager | Restricted | Invoices, payment records and financial information |
| A07 | Employee Laptops | Hardware | IT Manager | Internal | Devices used for daily business operations |
| A08 | Network Infrastructure | Infrastructure | IT Manager | Internal | Routers, switches and connectivity equipment |
| A09 | Company Website | Application | Marketing Manager | Public | Public-facing website with company and service information |
| A10 | Backup Systems | Infrastructure / Data | IT Manager | Restricted | Backup copies of critical organisational information |

---

## 4. CIA Security Assessment

### 4.1 Rating key

| Rating | Meaning |
|---|---|
| High | Compromise would cause severe financial, legal, operational or reputational harm |
| Medium | Compromise would cause noticeable but manageable harm |
| Low | Compromise would cause minimal harm |

- **Confidentiality** — protection against unauthorised disclosure
- **Integrity** — protection against unauthorised modification or destruction
- **Availability** — information and systems are accessible when required

### 4.2 Initial CIA ratings

| ID | Asset | Confidentiality | Integrity | Availability |
|---|---|---|---|---|
| A01 | Client Database | High | High | High |
| A02 | Employee Records | High | High | Medium |
| A03 | Source Code Repository | High | High | High |
| A04 | Cloud Storage | High | High | High |
| A05 | Corporate Email | Medium | High | High |
| A06 | Financial Records | High | High | High |
| A07 | Employee Laptops | Medium | Medium | High |
| A08 | Network Infrastructure | Medium | High | High |
| A09 | Company Website | Low | Medium | High |
| A10 | Backup Systems | High | High | High |

CIA ratings are preliminary qualitative assumptions for this simulated assessment.

---

## 5. High-Priority Assets

**Rule:** an asset is high-priority when all three CIA ratings are High.

| ID | Asset | Why it matters |
|---|---|---|
| A01 | Client Database | Unauthorised disclosure or loss would cause financial and reputational damage |
| A03 | Source Code Repository | Core intellectual property; tampering could affect all delivered software |
| A04 | Cloud Storage | Misconfiguration could expose several data categories at once |
| A06 | Financial Records | Modification or disclosure could cause financial loss and fraud |
| A10 | Backup Systems | If compromised, recovery after an incident may not be possible |

---

## 6. Asset-to-Risk Linkage

Every asset is covered by at least one risk in `04_risk_assessment.md`.

| ID | Asset | Related risks |
|---|---|---|
| A01 | Client Database | R02, R03 |
| A02 | Employee Records | R03 |
| A03 | Source Code Repository | R08 |
| A04 | Cloud Storage | R04 |
| A05 | Corporate Email | R01 |
| A06 | Financial Records | R09 |
| A07 | Employee Laptops | R05 |
| A08 | Network Infrastructure | R06 (supporting asset) |
| A09 | Company Website | R06 |
| A10 | Backup Systems | R07 |

---

## 7. Key Observations

1. Client, employee and financial information needs strict access restrictions.
2. Source code needs protection against unauthorised access and modification.
3. Cloud infrastructure needs secure configuration and access management.
4. Backup systems are essential for business continuity.
5. Employee devices and email are likely entry points for cyberattacks.

---

## 8. Conclusion

Ten information assets support Nexora's operations; five of them are high-priority. The classification and CIA ratings provide the basis for the threat and vulnerability assessment.

Asset ownership and criticality would need validation with real asset owners in a live assessment.

---

**Project:** Cybersecurity Risk Assessment & ISO 27001 Case Study
**Document:** 02 — Asset Identification and Classification
**Status:** Completed — Simulated
