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

## New / Additional Personas (Added)

These personas were added to reduce role ambiguity, speed onboarding, and clarify escalation and handoffs.

### Delivery Lead
- Responsibilities: Owns day-to-day delivery cadence, coordinates across squads, manages sprint commitments, tracks blockers and ensures timely escalation.
- Decision authority: Prioritizes work within a sprint and approves changes to sprint scope in collaboration with the PM.
- Interactions: Works with the Product Manager (PM) for priorities, with the Technical Lead for trade-offs, and with QA to ensure acceptance criteria are testable.
- Typical handoffs: Receives prioritized backlog from PM, hands off acceptance criteria to QA, escalates unresolved blockers to PM or Project Manager.

### Technical Lead
- Responsibilities: Sets architecture and design approaches, mentors developers, reviews complex PRs, ensures technical quality and maintainability.
- Decision authority: Makes technical design decisions within agreed constraints and can approve technical exceptions.
- Interactions: Works with Developers on implementation details, with Delivery Lead to align scope and schedule, and with PM on feasibility and risk.
- Typical handoffs: Provides technical design docs to developers, hands off deployment plans to Release Lead.

### Support Lead / On-call Engineer
- Responsibilities: First responder for incidents, maintains runbooks and playbooks, coordinates post-incident reviews, and identifies fixes or mitigations.
- Decision authority: Initiates incident response and triage; coordinates rollbacks when required in consultation with Release Lead.
- Interactions: Notifies PM/Project Manager for customer-impacting incidents, works with Developers for fixes, and escalates to Security when necessary.
- Typical handoffs: Escalates incident summaries to stakeholders and hands off root cause analysis outputs to the team.

### Data Analyst / Observability Owner
- Responsibilities: Define success metrics, build and maintain dashboards, analyze release and incident impact, and recommend measurement approaches.
- Decision authority: Defines what instrumentation and metrics to track for release validation (in collaboration with PM and Tech Lead).
- Interactions: Collaborates with PM to set metrics and targets, with Developers to implement instrumentation, and with Release Lead to validate rollouts.
- Typical handoffs: Provides dashboards and post-release analysis to PM and stakeholders.

### Release Lead
- Responsibilities: Coordinates release activities, verifies pre-release checklists, owns rollback plans and deployment communications.
- Decision authority: Authorizes production deployment windows and initiates rollback when post-release checks fail.
- Interactions: Works with Delivery Lead, QA, and Support Lead during deployments; collaborates with Technical Lead to ensure release readiness.
- Typical handoffs: Posts release summaries, notifies stakeholders, and updates release notes.

### UX/Design Representative (when applicable)
- Responsibilities: Ensure product changes meet usability and accessibility goals, provide design assets and acceptance criteria.
- Interactions: Works with PM to align on user needs and with Developers to clarify design details.

---

## How to use these persona entries
- Each project should indicate which personas are assigned and who the named owners are in the project README.
- For cross-functional handoffs, include the flow (who notifies whom, and typical SLAs) in the relevant docs or runbooks.
- Keep the persona list lean; add personas only when they provide clear ownership or change the decision path.
