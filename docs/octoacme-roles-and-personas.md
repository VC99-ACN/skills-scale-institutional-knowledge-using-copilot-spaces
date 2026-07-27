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
QA/Testing Leads define quality standards, develop comprehensive test strategies, and ensure acceptance criteria are validated before release. They collaborate with product and development teams to embed quality throughout the project lifecycle rather than treating it as a final gate.

### Responsibilities
- Define test strategy and quality gates for each release
- Design and execute integration and end-to-end test plans
- Identify quality risks and propose mitigation strategies
- Validate acceptance criteria and sign off on readiness
- Coach developers on testing best practices and coverage
- Manage test environments and automation infrastructure

### Goals
- Achieve high quality and reliability while maintaining delivery velocity
- Shift testing left by embedding quality early in development
- Reduce post-release defects and support burden
- Build team capability in quality practices

### Typical Communication
- Weekly quality metrics in project syncs
- Test plan reviews with developers and product team
- Release readiness sign-off before deployment
- Escalation of critical quality risks to PM and project sponsor

### Interaction with Existing Roles
- **Developers**: Collaborate on test requirements, review test coverage, and fix defects identified through testing
- **Product Managers**: Align on acceptance criteria and release quality expectations
- **Project Managers**: Report quality metrics, risks, and readiness status; escalate blockers

---

## Technical Lead/Architect

### Role Summary
Technical Leads define the technical direction for projects, review architectural decisions, identify technical risks, and ensure solutions are scalable, maintainable, and aligned with platform standards. They serve as technical escalation point for complex decisions.

### Responsibilities
- Define and document technical architecture and design patterns
- Review pull requests and technical designs for quality and alignment
- Identify and mitigate technical risks and performance bottlenecks
- Ensure solutions follow platform standards and best practices
- Mentor developers on technical topics and code quality
- Provide technical input to planning and estimation

### Goals
- Deliver technically sound, maintainable, and scalable solutions
- Reduce technical debt and rework
- Build team technical capability
- Ensure solutions are resilient and performant

### Typical Communication
- Architecture review meetings before implementation
- Code review comments and technical guidance
- Technical risk assessments in planning and execution
- Design decision documentation and rationale

### Interaction with Existing Roles
- **Developers**: Guide technical decisions, review code, and mentor on best practices
- **Product Managers**: Advise on technical trade-offs and feasibility during planning
- **Project Managers**: Flag technical risks and dependencies that impact timelines

---

## Stakeholder Representative

### Role Summary
Stakeholder Representatives serve as the primary liaison between the project team and business/external stakeholders. They gather requirements, communicate progress, manage expectations, and escalate business-impacting decisions.

### Responsibilities
- Gather and clarify business requirements and priorities from stakeholders
- Communicate project status, risks, and decisions to stakeholder groups
- Manage stakeholder expectations and feedback loops
- Escalate business-impacting decisions and risks to sponsors
- Provide user/customer perspective to the team
- Coordinate stakeholder reviews and demos

### Goals
- Maintain strong stakeholder alignment and satisfaction
- Ensure project delivers business value
- Reduce rework due to unclear requirements
- Enable quick resolution of priority conflicts

### Typical Communication
- Weekly or bi-weekly stakeholder status updates
- Requirement clarification sessions with product and development teams
- Escalation of priority conflicts or blocking decisions
- Demo and feedback sessions with key stakeholders

### Interaction with Existing Roles
- **Product Managers**: Work closely to translate business needs into product requirements
- **Project Managers**: Provide stakeholder feedback on priorities, risks, and readiness
- **Developers**: Share user/business context to inform design and implementation decisions

---

## DevOps/Platform Engineer

### Role Summary
DevOps/Platform Engineers manage infrastructure, CI/CD pipelines, deployment tooling, and platform reliability. They enable fast, safe deployments and provide the operational foundation for project delivery.

### Responsibilities
- Design and maintain CI/CD pipelines for automated testing and deployment
- Manage infrastructure, environments, and deployment procedures
- Implement security scanning and compliance checks in CI
- Monitor systems and respond to incidents
- Document deployment procedures and runbooks
- Provide deployment guidance and support to delivery teams

### Goals
- Enable fast, reliable, and safe deployments
- Reduce deployment risk and incident response time
- Maintain high system availability and performance
- Support team velocity through robust automation and tooling

### Typical Communication
- CI/CD pipeline design reviews with developers
- Deployment procedures and release coordination
- Infrastructure capacity and performance metrics
- Incident response and post-incident reviews

### Interaction with Existing Roles
- **Developers**: Collaborate on deployment pipelines, provide deployment support, and gather feedback on tooling
- **Project Managers**: Flag infrastructure risks and deployment constraints that impact timelines
- **QA/Testing Leads**: Ensure test environments are robust and deployment validation is automated

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- For team composition guidance, see [Team Composition Guide](octoacme-team-composition-guide.md)
- For role interaction patterns, see [Role Interaction Matrix](octoacme-role-interaction-matrix.md)
