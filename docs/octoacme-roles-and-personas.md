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

## QA/Testing Lead

### Role Summary
QA and Testing Leads define and execute quality strategies to validate that features meet acceptance criteria and maintain system reliability. They collaborate with developers and product to establish testing standards and reduce production defects.

### Responsibilities
- Define testing strategy (unit, integration, end-to-end, performance)
- Create and maintain test plans and automation frameworks
- Validate acceptance criteria before features ship
- Triage and manage defect lifecycle
- Establish quality metrics and trend reporting

### Goals
- Minimize production defects and regressions
- Provide early feedback to developers on testability and quality
- Build confidence in release readiness

### Interactions with Other Roles
- **Developers**: Collaborate on test automation, code review for testability, and defect resolution
- **Product Managers**: Validate acceptance criteria against test coverage and quality gates
- **Project Managers**: Report quality metrics and flag testing blockers for escalation
- **DevOps/Release Engineer**: Coordinate automated testing in CI/CD pipelines and pre-release smoke tests

### Typical Communication
- Sprint planning and retrospectives
- Test plan reviews and coverage discussions
- Defect triage and prioritization meetings
- Pre-release quality sign-offs

---

## Technical Lead / Architect

### Role Summary
Technical Leads guide architectural decisions, manage technical risks, and mentor the development team. They ensure solutions are scalable, maintainable, and aligned with platform standards.

### Responsibilities
- Review and approve technical designs and trade-offs
- Identify and mitigate architectural risks
- Mentor developers on coding standards and best practices
- Collaborate with DevOps on deployment and scalability concerns
- Validate that solutions meet performance and reliability requirements

### Goals
- Deliver technically sound, maintainable solutions
- Reduce technical debt and rework
- Enable fast, confident deployments

### Interactions with Other Roles
- **Developers**: Provide architectural guidance, code review leadership, and mentoring
- **Product Managers**: Advise on technical feasibility and implementation trade-offs
- **Project Managers**: Identify and escalate technical risks and dependencies
- **DevOps/Release Engineer**: Collaborate on infrastructure requirements and deployment patterns

### Typical Communication
- Design review sessions
- Architecture decision records (ADRs)
- Code review feedback and pair programming
- Technical risk escalations

---

## Scrum Master / Agile Coach

### Role Summary
Scrum Masters and Agile Coaches facilitate team processes, remove blockers, and protect team capacity. They enable effective collaboration and continuous improvement within the project team.

### Responsibilities
- Facilitate daily standups, sprint planning, and retrospectives
- Identify and remove impediments blocking the team
- Coach team members on Agile practices and ceremonies
- Protect team capacity from scope creep and external interruptions
- Track team velocity and sprint metrics
- Support process improvements based on retrospective feedback

### Goals
- Maximize team productivity and predictability
- Build a healthy, collaborative team culture
- Enable the team to self-organize and continuously improve
- Reduce cycle time and delivery friction

### Interactions with Other Roles
- **Developers**: Remove blockers, facilitate collaboration, and protect focus time
- **Project Managers**: Work closely on planning, risk escalation, and stakeholder communication
- **Product Managers**: Help prioritize backlog and manage scope within sprint capacity
- **All Roles**: Facilitate ceremonies and foster psychological safety

### Typical Communication
- Facilitation of sprint ceremonies and team meetings
- One-on-one coaching and retrospective observations
- Impediment tracking and escalation
- Velocity and process metrics reporting

---

## Stakeholder / Sponsor

### Role Summary
Stakeholders and Sponsors provide business context, strategic direction, and organizational support for projects. They approve scope and resources, remove organizational blockers, and represent business and customer interests.

### Responsibilities
- Provide business context and success criteria
- Approve project scope, timeline, and resource allocation
- Remove organizational and executive blockers
- Communicate project importance and strategy to wider organization
- Provide business feedback and validate outcomes
- Escalate business-level risks and trade-offs

### Goals
- Ensure project alignment with business strategy
- Enable successful project delivery through organizational support
- Maximize business value and customer satisfaction
- Minimize enterprise-level risks and dependencies

### Interactions with Other Roles
- **Project Managers**: Provide business approval, escalation path, and strategic guidance
- **Product Managers**: Align on business vision, success metrics, and market positioning
- **Developers/Technical Leads**: Communicate business context and validate technical trade-offs
- **All Roles**: Provide high-level direction and organizational enablement

### Typical Communication
- Milestone reviews and gate decisions
- Executive status updates and escalations
- Business requirements and strategy briefings
- Stakeholder approval meetings and decision logs

---

## DevOps / Release Engineer

### Role Summary
DevOps and Release Engineers manage deployment infrastructure, CI/CD pipelines, and release orchestration. They ensure reliable, repeatable deployments and maintain operational readiness.

### Responsibilities
- Design and maintain CI/CD pipelines
- Manage deployment environments (staging, production)
- Automate testing, security scanning, and deployment processes
- Coordinate release deployments and rollbacks
- Monitor system health and performance post-deployment
- Document runbooks and incident response procedures

### Goals
- Enable fast, safe deployments with minimal manual intervention
- Maintain high system availability and reliability
- Provide clear visibility into deployment and operational metrics
- Reduce deployment risk through automation and observability

### Interactions with Other Roles
- **Developers**: Enable rapid feedback loops through automated testing and deployment
- **QA/Testing Lead**: Coordinate automated testing in pipelines and smoke tests before release
- **Technical Lead**: Collaborate on infrastructure requirements and architectural scalability
- **Project Managers**: Provide deployment readiness assessments and release coordination
- **Product Managers**: Enable rapid iteration through efficient deployment processes

### Typical Communication
- Release planning and deployment windows
- Incident response coordination
- Infrastructure and tooling proposals
- Post-deployment health checks and monitoring

---

## UX/Design Lead

### Role Summary
UX and Design Leads define user experience strategy, validate usability, and ensure solutions are intuitive and aligned with customer needs. They collaborate with product and engineering on design decisions and acceptance criteria.

### Responsibilities
- Define and maintain design systems and user experience standards
- Conduct user research and usability testing
- Create wireframes, prototypes, and design specifications
- Validate design decisions against customer feedback and metrics
- Collaborate on accessibility and inclusive design practices
- Ensure visual and interaction consistency across features

### Goals
- Maximize user satisfaction and product usability
- Reduce support burden through intuitive design
- Align product with customer expectations and mental models
- Maintain design consistency and brand alignment

### Interactions with Other Roles
- **Product Managers**: Collaborate on feature prioritization and customer insights
- **Developers**: Provide design specifications and validate implementation quality
- **QA/Testing Lead**: Define acceptance criteria for usability and accessibility
- **Project Managers**: Communicate design timelines and dependencies

### Typical Communication
- Design reviews and critique sessions
- User research findings and usability test results
- Design specifications and component libraries
- Acceptance criteria for user experience and accessibility

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the "Interactions with Other Roles" sections to understand cross-functional dependencies and communication patterns.
