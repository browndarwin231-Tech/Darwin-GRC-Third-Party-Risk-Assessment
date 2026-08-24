# Darwin-GRC-Third-Party-Risk-Assessment

Hands-on GRC project evaluating third-party vendor cybersecurity risk using a security questionnaire, risk scoring, control gaps, and remediation recommendations.

# Third-Party Risk Assessment Project

## Project Overview

This project simulates a third-party cybersecurity risk assessment for a fictional vendor called **SecureCloud Solutions**.

The objective is to evaluate the vendor's security posture, identify control weaknesses, assess risk, and recommend remediation actions before the vendor is approved for use.

This project demonstrates practical GRC and Third-Party Risk Management skills including:

- Vendor security questionnaires
- Third-party risk assessment
- Risk scoring
- Control gap analysis
- Vendor due diligence
- Security control review
- Risk register development
- Remediation planning
- Compliance documentation

## Business Scenario

CloudNova Technologies is considering SecureCloud Solutions as a third-party vendor for cloud-based file sharing and collaboration.

Because the vendor may store or process company data, a security review is required before approval.

The assessment focuses on areas such as:

- Access Control
- Multi-Factor Authentication
- Encryption
- Incident Response
- Vulnerability Management
- Business Continuity
- Security Awareness
- Data Protection
- Vendor Management
- Logging and Monitoring

## Vendor Profile

**Vendor Name:** SecureCloud Solutions

**Service:** Cloud File Sharing and Collaboration

**Data Access:** Internal company documents and user account information

**Risk Classification:** High

**Assessment Type:** Initial Vendor Security Review

## Key Findings

The assessment identified several potential risks:

- MFA is not enforced for all administrator accounts
- Incident response testing is not performed regularly
- Penetration testing is conducted inconsistently
- Vendor security awareness training is not formally tracked
- Backup recovery tests are not performed quarterly
- Third-party subcontractor reviews are limited
- Security log retention is shorter than recommended

## Risk Assessment Method

Risk is evaluated using:

Risk Score = Likelihood × Impact

### Risk Ratings

- 1–4 = Low
- 5–10 = Medium
- 11–15 = High
- 16–25 = Critical

## Assessment Areas

| Area | Status | Risk |
|---|---|---|
| Multi-Factor Authentication | Partial | High |
| Encryption at Rest | Implemented | Low |
| Encryption in Transit | Implemented | Low |
| Incident Response Testing | Partial | High |
| Vulnerability Management | Partial | Medium |
| Penetration Testing | Partial | Medium |
| Backup and Recovery | Partial | Medium |
| Security Awareness | Partial | Medium |
| Logging and Monitoring | Partial | Medium |
| Subcontractor Risk Review | Missing | High |

## Risk Summary

| Risk | Likelihood | Impact | Score | Rating |
|---|---:|---:|---:|---|
| Administrator account compromise | 3 | 5 | 15 | High |
| Unprepared incident response | 3 | 5 | 15 | High |
| Subcontractor compromise | 3 | 4 | 12 | High |
| Backup recovery failure | 2 | 5 | 10 | Medium |
| Undetected security event | 2 | 4 | 8 | Medium |

## Vendor Decision

Based on the assessment, SecureCloud Solutions would be classified as:

**Conditionally Approved**

The vendor may proceed only after high-risk issues are addressed or formally accepted by management.

## Recommended Actions

1. Enforce MFA for all administrator accounts
2. Conduct annual incident response tabletop exercises
3. Establish recurring subcontractor security reviews
4. Perform quarterly backup recovery testing
5. Increase security log retention
6. Track employee security awareness training
7. Perform recurring penetration testing
8. Document remediation evidence

## Repository Structure

Darwin-GRC-Third-Party-Risk-Assessment/
│
├── README.md
├── vendor_security_questionnaire.csv
├── vendor_risk_register.csv
├── vendor_gap_assessment.md
├── vendor_remediation_plan.md
└── evidence/

## Skills Demonstrated

- Governance, Risk, and Compliance
- Third-Party Risk Management
- Vendor Risk Assessment
- Vendor Due Diligence
- Security Questionnaires
- Risk Scoring
- Risk Registers
- Control Assessment
- Gap Analysis
- Remediation Planning
- Security Governance
- Compliance Documentation

## Project Goal

The goal of this project is to demonstrate the ability to evaluate third-party cybersecurity risk, identify control weaknesses, prioritize findings, and recommend remediation before approving a vendor for business use.
