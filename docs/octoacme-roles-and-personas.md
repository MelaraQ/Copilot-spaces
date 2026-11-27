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

## Business Analysts / Requirements Leads

### Role Summary
Business Analysts and Requirements Leads clarify stakeholder needs and turn them into testable requirements. They maintain traceability between the problem, proposed solution, acceptance criteria, and delivered outcomes.

### Responsibilities
- Facilitate requirements discovery and stakeholder interviews
- Define and document current-state and future-state processes
- Develop user stories, acceptance criteria, dependencies, and requirements traceability
- Clarify ambiguities and resolve requirement conflicts
- Validate that delivered work addresses the stated need

### Goals
- Increase requirement completeness and clarity
- Reduce rework caused by misunderstanding
- Ensure solutions remain traceable to measurable outcomes

### Interactions with Existing Roles
- Partner with Product Managers to refine problem statements and prioritize scope.
- Work with Project Managers to identify dependencies and requirements risks.
- Collaborate with Developers and QA on feasibility, acceptance criteria, and test coverage.
- Engage stakeholders to confirm needs and validate proposed outcomes.

### Typical Communication
- Requirements workshops and backlog refinement
- Scope, requirement, and decision reviews
- Traceability updates and stakeholder demos

---

## UX / Design Leads

### Role Summary
UX and Design Leads own the user-centered design direction, ensuring the product is usable, accessible, and consistent.

### Responsibilities
- Lead or facilitate user research and usability testing
- Create and maintain interaction models, prototypes, and design specifications
- Define accessibility requirements and interaction standards
- Validate implemented experiences against the approved design
- Identify user-experience risks and propose mitigations

### Goals
- Improve usability and customer value
- Reduce usability defects and design rework
- Create consistent and accessible experiences

### Interactions with Existing Roles
- Partner with Product Managers to translate customer outcomes into usable designs.
- Collaborate with Developers on implementation feasibility and design-system reuse.
- Work with QA on accessibility and usability acceptance criteria.
- Provide Project Managers with design dependencies and review needs.
- Incorporate stakeholder and user feedback into design decisions.

### Typical Communication
- Design reviews and usability sessions
- Prototypes, annotated designs, and acceptance walkthroughs
- Regular backlog and implementation collaboration

---

## Engineering Leads / Tech Leads

### Role Summary
Engineering Leads and Tech Leads provide technical direction and ensure that solutions are maintainable, observable, secure, and aligned with the delivery plan.

### Responsibilities
- Establish architecture and implementation standards
- Guide technical design and cross-team technical dependencies
- Support scope estimation and identify technical risks
- Facilitate code and design reviews
- Coach Developers on quality, testing, and operational readiness

### Goals
- Deliver sustainable, reliable technical solutions
- Reduce architectural and delivery risks
- Improve engineering quality and technical consistency

### Interactions with Existing Roles
- Partner with Developers on implementation and technical reviews.
- Work with Product Managers to explain technical trade-offs and sequencing.
- Collaborate with Project Managers on technical dependencies and timelines.
- Coordinate with UX, Security, Release/Operations, and QA where responsibilities overlap.
- Ensure stakeholder decisions are reflected in the technical plan.

### Typical Communication
- Technical design and architecture reviews
- Engineering estimation and risk discussions
- Code-review and delivery syncs

---

## Security Leads

### Role Summary
Security Leads define and coordinate security requirements, assess delivery risks, and ensure appropriate controls are included throughout the project lifecycle.

### Responsibilities
- Identify application, infrastructure, data, and compliance risks
- Define security acceptance criteria and control requirements
- Review threat models and security assessments
- Coordinate security testing and remediation
- Support incident readiness and security escalation

### Goals
- Prevent avoidable security vulnerabilities
- Improve the organization's security posture
- Enable clear and timely security decisions

### Interactions with Existing Roles
- Work with Engineering Leads and Developers on secure design and remediation.
- Partner with QA on security testing and acceptance evidence.
- Advise Project Managers on security risks, gates, and dependencies.
- Collaborate with Product Managers on risk-based prioritization.
- Coordinate with Release/Operations Leads and on-call teams on incidents or deployment controls.
- Communicate material risks to stakeholders through the established escalation path.

### Typical Communication
- Threat and risk reviews
- Security findings and remediation tracking
- Release security gates and incident escalations

---

## Release / Operations Leads

### Role Summary
Release and Operations Leads coordinate operational readiness and the safe delivery of releases. They provide a clear bridge between implementation and production operations.

### Responsibilities
- Define release windows and deployment coordination
- Maintain rollback and contingency plans
- Coordinate staging validation and post-deployment verification
- Monitor operational readiness and service health
- Coordinate incident response and operational handoffs

### Goals
- Deliver reliable releases with limited disruption
- Improve observability and rollback readiness
- Accelerate recovery from operational incidents

### Interactions with Existing Roles
- Coordinate with Developers and Engineering Leads on release artifacts and runbooks.
- Work with QA on smoke tests and acceptance evidence.
- Partner with Project Managers on schedules, communications, and go/no-go decisions.
- Support Product Managers with release scope and customer-impact information.
- Coordinate with Security Leads on controls and incident response.
- Provide operational updates to stakeholders and Support Leads.

### Typical Communication
- Release planning and readiness reviews
- Deployment checklists and post-release verification
- Incident updates and operational reporting

---

## Support Leads

### Role Summary
Support Leads represent customer support and service-readiness perspectives. They ensure that support teams understand changes and can resolve customer issues after release.

### Responsibilities
- Define support readiness and documentation requirements
- Prepare FAQs, known-issue lists, and escalation guidance
- Identify likely customer impacts and support capacity needs
- Triage customer-impacting issues and coordinate handoffs
- Share post-release feedback and recurring issue patterns

### Goals
- Reduce customer disruption and support resolution time
- Improve service readiness for releases
- Connect customer feedback to product improvement

### Interactions with Existing Roles
- Partner with Product Managers on customer impact and prioritization.
- Work with Developers and Engineering Leads on known limitations and troubleshooting.
- Coordinate with Release/Operations Leads on release timing and incident communications.
- Collaborate with QA on acceptance scenarios and support validation.
- Provide Project Managers with support readiness risks and stakeholder updates.
- Incorporate stakeholder feedback into recurring backlog and planning discussions.

### Typical Communication
- Support readiness reviews
- Release announcements and known-issue updates
- Incident triage and customer-impact reporting

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

