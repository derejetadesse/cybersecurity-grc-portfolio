# 🛡️ Enterprise Cybersecurity Risk Assessment

## Executive Overview

This project demonstrates an enterprise cybersecurity risk assessment for a fictional healthcare technology company, **Aegis HealthTech Solutions**.

The assessment identifies critical information assets, evaluates cybersecurity threats and vulnerabilities, analyzes inherent risk, evaluates existing security controls, determines residual risk, and develops risk treatment recommendations.

The objective is to demonstrate a practical, business-focused approach to cybersecurity risk management similar to the work performed by a GRC Analyst or Cybersecurity Risk Analyst.

> **Portfolio Notice:** Aegis HealthTech Solutions is a fictional organization created for this portfolio. All systems, risks, findings, employees, vendors, and evidence are simulated.

---

## 🏢 Business Scenario

Aegis HealthTech Solutions is a mid-sized healthcare technology organization with approximately 250 employees.

The organization relies on:

- AWS cloud infrastructure
- Microsoft 365
- Windows employee endpoints
- Cloud-hosted databases
- Identity and access management systems
- SaaS business applications
- Third-party service providers
- Security monitoring and logging
- Backup and disaster recovery systems

The organization processes sensitive customer, employee, and business information.

Management requested an enterprise cybersecurity risk assessment to identify significant cyber risks and determine which risks require prioritized remediation.

---

## 🎯 Assessment Objectives

The assessment is designed to:

1. Identify critical business and information assets.
2. Identify relevant threats and vulnerabilities.
3. Develop realistic cybersecurity risk scenarios.
4. Evaluate likelihood and business impact.
5. Calculate inherent risk.
6. Evaluate existing security controls.
7. Identify control gaps.
8. Determine residual risk.
9. Recommend risk treatment actions.
10. Assign risk ownership and remediation priorities.

---

## 🔄 Risk Assessment Process

**Business Context**

↓

**Asset Identification**

↓

**Threat & Vulnerability Identification**

↓

**Risk Scenario Development**

↓

**Likelihood & Impact Assessment**

↓

**Inherent Risk**

↓

**Existing Control Assessment**

↓

**Residual Risk**

↓

**Risk Treatment**

↓

**Management Reporting & Monitoring**

---

## 📊 Risk Scoring Methodology

This assessment uses a **5 × 5 likelihood and impact model**.

### Likelihood Scale

| Rating | Level | Description |
|---:|---|---|
| 1 | Rare | Event is highly unlikely |
| 2 | Unlikely | Event could occur but is not expected |
| 3 | Possible | Event could reasonably occur |
| 4 | Likely | Event is expected to occur |
| 5 | Almost Certain | Event is expected frequently |

### Impact Scale

| Rating | Level | Description |
|---:|---|---|
| 1 | Insignificant | Minimal operational or business impact |
| 2 | Minor | Limited disruption or financial impact |
| 3 | Moderate | Noticeable business or operational impact |
| 4 | Major | Significant operational, financial, or regulatory impact |
| 5 | Severe | Critical business, regulatory, financial, or reputational impact |

### Risk Formula

**Risk Score = Likelihood × Impact**

| Score | Rating |
|---:|---|
| 1–4 | Low |
| 5–9 | Moderate |
| 10–16 | High |
| 17–25 | Critical |

---

## ⚠️ Risk Scenarios Evaluated

The assessment considers enterprise risks including:

- Phishing and business email compromise
- Ransomware
- Privileged account compromise
- Excessive AWS IAM permissions
- Missing or inconsistent MFA
- Delayed vulnerability remediation
- Third-party security compromise
- Sensitive data leakage
- Insufficient security logging
- Incomplete asset inventory
- Backup and recovery failure
- Unauthorized access to sensitive information
- Endpoint compromise
- Cloud misconfiguration
- Security incident response deficiencies

---

## 🔍 Example Risk Analysis

### RISK-001 — Privileged Cloud Account Compromise

**Asset:** AWS Production Environment

**Threat:** Credential theft / account compromise

**Vulnerability:** Excessive privileges and insufficient privileged-access governance

**Risk Scenario:**  
An attacker compromises a privileged cloud account and gains unauthorized access to production infrastructure and sensitive information.

**Potential Business Impact:**

- Sensitive data exposure
- Production service disruption
- Regulatory consequences
- Incident response costs
- Reputational damage

### Inherent Risk

**Likelihood:** 4 — Likely  
**Impact:** 5 — Severe  
**Risk Score:** 20  
**Risk Rating:** 🔴 Critical

### Existing Controls

- AWS IAM
- Password requirements
- MFA for selected accounts
- Cloud activity logging

### Identified Control Gaps

- MFA is not consistently enforced
- Excessive permissions exist
- Privileged access reviews are not performed regularly
- No centralized PAM capability

### Recommended Treatment

- Enforce MFA for all privileged accounts
- Implement least-privilege access
- Conduct quarterly privileged-access reviews
- Remove unused permissions
- Implement privileged access management
- Monitor privileged account activity

**Treatment Strategy:** Mitigate

---

## 🛠️ Risk Treatment Options

| Treatment | Description |
|---|---|
| Mitigate | Implement controls to reduce likelihood or impact |
| Avoid | Discontinue the activity creating unacceptable risk |
| Transfer | Transfer part of the exposure through contracts, insurance, or third parties |
| Accept | Formally accept risk within established risk tolerance |

---

## 📦 Project Deliverables

| Deliverable | Purpose |
|---|---|
| Enterprise Risk Register | Central record of identified cybersecurity risks |
| Risk Treatment Plan | Documents remediation actions, owners, and timelines |
| Risk Assessment Report | Documents methodology, findings, and recommendations |
| Executive Risk Summary | Communicates major risks and priorities to leadership |

---

## 🧠 Skills Demonstrated

- Enterprise Cybersecurity Risk Assessment
- Risk Identification & Analysis
- Risk Registers
- Inherent & Residual Risk
- Risk Treatment
- Security Control Assessment
- CIA Triad
- NIST CSF Concepts
- IAM Risk
- Cloud Security Risk
- Third-Party Risk
- Vulnerability Management
- Executive Risk Communication

---

## 🚧 Project Status

**Current Phase:** Risk Register Development

### Next Deliverable

📊 `Enterprise-Risk-Register.xlsx`

---

## ⚠️ Disclaimer

This project is a simulated professional GRC case study created for portfolio purposes.

All organizations, systems, employees, vendors, risks, findings, and evidence are fictional. No confidential employer, client, customer, or proprietary training information is included.
