# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management documentation hub. This folder contains standardized processes, templates, and guidance for running projects across OctoAcme.

## Quick Start

New to OctoAcme's project approach? Start with the [Project Management Overview](octoacme-project-management-overview.md) to understand our core principles, roles, and lifecycle.

## Project Lifecycle

OctoAcme projects follow a structured lifecycle designed to deliver value iteratively while maintaining clear ownership, transparency, and quality:

1. **[Initiation](octoacme-project-initiation.md)** — Validate business need, align stakeholders, and define a high-level plan
   - Confirm measurable outcomes and success criteria
   - Build stakeholder alignment
   - Go/no-go decision gate

2. **[Planning](octoacme-project-planning.md)** — Break work into shippable increments and identify dependencies
   - Create prioritized backlog with acceptance criteria
   - Estimate scope and define Definition of Done
   - Map release timelines and milestones

3. **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Manage day-to-day delivery and track progress
   - Daily standups and weekly delivery syncs
   - Maintain project board and risk register
   - Escalate blockers and dependencies

4. **[Release & Deployment](octoacme-release-and-deployment.md)** — Deploy to production safely and verify success
   - Pre-release checklists and smoke tests
   - Rollback and incident playbooks
   - Release announcements and documentation

5. **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings and iterate
   - Reflect on what went well and what could improve
   - Convert insights into actionable improvements
   - Track and measure impact of changes

## Core Processes

- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — Identify, track, and communicate risks and dependencies throughout the project lifecycle
  - Maintain Risk Register with impact/likelihood assessment
  - Escalation paths (team → PM → Product Lead → Sponsor)
  - Stakeholder communication templates

- **[Roles & Personas](octoacme-roles-and-personas.md)** — Understand key team roles, responsibilities, and communication patterns
  - Product Managers: Define what to build and measure outcomes
  - Project Managers: Coordinate delivery, manage risks and schedules
  - Developers: Implement features and maintain quality
  - QA/Testing: Validate acceptance criteria and quality

## Key Principles

- **Customer-first**: Prioritize customer value and usability in all decisions
- **Iterative delivery**: Deliver small, testable increments to reduce risk and gather feedback early
- **Clear ownership**: Each project has named leads (PM and Product Manager) with defined accountability
- **Data-informed**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback, learning, and blameless retrospectives

## Communication Cadence

OctoAcme maintains a structured communication rhythm to ensure alignment and early risk identification:

- **Daily standups** (15 min) — Focus on progress, blockers, and dependencies
- **Weekly PM + Product Manager sync** — Alignment on priorities and issues
- **Twice-weekly delivery team standups** — Team coordination and execution
- **Weekly stakeholder updates** — Status, risks, and decisions
- **Monthly stakeholder briefings** — High-level progress and roadmap
- **End-of-sprint/milestone demos** — Show progress and gather feedback

## Quality & Testing Standards

All work must meet our Definition of Done before merging:

- Unit tests for new logic
- Integration tests where applicable
- Passing CI checks and automated linting
- Security scanning in the pipeline
- End-to-end smoke tests for critical flows before release
- At least one code review approval (or team-defined policy)
- Acceptance criteria verification

## Key Artifacts & Templates

Project documentation typically includes:

- **Project One-pager** — Problem, goal, success metrics, stakeholders, timeline, risks, resources
- **Risk Register** — ID, description, impact, likelihood, owner, mitigation, status
- **Release Plan** — Timeline, milestones, dependencies, release notes
- **Backlog** — Prioritized items with acceptance criteria, estimates, and owners
- **Decision Log** — Key decisions, rationale, and impact

## How to Use These Docs

1. **For new projects**: Start with Initiation, then follow the lifecycle in sequence
2. **For ongoing projects**: Use Execution & Tracking and Risk Management as your primary references
3. **For releases**: Reference Release & Deployment and use the provided checklists
4. **For team onboarding**: Have new members read the Overview and Roles & Personas
5. **For process improvements**: Submit updates via the [Process Doc Update issue template](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)

## Contributing to OctoAcme Docs

Found a gap or have an improvement? Use the **[Process Doc Update issue template](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)** to propose changes. All process improvements are reviewed for alignment and team benefit.

---

**Last updated**: 2026-09-13  
**Maintained by**: OctoAcme Program Team
