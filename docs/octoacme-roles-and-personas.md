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

## Technical Lead

### Role Summary
Technical Leads guide architecture, implementation quality, and technical decision-making across the project. They ensure the team builds a solution that is sustainable, secure, and aligned with product priorities.

### Responsibilities
- Define technical direction and design constraints for the project
- Lead architecture and implementation reviews for high-risk work
- Coach developers on patterns, standards, and trade-offs
- Identify technical risks, dependency issues, and mitigation strategies
- Align engineering execution with product goals and delivery timelines

### Goals
- Improve engineering consistency and maintainability
- Reduce technical debt and implementation risk
- Ensure the solution can scale and evolve with user needs

### Typical Communication
- Architecture discussions and design reviews
- Engineering planning and risk assessment sessions
- Cross-functional trade-off conversations with PM and Product Manager

### Interaction with Existing Roles
- Works closely with Developers to define solutions and review implementation quality
- Advises Product Managers and Project Managers on feasibility, estimates, and delivery risks
- Supports QA by clarifying acceptance criteria for technical edge cases and operational readiness

---

## Delivery Lead / Scrum Master

### Role Summary
Delivery Leads help the team operate effectively by facilitating planning, removing blockers, and improving delivery flow. They maintain momentum and help teams focus on the work that matters most.

### Responsibilities
- Facilitate sprint planning, standups, reviews, and retrospectives
- Remove or escalate blockers that slow delivery
- Track team throughput, dependencies, and delivery risks
- Support healthy team rituals and continuous improvement
- Coordinate cross-team dependencies and sequencing of work

### Goals
- Keep delivery predictable and transparent
- Improve team focus and throughput
- Reduce friction and unplanned work across the project

### Typical Communication
- Daily standups and sprint ceremonies
- Dependency tracking and blocker review
- Weekly progress and delivery health updates with PM and stakeholders

### Interaction with Existing Roles
- Partners with Project Managers to align milestones, risk tracking, and planning cadence
- Supports Developers by removing impediments and maintaining flow
- Shares delivery health with Product Managers so prioritization and commitments stay realistic

---

## UX Researcher / Designer

### Role Summary
UX Researchers and Designers ensure the product is easy to use, meets user needs, and delivers value through clear and effective experiences.

### Responsibilities
- Conduct user research and synthesize insights into product opportunities
- Create flows, wireframes, prototypes, and design specs
- Define usability and accessibility expectations
- Partner with product and engineering to validate design feasibility
- Ensure the customer experience matches the intended goals and success metrics

### Goals
- Improve usability, accessibility, and customer satisfaction
- Align product experience with business goals and user needs
- Reduce rework caused by unclear or unvalidated design assumptions

### Typical Communication
- Research findings, user interviews, and prototype reviews
- Design critiques and feedback loops with product and engineering
- Acceptance discussions tied to user value and usability

### Interaction with Existing Roles
- Works with Product Managers to validate problem statements and prioritize user needs
- Provides design artifacts and UX acceptance criteria to Developers and QA
- Coordinates with Project Managers to ensure design milestones and dependencies are planned

---

## Release Engineer / DevOps

### Role Summary
Release Engineers and DevOps specialists maintain the delivery pipeline, deployment process, and operational readiness needed for successful releases.

### Responsibilities
- Manage CI/CD pipelines, deployment automation, and release calendars
- Support staging, production readiness, and rollback planning
- Monitor service health, logs, and environment consistency
- Ensure release runbooks, observability, and restore procedures are current
- Coordinate deployment windows with PMs and stakeholders

### Goals
- Reduce release risk and deployment failures
- Keep environments consistent and recoverable
- Improve operational visibility and release confidence

### Typical Communication
- Release readiness reviews and deployment checklists
- Post-release verification and incident communication
- Coordination with engineering and support teams during launch windows

### Interaction with Existing Roles
- Works with Developers to validate deployment readiness and environment configuration
- Collaborates with QA on smoke tests and release verification
- Supports Project Managers and Product Managers on launch timing and release communications

---

## Data Analyst / Measurement Lead

### Role Summary
Data Analysts and Measurement Leads help the team define, instrument, and evaluate the outcomes that matter most to the business and customers.

### Responsibilities
- Define metrics and instrumentation plans for product and project success
- Design dashboards and reporting for usage, quality, and operational signals
- Analyze results after launch and identify trends or gaps
- Validate whether outcomes align with stated business objectives
- Communicate evidence and recommendations to stakeholders

### Goals
- Ground decisions in measurable evidence
- Improve confidence in product and process changes
- Identify opportunities for iteration and continuous improvement

### Typical Communication
- Metric definitions, reporting updates, and dashboard reviews
- Experiment and launch outcome reviews with product and leadership
- Weekly or milestone-based stakeholder updates

### Interaction with Existing Roles
- Partners with Product Managers to define success metrics and desired outcomes
- Supplies evidence and trend data to Project Managers and stakeholders for status reporting
- Works with Developers and QA to confirm instrumentation and monitor release quality

---

## Security & Compliance Owner

### Role Summary
Security and Compliance Owners protect the project from avoidable risk by defining and enforcing required safeguards, reviews, and controls.

### Responsibilities
- Review architecture, processes, and changes for security and compliance implications
- Support threat modeling, risk assessments, and secure design reviews
- Ensure required controls, policies, and audit evidence are maintained
- Coordinate escalations for security-sensitive issues or incidents
- Partner with the team on remediation and secure-by-default practices

### Goals
- Reduce security and compliance risk in project delivery
- Improve confidence in the solution and its operating model
- Support safe, compliant releases and ongoing operations

### Typical Communication
- Security review check-ins and risk assessments
- Incident escalation coordination and control remediation discussions
- Compliance and audit readiness updates with leadership and PMs

### Interaction with Existing Roles
- Reviews technical decisions with Technical Lead and Developers to identify risk early
- Documents security implications for Project Managers and Product Managers during planning and release readiness
- Coordinates with Release Engineer / DevOps on secure deployment and rollback requirements

---

## Support / Operations Liaison

### Role Summary
Support and Operations Liaisons connect the project to the realities of production usage, operational readiness, and customer impact.

### Responsibilities
- Capture customer issues, incidents, and recurring operational pain points
- Share post-deployment feedback and support trends with the delivery team
- Coordinate on-call handoffs and escalations for production issues
- Help prioritize fixes based on customer impact and operational risk
- Support process continuity between delivery and operational teams

### Goals
- Improve service reliability and customer experience
- Reduce time to resolve production issues
- Create more effective feedback loops between delivery and operations

### Typical Communication
- Incident triage updates and support escalations
- Operational readiness and release follow-up reviews
- Customer-impact communication with PM and stakeholders

### Interaction with Existing Roles
- Works with Developers and Technical Lead to prioritize production issues and define mitigations
- Partners with Project Managers to manage communication and escalation paths
- Helps Product Managers understand real-world user pain and operational constraints

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

