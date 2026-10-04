# OctoAcme Project Management Processes

Welcome to the OctoAcme Project Management documentation. This guide centralizes our process knowledge and helps you navigate the frameworks we use to deliver projects successfully.

## Overview

OctoAcme uses a structured, cross-functional project lifecycle that emphasizes customer value, iterative delivery, clear ownership, measurable outcomes, and continuous learning. Each project starts with a clear problem statement, defined stakeholders, success metrics, timeline, and resource allocation before work begins. The approach is intentionally lightweight but consistent, allowing teams to maintain accountability while remaining flexible enough to adapt to changing requirements.

The documentation you'll find here covers the complete project journey—from validating an idea through planning, executing, releasing, and learning from what we build. These processes are designed to be collaborative, ensuring that developers, product managers, project managers, QA, and stakeholders all work together around shared artifacts and a common understanding of success.

## Quick Start: Project Lifecycle

OctoAcme follows a five-phase project lifecycle:

1. **Initiation** - Validate the business problem, align stakeholders, and create a lightweight project charter
2. **Planning** - Break work into shippable increments, estimate scope, and define acceptance criteria
3. **Execution** - Build, test, and iterate with regular standups, code reviews, and risk management
4. **Release** - Deploy to production with staged rollout, smoke tests, and rollback procedures
5. **Retrospective** - Capture learnings, measure impact, and improve the process

## Core Documents

Navigate to the process guide that's most relevant to your current phase or role:

| Document | Purpose | Use When |
|----------|---------|----------|
| [Project Management Overview](octoacme-project-management-overview.md) | Introduction to OctoAcme's approach, principles, roles, and key artifacts | You're new to OctoAcme or need a high-level orientation |
| [Project Initiation Guide](octoacme-project-initiation.md) | Steps to validate and authorize work | Starting a new project or feature proposal |
| [Project Planning](octoacme-project-planning.md) | Turn initiatives into actionable plans and backlogs | Approved to begin planning and defining scope |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Day-to-day execution and progress management | Managing active development and sprint delivery |
| [Risk Management & Communication](octoacme-risks-and-communication.md) | Identify, manage, and communicate risks and dependencies | Throughout the project lifecycle; especially for escalations |
| [Release & Deployment Guide](octoacme-release-and-deployment.md) | Standardize releases and deployments | Preparing for or executing a production release |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Capture learnings and improve processes | After a sprint, release, or important milestone |
| [Roles & Personas](octoacme-roles-and-personas.md) | Define team roles and responsibilities | Understanding responsibilities and communication patterns |

## Key Principles

Our project management approach is grounded in five core principles:

- **Customer-first**: Prioritize customer value and usability above internal convenience
- **Iterative delivery**: Deliver small, testable increments rather than waiting for big releases
- **Clear ownership**: Every project has a named Project Manager and Product Lead who are accountable for outcomes
- **Data-informed decisions**: Measure impact and iterate based on evidence, not assumptions
- **Psychological safety**: Encourage feedback, questions, and learning across the team

## Core Roles

OctoAcme projects bring together several key roles, each with distinct responsibilities:

- **Product Manager (PdM)** - Defines outcomes, prioritizes the backlog, and measures success against business goals
- **Project Manager (PM)** - Coordinates delivery, manages schedules, mitigates risks, and keeps stakeholders informed
- **Developers** - Implement features, write tests, and collaborate on design and technical decisions
- **QA / Testing** - Validates quality against acceptance criteria and runs critical smoke tests
- **Stakeholders** - Provide business context, approvals, and strategic direction

## Communication & Coordination

Effective communication is critical to OctoAcme's success. Here's how we stay aligned:

- **Daily standups** (15 min) - Team syncs on progress, blockers, and dependencies
- **Weekly PM + PdM sync** - Alignment on priorities, risks, and progress
- **Weekly stakeholder updates** - Status on key milestones and decisions needed
- **Regular demos** - Show progress and gather feedback at the end of each sprint or milestone
- **Risk escalation path** - Team-level → PM → Product Lead → Sponsor for business-impacting issues

## Quality & Testing Standards

Quality is everyone's responsibility. Our execution standards include:

- **Unit tests** for new logic
- **Integration tests** where applicable
- **End-to-end smoke tests** for critical flows before release
- **Security scanning** in CI
- **Code review** requiring at least one approval before merge
- **PR conventions**: Keep PRs small (≤400 lines when possible) and include issue links and acceptance criteria
- **Manual QA** for feature acceptance when needed

## Getting Started

**For new team members**: Start with [Project Management Overview](octoacme-project-management-overview.md) to understand our overall approach, then explore the specific guides relevant to your role.

**For project leads**: Use the [Project Initiation Guide](octoacme-project-initiation.md) when starting a new initiative, then move through Planning, Execution, and Release guides as the project progresses.

**For individual contributors**: Review [Roles & Personas](octoacme-roles-and-personas.md) to understand expectations, then consult [Execution & Tracking](octoacme-execution-and-tracking.md) for day-to-day workflows.

## Continuous Improvement

OctoAcme's processes are living documents. We improve them by:

1. Capturing learnings in retrospectives after each sprint or release
2. Converting action items into process refinements
3. Measuring the impact of changes and iterating
4. Sharing improvements across the organization

If you have feedback on these processes, please open an issue or create a pull request to propose updates. See `.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml` for the standard template.

---

*Last updated: October 2026*
