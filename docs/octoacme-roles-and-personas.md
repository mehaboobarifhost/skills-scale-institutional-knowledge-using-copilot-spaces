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

## New / Specialized Personas (added to improve clarity and accountability)

### UX Designer
- Role summary: Ensures the product is usable, accessible, and aligned with user needs by conducting research, designing flows, and validating solutions.
- Responsibilities:
  - Conduct user interviews, usability testing, and analyze user research
  - Create wireframes, interaction designs, and low/high-fidelity prototypes
  - Provide design acceptance criteria and UX notes for backlog items
  - Review implementation for fidelity to designs and user experience
- Interaction with existing roles:
  - Product Managers: Partner to validate requirements and success criteria
  - Developers: Provide designs, assets, and acceptance criteria; participate in design/implementation reviews
  - QA: Define usability acceptance tests and validate UX in testing
  - Project Managers: Share timeline impacts for design deliverables

### Scrum Master
- Role summary: Supports the delivery team to follow Agile practices, remove impediments, and improve team effectiveness.
- Responsibilities:
  - Facilitate Agile ceremonies (standups, planning, retrospectives, demos)
  - Help remove blockers and coordinate cross-team impediment resolution
  - Coach the team on Agile practices and continuous improvement
  - Monitor team health metrics and raise concerns early
- Interaction with existing roles:
  - Project Managers: Align on delivery cadence and escalate persistent impediments
  - Developers & QA: Support team self-organization and help unblock work
  - Product Managers: Help ensure backlog items are ready and well-scoped for planning

### Technical Writer
- Role summary: Owns user-facing and developer-facing documentation quality, discoverability, and maintenance.
- Responsibilities:
  - Author and maintain documentation: README, how-tos, runbooks, release notes
  - Establish and enforce documentation templates and style guidelines
  - Coordinate documentation reviews and updates as features change
  - Support onboarding material and knowledge base organization
- Interaction with existing roles:
  - Developers: Collaborate to capture technical details and ensure accuracy
  - Product Managers: Extract product-context for user-facing docs and release notes
  - QA: Verify documentation steps for test plans and runbooks
  - Project Managers: Track documentation tasks in project plans and acceptance criteria

### Release Manager
- Role summary: Coordinates releases across engineering, QA, and stakeholders to ensure predictable, low-risk deployments.
- Responsibilities:
  - Maintain release calendars and coordinate release windows
  - Validate release readiness (acceptance criteria, checklist completion, rollback plans)
  - Author or oversee release notes and stakeholder communications
  - Own post-release verification and incident coordination for release-related issues
- Interaction with existing roles:
  - Developers & QA: Coordinate deployment steps, verify smoke tests and rollbacks
  - Project Managers: Align on release timing and stakeholder notifications
  - Product Managers: Confirm which features are included and messaging for releases

---

## Role Interaction Guidance & RACI highlights
- For key activities we recommend a lightweight RACI to avoid ambiguity. Example:

| Activity | Responsible | Accountable | Consulted | Informed |
|---|---:|---:|---:|---:|
| Define success metrics | Product Manager | Product Lead | PM, UX | Stakeholders |
| Plan sprint scope | Developers | Project Manager | Product Manager, Scrum Master | Stakeholders |
| Author release notes | Technical Writer | Release Manager | Product Manager, Developers | Stakeholders |
| Deploy to production | Release Manager | Engineering Lead | QA, PM | Stakeholders |

Notes:
- "Responsible" is the doer(s); "Accountable" is the single owner who signs off; "Consulted" are subject-matter experts; "Informed" are stakeholders who need updates.

## How to adopt these personas
- Add the appropriate role(s) to the project one-pager and onboarding artifacts when starting a project.
- Use the responsibilities list to set clear acceptance criteria for deliverables tied to each role.
- If a role is not dedicated full-time, assign a named person and document the time commitment.

