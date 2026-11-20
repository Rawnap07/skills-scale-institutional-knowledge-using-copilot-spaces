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

## Potential Additional Personas

These personas provide reusable guidance for cross-functional work. They are not mandatory roles; smaller teams may assign some responsibilities to existing team members. The Project Manager remains accountable for coordinating delivery, but the named role or group owns the specialist work described below.

### Release Manager

#### Role Summary
The Release Manager owns release readiness and coordinates the activities required to deliver a safe, well-understood release.

#### Responsibilities
- Coordinate deployment windows and release calendars
- Maintain release readiness checklists and go/no-go decisions
- Prepare release notes and stakeholder announcements
- Coordinate rollback plans and ownership
- Facilitate handoffs to operations and support

#### Goals
- Reduce deployment risk and surprise incidents
- Ensure stakeholders understand when and what is changing
- Make release and rollback decisions based on clear readiness evidence

#### Typical Communication
- Release calendars and readiness reviews
- Go/no-go check-ins
- Release notes, incident status, and stakeholder announcements

#### Interactions with Existing Personas
- Works with the Project Manager on schedules, dependencies, and delivery risks.
- Works with Developers on build readiness, deployment steps, and rollback readiness.
- Works with QA/Testing on verification evidence and unresolved defects.
- Works with Support/Operations on production deployment and incident handling.
- Works with the Security Representative on release-gating checks.

#### Accountability and Contributions
The Release Manager is accountable for release coordination and go/no-go recommendations. Developers contribute deployable artifacts and rollback support, QA/Testing provides verification evidence, Security provides required risk decisions or approvals, and the Project Manager maintains dependencies and communications.

### Support/Operations Representative

#### Role Summary
The Support/Operations Representative represents operational readiness and the production experience, including health monitoring, incidents, and customer impact.

#### Responsibilities
- Validate operational readiness and runbooks
- Monitor production health and respond to or triage incidents
- Reproduce and communicate customer-impacting issues
- Maintain feedback loops from support and operations to delivery teams
- Escalate production risks and coordinate service recovery

#### Goals
- Improve service reliability and customer experience
- Shorten incident detection and resolution time
- Ensure operational concerns influence prioritization and planning

#### Typical Communication
- Operational readiness reviews and on-call handoffs
- Incident summaries and customer-impact updates
- Support trends, defect reports, and escalation notices

#### Interactions with Existing Personas
- Works with the Product Manager to prioritize operational concerns and customer-impacting fixes.
- Works with Developers to provide diagnostics and validate fixes.
- Works with QA/Testing on issue reproduction and release verification.
- Works with the Project Manager on status, risks, and escalations.
- Works with the Release Manager on deployment and incident coordination.

#### Accountability and Contributions
The Support/Operations Representative is accountable for operational awareness and incident communication. Developers own diagnosis and remediation, QA/Testing validates fixes, the Product Manager prioritizes customer-impact work, and the Project Manager coordinates cross-team escalation and status.

### UX Designer / UX Researcher

#### Role Summary
The UX Designer / UX Researcher translates customer and user needs into usable experiences and validates whether proposed solutions meet those needs.

#### Responsibilities
- Conduct discovery and usability research
- Define workflows, interaction patterns, and user experience acceptance considerations
- Create or review prototypes, wireframes, and design specifications
- Validate usability through testing and feedback
- Communicate customer insights and unmet needs to delivery teams

#### Goals
- Make product experiences clear, accessible, and usable
- Ground scope and prioritization in validated customer needs
- Identify usability risks before and during delivery

#### Typical Communication
- Research plans and findings
- Design reviews and prototypes
- Usability findings and acceptance recommendations

#### Interactions with Existing Personas
- Works with the Product Manager on outcomes, scope, and prioritization.
- Works with Developers on feasibility and implementation details.
- Works with QA/Testing on usability acceptance and edge cases.
- Shares validated insights with stakeholders and delivery participants.

#### Accountability and Contributions
The UX Designer / UX Researcher is accountable for user-centered evidence and interaction recommendations. The Product Manager owns product outcomes and scope, Developers implement the experience, QA/Testing validates acceptance conditions, and stakeholders provide context and decision support.

### Security Representative

#### Role Summary
The Security Representative ensures security requirements, threat considerations, and risk responses are integrated throughout planning and delivery.

