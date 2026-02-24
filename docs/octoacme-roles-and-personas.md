# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## QA Engineers

### Role Summary
QA Engineers validate that delivered software meets acceptance criteria and quality standards before release. They design and execute test plans, report defects, and work closely with Developers and Product Managers to ensure product quality.

### Key Responsibilities
- Design, execute, and maintain test plans and test cases
- Perform functional, regression, and exploratory testing
- Log, reproduce, and track defects through resolution
- Validate acceptance criteria are met before signoff
- Contribute to CI/CD test automation efforts

### Goals and Success Metrics
- Zero critical defects reaching production
- Test coverage aligned to risk and acceptance criteria
- Reduction in escaped defects over time

### Typical Communication Patterns
- Participate in sprint planning to flag testability concerns
- Provide QA signoff reports before release
- Collaborate with Developers on defect triage

### Interaction with Existing Roles
- **Product Manager**: Clarify acceptance criteria and edge cases
- **Developers**: Coordinate on defect fixes and test environments
- **Project Manager**: Report testing status, blockers, and release readiness

---

## UX Designers

### Role Summary
UX Designers are responsible for designing user interfaces and experiences that are intuitive, accessible, and aligned with customer needs. They bridge the gap between user research and engineering implementation.

### Key Responsibilities
- Design wireframes, prototypes, and high-fidelity mockups
- Conduct usability tests and synthesize user feedback
- Define interaction patterns and UI component standards
- Collaborate with Product Managers on feature requirements
- Partner with Developers to ensure design fidelity in implementation

### Goals and Success Metrics
- High usability scores and task completion rates
- Reduction in user-reported UX issues
- Design assets and specifications delivered before development begins

### Typical Communication Patterns
- Design reviews and critique sessions with Product and Engineering
- Async design handoffs via Figma or equivalent tooling
- Usability test readouts shared with the broader team

### Interaction with Existing Roles
- **Product Manager**: Co-define user stories and validate design decisions against product goals
- **Developers**: Provide detailed specs and answer implementation questions
- **QA Engineers**: Review builds for design fidelity and flag UX regressions
- **Project Manager**: Communicate design timelines and flag design-related risks

---

## Technical Writers

### Role Summary
Technical Writers own the quality and completeness of all user-facing and internal documentation. They work alongside Developers and QA to ensure that guides, release notes, and onboarding materials are clear, accurate, and accessible.

### Key Responsibilities
- Create and maintain user-facing documentation (guides, release notes, onboarding materials)
- Maintain internal documentation such as runbooks and process guides
- Review Developers' and QA's documentation contributions for clarity and accuracy
- Ensure documentation is updated in sync with each release
- Define and enforce documentation standards across teams

### Goals and Success Metrics
- Documentation completeness and accuracy at each release
- Reduction in support tickets attributable to unclear documentation
- Time-to-productivity improvement for new users and team members

### Typical Communication Patterns
- Participate in sprint reviews to capture documentation needs
- Sync with Developers and QA before release cutoffs
- Publish documentation updates alongside release notes

### Interaction with Existing Roles
- **Developers**: Gather technical detail and review accuracy of implementation-facing docs
- **QA Engineers**: Validate documentation against tested behavior
- **Product Manager**: Align docs with user-facing feature descriptions and messaging
- **Project Manager**: Coordinate documentation milestones within the release plan

---

## DevOps Engineers

### Role Summary
DevOps Engineers facilitate CI/CD pipelines, system reliability, and infrastructure operations. They enable development teams to ship software safely and at scale.

### Key Responsibilities
- Build and maintain CI/CD pipelines for automated testing and deployment
- Manage cloud infrastructure, configuration, and monitoring
- Respond to and resolve production incidents
- Drive reliability improvements (SLOs, SLAs, error budgets)
- Partner with Developers and QA on environment provisioning and test automation

### Goals and Success Metrics
- High deployment frequency with low change failure rate
- Mean time to recovery (MTTR) below defined targets
- Infrastructure cost efficiency within budget targets

### Typical Communication Patterns
- On-call rotation and incident response channels
- Weekly infrastructure sync with engineering leads
- Change management communications before major releases

### Interaction with Existing Roles
- **Developers**: Support environment setup, pipeline debugging, and deployment tooling
- **QA Engineers**: Provide stable test environments and test data pipelines
- **Project Manager**: Communicate infrastructure risks and release readiness
- **Product Manager**: Advise on infrastructure implications of roadmap decisions

---

## Support Leads

### Role Summary
Support Leads act as the primary escalation point for user-facing issues, translating customer pain into actionable product and engineering feedback. They ensure that recurring problems surface quickly to the right stakeholders.

### Key Responsibilities
- Triage and manage escalated support tickets from customers
- Identify patterns in recurring issues and report trends to Product and QA
- Maintain the support knowledge base and troubleshooting guides
- Coordinate with Engineering on critical bug fixes affecting customers
- Represent the customer voice in product and planning meetings

### Goals and Success Metrics
- First response and resolution time within SLA targets
- Customer satisfaction (CSAT) scores above defined thresholds
- Reduction in repeat issues through proactive product improvements

### Typical Communication Patterns
- Weekly support summary shared with Product and Engineering
- Escalation pings in dedicated incident/support channels
- Monthly trend reports presented to leadership

### Interaction with Existing Roles
- **Product Manager**: Surface recurring user pain points as input to the roadmap
- **QA Engineers**: Collaborate on reproducing and validating fixes for customer-reported defects
- **Developers**: Coordinate rapid response for critical production issues
- **Project Manager**: Flag support-driven escalations that impact release scope or timelines

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

