02 — Asset Identification & Classification

Organisation: Nexora Solutions Pvt. Ltd.
Assessment Type: Simulated Cybersecurity Risk Assessment
Framework Reference: ISO/IEC 27001:2022
Document Status: Initial Assessment

⸻

1. Objective

The purpose of asset identification is to identify the information, systems and resources that support the organisation’s business operations.

Each asset is assigned:

* A unique asset ID
* An asset category
* An assigned owner
* A security classification
* A CIA security assessment

⸻

2. Asset Classification Levels

The organisation uses four classification levels.

2.1 Public

Information approved for public distribution.

Example: Company website content.

2.2 Internal

Information intended for employees and authorised personnel.

Example: Internal business communications.

2.3 Confidential

Sensitive business or client information requiring restricted access.

Example: Employee records and source code.

2.4 Restricted

Highly sensitive information requiring strict access controls.

Example: Client databases and financial records.

⸻

3. Asset Inventory

Asset A01 — Client Database

* Category: Data
* Owner: IT Manager
* Classification: Restricted
* Description: Stores client information, contact details and business records.

Asset A02 — Employee Records

* Category: Data
* Owner: HR Manager
* Classification: Confidential
* Description: Contains employee personal information and employment records.

Asset A03 — Source Code Repository

* Category: Application / Data
* Owner: Development Manager
* Classification: Confidential
* Description: Stores application source code and development projects.

Asset A04 — Cloud Storage

* Category: Infrastructure
* Owner: IT Manager
* Classification: Restricted
* Description: Stores organisational documents, business data and project files.

Asset A05 — Corporate Email

* Category: Application
* Owner: IT Manager
* Classification: Internal
* Description: Used for internal communication and external business correspondence.

Asset A06 — Financial Records

* Category: Data
* Owner: Finance Manager
* Classification: Restricted
* Description: Contains invoices, payment records and financial information.

Asset A07 — Employee Laptops

* Category: Hardware
* Owner: IT Manager
* Classification: Internal
* Description: Devices used by employees for daily business operations.

Asset A08 — Network Infrastructure

* Category: Infrastructure
* Owner: IT Manager
* Classification: Internal
* Description: Includes routers, switches and network connectivity equipment.

Asset A09 — Company Website

* Category: Application
* Owner: Marketing Manager
* Classification: Public
* Description: Public-facing website providing company and service information.

Asset A10 — Backup Systems

* Category: Infrastructure / Data
* Owner: IT Manager
* Classification: Restricted
* Description: Stores backup copies of critical organisational information.

⸻

4. CIA Security Assessment

The CIA Triad evaluates the security requirements of each asset.

4.1 Confidentiality

Protects information against unauthorised access or disclosure.

4.2 Integrity

Protects information against unauthorised modification or destruction.

4.3 Availability

Ensures information and systems remain accessible when required.

4.4 Initial CIA Assessment

AssetID	  Confidentiality	   Integrity    Availability
A01	      High	             High	        High
A02	      High	             High	        Medium
A03	      High	             High	        High
A04	      High	             High	        High
A05	      Medium	           High	        High
A06	      High	             High	        High
A07	      Medium	           Medium	      High
A08	      Medium	           High	        High
A09	      Low	               Medium	      High
A10	      High	             High	        High

Note: CIA ratings represent preliminary qualitative assumptions for this simulated assessment.

⸻

5. High-Priority Assets

Based on the initial assessment, the following assets require particular attention:

A01 — Client Database

* Contains sensitive client information.
* Unauthorised disclosure could cause financial and reputational damage.

A04 — Cloud Storage

* Supports storage and access to business information.
* Misconfiguration or unauthorised access could expose multiple data categories.

A06 — Financial Records

* Contains sensitive financial information.
* Unauthorised modification could result in financial losses.

A10 — Backup Systems

* Supports business continuity and recovery.
* Compromised backups could prevent effective recovery after an incident.

⸻

6. Key Observations

1. Sensitive client and employee information requires appropriate access restrictions.
2. Source code requires protection against unauthorised access and modification.
3. Cloud infrastructure needs secure configuration and access management.
4. Backup systems are essential for business continuity.
5. Employee devices represent potential entry points for cyberattacks.

⸻

7. Assessment Conclusion

The initial asset inventory identifies ten important assets supporting Nexora Solutions’ operations.

The classification and CIA assessments provide a foundation for identifying potential threats, vulnerabilities and associated cybersecurity risks.

Further validation of asset ownership, business criticality and security requirements would be necessary in a real organisational assessment.

⸻

Project: Cybersecurity Risk Assessment & ISO 27001 Case Study
Organisation: Nexora Solutions Pvt. Ltd.
Document: 02 — Asset Identification & Classification
Status: Completed
