# OctoAcme — Project Planning

## Purpose
Turn an approved initiative into an actionable plan and backlog for delivery.

## Objectives
- Break work into shippable increments
- Identify dependencies and risks
- Align timelines, releases, and responsibilities

## Activities
1. Kickoff meeting with stakeholders and delivery team
2. Create prioritized backlog with acceptance criteria
3. Estimate scope (T-shirt sizing or story points)
4. Define Definition of Done (DoD)
5. Identify dependencies and integration points
6. Create release plan and milestone map

## Backlog Item Template
- Title:
- Description:
- Acceptance criteria:
- Priority:
- Estimate:
- Owner:
- Related docs/links:

### Acceptance Criteria Examples
Well-formed acceptance criteria follow the **Given / When / Then** pattern:

- **Given** a logged-in user on the dashboard, **When** they click "Export Report", **Then** a CSV file containing the current filtered data is downloaded within 3 seconds.
- **Given** a new user registering, **When** they submit the form with a duplicate email, **Then** an inline error message reads "An account with this email already exists" and the form is not submitted.
- **Given** an admin user, **When** they deactivate another user's account, **Then** that user is immediately logged out and cannot log back in until reactivated.

Acceptance criteria should be:
- **Specific** — avoid vague language like "works correctly" or "is fast"
- **Testable** — QA should be able to write a test case directly from each criterion
- **Complete** — cover happy paths, error paths, and edge cases

## Sprint / Iteration Planning
- Timebox planning to agreed sprint length
- Pull items that meet DoD and have clear acceptance criteria
- Ensure team capacity is respected

## Risk & Dependency Management
- Capture in Risk Register:
  - ID, Description, Impact, Probability, Owner, Mitigation
- Mark cross-team dependencies in the project board and escalate during weekly syncs

### Dependency Mapping Template

Use this template to document cross-team and external dependencies:

| Dependency ID | Description | Depends On (Team/System) | Owner | Required By | Status | Notes |
|--------------|-------------|--------------------------|-------|-------------|--------|-------|
| DEP-001 | Auth service API contract | Platform Team | Jane D. | Sprint 3 | In Progress | Contract under review |
| DEP-002 | Design system component update | UX Team | Alex M. | Sprint 2 | Blocked | Awaiting design review sign-off |

- Review dependency table in every weekly sync
- Flag any dependency at risk of missing its "Required By" date immediately to the Project Manager
- Escalate unresolved cross-team dependencies to the relevant team leads within 48 hours of identification

## Planning Checklist
- [ ] Project kickoff held
- [ ] Backlog prioritized and estimated
- [ ] Release timeline and milestones agreed
- [ ] Definition of Done documented
- [ ] Initial test plan / QA approach drafted

## Cross-Functional Review Checklist

Before moving from planning to execution, confirm the following with all involved functions:

### Product & Design
- [ ] Acceptance criteria reviewed and approved by Product Manager
- [ ] UX designs finalized and handed off to Engineering
- [ ] Edge cases and error states designed and documented

### Engineering & QA
- [ ] Technical approach reviewed and approved in design doc or ADR
- [ ] Definition of Done agreed and documented
- [ ] Test plan drafted and shared with QA
- [ ] Automation strategy defined (which tests will be automated vs. manual)

### DevOps & Infrastructure
- [ ] Environment requirements identified and provisioned
- [ ] CI/CD pipeline changes scoped if needed
- [ ] Feature flags or release toggles planned if applicable

### Documentation & Support
- [ ] Documentation scope identified and assigned to Technical Writer
- [ ] Support team briefed on upcoming changes and potential user impact
- [ ] Release notes draft started

### Stakeholders
- [ ] Stakeholder communication plan agreed (who gets notified, when, how)
- [ ] Go/no-go criteria defined for release
- [ ] Rollback plan documented and reviewed
