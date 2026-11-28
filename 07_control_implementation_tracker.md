# 07 — Security Control Implementation Tracker

| Field | Details |
|---|---|
| Organisation | Nexora Solutions Pvt. Ltd. (fictional) |
| Document | 07 — Security Control Implementation Tracker |
| Related document | 06 — Statement of Applicability |
| Framework | ISO/IEC 27001:2022 |
| Version | 2.0 |
| Status | Proposed — Not Verified |

---

## 1. Purpose

This tracker records the proposed implementation of the **23 controls** selected in the Statement of Applicability. For each control it sets out the related risks, proposed owner, priority, phase, planned activities and the evidence needed to verify it.

> **Important:** This is a proposed tracker. It does not confirm that any control has been implemented, tested or verified.

---

## 2. Status Definitions

| Status | Meaning |
|---|---|
| Proposed — Not Verified | Selected for implementation; implementation not established by evidence |
| In Progress | Implementation has started but is not complete |
| Implemented — Pending Verification | Reported as deployed; operation and effectiveness not yet verified |
| Partially Implemented | Some requirements in place; gaps remain |
| Verified | Implementation and effectiveness assessed and supported by evidence |

All 23 controls are currently **Proposed — Not Verified**.

---

## 3. Tracker Summary

| Control | Name | Risks | Owner | Priority | Phase | Status |
|---|---|---|---|---|---|---|
| A.5.15 | Access control | R03, R04, R08, R09 | IT Manager | High | 2 | Proposed — Not Verified |
| A.5.17 | Authentication information | R01 | IT Manager | High | 1 | Proposed — Not Verified |
| A.5.18 | Access rights | R03, R08, R09 | IT Manager / HR Manager | High | 2 | Proposed — Not Verified |
| A.5.23 | Information security for use of cloud services | R04 | IT Manager | High | 1 | Proposed — Not Verified |
| A.5.24 | Incident management planning and preparation | R01–R09 | Security Officer / IT Manager | High | 1 | Proposed — Not Verified |
| A.5.30 | ICT readiness for business continuity | R02, R07 | IT Manager / Senior Management | High | 2 | Proposed — Not Verified |
| A.6.3 | Security awareness, education and training | R01, R02, R03 | HR Manager / Security Officer | Medium | 2 | Proposed — Not Verified |
| A.8.2 | Privileged access rights | R03, R08 | IT Manager | High | 1 | Proposed — Not Verified |
| A.8.3 | Information access restriction | R03, R09 | IT Manager / Data Owners | High | 2 | Proposed — Not Verified |
| A.8.4 | Access to source code | R08 | Development Manager | High | 2 | Proposed — Not Verified |
| A.8.5 | Secure authentication | R01, R04, R08, R09 | IT Manager | High | 1 | Proposed — Not Verified |
| A.8.6 | Capacity management | R06 | IT Manager | Medium | 3 | Proposed — Not Verified |
| A.8.7 | Protection against malware | R01, R02 | IT Manager | High | 1 | Proposed — Not Verified |
| A.8.8 | Management of technical vulnerabilities | R02, R05 | IT Manager / Security Officer | High | 2 | Proposed — Not Verified |
| A.8.9 | Configuration management | R04, R05 | IT Manager | High | 2 | Proposed — Not Verified |
| A.8.13 | Information backup | R02, R07, R08, R09 | IT Manager | High | 1 | Proposed — Not Verified |
| A.8.14 | Redundancy of information processing facilities | R07 | IT Manager | Medium | 3 | Proposed — Not Verified |
| A.8.16 | Monitoring activities | R01, R02, R03, R04, R06, R08, R09 | IT Manager / Security Officer | High | 2 | Proposed — Not Verified |
| A.8.19 | Installation of software on operational systems | R02, R05 | IT Manager | Medium | 2 | Proposed — Not Verified |
| A.8.20 | Networks security | R06 | IT Manager / Network Administrator | High | 2 | Proposed — Not Verified |
| A.8.21 | Security of network services | R06 | IT Manager | Medium | 2 | Proposed — Not Verified |
| A.8.23 | Web filtering | R01 | IT Manager | High | 1 | Proposed — Not Verified |
| A.8.24 | Use of cryptography | R04 | IT Manager | Medium | 2 | Proposed — Not Verified |

