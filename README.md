# 🧸 Botium Toys – Internal IT Audit Report
**Framework Used:** NIST Cybersecurity Framework (NIST CSF)  
**Audit Type:** Internal IT Security Audit  
**Company Type:** Small U.S.-based retail & eCommerce business (Fictional Case Study)

---

## 1. Executive Summary

Botium Toys is a growing retail company with both physical and online operations, serving customers in the United States and the European Union. Due to rapid business expansion and increased online transactions, the IT department conducted an internal IT audit to evaluate the organization’s current security posture.

This audit assesses existing assets, identifies risks, reviews implemented controls, and evaluates compliance with relevant regulations and industry standards. The objective is to identify security gaps, assess risk levels, and recommend improvements to protect sensitive data, ensure regulatory compliance, and strengthen overall cybersecurity maturity.

---

## 2. Audit Scope and Goals

### 2.1 Audit Scope

The internal IT audit assessed the following areas:

- User access permissions  
- Existing security controls, procedures, and system protocols  
- Technology and systems currently in use  
- Data handling, retention, and storage practices  

---

### 2.2 Audit Goals

The goals of this audit are to:

- Align business practices with the **NIST Cybersecurity Framework (CSF)**  
- Identify risks, threats, and vulnerabilities to critical assets  
- Establish policies and procedures to ensure regulatory compliance  
- Fortify system and security controls  

---

## 3. Asset Inventory

Assets managed by the IT department include:

- On-premises equipment for office and business operations  
- Employee devices (desktops, laptops, smartphones, remote workstations)  
- Peripheral equipment (keyboards, mice, headsets, docking stations, cables)  
- Surveillance systems (CCTV)  
- Internal network and internet access  
- Business systems (accounting, databases, ecommerce, inventory management)  
- Data retention and storage systems  
- Legacy systems requiring manual monitoring and maintenance  
- Physical storefront, warehouse, and inventory  

---

## 4. Risk Assessment

### 4.1 Risk Overview

Botium Toys currently lacks adequate asset management and does not have sufficient security controls in place. As a result, the organization is exposed to increased risk related to unauthorized access, data breaches, regulatory fines, and operational disruption.

---

### 4.2 Key Risk Findings

- All employees have unrestricted access to internal data, including customer PII and credit card information  
- Credit card data is not encrypted when accepted, processed, transmitted, or stored  
- No disaster recovery or backup solutions exist  
- No intrusion detection system (IDS) is deployed  
- Weak password policies and lack of centralized password management  
- Legacy systems lack a formal maintenance and monitoring schedule  

---

### 4.3 Risk Score

- **Risk Score:** 8 / 10 (High)  
- **Impact Level:** Medium to High  
- **Likelihood:** High  

---

## 5. Control Categories and Types

### Control Categories Reviewed

- Administrative / Managerial Controls  
- Technical Controls  
- Physical / Operational Controls  

### Control Types Considered

- Preventative  
- Detective  
- Corrective  
- Deterrent  

---

## 6. Controls Assessment Checklist

| Control | Implemented | Explanation |
|------|------------|-------------|
| Least Privilege | No | All employees currently have access to sensitive data |
| Disaster Recovery Plan | No | No business continuity or recovery plans exist |
| Password Policies | No | Password requirements are minimal |
| Separation of Duties | No | CEO manages daily operations and payroll |
| Firewall | Yes | Firewall rules are properly configured |
| Intrusion Detection System (IDS) | No | No IDS is in place |
| Backups | No | No backups of critical data |
| Antivirus Software | Yes | Installed and monitored regularly |
| Legacy System Monitoring | No | No formal schedule or documented procedures |
| Encryption | No | Sensitive data is not encrypted |
| Password Management System | No | No centralized password management solution |
| Physical Locks | Yes | Offices, storefront, and warehouse secured |
| CCTV Surveillance | Yes | Cameras installed and operational |
| Fire Detection & Prevention | Yes | Fire alarm and sprinkler systems in place |

