# OctoAcme Project Management Docs

## Overview

This folder centralizes OctoAcme’s project management processes so teams can run projects consistently and onboard quickly. The docs explain how we move from problem definition and stakeholder alignment through prioritized planning, iterative execution, deployment, and continuous improvement. They describe core artifacts, common workflows, and the roles and communication rhythms that keep projects aligned and low-risk.

## Brief summary of processes

OctoAcme runs projects iteratively and outcome-first. Work begins with a lightweight initiation (Project One‑pager) to confirm the business need and success metrics, then moves into planning where scope is broken into prioritized backlog items with acceptance criteria and a release plan. Execution is tracked on a project board and supported by a disciplined pull request workflow, automated CI (tests, linting, security scans), and layered testing (unit, integration, smoke/end-to-end). Releases follow a documented checklist including pre-release verification, rollback plans, and post-deploy checks.

Roles and responsibilities are explicit: Product Managers (PdM) set outcomes and prioritize the backlog; Project Managers (PM) coordinate delivery, risks, and stakeholder communications; Developers implement and own tests/code quality; and QA validates acceptance criteria. Communication is regular and transparent: daily standups (or twice-weekly as agreed), weekly PM+PdM syncs, demos at sprint/milestone review, and monthly stakeholder updates. Risks are tracked in a Risk Register and escalated through defined paths.

Continuous improvement is enforced through timeboxed retrospectives after sprints, releases, or incidents, capturing action items that are added back to the backlog and tracked to completion. The docs below give templates, checklists, and examples to make these practices repeatable across projects.

## Process documents in this folder

- [Project Management Overview](octoacme-project-management-overview.md)  
- [Project Initiation Guide](octoacme-project-initiation.md)  
- [Project Planning](octoacme-project-planning.md)  
- [Execution & Tracking](octoacme-execution-and-tracking.md)  
- [Risk Management & Communication](octoacme-risks-and-communication.md)  
- [Release & Deployment Guide](octoacme-release-and-deployment.md)  
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)  
- [Roles and Personas](octoacme-roles-and-personas.md)  

## Contributing & process improvements

Use the issue templates in `.github/ISSUE_TEMPLATE/` to propose changes or additions to these process documents. Keep process docs in `docs/` or `.copilot/` if you want Copilot Spaces to consume them as context.
