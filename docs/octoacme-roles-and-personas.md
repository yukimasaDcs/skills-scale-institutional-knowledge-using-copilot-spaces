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
QA/Testing Leads own quality assurance strategy and execution. They define testing approaches, validate acceptance criteria, and ensure features meet quality standards before release.

### Responsibilities
- Define test strategy (unit, integration, E2E, manual) for each project phase
- Create and maintain test plans aligned with acceptance criteria
- Collaborate with Developers on test automation and coverage goals
- Conduct manual testing and acceptance validation
- Report quality metrics and risks to PM and Project Manager
- Lead incident triage for production issues and define remediation
- Document known issues and workarounds

### Goals
- Deliver high-quality features with minimal defects reaching production
- Establish test coverage standards and measure compliance
- Enable fast, confident releases through automation and efficiency

### Typical Communication
- Sprint planning and acceptance criteria review
- Daily stand-ups on critical path items
- Test reports and quality dashboards
- Post-release verification and incident response

### Interactions with Existing Roles
- **Developers**: Collaborate on test automation frameworks, coverage targets, and test design reviews
- **Product Managers**: Validate acceptance criteria and success metrics before sprint execution
- **Project Managers**: Report quality status, risks, and blockers in weekly syncs

---

## DevOps/Release Engineer

### Role Summary
DevOps/Release Engineers enable reliable, repeatable deployments. They own CI/CD pipelines, infrastructure, and release orchestration to reduce deployment risk and enable rapid iteration.

### Responsibilities
- Design and maintain CI/CD pipelines (testing, security scanning, deployment)
- Manage infrastructure, staging environments, and production deployments
- Implement and validate rollback procedures
- Coordinate pre-release verification (security scans, smoke tests)
- Monitor post-deployment health and performance
- Document release runbooks and deployment processes
- Collaborate with Developers on artifact management and environment parity

### Goals
- Enable safe, automated deployments with minimal manual intervention
- Reduce deployment lead time and increase deployment frequency
- Maintain high availability and rapid incident response capability

### Typical Communication
- Release planning and pre-deployment reviews
- Deployment windows and incident response coordination
- Infrastructure and pipeline improvement discussions
- Performance and reliability reporting

### Interactions with Existing Roles
- **Developers**: Partner on artifact management, environment parity, and deployment validation
- **Project Managers**: Coordinate release schedules, deployment windows, and rollback decisions
- **QA/Testing Lead**: Execute pre-release smoke tests and coordinate post-deployment verification

---

## Stakeholder/Sponsor

### Role Summary
Stakeholders and Sponsors provide business context, approvals, and resources for projects. They represent customer needs, business goals, and organizational priorities.

### Responsibilities
- Provide initial problem statement and business context
- Define success metrics and business outcomes
- Approve project initiation, planning, and major scope changes
- Allocate budget and resources for project delivery
- Resolve escalations and remove organizational blockers
- Receive regular status updates and provide strategic guidance
- Champion project within their organization and advocate for team needs

### Goals
- Ensure projects deliver measurable business value
- Maintain alignment between project delivery and organizational strategy
- Remove impediments and unblock the team to enable delivery

### Typical Communication
- Project initiation and kickoff meetings
- Monthly stakeholder updates and progress reviews
- Ad-hoc escalations and decision gates
- Executive reporting and retrospectives

### Interactions with Existing Roles
- **Product Managers**: Partner on vision, success metrics, and prioritization decisions
- **Project Managers**: Receive status updates, make go/no-go decisions, and resolve blockers
- **Developers**: Provide context during kickoffs and accept completed deliverables

---

## Technical Architect

### Role Summary
Technical Architects provide strategic technical guidance for complex projects. They ensure scalability, maintainability, and alignment with organizational technical standards.

### Responsibilities
- Define technical design and architecture for complex features
- Identify technical risks and propose mitigations
- Review designs for scalability, security, and maintainability
- Collaborate with Developers on implementation approach
- Ensure alignment with organizational technical standards
- Mentor Developers on architectural patterns and best practices
- Identify technical debt and propose remediation strategies

### Goals
- Deliver technically sound, scalable solutions
- Reduce future maintenance burden and technical debt accumulation
- Maintain high code quality and architectural consistency

### Typical Communication
- Design reviews and technical planning sessions
- Architecture decision records (ADRs)
- Code reviews and mentoring sessions
- Technical risk discussions in planning and execution

### Interactions with Existing Roles
- **Developers**: Mentor on architectural patterns and review implementation approaches
- **Product Managers**: Advise on technical feasibility and trade-offs during planning
- **Project Managers**: Identify and escalate technical risks and dependencies

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Refer to the interaction sections to understand cross-functional collaboration and handoff points.
