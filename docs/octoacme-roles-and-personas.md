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

## Additional Personas & Responsibilities

The following cross-functional personas ensure successful delivery, quality, and accountability across planning, execution, release, and incident response phases.

---

## Delivery Lead

### Role Summary
Delivery Leads coordinate sprint-level execution, manage cross-team dependencies, and ensure the team meets iteration goals and acceptance criteria.

### Responsibilities
- Maintain and update the sprint/iteration plan
- Coordinate dependencies across teams and manage handoffs
- Escalate blockers and risks to the Project Manager
- Ensure acceptance criteria are met before marking work complete
- Facilitate daily standups and remove obstacles
- Track iteration velocity and burndown

### Goals
- Deliver committed work on schedule
- Minimize context switching and rework
- Maintain team focus and momentum

### Primary Collaborators
- Project Manager (escalates blockers and resource issues)
- Developers (coordinates task execution and dependencies)
- QA/Testing (ensures handoff to QA when ready)
- Release Manager (coordinates pre-release handoff)

### Typical Communication
- Daily standups
- Sprint planning and backlog refinement
- Dependency tracking and status updates
- Escalation notes to Project Manager

---

## Engineering Lead

### Role Summary
Engineering Leads provide technical ownership, guide implementation approaches, ensure code quality, and mentor engineers on the team.

### Responsibilities
- Own technical architecture and design decisions
- Guide implementation approach for complex features
- Conduct technical code reviews and provide feedback
- Identify and escalate technical risks
- Mentor junior developers and share technical expertise
- Contribute estimates for technical complexity

### Goals
- Deliver scalable, maintainable, and secure code
- Build team technical capability and consistency
- Reduce technical debt and complexity

### Primary Collaborators
- Developers (guidance and code review)
- Security Engineer (threat modeling and secure defaults)
- Product Manager (technical feasibility assessment)
- Project Manager (technical risk escalation)

### Typical Communication
- Design reviews and architecture discussions
- Code review comments and technical guidance
- Technical risk flags in planning and execution
- Mentoring and 1:1 guidance

---

## UX Researcher

### Role Summary
UX Researchers validate product hypotheses, run user research and usability tests, and produce insights that inform product decisions and feature refinement.

### Responsibilities
- Plan and conduct user research (interviews, surveys, usability tests)
- Analyze user feedback and produce actionable insights
- Document findings and share recommendations with product and design teams
- Validate acceptance criteria with user perspective
- Contribute to feature demos and retrospectives with user context
- Collaborate on success metrics and measurement

### Goals
- Ensure product solutions meet real user needs
- Reduce rework by catching usability issues early
- Drive product decisions with evidence

### Primary Collaborators
- Product Manager (feedback on prioritization and specs)
- Developers (usability feedback during implementation)
- Design (UX validation and iteration)
- Support Lead (customer feedback and trends)

### Typical Communication
- Research findings and recommendations
- User feedback summaries
- Acceptance criteria validation
- Demo and retrospective contributions

---

## Support Lead

### Role Summary
Support Leads triage and prioritize customer-reported issues, coordinate communication with support teams, and drive fixes for high-impact customer problems.

### Responsibilities
- Triage incoming customer issues and bugs
- Prioritize issues by customer impact and business value
- Escalate critical issues to the development team
- Coordinate communication between support, customers, and engineering
- Feed recurring customer issues into the backlog with recommended priorities
- Participate in incident response and post-incident reviews

### Goals
- Minimize customer impact from issues
- Reduce recurring customer problems through backlog prioritization
- Improve support team efficiency and customer satisfaction

### Primary Collaborators
- Developers (issue investigation and fixes)
- Product Manager (prioritization and customer feedback)
- Project Manager (incident escalation and tracking)
- Release Manager (rollback coordination during incidents)

### Typical Communication
- Issue escalation and severity tracking
- Customer impact summaries
- Backlog prioritization requests
- Incident communication and coordination

---

## Security Engineer

### Role Summary
Security Engineers review threat models, conduct security assessments, advise on remediation, and participate in incident response to ensure secure product defaults and practices.

