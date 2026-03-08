# Cybersecurity-Audit-Botium-Toys
"Security audit and risk assessment lab for 'Botium Toys'—completed as part of the Google Cybersecurity Professional Certificate. Evaluates simulated risk posture against NIST CSF, PCI DSS, and GDPR standards.
# Security Audit: Botium Toys (Lab Simulation)

## Project Overview
This project is a simulated security audit conducted as part of the **Google Cybersecurity Professional Certificate** program. The goal was to assess the security posture of a fictional company, **Botium Toys**, identify critical gaps in their current controls, and provide recommendations to align with industry standards and legal regulations.

## Scenario Summary
Botium Toys is a growing e-commerce company expanding into the E.U. market. Currently, they lack several foundational security controls, leaving them vulnerable to data breaches and non-compliance fines.

* **Scope:** Entire security program, including internal networks, employee equipment, and data systems.
* **Current Risk Score:** **8/10** (High) due to a lack of controls and adherence to best practices.
* **Primary Compliance Goals:** PCI DSS (Credit Card Security) and GDPR (E.U. Data Privacy).

## Key Audit Findings

### ❌ Critical Gaps Identified
* **Data Protection:** No encryption is used for PII/SPII or customer credit card data.
* **Access Control:** All employees have access to all internally stored data; the principles of **Least Privilege** and **Separation of Duties** are not implemented.
* **Monitoring:** No **Intrusion Detection System (IDS)** is installed to monitor for malicious activity.
* **Availability:** There is no **Disaster Recovery Plan** or regular backup schedule for critical data.

### ✅ Existing Controls
* **Network Security:** A functional firewall is in place with defined security rules.
* **Endpoint Protection:** Antivirus software is installed and monitored.
* **Physical Security:** Office and warehouse locations have sufficient locks and CCTV surveillance.
* **GDPR Readiness:** A 72-hour breach notification plan has been established.

## Recommendations
To improve Botium Toys' security posture, the following actions are recommended:
1.  **Implement Encryption:** Encrypt all sensitive data at rest and in transit to meet PCI DSS/GDPR requirements.
2.  **Enforce Least Privilege:** Restrict data access based on job roles to minimize internal risk.
3.  **Establish Backups:** Create a formal Disaster Recovery Plan including regular, automated data backups.
4.  **Deploy IDS:** Install an Intrusion Detection System to provide visibility into network threats.

---
*Note: This is a portfolio project created for educational purposes within the Google Cybersecurity Professional Certificate program.*
