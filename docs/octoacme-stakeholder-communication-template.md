# OctoAcme — Stakeholder Communication Templates

## Purpose
Standardize how teams communicate project status, risks, and incidents to stakeholders. Use the templates below as a starting point and adapt as needed for your project context.

---

## Weekly Status Update

**Cadence:** Every Friday (or as agreed with stakeholders)
**Audience:** Project sponsors, Product leads, dependent teams

```
Subject: [Project Name] Weekly Status — Week of [Date]

**Overall Status:** 🟢 On Track | 🟡 At Risk | 🔴 Off Track

**Progress This Week**
- [Completed item 1]
- [Completed item 2]

**Planned for Next Week**
- [Upcoming item 1]
- [Upcoming item 2]

**Risks & Blockers**
| Risk/Blocker | Impact | Owner | Mitigation |
|---|---|---|---|
| [Description] | High/Med/Low | [Name] | [Action] |

**Decisions Needed**
- [Decision 1 — needed by Date]

**Key Metrics (if applicable)**
- Velocity: [X points]
- Open defects: [N critical, N high]
- Test coverage: [X%]
```

---

## Monthly Executive Summary

**Cadence:** Last business day of each month
**Audience:** Senior leadership, business sponsors

```
Subject: [Project Name] Executive Summary — [Month Year]

**Executive Summary**
[2–3 sentence summary of where the project stands relative to goals and timeline.]

**Key Accomplishments This Month**
- [Milestone or deliverable achieved]
- [Milestone or deliverable achieved]

**Upcoming Milestones (Next 30 Days)**
| Milestone | Target Date | Owner | Status |
|---|---|---|---|
| [Milestone] | [Date] | [Name] | On Track / At Risk |

**Budget & Resource Summary**
- Budget consumed to date: [X%]
- Headcount: [N FTEs / N contractors]
- Notable resource changes: [e.g., engineer joining/leaving]

**Top Risks**
| Risk | Impact | Likelihood | Mitigation Status |
|---|---|---|---|
| [Description] | High/Med/Low | High/Med/Low | [Action taken] |

**Decisions Required from Leadership**
- [Decision — needed by Date]
```

---

## Risk & Blocker Communication

Use this template to communicate an emerging risk or active blocker that requires immediate stakeholder awareness.

**Trigger:** Any risk rated High impact + High likelihood, or any blocker preventing delivery of a milestone.

```
Subject: ⚠️ [Risk/Blocker] — [Project Name]

**Summary**
[One-sentence description of the risk or blocker.]

**Impact**
[Describe what is affected: timeline, scope, quality, cost, teams.]

**Current Status**
[What is happening right now and what has been tried.]

**Owner**
[Name of the person leading the resolution.]

**Proposed Mitigation / Next Steps**
1. [Action 1] — Owner: [Name] — Due: [Date]
2. [Action 2] — Owner: [Name] — Due: [Date]

**Decision Needed**
[Clearly state what you need from the stakeholder — a decision, resource, approval, etc.]

**Expected Resolution Date**
[Date or "TBD — update by Date"]
```

---

## Escalation Notification

Use when a risk or blocker has not been resolved at the team or PM level and requires senior leadership involvement.

```
Subject: 🚨 Escalation — [Issue Title] — [Project Name]

**Escalation Level:** [Team → PM → Product Lead → Sponsor]

**Escalated By:** [Name, Role]
**Escalated To:** [Name, Role]
**Date:** [Date]

**Issue Summary**
[Clear, concise description of the issue and why it is being escalated.]

**Timeline of Events**
- [Date]: Issue identified
- [Date]: First mitigation attempted
- [Date]: Escalation to [next level]

**Business Impact**
[Describe the consequence of not resolving: delayed release, customer impact, cost, etc.]

**Options Considered**
| Option | Pros | Cons |
|---|---|---|
| [Option A] | [Pro] | [Con] |
| [Option B] | [Pro] | [Con] |

**Recommended Path Forward**
[State the recommended option and why.]

**Decision Needed by:** [Date]
```

---

## Post-Incident Communication

Use after a production incident to communicate resolution and next steps to affected stakeholders.

**Timing:**
- Initial notification: within 15 minutes of incident detection
- Resolution notification: within 1 hour of resolution
- Post-incident summary: within 3 business days

### Initial Incident Notification

```
Subject: 🔴 [INCIDENT] [Brief description] — [Service/Product]

**Status:** Investigating | Identified | Monitoring | Resolved

**Summary**
[What is impacted and what symptoms are observed.]

**Impact**
- Affected users/systems: [description]
- Start time: [Time + Timezone]
- Current status: [Investigating / Mitigation in progress]

**Next Update:** [Time]
**Incident Commander:** [Name]
**Communication Channel:** [Link to incident channel]
```

### Resolution Notification

```
Subject: ✅ [RESOLVED] [Brief description] — [Service/Product]

**Status:** Resolved

**Summary**
[What happened and how it was resolved.]

**Timeline**
- [Time]: Issue detected
- [Time]: Cause identified
- [Time]: Mitigation applied
- [Time]: Full service restored

**Root Cause (Preliminary)**
[Brief root cause if known; "Under investigation" if not yet confirmed.]

**Next Steps**
- Post-incident review scheduled: [Date]
- Short-term preventive actions: [List]

**Incident Commander:** [Name]
```

### Post-Incident Summary (Blameless Retrospective)

```
Subject: Post-Incident Summary — [Incident Title] — [Date]

**Incident Overview**
- Date/Time: [Start] to [End]
- Duration: [X hours Y minutes]
- Severity: P1 / P2 / P3
- Services affected: [List]
- Users impacted: [N users / X% of traffic]

**Root Cause**
[Detailed description of the root cause.]

**Contributing Factors**
- [Factor 1]
- [Factor 2]

**What Went Well**
- [Item]

**What Could Be Improved**
- [Item]

**Action Items**
| Action | Owner | Due Date | Status |
|---|---|---|---|
| [Action] | [Name] | [Date] | Open / In Progress / Done |
```
