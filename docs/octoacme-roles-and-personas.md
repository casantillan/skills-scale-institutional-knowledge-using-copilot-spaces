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

### Interactions with Other Roles
- Work with **Technical Architects** on design reviews and technical approach
- Collaborate with **QA/Testing Leads** on test automation and acceptance criteria
- Coordinate with **DevOps/Release Engineers** on CI/CD integration and deployment
- Report progress to **Project Managers** during standups and planning
- Receive feature specifications from **Product Managers**

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

### Interactions with Other Roles
- Partner with **Project Managers** on delivery planning and timelines
- Align with **Stakeholders/Sponsors** on strategic priorities
- Collaborate with **Technical Architects** on feasibility and technical trade-offs
- Review quality metrics with **QA/Testing Leads**
- Gather security requirements from **Security Champions**

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

### Interactions with Other Roles
- Work with **Developers** and **Technical Architects** on capacity planning and estimates
- Coordinate with **Product Managers** on scope and priorities
- Track quality metrics with **QA/Testing Leads**
- Manage deployment schedules with **DevOps/Release Engineers**
- Report escalations to **Stakeholders/Sponsors**
- Facilitate retrospectives with **Scrum Masters/Agile Coaches**

---

## QA/Testing Lead

### Role Summary
The QA/Testing Lead owns quality assurance strategy, test planning, and acceptance validation. They work with product and development teams to ensure deliverables meet quality standards and user expectations.

### Responsibilities
- Define test strategy and QA approach for each project phase
- Create and maintain test plans, test cases, and acceptance criteria validation
- Collaborate with developers on test automation and CI integration
- Execute manual testing for feature acceptance and regression
- Identify and triage quality issues, prioritize defects
- Participate in release readiness reviews and post-deploy verification

### Goals
- Deliver reliable, high-quality features to production
- Reduce production defects and improve customer experience
- Enable fast, confident deployments through comprehensive testing

### Typical Communication
- Sprint planning and QA strategy reviews
- Defect and issue triage meetings
- Release checklists and sign-off
- Test coverage reports and quality metrics

### Interactions with Other Roles
- Partner with **Developers** on test automation, testability, and CI integration
- Define acceptance criteria with **Product Managers**
- Align quality standards with **Technical Architects**
- Coordinate release testing with **DevOps/Release Engineers**
- Report quality metrics to **Project Managers**
- Review security testing requirements with **Security Champions**

---

## Technical Architect

### Role Summary
The Technical Architect defines technical direction, conducts design reviews, and makes system-level decisions. They ensure solutions are scalable, maintainable, and aligned with technical strategy.

### Responsibilities
- Define technical approach and architecture for new features or services
- Conduct design reviews and propose alternative solutions
- Identify technical risks, dependencies, and integration points
- Mentor developers on best practices and technical standards
- Participate in planning to estimate technical complexity and effort
- Advise on technology choices, frameworks, and tools

### Goals
- Ensure solutions are architecturally sound and future-proof
- Reduce technical debt and improve system maintainability
- Enable scalability and performance at scale

### Typical Communication
- Design review meetings and technical spike documentation
- Architecture decision records (ADRs)
- Planning and estimation discussions
- Code review guidance on architectural concerns

### Interactions with Other Roles
- Guide **Developers** on technical approach and architectural standards
- Advise **Product Managers** on feasibility and technical trade-offs
- Support **Project Managers** with technical risk identification and estimation
- Collaborate with **DevOps/Release Engineers** on infrastructure and deployment architecture
- Work with **Security Champions** on security architecture and design reviews
- Mentor **Scrum Masters/Agile Coaches** on technical best practices

---

## Security Champion

### Role Summary
The Security Champion ensures security best practices are integrated into all phases of project execution. They own security validation, vulnerability assessment, and compliance oversight.

### Responsibilities
- Define security requirements and acceptance criteria
- Conduct security reviews during design and development phases
- Oversee security testing and vulnerability scanning in CI
- Identify and prioritize security risks in the project risk register
- Ensure compliance with organizational security policies
- Participate in incident response and post-incident reviews

### Goals
- Deliver secure features and protect customer data
- Reduce security vulnerabilities and compliance violations
- Build a security-conscious project culture

