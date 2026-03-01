# OctoAcme Project Management Docs

This README provides an overview of OctoAcme's project management approach and links to detailed process documents that support consistent, repeatable project delivery.

## Project Management Summary

OctoAcme follows a structured, lifecycle-based approach to project management grounded in customer-first principles and iterative delivery. The organization applies five distinct phases to all cross-functional projects: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. During Initiation, teams validate business need and stakeholder alignment by producing a lightweight Project One-pager that defines the problem, goals, success metrics, and initial risks. This gates the decision to move forward only when success criteria are clear and key stakeholders are aligned. Once approved, the Planning phase transforms the initiative into an actionable backlog with prioritized items, acceptance criteria, release timelines, and a Definition of Done that sets quality expectations across the team.

Execution and Tracking emphasize daily collaboration and transparent progress management through a disciplined team rhythm: daily standups focus on blockers and dependencies, weekly delivery syncs showcase progress and flag risks, and end-of-sprint demos ensure stakeholder visibility. The team uses a project board with standard columns (Backlog, Ready, In Progress, In Review, QA, Done) and enforces quality gates including unit and integration tests, automated CI/linting, security scanning, and at least one code review approval before merging. Risk and dependency management are continuous activities—captured in a Risk Register and escalated through three levels (team triage, PM escalation to Product Lead, and sponsor-level escalation for business-impacting issues).

The OctoAcme organizational structure defines clear ownership through three core personas: **Project Managers** coordinate delivery, timelines, and risk communication; **Product Managers** define outcomes, prioritize the backlog, and measure success; and **Developers** implement features, write tests, and collaborate on design. Weekly syncs between PM and Product Manager, twice-weekly standups for the delivery team, and monthly stakeholder updates ensure alignment across all levels. Communication uses standardized templates for weekly status (progress, next steps, risks, decisions needed) and incident response, with a single source of truth maintained in the project repository.

Finally, Release & Deployment and Retrospectives close the loop on quality and learning. Before release, teams verify all acceptance criteria are met, run smoke tests, document rollback plans, and draft release notes. Post-release, structured retrospectives (45–75 minutes) capture what went well and what could improve, converting insights into prioritized action items tracked in the backlog. This emphasis on measurement, blameless incident response, and continuous improvement ensures OctoAcme teams deliver reliable, customer-focused outcomes while building institutional knowledge that accelerates future projects.

## Process Documents

Navigate to detailed guidance on each phase and aspect of OctoAcme's methodology:

- **[Project Management Overview](octoacme-project-management-overview.md)** — High-level introduction to OctoAcme's approach, principles, core roles, and key artifacts
- **[Project Initiation Guide](octoacme-project-initiation.md)** — Steps to validate business need, align stakeholders, and authorize work through the Project One-pager
- **[Project Planning](octoacme-project-planning.md)** — How to break work into shippable increments, estimate scope, and define release timelines
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Day-to-day team rhythms, quality gates, and progress tracking through sprints
- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — How to identify, assess, and communicate risks and dependencies across stakeholders
- **[Release & Deployment Guide](octoacme-release-and-deployment.md)** — Pre-release checklist, deployment procedures, and rollback playbooks
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — How to capture learnings and convert them into actionable improvements
- **[Roles and Personas](octoacme-roles-and-personas.md)** — Definitions of Project Manager, Product Manager, Developer, and other key roles and responsibilities

## Getting Started

**New to OctoAcme?** Start with the [Project Management Overview](octoacme-project-management-overview.md) for a concise introduction to our approach.

**Starting a new project?** Follow the path: Initiation → Planning → Execution → Release → Retrospective. Each phase document includes checklists and templates to guide your work.

**Looking for specific guidance?** Use the links above to jump to the phase or topic you need.

## Key Principles

- **Customer-first:** Prioritize customer value and usability in every decision
- **Iterative delivery:** Deliver small, testable increments to reduce risk and gather feedback early
- **Clear ownership:** Every project has a named Project Manager and Product Lead
- **Data-informed decisions:** Measure impact and iterate based on evidence
- **Psychological safety:** Encourage feedback, learning, and blameless continuous improvement

## Questions or Feedback?

These documents are living artifacts. If you have feedback, identified gaps, or suggestions for improvement, please open an issue using the ["Add Content to Project Management Process Docs"](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template.