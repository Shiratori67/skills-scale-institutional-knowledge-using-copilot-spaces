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

## Sponsor / Executive Stakeholder

### Role Summary
Sponsors provide strategic direction, approve budget and resource allocation, and serve as the escalation point for business-critical decisions. They ensure the project aligns with organizational strategy and have authority to remove blockers.

### Responsibilities
- Approve project initiation and budget allocation
- Make go/no-go decisions at key project gates
- Remove organizational and resource blockers
- Serve as executive escalation point for business-impacting issues
- Provide strategic direction and ensure business alignment

### Goals
- Maximize return on investment for approved projects
- Ensure alignment between project outcomes and business objectives
- Remove systemic blockers preventing team success

### Typical Communication
- Monthly stakeholder updates and milestone reviews
- Ad-hoc escalation calls for critical issues
- Budget and resource reviews
- Post-project retrospectives

### Interaction with Other Roles
- **Approves initiatives** defined by Product Managers and planned by Project Managers
- **Escalation point** for risks identified by Project Managers and technical concerns raised by Technical Architects
- **Removes blockers** that Project Managers cannot resolve independently
- **Reviews outcomes** with QA/Testing Lead to ensure quality standards are met before release

---

## QA / Testing Lead

### Role Summary
QA/Testing Leads define quality standards, execute test plans, validate acceptance criteria, and ensure features meet production readiness standards before release.

### Responsibilities
- Develop and maintain test plans aligned with acceptance criteria
- Execute unit, integration, and end-to-end testing
- Conduct smoke tests before production deployment
- Document and triage bugs and quality issues
- Validate feature acceptance against Definition of Done
- Collaborate with developers on test automation and coverage

### Goals
- Ensure high-quality, reliable features reach production
- Reduce post-release defects and customer impact
- Build confidence in deployment readiness

### Typical Communication
- Daily standup participation
- Sprint planning and acceptance criteria review
- QA status in weekly syncs
- Pre-release quality sign-off

### Interaction with Other Roles
- **Reviews acceptance criteria** with Product Managers to understand success metrics
- **Collaborates with Developers** on test automation and coverage strategies
- **Reports quality status** to Project Managers for release planning
- **Participates in planning** with Project Managers to assess test effort and timelines
- **Signs off on releases** in coordination with Security Lead before production deployment

---

## Security Lead

### Role Summary
Security Leads ensure projects meet security standards, conduct threat assessments, oversee security scanning, and coordinate incident response. They are the escalation point for security-related risks.

### Responsibilities
- Conduct security reviews and threat assessments during planning
- Configure and monitor security scanning in CI/CD pipelines
- Review and approve changes to security-sensitive components
- Participate in incident response and post-incident reviews
- Provide security guidance and training to the team
- Maintain and update the security incident runbook

### Goals
- Prevent security vulnerabilities from reaching production
- Maintain compliance with organizational security standards
- Enable rapid response to security incidents

### Typical Communication
- Security review checkpoints during planning and implementation
- Pre-release security sign-off
- On-call rotation for security incidents
- Quarterly security awareness updates

### Interaction with Other Roles
- **Participates in project planning** with Project Managers and Technical Architects to assess security risks
- **Guides Developers** on secure coding practices and security best practices
- **Reviews test plans** with QA/Testing Lead to ensure security testing is included
- **Signs off on releases** alongside QA/Testing Lead before production deployment
- **Escalates security issues** to Sponsor/Executive Stakeholder when critical vulnerabilities are discovered
- **Coordinates with Project Managers** on incident response and post-incident retrospectives

---

## Technical Architect

### Role Summary
Technical Architects define the high-level system design, assess technical feasibility, identify architectural risks, and guide technical decisions to ensure scalability and maintainability.

### Responsibilities
- Conduct technical feasibility assessments during planning
- Design system architecture and integration points
- Identify technical dependencies and risks
- Review and approve major technical decisions
- Guide best practices for code quality, scalability, and maintainability
- Participate in design reviews and code reviews for critical components

### Goals
- Ensure technical solutions are scalable, maintainable, and aligned with organizational standards
- Reduce technical debt and long-term maintenance burden
- Enable team confidence in architectural decisions

### Typical Communication
- Kickoff and planning meetings for technical design review
- Architecture decision records and design documentation
- Code review participation for critical features
- Technical risk assessment in weekly syncs

### Interaction with Other Roles
- **Works with Product Managers** to understand business requirements and translate them into technical strategy
- **Guides Developers** on architectural patterns and technical direction
- **Collaborates with QA/Testing Lead** to identify architectural testing needs (performance, scalability, integration)
- **Advises Project Managers** on technical risks and dependencies for accurate planning and scheduling
- **Partners with Security Lead** on security architecture and threat modeling
- **Escalates architectural risks** to Sponsor/Executive Stakeholder when they impact project viability

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the interaction patterns between roles to understand dependencies and communication flows in project execution.