---

## 7. Compliance Assessment

## ✅ Compliance Checklist

---

## Payment Card Industry Data Security Standard (PCI DSS)

| Best Practice | Yes | No | Explanation |
|---------------|-----|----|-------------|
| Only authorized users have access to customers’ credit card information |  | ❌ | Currently, all employees have access to internal data, including customers’ credit card information |
| Credit card information is stored, accepted, processed, and transmitted internally in a secure environment |  | ❌ | Credit card data is not encrypted and access is not restricted |
| Implement data encryption procedures to better secure credit card transaction touchpoints and data |  | ❌ | Encryption is not currently used for cardholder data |
| Adopt secure password management policies |  | ❌ | Password policies are weak and no password management system is in place |

**PCI DSS Compliance Status:** ❌ Non-Compliant

---

## General Data Protection Regulation (GDPR)

| Best Practice | Yes | No | Explanation |
|---------------|-----|----|-------------|
| E.U. customers’ data is kept private and secured |  | ❌ | Encryption is not used to protect customer data |
| There is a plan in place to notify E.U. customers within 72 hours of a data breach | ✅ |  | A breach notification plan exists and meets GDPR requirements |
| Ensure data is properly classified and inventoried |  | ❌ | Assets are inventoried but not classified |
| Enforce privacy policies, procedures, and processes | ✅ |  | Privacy policies and procedures are documented and enforced |

**GDPR Compliance Status:** ⚠️ Partially Compliant

---

## System and Organization Controls (SOC Type 1 & Type 2)

| Best Practice | Yes | No | Explanation |
|---------------|-----|----|-------------|
| User access policies are established |  | ❌ | Least Privilege and separation of duties are not implemented |
| Sensitive data (PII/SPII) is confidential and private |  | ❌ | Sensitive data is not encrypted |
| Data integrity ensures data is consistent, complete, accurate, and validated | ✅ |  | Integrity controls are in place |
| Data is available only to authorized individuals |  | ❌ | Data is accessible to all employees, authorization needs restriction |

**SOC Compliance Status:** ❌ Non-Compliant

---

## 📌 Overall Compliance Summary

- **PCI DSS:** ❌ Non-Compliant  
- **GDPR:** ⚠️ Partially Compliant  
- **SOC Type 1 & 2:** ❌ Non-Compliant  

---

## 🔧 Compliance Improvement Recommendations

To address compliance gaps, Botium Toys should:

- Implement **Least Privilege** and **role-based access control**
- Encrypt sensitive data (PII, SPII, and cardholder data)
- Deploy a **password management system**
- Strengthen password complexity requirements
- Properly classify and inventory all assets
- Restrict access to sensitive data based on job responsibilities


## 8. Recommendations

To improve Botium Toys’ security posture and compliance standing, the following actions are recommended:

### Administrative Controls
- Implement Least Privilege access  
- Enforce separation of duties  
- Establish disaster recovery and incident response plans  
- Strengthen password policies  

### Technical Controls
- Implement encryption for data at rest and in transit  
- Deploy an intrusion detection system (IDS)  
- Implement centralized password management  
- Establish automated backups  
- Create a formal maintenance schedule for legacy systems  

### Compliance Improvements
- Align controls with PCI DSS requirements  
- Properly classify and inventory assets  
- Restrict access to sensitive data based on job roles  

---

## 9. Conclusion

This internal IT audit identified multiple high-risk gaps in Botium Toys’ cybersecurity and compliance posture. While basic security controls such as firewalls, antivirus software, and physical protections are in place, the absence of access controls, encryption, monitoring, and recovery planning significantly increases organizational risk.

Implementing the recommended controls will improve the confidentiality, integrity, and availability of data while reducing the likelihood of security incidents and regulatory penalties.

---

> **Note:** This project is an academic case study created for learning purposes and demonstrates internal IT audit practices aligned with the NIST Cybersecurity Framework.

