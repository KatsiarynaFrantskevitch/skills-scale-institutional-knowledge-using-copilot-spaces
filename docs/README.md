# OctoAcme Project Management Docs

Welcome to OctoAcme's centralized project management knowledge base. This collection of documents provides guidance for running projects collaboratively, delivering customer value iteratively, and maintaining clarity across teams.

## Core Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has named roles and accountabilities
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Project Lifecycle

OctoAcme projects follow a structured lifecycle:

1. **Initiation** — Validate business need and align stakeholders
2. **Planning** — Break work into shippable increments and identify risks
3. **Execution** — Build, test, review, and iterate
4. **Release** — Deploy and verify in production
5. **Close & Retrospective** — Capture learnings and improve

## Key Processes

### [Project Initiation Guide](octoacme-project-initiation.md)
Define initial steps to validate work, align stakeholders, and create a lightweight plan. Use this when a new project idea or feature proposal is ready to be explored.
- **Key deliverables**: One-pager, stakeholder list, timeline, risk list, resource needs
- **Decision gate**: Move to planning when success metrics are clear and stakeholders are aligned

### [Project Planning](octoacme-project-planning.md)
Turn an approved initiative into an actionable plan and backlog for delivery. Break work into shippable increments and identify dependencies and risks.
- **Key activities**: Kickoff meeting, backlog creation, estimation, Definition of Done, risk mapping
- **Outputs**: Prioritized backlog, release plan, milestone timeline

### [Execution & Tracking](octoacme-execution-and-tracking.md)
Guidance for managing day-to-day execution and tracking progress toward project milestones. Maintain team rhythm through standups and syncs while ensuring quality and managing blockers.
- **Team rhythm**: Daily standups, weekly delivery sync, demo/review at milestone end
- **Key practices**: Small PRs, automated testing, quality assurance, velocity tracking

### [Risk Management & Communication](octoacme-risks-and-communication.md)
Identify, manage, and communicate risks and dependencies effectively. Maintain a risk register and ensure consistent stakeholder updates.
- **Risk lifecycle**: Identify, assess, mitigate, monitor
- **Escalation paths**: Team-level → PM → Product Lead → Sponsor

### [Release & Deployment Guide](octoacme-release-and-deployment.md)
Standardize how OctoAcme releases features to production to reduce risk and improve observability. Define release types and ensure pre-release requirements are met.
- **Release types**: Patch, Minor, Major
- **Pre-release requirements**: Acceptance criteria met, CI passing, smoke tests prepared, rollback plan documented

### [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
Capture learnings and convert them into actionable improvements. Run structured retrospectives after each sprint, release, or milestone.
- **Structure**: What went well, what could improve, action items with owners and due dates
- **Frequency**: After each sprint, release, or important milestone

### [Roles and Personas](octoacme-roles-and-personas.md)
Define typical roles and responsibilities used in OctoAcme projects. Understand the key personas and how they interact.
- **Core roles**: Project Manager (PM), Product Manager (PdM), Developers, QA/Testing, Stakeholders

## How to Use These Docs

- **Starting a new project?** Begin with the [Project Initiation Guide](octoacme-project-initiation.md) to define the business need and align stakeholders
- **In planning phase?** Follow the [Project Planning](octoacme-project-planning.md) process to create your backlog and timeline
- **Managing execution?** Reference [Execution & Tracking](octoacme-execution-and-tracking.md) for day-to-day practices and team rhythm
- **Dealing with risks?** Consult [Risk Management & Communication](octoacme-risks-and-communication.md) for escalation and stakeholder updates
- **Preparing a release?** Use the [Release & Deployment Guide](octoacme-release-and-deployment.md) to ensure quality and readiness
- **After a milestone?** Run a retrospective using [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)

## Tips for Success

- **Use templates and checklists** as starting points, then adapt to your team's needs
- **Keep project artifacts updated** in your project repository (e.g., One-pager, risk register, backlog)
- **Share relevant docs** with new team members and stakeholders for onboarding
- **Reference specific sections** when discussing project activities with your team
- **Contribute improvements** back to these docs to keep them accurate and valuable

## Communication Cadence

- **Daily**: Team standups (15 min focus on progress, blockers, dependencies)
- **Weekly**: PM + PdM sync; twice-weekly standups for delivery team
- **Monthly**: Stakeholder updates
- **Ad-hoc**: Escalations and incident communication

## Need Help?

If you have questions about a specific process or need to propose updates to these documents, please refer to the issue template in `.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml` to submit a Process Doc Update request.
