# OctoAcme Project Management Process Documentation

Welcome to the OctoAcme project management documentation hub. This README is a central navigation point for the process documents that guide how we initiate, plan, deliver, and improve projects.

OctoAcme follows a customer-first, iterative delivery approach: projects move through a clear lifecycle (Initiation → Planning → Execution → Release → Close/Retrospective) with named owners and measurable success criteria. Work is broken into small, testable increments and tracked on a project board. Decisions are data-informed and teams are encouraged to iterate based on outcomes and feedback.

Operational workflows emphasize clear pull request practices, CI gating, and a concise backlog flow (Backlog → Ready → In Progress → In Review → QA → Done). Day-to-day coordination relies on short standups for blockers and progress, weekly delivery syncs for show-and-tell and risk review, and demos at the end of each sprint or milestone. Cross-team dependencies and high-impact blockers follow an explicit escalation path (team → PM → Product Lead → Sponsor).

Quality assurance and release rigor are built into the process: unit and integration tests, CI-enforced checks and security scans, smoke tests for critical flows, and manual QA when needed. Releases require passing checks, release notes, and a rollback plan; deployments are staged and post-deploy verifications are run. Retrospectives convert lessons into tracked action items to continuously improve the process.

Project phase guides and detailed process docs
- Project Overview: ./octoacme-project-management-overview.md
- Initiation: ./octoacme-project-initiation.md
- Planning: ./octoacme-project-planning.md
- Execution & Tracking: ./octoacme-execution-and-tracking.md
- Risks & Communication: ./octoacme-risks-and-communication.md
- Release & Deployment: ./octoacme-release-and-deployment.md
- Retrospectives & Continuous Improvement: ./octoacme-retrospective-and-continuous-improvement.md
- Roles & Personas: ./octoacme-roles-and-personas.md

Quick references
- Decision gates:
  - Initiation → Planning: success metrics defined, stakeholders aligned, team availability confirmed.
  - Planning → Execution: prioritized backlog, Definition of Done defined, risks identified.
  - Execution → Release: acceptance criteria met, PRs merged, CI passing, rollback plan documented.
  - Release → Close: deployment verified, release notes published, retrospective scheduled.
- Communication cadence:
  - Daily: 15-minute standups
  - Weekly: PM + PdM sync, delivery sync, risk review
  - Monthly: stakeholder updates
- Key artifacts: Project One-pager, Roadmap & Release Plan, Backlog, Risk Register, Retrospective action items

Getting started
1. New to OctoAcme? Read the [Project Management Overview](./octoacme-project-management-overview.md).
2. Starting a new project? Begin with the [Project Initiation Guide](./octoacme-project-initiation.md).
3. Need role clarity? See [Roles & Personas](./octoacme-roles-and-personas.md).