**Baseline:** Proposed — Not Verified 23 · In Progress 0 · Implemented — Pending Verification 0 · Partially Implemented 0 · Verified 0 · **Initial implementation progress: 0%**

Phase 1 = 0–3 months, Phase 2 = 3–6 months, Phase 3 = 6–12 months (indicative only).

---

## 4. Control Details

### 4.1 Organisational controls — A.5

**A.5.15 — Access control** (R03, R04, R08, R09)
- Objective: restrict access to information and systems according to business needs.
- Activities: approve an access control policy; define access by role; apply least privilege; review access periodically.
- Evidence: approved policy; role-based access matrix; access review records.

**A.5.17 — Authentication information** (R01)
- Objective: protect passwords and other credentials throughout their life.
- Activities: set rules for credential handling; prohibit sharing; use secure password storage; define a reset procedure for compromised credentials.
- Evidence: authentication and password policy; reset procedure; configuration records.

**A.5.18 — Access rights** (R03, R08, R09)
- Objective: grant, review, change and remove access in line with requirements.
- Activities: formal access request and approval; periodic permission reviews; remove access when staff leave or change role; keep records.
- Evidence: approval records; access review reports; onboarding and offboarding records; revocation records.

**A.5.23 — Information security for use of cloud services** (R04)
- Objective: select, use, manage and monitor cloud services securely.
- Activities: set cloud service requirements; evaluate providers; define shared responsibilities; review permissions and configurations; set data protection requirements.
- Evidence: cloud security policy; cloud service inventory; provider assessments; configuration review records.

**A.5.24 — Incident management planning and preparation** (R01–R09)
- Objective: prepare to respond to and manage information security incidents.
- Activities: write an incident response plan; define reporting and escalation; assign roles; classify and document incidents; run exercises.
- Evidence: approved plan; reporting procedure; incident register; escalation matrix; exercise records.

**A.5.30 — ICT readiness for business continuity** (R02, R07)
- Objective: ensure ICT can support business continuity during disruption.
- Activities: identify critical ICT systems; define recovery time and recovery point objectives; document recovery procedures; test restoration; review periodically.
- Evidence: ICT continuity plan; recovery procedures; recovery objectives; restoration test reports.

### 4.2 People controls — A.6

**A.6.3 — Information security awareness, education and training** (R01, R02, R03)
- Objective: ensure staff understand their responsibilities and common threats.
- Activities: regular awareness sessions; phishing awareness; password and data handling guidance; training records; periodic evaluation.
- Evidence: training materials; attendance records; acknowledgements; phishing simulation results.

### 4.3 Technological controls — A.8

**A.8.2 — Privileged access rights** (R03, R08)
- Objective: restrict and manage privileged access.
- Activities: identify privileged accounts; restrict admin permissions; require approval; review periodically; monitor privileged activity.
- Evidence: privileged account inventory; approval records; review reports; audit logs.

**A.8.3 — Information access restriction** (R03, R09)
- Objective: restrict access to information according to access control requirements.
- Activities: define restrictions; apply role-based permissions; restrict sensitive files and folders; review regularly.
- Evidence: information access policy; permission records; role matrix; review records.

**A.8.4 — Access to source code** (R08)
- Objective: control access to source code, development tools and libraries.
- Activities: restrict repository access by role; require branch protection and peer review; separate admin rights; log access and changes; remove access on role change.
- Evidence: repository access list; branch protection settings; access review records; repository audit logs.

**A.8.5 — Secure authentication** (R01, R04, R08, R09)
- Objective: protect access to systems with secure authentication.
- Activities: enable MFA on email, cloud, repository and finance systems; apply secure configurations; use account lockout; review settings.
- Evidence: MFA configuration records; authentication policy; authentication logs.

