# OctoAcme Project Management Documentation

Welcome to the OctoAcme project management process library. This folder contains the canonical process documents that guide how teams plan, execute, and continuously improve product delivery across the organization.

## About OctoAcme's Approach

OctoAcme follows a structured, lifecycle-based approach to project management grounded in five core principles: customer-first delivery, iterative development, clear ownership, data-informed decisions, and psychological safety. The organization organizes work through distinct phases—Initiation, Planning, Execution, Release, and Retrospective—each with defined deliverables and decision gates. At initiation, teams validate business need and create a lightweight Project One-pager that captures the problem statement, success metrics, stakeholders, and initial resource requirements. Once stakeholder alignment is confirmed, the project moves into detailed planning where work is broken into prioritized, estimated backlog items with clear acceptance criteria, dependencies are mapped, and a release plan is established.

The core team structure centers on three primary roles: **Project Managers** who coordinate delivery, manage schedules, risks, and stakeholder communication; **Product Managers** who define what should be built, prioritize the backlog, and measure outcomes; and **Developers** who implement features, write tests, and participate in design reviews. This clear ownership model is reinforced through a consistent communication cadence: daily standups focused on blockers and progress, weekly syncs between PM and Product Manager, twice-weekly delivery team standups, and monthly stakeholder updates. Risk management is embedded throughout the lifecycle via a maintained Risk Register that tracks impact, likelihood, mitigation plans, and status, with escalation flowing from team-level triage through PM to Product Lead to Sponsor depending on severity.

Quality and execution are ensured through multiple practices: pull requests limited to ~400 lines with required approvals, automated CI testing and security scanning, unit and integration tests for new logic, and end-to-end smoke tests before release. Teams use GitHub Projects with standardized columns (Backlog, Ready, In Progress, In Review, QA, Done) and track velocity and burndown metrics tied to success metrics defined in the Project One-pager. Before any release, teams verify all acceptance criteria are met, passing CI/security scans are complete, rollback plans are documented, and smoke tests have been prepared. Finally, OctoAcme emphasizes continuous improvement through retrospectives after each sprint, release, or milestone, where teams capture learnings, identify 2–3 prioritized action items with clear owners and due dates, and measure the impact of improvements to build a culture of iterative enhancement.

---

## Documentation Index

| Document | Description |
|---|---|
| [Project Management Overview](octoacme-project-management-overview.md) | High-level introduction to OctoAcme's project management principles, roles, artifacts, and lifecycle |
| [Project Initiation Guide](octoacme-project-initiation.md) | How to kick off a project: problem statement, stakeholders, Project One-pager, and approval gates |
| [Project Planning](octoacme-project-planning.md) | Scope, backlog, milestones, dependencies, and release plan creation |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Sprint ceremonies, GitHub Projects setup, velocity tracking, and Definition of Done |
| [Risk Management & Communication](octoacme-risks-and-communication.md) | Risk Register maintenance, escalation paths, and stakeholder communication cadence |
| [Release & Deployment Guide](octoacme-release-and-deployment.md) | Pre-release checklist, deployment steps, rollback procedures, and post-release verification |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Retrospective format, action item tracking, and measuring improvement impact |
| [Roles & Personas](octoacme-roles-and-personas.md) | Detailed responsibilities, decision authority, and collaboration expectations for each role |

---

## Navigation Guide

Use the table below to find the right document for each stage of your project:

| Stage | What you need | Go to |
|---|---|---|
| Starting a new project | Understand goals, validate need, get alignment | [Project Initiation Guide](octoacme-project-initiation.md) |
| Building the plan | Define scope, backlog, and milestones | [Project Planning](octoacme-project-planning.md) |
| Running the project | Track progress, manage work, run standups | [Execution & Tracking](octoacme-execution-and-tracking.md) |
| Managing risks | Log and mitigate risks, communicate blockers | [Risk Management & Communication](octoacme-risks-and-communication.md) |
| Shipping to production | Validate readiness, deploy, verify | [Release & Deployment Guide](octoacme-release-and-deployment.md) |
| Improving processes | Retrospect, capture learnings, track actions | [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) |
| Understanding team roles | Clarify responsibilities and ownership | [Roles & Personas](octoacme-roles-and-personas.md) |

---

## Contributing Updates

Process documentation should evolve as teams learn. To propose an update to any of these documents:

1. **Open an issue** using the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template (`[Process Doc Update]:`).
2. **Describe the change**: summarize the update, explain why it is needed, and optionally provide suggested content.
3. **Create a pull request** referencing the issue once you have drafted your changes.
4. **Request a review** from your PM or Product Manager to ensure alignment before merging.

All contributions should align with existing terminology and formatting conventions used in this process library.