### Responsibilities
- Participate in threat modeling and design reviews
- Review code and architecture for security vulnerabilities
- Advise on remediation and secure defaults for implementations
- Run security scans and assessments in the CI/CD pipeline
- Participate in incident response for security-related issues
- Flag release blockers when security concerns are not addressed

### Goals
- Reduce security vulnerabilities and risk
- Build secure-by-default practices into delivery
- Maintain compliance and customer trust

### Primary Collaborators
- Engineering Lead (design reviews and code guidance)
- Developers (security remediation and implementation)
- Release Manager (security clearance for releases)
- Project Manager (security risk escalation)

### Typical Communication
- Security review findings and recommendations
- Threat model discussions
- Security incident alerts and response coordination
- Release security clearance

---

## Analytics / Data Owner

### Role Summary
Analytics owners define success metrics, ensure proper instrumentation of features, validate data quality, and provide dashboards and insights to measure project impact.

### Responsibilities
- Define success metrics and measurement approach for features
- Ensure analytics instrumentation is implemented correctly
- Validate data quality and dashboard accuracy
- Provide metrics and insights for demos and stakeholder updates
- Track product health metrics and alerts for anomalies
- Contribute to retrospectives with data-driven insights

### Goals
- Enable data-driven decision-making
- Measure and demonstrate project impact
- Maintain high-quality, reliable analytics

### Primary Collaborators
- Product Manager (metrics definition and interpretation)
- Developers (instrumentation implementation)
- Project Manager (metrics tracking and reporting)
- Support Lead (customer impact metrics)

### Typical Communication
- Metrics definition and instrumentation specs
- Dashboard and reporting updates
- Data quality issues and resolution
- Insights and analysis for demos and retrospectives

---

## Release Manager

### Role Summary
Release Managers coordinate deployments, maintain release checklists, run pre- and post-deploy verifications, and manage rollback plans to ensure smooth, low-risk releases.

### Responsibilities
- Coordinate deployment schedules and communication
- Maintain and execute pre-release checklists and testing
- Run smoke tests and verify deployments in staging and production
- Manage rollback plans and execute rollbacks when necessary
- Coordinate with CI/CD, QA, and support teams for release windows
- Document release notes and communicate releases to stakeholders
- Post-deployment monitoring and incident readiness

### Goals
- Execute releases with minimal risk and downtime
- Maintain clear communication and coordination during releases
- Enable rapid incident response and rollback when needed

### Primary Collaborators
- Developers (feature completion and hot fixes)
- QA/Testing (pre-release testing and verification)
- Support Lead (incident readiness and communication)
- Security Engineer (security clearance for release)
- Project Manager (release planning and stakeholder communication)

### Typical Communication
- Release schedules and coordination
- Pre-release checklists and test results
- Deployment status updates
- Post-deployment verification results
- Rollback coordination and communication

---

## Implementation Specialist

### Role Summary
Implementation Specialists manage technical onboarding for customers, configure integrations for customer-specific needs, and create runbooks and documentation to accelerate customer success.

### Responsibilities
- Conduct technical onboarding sessions with customers
- Configure integrations and customizations for customer requirements
- Create runbooks and troubleshooting guides
- Document common setup scenarios and best practices
- Gather customer feedback on implementation challenges
- Collaborate with support on knowledge transfer and FAQs

### Goals
- Accelerate time-to-value for customers
- Reduce support burden through self-service documentation
- Improve customer satisfaction and retention

### Primary Collaborators
- Support Lead (customer handoff and feedback)
- Product Manager (feature feedback from customer implementations)
- Developers (custom integration support and clarification)
- Project Manager (resource planning for implementations)

### Typical Communication
- Implementation status and customer communication
- Runbooks and documentation
- Customer feedback and feature requests
- Best practices and lessons learned

---

## How these personas are used in the exercise

- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Map personas to your team members to clarify roles, responsibilities, and communication patterns during project execution.
- Reference interaction patterns to identify cross-functional handoffs and dependency points.