**A.8.6 — Capacity management** (R06)
- Objective: keep systems available and performing under load.
- Activities: identify critical resources; monitor CPU, memory, storage and network use; set thresholds; plan expansion; review trends.
- Evidence: capacity reports; utilisation records; capacity plan.

**A.8.7 — Protection against malware** (R01, R02)
- Objective: protect systems against malicious software.
- Activities: deploy anti-malware; enable real-time detection; keep tools updated; restrict unauthorised software; train staff on malicious attachments.
- Evidence: configuration records; endpoint protection reports; detection logs; update records.

**A.8.8 — Management of technical vulnerabilities** (R02, R05)
- Objective: identify, assess and address technical vulnerabilities.
- Activities: keep a system and software inventory; monitor vulnerability information; run periodic assessments; prioritise remediation by risk; track patching.
- Evidence: assessment reports; inventory; patch records; remediation register.

**A.8.9 — Configuration management** (R04, R05)
- Objective: maintain secure configurations for hardware, software, services and networks.
- Activities: define baselines; disable unnecessary services; change default credentials; document changes; review periodically.
- Evidence: configuration standards; configuration records; change logs; review reports.

**A.8.13 — Information backup** (R02, R07, R08, R09)
- Objective: protect information against loss through backups.
- Activities: set a backup policy; define frequency; protect backup copies from unauthorised access; set retention; test restoration.
- Evidence: backup policy and schedule; completion logs; retention records; access restrictions; restoration test reports.

**A.8.14 — Redundancy of information processing facilities** (R07)
- Objective: ensure availability through redundancy.
- Activities: identify critical systems; evaluate single points of failure; set redundancy requirements; consider redundant storage, network or processing; test failover.
- Evidence: redundancy documentation; architecture diagrams; failover test reports.

**A.8.16 — Monitoring activities** (R01, R02, R03, R04, R06, R08, R09)
- Objective: detect unusual behaviour and potential incidents.
- Activities: enable system and security logging; monitor critical activity; review alerts; investigate suspicious events; retain logs.
- Evidence: monitoring procedures; logs; monitoring reports; alert and investigation records.

**A.8.19 — Installation of software on operational systems** (R02, R05)
- Objective: control software installation to reduce malicious or unauthorised software.
- Activities: restrict installation permissions; require approval; keep an approved software list; remove unauthorised applications; review periodically.
- Evidence: installation policy; approved software inventory; approval records; review reports.

**A.8.20 — Networks security** (R06)
- Objective: protect networks and network devices.
- Activities: set network security requirements; configure firewalls and access restrictions; secure devices; separate networks where appropriate; review configurations.
- Evidence: network security policy; architecture documentation; firewall records; review reports.

**A.8.21 — Security of network services** (R06)
- Objective: define and apply security requirements for network services used by Nexora.
- Activities: inventory network services (internet, DNS, hosting); set security requirements and service levels; require provider DDoS protection; review provider arrangements.
- Evidence: network services inventory; service agreements; provider security documentation; review records.

**A.8.23 — Web filtering** (R01)
- Objective: reduce exposure to malicious websites.
- Activities: deploy web or DNS filtering; block known malicious categories; define an exceptions process; review blocked events.
- Evidence: filtering configuration; filtering policy; filtering reports.

**A.8.24 — Use of cryptography** (R04)
- Objective: protect information through appropriate encryption and key management.
- Activities: write a cryptography and key management policy; encrypt sensitive cloud data at rest and in transit; manage keys; review algorithms periodically.
- Evidence: cryptography policy; encryption configuration records; key management procedure.

---

## 5. Limitations

- Owners, priorities, phases and activities are planning assumptions for a simulated case study.
- No implementation evidence has been supplied or independently verified.
- Progress stays at 0% until evidence is available.

---

**Project:** Cybersecurity Risk Assessment & ISO 27001 Case Study
**Document:** 07 — Security Control Implementation Tracker
**Status:** Proposed — Not Verified