### Typical Communication
- Security design reviews
- Vulnerability reports and triage
- Risk register updates (security-related)
- Security incident response and retrospectives

### Interactions with Other Roles
- Partner with **Technical Architects** on security architecture and design
- Work with **Developers** on secure coding practices and vulnerability remediation
- Define security acceptance criteria with **Product Managers**
- Coordinate security testing with **QA/Testing Leads**
- Report security risks to **Project Managers** for escalation
- Advise **DevOps/Release Engineers** on secure deployment practices
- Collaborate with **Stakeholders/Sponsors** on security compliance and governance

---

## DevOps/Release Engineer

### Role Summary
The DevOps/Release Engineer manages deployment infrastructure, CI/CD pipelines, and production stability. They enable fast, reliable deployments and maintain observability and incident response capabilities.

### Responsibilities
- Design and maintain CI/CD pipelines and deployment automation
- Plan and execute production deployments
- Define deployment checklists and rollback procedures
- Implement monitoring, logging, and alerting for production systems
- Respond to deployment failures and production incidents
- Document deployment procedures and runbooks

### Goals
- Enable frequent, reliable deployments to production
- Minimize deployment risk and downtime
- Maintain high availability and performance in production

### Typical Communication
- Release planning and deployment window coordination
- Incident response and post-incident reviews
- CI/CD pipeline status and improvements
- On-call escalations and production alerts

### Interactions with Other Roles
- Integrate **Developers'** code through CI/CD pipelines and provide feedback
- Coordinate release schedules with **Project Managers**
- Work with **Technical Architects** on infrastructure and deployment architecture
- Collaborate with **QA/Testing Leads** on smoke tests and release verification
- Support **Security Champions** on secure deployment practices and incident response
- Partner with **Scrum Masters/Agile Coaches** on deployment ceremonies and metrics

---

## Scrum Master / Agile Coach

### Role Summary
The Scrum Master/Agile Coach facilitates agile ceremonies, removes blockers, and coaches the team on agile practices. They enable the team to self-organize and continuously improve delivery processes.

### Responsibilities
- Facilitate sprint planning, daily standups, sprint reviews, and retrospectives
- Identify and help remove impediments and blockers
- Coach team members on agile principles and practices
- Help the team maintain sustainable pace and focus
- Track team velocity and sprint metrics
- Foster a culture of continuous improvement and psychological safety

### Goals
- Enable high-performing, self-organizing teams
- Improve delivery predictability and cycle time
- Build team ownership and accountability
- Reduce blockers and increase team productivity

### Typical Communication
- Sprint ceremonies facilitation and scheduling
- Impediment tracking and escalation
- Team health and retrospective notes
- Velocity and metrics reporting

### Interactions with Other Roles
- Coach all team members (**Developers**, **QA/Testing Leads**, **Technical Architects**) on agile practices
- Support **Project Managers** in execution and metrics tracking
- Help **Product Managers** prioritize and refine the backlog
- Escalate blockers to **Stakeholders/Sponsors** when needed
- Collaborate with **DevOps/Release Engineers** on deployment metrics and process improvements

---

## Stakeholder / Sponsor

### Role Summary
Stakeholders and Sponsors provide strategic direction, approve key decisions, allocate resources, and champion the project. They represent business interests and ensure alignment with organizational goals.

### Responsibilities
- Approve project initiation and major scope changes
- Provide strategic direction and business priorities
- Allocate budget and resources for the project
- Make or escalate key business decisions
- Communicate project status to senior leadership
- Remove organizational blockers and barriers

### Goals
- Ensure project delivers business value
- Maintain strategic alignment and governance
- Enable team success through resource allocation
- Reduce decision latency and organizational friction

### Typical Communication
- Project approval and gate decisions
- Monthly or milestone-based status updates
- Budget and resource reviews
- Escalation of critical business issues

### Interactions with Other Roles
- Align with **Product Managers** on strategic priorities and success metrics
- Review project plans and risk registers with **Project Managers**
- Receive status updates from **Project Managers** and escalation reports
- Provide direction to **Scrum Masters/Agile Coaches** on business priorities
- Make decisions on trade-offs involving multiple teams or strategic implications
- Support **Security Champions** on compliance and governance requirements

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Understand cross-functional dependencies and communication paths between roles.
- Reference role interactions to plan effective project workflows and identify potential gaps.
