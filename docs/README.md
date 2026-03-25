# OctoAcme Project Management Documentation

Welcome to the OctoAcme Project Management Docs! This README provides an overview of OctoAcme's project management practices and acts as a hub linking to all process documents.

## Project Management Processes Summary

OctoAcme runs projects with a lightweight, iterative process that moves work from a Project One-pager through planning, execution, release, and retrospection. Initiation begins with a one-pager capturing the problem, objective, success metrics, stakeholders, timeline, and risks; a decision gate confirms readiness to plan. Planning breaks approved initiatives into prioritized backlog items with clear acceptance criteria, estimates, and a Definition of Done. Teams visualize work using a project board (Backlog → Ready → In Progress → In Review → QA → Done).

Execution emphasizes small, shippable increments and a disciplined pull request workflow: keep PRs small (target <= 400 lines), reference the linked issue and acceptance criteria, run CI (tests, lint, and security scans) before requesting reviews, and require at least one approval prior to merging. Sprint and iteration planning is timeboxed and respects team capacity; only items that meet the Definition of Done are pulled. Continuous risk management is maintained in a simple Risk Register and reviewed regularly, with escalation paths from team → PM → Product Lead → Sponsor for business-impacting issues.

Roles and responsibilities are clearly defined so everyone knows ownership: Product Managers set outcomes and success metrics, Project Managers coordinate delivery and communications, Developers implement and test, and QA validates acceptance criteria and performs manual testing when needed. Key artifacts (one-pager, backlog items with acceptance criteria, release notes, risk register, and retrospective action items) act as single sources of truth for decisions and progress.

Communication is structured and frequent: daily standups for progress and blockers, weekly delivery syncs for progress and risks, PM–PdM weekly alignment, monthly stakeholder updates, and ad-hoc escalations as required. Release practices include pre-release checks (passing CI/security scans, smoke tests, release notes, rollback plans), a deployment checklist, and a post-deploy verification plan. Incidents follow a prescribed playbook and blameless retrospectives, and continuous improvement is formalized through retrospectives that produce prioritized action items tracked back into the backlog.

## OctoAcme's Project Management Approach

- Customer-first value delivery and iterative improvement
- Clear roles and responsibilities for each project
- Lightweight process artifacts (one-pager, planning docs, risk register, release notes)
- Consistent tracking and communication of progress and risks
- Continuous improvement through retrospectives and feedback loops

## Documents Directory

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](octoacme-roles-and-personas.md)
