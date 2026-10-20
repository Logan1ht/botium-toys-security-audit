# Original Project Report

> Training scenario. This is a migrated copy of the original write-up; its analysis and historical references have been preserved.

Overview

# 🛡️ Internal Security Audit

Project: Botium Toys – Internal IT Audit using the NIST Cybersecurity Framework  
 Role: Security Analyst (Student)  
 Tools & Concepts: NIST CSF, Controls & Compliance Checklist, Risk Assessment, Internal Audit Documentation

## 📌 Project Overview

As part of my cybersecurity training, I conducted an internal IT security audit for a fictional company, Botium Toys, a small U.S.-based business expanding into international e-commerce. The goal of the audit was to identify existing vulnerabilities, assess regulatory compliance, and recommend improvements to the company’s security posture.

🎯 Objective

- Assess existing IT assets and infrastructure for risk
- Identify gaps in controls and compliance
- Evaluate alignment with NIST Cybersecurity Framework (CSF)
- Recommend mitigations to enhance security and reduce potential regulatory fines

## 🧩 Key Activities

### ✅ Reviewed Scope, Goals, and Risk Assessment

- Analyzed Botium’s current IT-managed assets
- Interpreted risk comments from the IT manager
- Identified customer, employee, and system-level risks

### ✅ Applied NIST CSF Control Categories

- Referenced key control areas (e.g., access control, asset management, governance)
- Mapped control categories to audit questions and compliance best practices

### ✅ Completed Controls & Compliance Checklist

- Marked “Yes” or “No” for 20+ controls across key categories
- Marked “Yes” or “No” for compliance with practices like PCI DSS, GDPR
- Noted areas needing stronger encryption, backup, and audit logging

## 💡 Key Findings

- Lack of centralized asset inventory
- No documented encryption protocols for sensitive data
- Missing incident response procedures
- Insufficient controls for user access and multi-factor authentication

---

## 🛠️ Recommendations

- Implement formal asset tracking and classification
- Encrypt all sensitive data at rest and in transit
- Create and test an incident response playbook
- Enforce multi-factor authentication for system and admin logins
- Conduct regular security awareness training for employees

---

## 📄 Deliverables

- Completed Controls and Compliance Checklist (attached)
- Internal audit summary aligned with NIST CSF
- Recommendation notes to IT manager

---

## 📚 Skills Applied

- Risk analysis and threat identification
- Compliance evaluation (NIST, PCI DSS, GDPR)
- Audit documentation and reporting
- Critical thinking and technical writing

Scope, goals, and risk assessment report

# Botium Toys: Scope, goals, and risk assessment report

## Scope and goals of the audit

Scope: The scope is defined as the entire security program at Botium Toys. This means all assets need to be assessed alongside internal processes and procedures related to the implementation of controls and compliance best practices.

Goals: Assess existing assets and complete the controls and compliance checklist to determine which controls and compliance best practices need to be implemented to  improve Botium Toys’ security posture.

## Current assets

Assets managed by the IT Department include:

●      On-premises equipment for in-office business needs

●      Employee equipment: end-user devices (desktops/laptops, smartphones), remote workstations, headsets, cables, keyboards, mice, docking stations, surveillance cameras, etc.

●      Storefront products available for retail sale on site and online; stored in the company’s adjoining warehouse

●      Management of systems, software, and services: accounting, telecommunication, database, security, ecommerce, and inventory management

●      Internet access

●      Internal network

●      Data retention and storage

●      Legacy system maintenance: end-of-life systems that require human monitoring

## Risk assessment

### Risk description

Currently, there is inadequate management of assets. Additionally, Botium Toys does not have all of the proper controls in place and may not be fully compliant with U.S. and international regulations and standards.

### Control best practices

The first of the five functions of the NIST CSF is Identify. Botium Toys will need to dedicate resources to identify assets so they can appropriately manage them. Additionally, they will need to classify existing assets and determine the impact of the loss of existing assets, including systems, on business continuity.

### Risk score

On a scale of 1 to 10, the risk score is 8, which is fairly high. This is due to a lack of controls and adherence to compliance best practices.

### Additional comments

The potential impact from the loss of an asset is rated as medium, because the IT department does not know which assets would be at risk. The risk to assets or fines from governing bodies is high because Botium Toys does not have all of the necessary controls in place and is not fully adhering to best practices related to compliance regulations that keep critical data private/secure. Review the following bullet points for specific details:

 

●          Currently, all Botium Toys employees have access to internally stored data and may be able to access cardholder data and customers’ PII/SPII.

●          Encryption is not currently used to ensure confidentiality of customers’ credit card information that is accepted, processed, transmitted, and stored locally in the company’s internal database.

●          Access controls pertaining to least privilege and separation of duties have not been implemented.

●          The IT department has ensured availability and integrated controls to ensure data integrity.

●          The IT department has a firewall that blocks traffic based on an appropriately defined set of security rules.

●          Antivirus software is installed and monitored regularly by the IT department.

