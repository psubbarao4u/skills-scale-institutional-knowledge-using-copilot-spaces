# OctoAcme Project Management — Overview

OctoAcme runs projects in a lightweight, iterative way: work starts with a Project One‑pager (problem, goal, success metrics) and a decision gate to enter planning. Approved initiatives move into planning where teams hold a kickoff, create a prioritized backlog with acceptance criteria and estimates, and define a Definition of Done. Delivery happens in timeboxed iterations with regular demos, CI‑backed PRs, and a formal release process that includes smoke tests and rollback plans.

Clear roles and responsibilities ensure ownership and fast decisions. Product Managers own outcomes and prioritization; Project Managers coordinate schedules, risks, and stakeholder communication; Developers implement and test; QA validates acceptance criteria; stakeholders provide inputs and approvals. These persona definitions and responsibilities are documented in docs/octoacme-roles-and-personas.md.

Communication is driven by predictable cadences and a single source of truth. Teams use daily standups, weekly delivery syncs, sprint demos, and monthly stakeholder updates while keeping status and artifacts in the project README/release docs and project boards. Risks are tracked in a simple Risk Register and reviewed weekly with a defined escalation path from team → PM → Product Lead → Sponsor.

Quality is enforced through small PRs, CI (tests, linters, security scans), unit/integration/e2e testing where appropriate, and manual QA for acceptance when needed. Releases follow a checklist (passing CI, release notes, staging smoke tests, and post‑deploy verification). Retrospectives convert learnings into actionable items tracked in the backlog so the team continuously improves.
