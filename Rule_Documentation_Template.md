# Transaction Monitoring Rule Documentation Template

## Rule Information

| Field            | Description                             |
| ---------------- | --------------------------------------- |
| Rule ID          | Unique identifier                       |
| Rule Name        | Name of monitoring rule                 |
| Risk Category    | AML/CTF/Fraud/Corruption/Sanctions      |
| Rule Owner       | Business owner responsible for the rule |
| Rule Developer   | Person or team that developed the rule  |
| Version          | Current version number                  |
| Date Implemented | Initial implementation date             |
| Last Review Date | Most recent review date                 |
| Rule Status      | Active / Inactive / Retired             |

---

## Business Rationale

### Purpose

Describe the financial crime risk or typology being addressed.

### Regulatory Drivers

List applicable:

* AML regulations
* Regulatory guidance
* FATF recommendations
* Internal policies

---

## Risk Assessment

### Inherent Risk

Describe:

* Customer risk
* Product risk
* Geographic risk
* Delivery channel risk

### Residual Risk

Document remaining risk after implementation.

---

## Detection Scenario

### Typology

Examples:

* Structuring
* Layering
* Mule Accounts
* Public Funds Diversion
* Insider Abuse
* Corruption
* PEP Activity

### Detection Objective

State what suspicious behavior the rule seeks to identify.

---

## Rule Logic

### Detection Logic

Document the exact rule logic.

Example:

```text
Customer withdraws ≥ 80% of incoming funds within 3 days of receipt.
```

### Data Sources

Identify source systems used.

Examples:

* Core Banking System
* Mobile Banking Platform
* Customer Information File (CIF)
* Transaction Monitoring System

### Customer Scope

Applicable segments:

* Retail
* SME
* Corporate
* Public Sector
* High Net Worth

---

## Threshold Design

### Current Threshold

Document approved threshold values.

| Parameter          | Value           |
| ------------------ | --------------- |
| Transaction Amount | KES 1,000,000   |
| Observation Period | 7 Days          |
| Alert Trigger      | 80% Utilization |

### Threshold Rationale

Explain why thresholds were selected.

---

## Alert Generation

### Expected Alert Volume

Estimate expected monthly alerts.

### Alert Priority

Select:

* Low
* Medium
* High
* Critical

### Escalation Criteria

Document escalation requirements.

---

## Back-Testing Results

### Testing Period

Document period tested.

### Results

| Metric           | Result |
| ---------------- | ------ |
| Alerts Generated |        |
| True Positives   |        |
| False Positives  |        |
| Precision Rate   |        |
| Recall Rate      |        |

### Conclusion

Document whether the rule performed as expected.

---

## Validation

### Validation Date

### Validation Performed By

### Validation Findings

Document:

* Logic accuracy
* Data quality review
* Threshold assessment
* Performance assessment

### Validation Outcome

* Approved
* Approved with Conditions
* Rejected

---

## Change History

| Version | Date | Change Description | Approved By |
| ------- | ---- | ------------------ | ----------- |
| 1.0     |      | Initial Release    |             |

---

## Approvals

| Role                 | Name | Date |
| -------------------- | ---- | ---- |
| Rule Owner           |      |      |
| AML Compliance       |      |      |
| Technology Team      |      |      |
| Governance Committee |      |      |

---

## Review Schedule

| Review Type        | Frequency |
| ------------------ | --------- |
| Threshold Review   | Quarterly |
| Performance Review | Monthly   |
| Validation Review  | Annual    |

---

## Supporting Documents

Reference:

* Rule Inventory
* Back-Testing Report
* Validation Report
* Change Request Forms
* Governance Committee Minutes