●          The IT department has not installed an intrusion detection system (IDS).

●          There are no disaster recovery plans currently in place, and the company does not have backups of critical data.

●          The IT department has established a plan to notify E.U. customers within 72 hours if there is a security breach. Additionally, privacy policies, procedures, and processes have been developed and are enforced among IT department members/other employees, to properly document and maintain data.

●          Although a password policy exists, its requirements are nominal and not in line with current minimum password complexity requirements (e.g., at least eight characters, a combination of letters and at least one number; special characters).

●          There is no centralized password management system that enforces the password policy’s minimum requirements, which sometimes affects productivity when employees/vendors submit a ticket to the IT department to recover or reset a password.

●          While legacy systems are monitored and maintained, there is no regular schedule in place for these tasks and intervention methods are unclear.

●          The store’s physical location, which includes Botium Toys’ main offices, store front, and warehouse of products, has sufficient locks, up-to-date closed-circuit television (CCTV) surveillance, as well as functioning fire detection and prevention systems.

Control categories

## Control categories

Controls within cybersecurity are grouped into three main categories:

 

●      Administrative/Managerial controls

●      Technical controls

●      Physical/Operational controls

 

Administrative/Managerial controls address the human component of cybersecurity. These controls include policies and procedures that define how an organization manages data and clearly defines employee responsibilities, including their role in protecting the organization. While administrative controls are typically policy based, the enforcement of those policies may require the use of technical or physical controls.

 

Technical controls consist of solutions such as firewalls, intrusion detection systems (IDS), intrusion prevention systems (IPS), antivirus (AV) products, encryption, etc. Technical controls can be used in a number of ways to meet organizational goals and objectives.

 

Physical/Operational controls include door locks, cabinet locks, surveillance cameras, badge readers, etc. They are used to limit physical access to physical assets by unauthorized personnel.

## Control types

Control types include, but are not limited to:               

1. Preventative
2. Corrective
3. Detective
4. Deterrent

 

 

These controls work together to provide defense in depth and protect assets. Preventative controls are designed to prevent an incident from occurring in the first place. Corrective controls are used to restore an asset after an incident. Detective controls are implemented to determine whether an incident has occurred or is in progress. Deterrent controls are designed to discourage attacks.

 

Review the following charts for specific details about each type of control and its purpose.

 

|  |  |  |
| --- | --- | --- |
| Administrative/Managerial Controls | | |
| Control Name | Control Type | Control Purpose |
| Least Privilege | Preventative | Reduce risk and overall impact of malicious insider or compromised accounts |
| Disaster recovery plans | Corrective | Provide business continuity |
| Password policies | Preventative | Reduce likelihood of account compromise through brute force or dictionary attack techniques |
| Access control policies | Preventative | Bolster confidentiality and integrity by defining which groups can access or modify data |
| Account management policies | Preventative | Managing account lifecycle, reducing attack surface, and limiting overall impact from disgruntled former employees and default account usage |
| Separation of duties | Preventative | Reduce risk and overall impact of malicious insider or compromised accounts |

 

 

 

|  |  |  |
| --- | --- | --- |
| Technical Controls | | |
| Control Name | Control Type | Control Purpose |
| Firewall | Preventative | To filter unwanted or malicious traffic from entering the network |
| IDS/IPS | Detective | To detect and prevent anomalous traffic that matches a signature or rule |
| Encryption | Deterrent | Provide confidentiality to sensitive information |
| Backups | Corrective | Restore/recover from an event |
| Password management | Preventative | Reduce password fatigue |
| Antivirus (AV) software | Corrective | Detect and quarantine known threats |
| Manual monitoring, maintenance, and intervention | Preventative | Necessary to identify and manage threats, risks, or vulnerabilities to out-of-date systems |

 

 

 

 

|  |  |  |
| --- | --- | --- |
| Physical/Operational Controls | | |
| Control Name | Control Type | Control Purpose |
| Time-controlled safe | Deterrent | Reduce attack surface and overall impact from physical threats |
| Adequate lighting | Deterrent | Deter threats by limiting “hiding” places |
| Closed-circuit television (CCTV) | Preventative/Detective | Closed circuit television is both a preventative and detective control because it’s presence can reduce risk of certain types of events from occurring, and can be used after an event to inform on event conditions |
| Locking cabinets (for network gear) | Preventative | Bolster integrity by preventing unauthorized personnel and other individuals from physically accessing or modifying network infrastructure gear |
| Signage indicating alarm service provider | Deterrent | Deter certain types of threats by making the likelihood of a successful attack seem low |
| Locks | Deterrent/Preventative | Bolster integrity by deterring and preventing unauthorized personnel, individuals from physically accessing assets |
| Fire detection and prevention (fire alarm, sprinkler system, etc.) | Detective/Preventative | Detect fire in physical location and prevent damage to physical assets such as inventory, servers, etc. |

 

Controls and compliance checklist

# Controls and compliance checklist

 

