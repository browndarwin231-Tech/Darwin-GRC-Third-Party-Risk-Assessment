# Vendor Gap Assessment

## Executive Summary

This assessment evaluates the cybersecurity posture of the fictional vendor **SecureCloud Solutions**.

The review was performed as part of a third-party risk management process before approving the vendor for business use.

The assessment identified several security gaps involving administrator access, incident response testing, vulnerability remediation, subcontractor oversight, backup recovery testing, security awareness tracking, and log retention.

The highest-priority issues involve missing MFA for administrator accounts, untested incident response procedures, and insufficient subcontractor risk management.

---

## Assessment Scope

The vendor was evaluated across the following security domains:

- Identity and Access Management
- Encryption
- Incident Response
- Vulnerability Management
- Penetration Testing
- Logging and Monitoring
- Backup and Recovery
- Security Awareness
- Third-Party Risk Management
- Business Continuity
- Data Protection

---

## Finding 1: Administrator MFA

### Current State

Multi-factor authentication is not enforced for all administrator accounts.

### Risk

A compromised administrator account could provide an attacker with elevated access to critical systems and customer data.

### Risk Level

**High**

### Gap

Privileged accounts are not consistently protected by MFA.

### Recommendation

Require MFA for all administrator and privileged accounts.

The vendor should also periodically review MFA enrollment and document any approved exceptions.

---

## Finding 2: Incident Response Testing

### Current State

The vendor maintains a documented incident response plan.

However, the plan is not tested consistently.

### Risk

Employees may not be prepared to respond effectively during a real cybersecurity incident.

### Risk Level

**High**

### Gap

The incident response plan exists but has not been validated through regular exercises.

### Recommendation

Conduct an incident response tabletop exercise at least annually.

The exercise should document:

- Participants
- Incident scenario
- Response actions
- Escalation procedures
- Communication decisions
- Lessons learned
- Corrective actions

---

## Finding 3: Subcontractor Risk Management

### Current State

SecureCloud Solutions uses subcontractors but does not maintain a consistent process for evaluating their cybersecurity risk.

### Risk

A compromised subcontractor may expose systems, services, or sensitive customer data.

### Risk Level

**High**

### Gap

Subcontractors are not consistently assessed before receiving access to systems or data.

### Recommendation

Implement a formal subcontractor risk management process.

The process should include:

- Security questionnaires
- Risk classification
- Data-access review
- Contract security requirements
- Security documentation review
- Annual reassessment for high-risk subcontractors

---

## Finding 4: Vulnerability Remediation

### Current State

The vendor performs vulnerability scanning.

However, remediation timelines are not consistently documented or enforced.

### Risk

Critical vulnerabilities may remain unresolved longer than acceptable.

### Risk Level

**High**

### Gap

The vendor lacks clearly documented remediation service-level targets based on vulnerability severity.

### Recommendation

Establish vulnerability remediation SLAs.

Example targets:

- Critical: 7 days
- High: 30 days
- Medium: 60 days
- Low: 90 days

Exceptions should require documented risk acceptance.

---

## Finding 5: Backup Recovery Testing

### Current State

The vendor performs regular backups.

Backup restoration testing is not performed consistently.

### Risk

Backups may fail during ransomware, system failure, or disaster recovery.

### Risk Level

**Medium**

### Gap

There is no consistently documented quarterly restoration-testing process.

### Recommendation

Conduct quarterly restoration testing for critical systems.

Document:

- System tested
- Backup date
- Restoration date
- Recovery result
- Recovery time
- Problems identified
- Corrective actions

---

## Finding 6: Security Log Retention

### Current State

Security logs are centrally collected and monitored.

The vendor retains some security logs for less than 12 months.

### Risk

Historical evidence may not be available during investigations, audits, or compliance reviews.

### Risk Level

**Medium**

### Gap

Security-log retention is shorter than the organization's recommended retention period.

### Recommendation

Increase security-log retention to at least 12 months where technically and legally appropriate.

Retention requirements should be documented in policy.

---

## Finding 7: Security Awareness Tracking

### Current State

Employees receive security awareness training.

Training completion is not consistently tracked.

### Risk

The vendor may be unable to demonstrate that all employees have completed required security training.

### Risk Level

**Medium**

### Gap

Training exists, but evidence of completion is incomplete.

### Recommendation

Use centralized tracking for security awareness training.

Track:

- Employee name
- Training assigned
- Completion date
- Completion status
- Phishing simulation results
- Required follow-up training

---

## Finding 8: Penetration Testing

### Current State

Penetration testing is performed, but not on a consistent annual schedule.

### Risk

Security weaknesses may remain unidentified between assessments.

### Risk Level

**Medium**

### Gap

There is no formal requirement for recurring independent penetration testing.

### Recommendation

Perform independent penetration testing at least annually and after significant infrastructure changes.

High-risk findings should be tracked through remediation.

---

## Overall Risk Summary

| Finding | Risk Level | Priority |
|---|---|---|
| Administrator MFA | High | Immediate |
| Incident Response Testing | High | Immediate |
| Subcontractor Risk Management | High | High |
| Vulnerability Remediation | High | High |
| Backup Recovery Testing | Medium | Medium |
| Security Log Retention | Medium | Medium |
| Security Awareness Tracking | Medium | Medium |
| Penetration Testing | Medium | Medium |

---

## Vendor Assessment Decision

Based on the identified gaps, SecureCloud Solutions is classified as:

**Conditionally Approved**

The vendor may proceed if high-risk findings are remediated within agreed timelines or formally accepted by appropriate management.

---

## Conclusion

SecureCloud Solutions has several foundational cybersecurity controls in place, including encryption, centralized logging, vulnerability scanning, backups, access reviews, and security awareness training.

However, the assessment identified significant weaknesses in privileged-access protection, incident response testing, subcontractor oversight, and vulnerability remediation.

These findings should be tracked through remediation before the vendor receives full approval.