#### Responsibilities
- Identify applicable security and privacy requirements
- Facilitate threat assessment and risk review
- Recommend and track security controls and mitigations
- Coordinate security testing and remediation
- Provide or support release-gating security decisions

#### Goals
- Reduce security and privacy risk
- Make security requirements clear and testable
- Prevent unresolved security concerns from reaching production

#### Typical Communication
- Threat models and security risk reviews
- Security requirements and mitigation tracking
- Security verification results and exception decisions

#### Interactions with Existing Personas
- Works with Developers on secure design and implementation.
- Works with QA/Testing on security test planning and validation.
- Works with the Project Manager on risks, dependencies, and escalation.
- Works with the Release Manager on release-gating checks.
- Works with the Product Manager on scope and risk trade-offs.

#### Accountability and Contributions
The Security Representative is accountable for security guidance and risk recommendations. Developers implement controls and remediate findings, QA/Testing contributes validation, the Project Manager tracks actions and dependencies, and the Release Manager confirms required gates are met before release.

### Data/Analytics Representative

#### Role Summary
The Data/Analytics Representative defines measurable signals, validates instrumentation and reporting, and helps teams interpret delivery impact.

#### Responsibilities
- Define success measures and supporting event or data requirements
- Validate instrumentation, data quality, and reporting readiness
- Build or review dashboards and impact analyses
- Interpret metrics and identify follow-up questions or risks
- Align data availability with project milestones

#### Goals
- Make outcomes measurable and observable
- Improve confidence in reports and success decisions
- Surface unexpected trends and delivery impact

#### Typical Communication
- Metrics definitions and measurement plans
- Instrumentation requirements and data-quality reports
- Dashboards, experiment results, and milestone updates

#### Interactions with Existing Personas
- Works with the Product Manager on success metrics and outcome hypotheses.
- Works with Developers on telemetry implementation and data availability.
- Works with QA/Testing on data-quality and instrumentation validation.
- Works with the Project Manager on reporting, milestones, and data dependencies.

#### Accountability and Contributions
The Data/Analytics Representative is accountable for measurement design and interpretation. The Product Manager defines desired outcomes, Developers implement telemetry, QA/Testing verifies data behavior, and the Project Manager ensures reporting work is planned and visible.

### Technical Lead / Architect

#### Role Summary
The Technical Lead / Architect guides technical direction, identifies integration dependencies and trade-offs, and promotes maintainable solutions.

#### Responsibilities
- Establish or refine technical direction and architecture
- Identify integration, scalability, security, and operational dependencies
- Review major design decisions and technical trade-offs
- Promote consistency, maintainability, and testability
- Help resolve technical blockers and risks

#### Goals
- Keep implementation aligned with broader technical direction
- Reduce avoidable integration and maintenance risk
- Make trade-offs and constraints explicit

#### Typical Communication
- Technical design reviews and architecture decision records
- Dependency maps and risk discussions
- Planning estimates and implementation guidance

#### Interactions with Existing Personas
- Works with Developers on design, implementation, and code review.
- Works with the Product Manager on feasibility, scope, and sequencing.
- Works with the Project Manager on technical dependencies and risks.
- Works with QA/Testing on testability and verification strategies.
- Works with Security and Support/Operations on technical constraints and operational readiness.

#### Accountability and Contributions
The Technical Lead / Architect is accountable for technical direction and major design recommendations. Developers own implementation quality and trade-off details, the Product Manager sets outcome priorities, the Project Manager tracks delivery impacts, and QA/Testing validates testability and agreed behavior.

### Lifecycle Participation

These additional personas can contribute at different points in the project lifecycle:

- **Initiation:** Project and Product Managers frame outcomes; UX, Technical, Security, Data/Analytics, and Operations representatives identify needs, constraints, and success measures.
- **Planning:** The Project Manager coordinates scope and dependencies; specialist personas provide estimates, risk inputs, acceptance considerations, data plans, and operational requirements.
- **Execution:** Developers implement; QA/Testing validates; specialist personas review artifacts, resolve cross-functional concerns, and escalate risks in their domains.
- **Release:** The Release Manager leads readiness and coordination, with verification from QA/Testing, Security, Operations, and relevant technical or analytics representatives.
- **Retrospectives:** The project team examines delivery, quality, operational, security, usability, and measurement outcomes and assigns follow-up actions to an accountable role or group.

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When assigning personas to a small team, document who owns each accountability and who contributes to the work.
