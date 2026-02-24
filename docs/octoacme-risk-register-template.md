# OctoAcme — Risk Register Template

## Purpose
Provide a concrete, copy-paste-ready template for tracking project risks. Maintaining an up-to-date risk register helps teams identify, assess, and mitigate risks before they become blockers.

---

## Column Definitions

| Column | Data Type | Description |
|--------|-----------|-------------|
| **ID** | Text (e.g., RISK-001) | Unique identifier for the risk |
| **Category** | Enum: Technical / Resource / Schedule / Scope / External | The area the risk belongs to |
| **Description** | Text | Clear description of what could go wrong |
| **Impact** | Enum: High / Medium / Low | The severity of the outcome if the risk materializes |
| **Likelihood** | Enum: High / Medium / Low | The probability the risk will occur |
| **Priority Score** | Number (see scoring below) | Calculated priority to guide focus |
| **Owner** | Name | The person responsible for monitoring and mitigating this risk |
| **Mitigation Plan** | Text | Actions taken or planned to reduce impact or likelihood |
| **Contingency Plan** | Text | Fallback action if the risk materializes |
| **Status** | Enum: Open / Monitoring / Mitigated / Closed | Current state of the risk |
| **Last Reviewed** | Date | Date of the most recent review |

---

## Priority / Severity Scoring

Use the matrix below to calculate a **Priority Score** (1–9) for each risk.

|  | **Low Impact** | **Medium Impact** | **High Impact** |
|--|---------------|-------------------|-----------------|
| **High Likelihood** | 3 | 6 | 9 |
| **Medium Likelihood** | 2 | 4 | 6 |
| **Low Likelihood** | 1 | 2 | 3 |

**Score Thresholds:**
- **7–9 (Critical):** Immediate action required; escalate to Project Sponsor
- **4–6 (High):** Active mitigation plan required; review weekly
- **2–3 (Medium):** Monitor closely; update monthly
- **1 (Low):** Log and revisit quarterly

---

## Risk Register Table

Copy and populate this table for your project:

| ID | Category | Description | Impact | Likelihood | Priority Score | Owner | Mitigation Plan | Contingency Plan | Status | Last Reviewed |
|----|----------|-------------|--------|------------|----------------|-------|-----------------|-----------------|--------|---------------|
| RISK-001 | | | | | | | | | Open | |
| RISK-002 | | | | | | | | | Open | |
| RISK-003 | | | | | | | | | Open | |

---

## Example Entries

| ID | Category | Description | Impact | Likelihood | Priority Score | Owner | Mitigation Plan | Contingency Plan | Status | Last Reviewed |
|----|----------|-------------|--------|------------|----------------|-------|-----------------|-----------------|--------|---------------|
| RISK-001 | Technical | Third-party payment API may not support the new multi-currency feature in time for launch | High | Medium | 6 | Jane D. | Engage vendor early; test beta API by Sprint 4; identify fallback provider | Launch without multi-currency; scope to single-currency MVP | Monitoring | 2025-03-10 |
| RISK-002 | Resource | Key backend engineer may leave mid-project; no documented knowledge transfer | High | Low | 3 | Alex M. | Begin pair programming and documentation; cross-train a second engineer | Engage contract engineer from approved vendor list | Open | 2025-03-10 |
| RISK-003 | Schedule | Design delivery delayed, blocking frontend implementation | Medium | High | 6 | Sam K. | UX designer pulled in earlier; daily check-in with design team | Implement with placeholder UI; deliver design-polished version in follow-up sprint | Mitigated | 2025-03-10 |
| RISK-004 | External | Regulatory approval for data processing may be delayed beyond Q2 | High | Medium | 6 | Chris L. | Legal review started; submitted compliance documentation in advance | Delay feature release; implement behind feature flag until approved | Open | 2025-03-10 |
| RISK-005 | Scope | Stakeholder requests for additional features may expand scope mid-sprint | Medium | High | 6 | Taylor R. | Strict change control process; all scope changes require PM + sponsor approval | Defer additions to next release; maintain a backlog of requested enhancements | Monitoring | 2025-03-10 |

---

## Review Cadence

| Frequency | Activity |
|-----------|----------|
| **Weekly** | Review all Critical (7–9) and High (4–6) risks in the team sync |
| **Bi-weekly** | Review Medium (2–3) risks and update status |
| **Monthly** | Full register review — close resolved risks, add newly identified risks |
| **At each milestone** | Review risk register as part of milestone sign-off |
| **At project close** | Archive register and capture lessons learned for future projects |

---

## Guidance Notes

- **New risks** can be identified by anyone on the team at any time — use the team's risk channel or raise in the next standup.
- **Risk owners** are responsible for updating their risks before each weekly sync.
- A risk that materializes and is actively impacting the project should be converted into an **active blocker** and escalated per the escalation path in `octoacme-risks-and-communication.md`.
- Keep descriptions **specific and actionable** — avoid vague entries like "project may be late."
