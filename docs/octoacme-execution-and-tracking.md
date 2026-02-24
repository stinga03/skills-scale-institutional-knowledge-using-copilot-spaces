# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies
- Weekly delivery sync — show progress, updates, and flagged risks
- Demo/Review at the end of each sprint or milestone

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)

## Quality & Testing

### QA Roles and Responsibilities in the Execution Flow
- QA Engineers are involved from the **Ready** stage — reviewing acceptance criteria before development begins.
- During **In Review**, QA validates that the PR meets testability standards and that unit/integration tests are present.
- In the **QA** stage, QA Engineers execute functional, regression, and exploratory tests against the acceptance criteria.
- QA provides a formal **signoff** before any item moves to **Done** or is included in a release.

### Handoff Criteria Between Stages

| From → To | Criteria Required |
|-----------|-------------------|
| Ready → In Progress | Acceptance criteria reviewed and testable; design assets available |
| In Progress → In Review | PR submitted with linked issue, passing CI, and updated tests |
| In Review → QA | At least one code review approval; automated checks green |
| QA → Done | All acceptance criteria validated; no open critical/high defects |

### Definition of Done (DoD) Example
An item is considered **Done** when:
- All acceptance criteria are met and verified by QA
- Code is merged to the main branch and CI is green
- Unit and integration tests are written and passing
- Documentation is updated (if applicable)
- No critical or high-severity defects remain open
- Feature is deployed to staging and smoke-tested

### Automated vs. Manual Testing Decision Matrix

| Scenario | Recommended Approach |
|----------|----------------------|
| New business logic / algorithms | Automated unit tests |
| API contracts and integrations | Automated integration tests |
| Critical user flows (login, checkout) | Automated end-to-end tests |
| New UI features / visual design | Manual QA + exploratory testing |
| Edge cases and error paths | Manual exploratory testing |
| Regression of stable features | Automated regression suite |
| Accessibility and usability | Manual testing + automated linting tools |

- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- Level 1: Team-level triage in daily standup
- Level 2: PM escalates to Product Lead and dependent teams
- Level 3: Sponsor-level escalation for business-impacting issues

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly
