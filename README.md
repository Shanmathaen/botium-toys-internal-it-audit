# Botium Toys – Security Audit Case Study

🧸 Botium Toys – Internal IT Audit Report

Framework Used: NIST Cybersecurity Framework (NIST CSF)
Audit Type: Internal IT Security Audit
Company Type: Small U.S.-based retail & eCommerce business (fictional)

1. Executive Summary

Botium Toys is a growing retail company with both physical and online operations, serving customers in the United States and the European Union. Due to rapid business expansion and increased online transactions, the IT department conducted an internal IT audit to evaluate the organization’s current security posture.

This audit assesses existing assets, identifies risks, reviews implemented controls, and evaluates compliance with relevant regulations and industry standards. The objective is to identify security gaps, assess risk levels, and recommend improvements to protect sensitive data, ensure regulatory compliance, and strengthen overall cybersecurity maturity.

2. Audit Scope and Goals
2.1 Audit Scope

The internal IT audit assessed the following areas:

User access permissions

Existing security controls and procedures

IT systems, software, and infrastructure currently in use

Data handling and storage practices

Compliance with relevant security and privacy regulations

2.2 Audit Goals

The primary goals of this audit are to:

Align security practices with the NIST Cybersecurity Framework (CSF)

Identify risks, threats, and vulnerabilities to critical assets

Evaluate existing administrative, technical, and physical controls

Identify gaps in regulatory compliance (PCI DSS, GDPR, SOC)

Provide remediation recommendations to improve the organization’s security posture

3. Asset Inventory

The IT department manages the following assets:

On-premises office and business equipment

Employee devices (desktops, laptops, smartphones, remote workstations)

Peripheral equipment (keyboards, headsets, docking stations, cables)

Surveillance systems (CCTV)

Internal network and internet access

Business systems (accounting, databases, inventory, ecommerce platforms)

Data retention and storage systems

Legacy systems requiring manual monitoring and maintenance

Physical storefront, warehouse, and inventory

4. Risk Assessment
4.1 Risk Overview

Botium Toys currently has inadequate asset management and insufficient security controls. As a result, the organization faces elevated risk related to unauthorized access, data breaches, regulatory fines, and business disruption.

4.2 Key Identified Risks

All employees have access to sensitive internal data, including customer PII and credit card information

Lack of encryption for stored and transmitted payment card data

No disaster recovery or backup strategy

Absence of intrusion detection systems

Weak password policies and no centralized password management system

Unclear procedures for managing and maintaining legacy systems

4.3 Risk Score

Risk Score: 8 / 10 (High)

Impact Level: Medium to High

Likelihood: High due to lack of preventative and detective controls

5. Control Categories and Control Types
5.1 Control Categories Reviewed

Administrative / Managerial Controls

Technical Controls

Physical / Operational Controls

5.2 Control Types Considered

Preventative

Detective

Corrective

Deterrent

6. Controls Assessment Checklist
| Control                     | Implemented | Explanation                                                           |
| --------------------------- | ----------- | --------------------------------------------------------------------- |
| Least Privilege             | ❌ No        | All employees currently have access to sensitive customer data        |
| Disaster Recovery Plan      | ❌ No        | No formal disaster recovery or business continuity plan               |
| Password Policy             | ❌ No        | Existing policy is weak and does not meet modern complexity standards |
| Separation of Duties        | ❌ No        | CEO handles operations and payroll without separation                 |
| Firewall                    | ✅ Yes       | Firewall rules are properly configured                                |
| IDS                         | ❌ No        | No intrusion detection system in place                                |
| Backups                     | ❌ No        | No backups of critical business data                                  |
| Antivirus Software          | ✅ Yes       | Installed and monitored regularly                                     |
| Legacy System Monitoring    | ❌ Partial   | Systems monitored, but no formal schedule or documented procedures    |
| Encryption                  | ❌ No        | Sensitive data is stored and transmitted unencrypted                  |
| Password Management System  | ❌ No        | No centralized password management solution                           |
| Physical Locks              | ✅ Yes       | Offices, storefront, and warehouse secured                            |
| CCTV                        | ✅ Yes       | Surveillance cameras installed and operational                        |
| Fire Detection & Prevention | ✅ Yes       | Fire alarm and sprinkler systems in place                             |

7. Compliance Assessment
7.1 PCI DSS (Payment Card Industry Data Security Standard)

Status: ❌ Non-compliant

Key Issues:

Unauthorized access to credit card data

No encryption of payment card information

Weak password controls

7.2 GDPR (General Data Protection Regulation)

Status: ⚠️ Partially Compliant

Strengths:

Breach notification plan within 72 hours exists

Privacy policies are documented and enforced

Gaps:

Lack of encryption for personal and financial data

Assets not properly classified

7.3 SOC Type 1 & Type 2

Status: ❌ Non-compliant

Key Issues:

No least privilege or separation of duties

No encryption for PII/SPII

Data availability exists, but access is overly permissive

8. Recommendations

To improve Botium Toys’ security posture and compliance standing, the following actions are recommended:

Administrative Controls

Implement Least Privilege access

Enforce separation of duties

Establish formal disaster recovery and incident response plans

Strengthen password policies

Technical Controls

Implement encryption for data at rest and in transit

Deploy an intrusion detection system (IDS)

Implement centralized password management

Establish automated backups for critical systems

Create a formal maintenance schedule for legacy systems

Compliance Improvements

Align controls with PCI DSS requirements

Classify and inventory all assets

Restrict access to sensitive data based on job role

9. Conclusion

This internal IT audit identified several high-risk gaps in Botium Toys’ cybersecurity controls and compliance posture. While basic security measures such as firewalls, antivirus software, and physical protections are in place, the lack of access control, encryption, monitoring, and recovery planning significantly increases organizational risk.

Implementing the recommended controls will substantially improve Botium Toys’ confidentiality, integrity, and availability of data, while reducing the likelihood of security incidents and regulatory penalties.
