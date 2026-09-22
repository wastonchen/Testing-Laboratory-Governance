
# Laboratory Risk Scoring

A risk-based approach for prioritizing risks associated with third-party testing laboratories.

## 1. Risk Scoring Method

Risk priority is assessed using two dimensions:

- **Likelihood** – How likely the risk is to occur.
- **Impact** – The potential consequence if the risk occurs.

The overall risk score is calculated as:

> **Risk Score = Likelihood × Impact**

Each dimension is rated from 1 to 5.

---

## 2. Likelihood Rating

| Score | Likelihood | Description |
|---:|---|---|
| 1 | Rare | Unlikely to occur under normal conditions |
| 2 | Unlikely | Could occur, but not expected frequently |
| 3 | Possible | May occur periodically |
| 4 | Likely | Expected to occur in some circumstances |
| 5 | Almost Certain | Expected to occur frequently or repeatedly |

---

## 3. Impact Rating

| Score | Impact | Description |
|---:|---|---|
| 1 | Minor | Limited operational impact with no significant compliance consequence |
| 2 | Low | Localized impact that can be addressed through normal corrective actions |
| 3 | Moderate | Significant operational or compliance impact requiring management attention |
| 4 | Major | Significant impact to testing reliability, accreditation, compliance, or customer experience |
| 5 | Critical | Potentially severe impact to product safety, certification integrity, regulatory compliance, or business continuity |

---

## 4. Risk Level

The risk score is calculated as:

> **Risk Score = Likelihood × Impact**

| Score | Risk Level | Suggested Response |
|---:|---|---|
| 1–4 | Low | Monitor through normal laboratory governance activities |
| 5–9 | Medium | Define appropriate controls and monitor periodically |
| 10–16 | High | Establish corrective actions and enhanced monitoring |
| 17–25 | Critical | Immediate management attention and escalation |

---

## 5. Risk Matrix

| Likelihood \ Impact | 1 | 2 | 3 | 4 | 5 |
|---|---:|---:|---:|---:|---:|
| **5 Almost Certain** | 5 | 10 | 15 | 20 | 25 |
| **4 Likely** | 4 | 8 | 12 | 16 | 20 |
| **3 Possible** | 3 | 6 | 9 | 12 | 15 |
| **2 Unlikely** | 2 | 4 | 6 | 8 | 10 |
| **1 Rare** | 1 | 2 | 3 | 4 | 5 |

---

## 6. Example Risk Assessment

The following examples demonstrate how laboratory risks can be assessed using the scoring method.

| Risk | Likelihood | Impact | Risk Score | Risk Level |
|---|---:|---:|---:|---|
| Data Integrity | 4 | 5 | 20 | Critical |
| Scope & Accreditation | 3 | 5 | 15 | High |
| Personnel Competency | 3 | 3 | 9 | Medium |
| Safety & Facility | 2 | 5 | 10 | High |
| Technical Misjudgment | 3 | 5 | 15 | High |
| Corrective Action | 4 | 4 | 16 | High |
| Impartiality | 2 | 5 | 10 | High |
| Cybersecurity / IP | 2 | 4 | 8 | Medium |

These values are illustrative and should be reassessed based on laboratory-specific evidence.

---

## 7. Risk-Based Monitoring

Risk scores should be reviewed together with available evidence and laboratory performance information.

Relevant indicators may include:

- Audit findings
- Repeat findings
- Overdue corrective actions
- Accreditation status
- Scope changes
- Personnel competency gaps
- Data integrity concerns
- Testing errors
- Customer complaints
- Safety incidents
- Significant changes in laboratory capability

A change in risk indicators may require the risk score and associated controls to be reassessed.

---

## 8. Risk Response

Depending on the assessed risk and available evidence, possible responses include:

### Low Risk
- Normal monitoring
- Periodic review
- Maintain existing controls

### Medium Risk
- Define additional controls
- Increase monitoring frequency where appropriate
- Track relevant indicators

### High Risk
- Establish corrective actions
- Increase monitoring frequency
- Assign responsible owner
- Escalate significant issues to relevant stakeholders

### Critical Risk
- Immediate assessment
- Management escalation
- Containment or restriction where appropriate
- Defined corrective action and follow-up
- Reassessment before returning to normal monitoring

---

## 9. Risk Review Cycle

The risk assessment should be treated as a continuous governance process:

```text
Risk Identification
        ↓
Risk Assessment
        ↓
Risk Scoring
        ↓
Risk Control
        ↓
Monitoring
        ↓
Corrective Action
        ↓
Risk Reassessment
        ↓
Management Review
```

Risk levels should be updated when new evidence, significant findings, changes in laboratory capability, accreditation status, personnel, or operational conditions indicate that the existing assessment may no longer be appropriate.