Type an X in the “yes” or “no” column to answer the question: Does Botium Toys currently have this control in place?

 

Controls assessment checklist

 

|  |  |  |  |
| --- | --- | --- | --- |
| Yes | No | Control | Explanation |
|  | X | Least Privilege | Currently, all employees have access to customer data; privileges need to be limited to reduce the risk of a breach. |
|  | X | Disaster recovery plans | There are no disaster recovery plans in place. These need to be implemented to ensure business continuity. |
|  | X | Password policies | Employee password requirements are minimal, which could allow a threat actor to more easily access secure data/other assets via employee work equipment/the internal network. |
|  | X | Separation of duties | Needs to be implemented to reduce the possibility of fraud/access to critical data, since the company CEO currently runs day-to-day operations and manages the payroll. |
| X |  | Firewall | The existing firewall blocks traffic based on an appropriately defined set of security rules. |
|  |  |  |  |
|  | X | Intrusion detection system (IDS) | The IT department needs an IDS in place to help identify possible intrusions by threat actors. |
|  | X | Backups | The IT department needs to have backups of critical data, in the case of a breach, to ensure business continuity. |
| X |  | Antivirus software | Antivirus software is installed and monitored regularly by the IT department. |
|  | X | Manual monitoring, maintenance, and intervention for legacy systems | The list of assets notes the use of legacy systems. The risk assessment indicates that these systems are monitored and maintained, but there is not a regular schedule in place for this task and procedures/ policies related to intervention are unclear, which could place these systems at risk of a breach. |
|  | X | Encryption | Encryption is not currently used; implementing it would provide greater confidentiality of sensitive information. |
|  | X | Password management system | There is no password management system currently in place; implementing this control would improve IT department/other employee productivity in the case of password issues. |
| X |  | Locks (offices, storefront, warehouse) | The store’s physical location, which includes the company’s main offices, store front, and warehouse of products, has sufficient locks. |
| X |  | Closed-circuit television (CCTV) surveillance | CCTV is installed/functioning at the store’s physical location. |
| X |  | Fire detection/prevention (fire alarm, sprinkler system, etc.) | Botium Toys’ physical location has a functioning fire detection and prevention system. |

 

---

 

Compliance checklist

 

Type an X in the “yes” or “no” column to answer the question: Does Botium Toys currently adhere to this compliance best practice?

 

Payment Card Industry Data Security Standard (PCI DSS)

|  |  |  |  |
| --- | --- | --- | --- |
| Yes | No | Best practice | Explanation |
|  | X | Only authorized users have access to customers’ credit card information. | Currently, all employees have access to the company’s internal data. |
|  | X | Credit card information is accepted, processed, transmitted, and stored internally, in a secure environment. | Credit card information is not encrypted and all employees currently have access to internal data, including customers’ credit card information. |
|  | X | Implement data encryption procedures to better secure credit card transaction touchpoints and data. | The company does not currently use encryption to better ensure the confidentiality of customers’ financial information. |
|  | X | Adopt secure password management policies. | Password policies are nominal and no password management system is currently in place. |

 

 

General Data Protection Regulation (GDPR)

|  |  |  |  |
| --- | --- | --- | --- |
| Yes | No | Best practice | Explanation |
|  | X | E.U. customers’ data is kept private/secured. | The company does not currently use encryption to better ensure the confidentiality of customers’ financial information. |
| X |  | There is a plan in place to notify E.U. customers within 72 hours if their data is compromised/there is a breach. | There is a plan to notify E.U. customers within 72 hours of a data breach. |
|  | X | Ensure data is properly classified and inventoried. | Current assets have been inventoried/listed, but not classified. |
| X |  | Enforce privacy policies, procedures, and processes to properly document and maintain data. | Privacy policies, procedures, and processes have been developed and enforced among IT team members and other employees, as needed. |

 

 

System and Organizations Controls (SOC type 1, SOC type 2)

|  |  |  |  |
| --- | --- | --- | --- |
| Yes | No | Best practice | Explanation |
|  | X | User access policies are established. | Controls of Least Privilege and separation of duties are not currently in place; all employees have access to internally stored data. |
|  | X | Sensitive data (PII/SPII) is confidential/private. | Encryption is not currently used to better ensure the confidentiality of PII/SPII. |
| X |  | Data integrity ensures the data is consistent, complete, accurate, and has been validated. | Data integrity is in place. |
|  | X | Data is available to individuals authorized to access it. | While data is available to all employees, authorization needs to be limited to only the individuals who need access to it to do their jobs. |

 

---

Recommendations:

Multiple controls need to be implemented to improve Botium Toys’ security posture and better ensure the confidentiality of sensitive information, including: Least Privilege, disaster recovery plans, password policies, separation of duties, an IDS, ongoing legacy system management, encryption, and a password management system.

To address gaps in compliance, Botium Toys needs to implement controls such as Least Privilege, separation of duties, and encryption. The company also needs to properly classify assets, to identify additional controls that may need to be implemented to improve their security posture and better protect sensitive information.
