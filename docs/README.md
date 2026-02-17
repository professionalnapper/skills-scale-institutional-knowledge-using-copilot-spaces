# OctoAcme Project Management Documentation

Welcome to the central hub for OctoAcme's project management processes, practices, and guidelines. This documentation serves as the single source of truth for how we run projects, deliver value to customers, and continuously improve our processes.

## Overview

OctoAcme follows a structured five-stage project lifecycle designed to deliver customer value through iterative, quality-focused development. Our approach emphasizes **customer-first thinking**, **clear ownership**, **data-informed decisions**, and **psychological safety**. Every project follows a consistent journey from Initiation through Planning, Execution, Release, and Retrospective, ensuring alignment across stakeholders while maintaining flexibility for team-specific needs.

Our project management framework centers on clear roles and responsibilities across four key personas: **Project Managers** coordinate delivery, schedules, risks, and communications; **Product Managers** define outcomes, prioritize the backlog, and measure success; **Developers** implement features and maintain quality standards; and **QA/Testing** validates acceptance criteria and product quality. Communication is standardized through weekly PM and Product Manager syncs, twice-weekly delivery team standups, and monthly stakeholder updates, with well-defined escalation paths from team-level triage through PM escalation to Product Lead and Sponsor levels.

Execution follows a rigorous GitHub Projects workflow with six clearly defined board columns (Backlog, Ready, In Progress, In Review, QA, Done), complemented by strict pull request standards requiring small changes (≤400 lines), issue links, acceptance criteria, and passing CI checks. Quality assurance is comprehensive, including unit tests, integration tests, end-to-end smoke tests for critical flows, security scanning in CI, and manual QA for feature acceptance. Every project maintains detailed success metrics, tracks velocity and burndown, and uses dashboards to monitor key signals like errors, latency, and usage.

Risk management and continuous improvement are embedded throughout the lifecycle. Teams maintain a risk register with detailed tracking of ID, description, impact, likelihood, owner, mitigation plan, and status, reviewed weekly during syncs. Releases follow standardized checklists with pre-release requirements, staging verification, and rollback playbooks. After each sprint, release, or milestone, teams conduct 45–75 minute retrospectives following a structured format: review what went well, identify improvements, and assign action items with clear owners and due dates. This blameless, learning-focused culture ensures continuous evolution of our processes and delivery capabilities.

## Documentation Index

This documentation is organized into focused guides covering each phase of our project lifecycle and key cross-cutting concerns:

### Core Lifecycle Documents

- **[Project Management Overview](octoacme-project-management-overview.md)** — High-level introduction to OctoAcme's project management approach, principles, core roles, key artifacts, and communication cadence
- **[Project Initiation](octoacme-project-initiation.md)** — How to validate and authorize new work, create a project one-pager, align stakeholders, and define success criteria
- **[Project Planning](octoacme-project-planning.md)** — Turning approved initiatives into actionable plans, creating prioritized backlogs, estimating scope, and managing dependencies
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Day-to-day execution guidance, GitHub Projects workflow, PR standards, quality practices, and blocker escalation
- **[Release & Deployment](octoacme-release-and-deployment.md)** — Standardized release processes, pre-release checklists, deployment workflows, and rollback playbooks
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — How to run effective retrospectives, capture learnings, and track improvement action items

### Cross-Cutting Topics

- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — Risk registers, stakeholder communication templates, escalation paths, and incident communication
- **[Roles & Personas](octoacme-roles-and-personas.md)** — Detailed definitions of Project Managers, Product Managers, Developers, and QA/Testing roles with responsibilities and communication patterns

## Quick Start for New Team Members

If you're new to OctoAcme, here's your onboarding path:

1. **Start here**: Read the **[Project Management Overview](octoacme-project-management-overview.md)** to understand our core principles, roles, and high-level lifecycle
2. **Understand your role**: Review the **[Roles & Personas](octoacme-roles-and-personas.md)** document to understand your responsibilities and how you fit into the team
3. **Learn the lifecycle**: Read through the lifecycle documents in order (Initiation → Planning → Execution → Release → Retrospective) to understand how projects flow from start to finish
4. **Dive into specifics**: Explore the risk management and communication guides to understand how we handle challenges and keep stakeholders informed

### Your First Week Checklist

- [ ] Read the Project Management Overview and Roles & Personas documents
- [ ] Attend a standup and weekly sync to observe team rhythms
- [ ] Review an active project's GitHub Projects board to see our workflow in action
- [ ] Shadow a PR review to understand our quality standards
- [ ] Join a retrospective to experience our continuous improvement culture
- [ ] Meet with your PM or team lead to discuss your first assignments

## Using Copilot Spaces for Knowledge Management

This documentation repository is designed to work seamlessly with **GitHub Copilot Spaces**, which provides AI-assisted knowledge management and context-aware guidance. By storing these process documents in your repository, you enable Copilot to:

- **Provide role-specific guidance**: Get answers tailored to your persona (PM, Product Manager, Developer, QA)
- **Answer process questions**: Ask Copilot about specific workflows, templates, or best practices without leaving your IDE
- **Accelerate onboarding**: New team members can ask Copilot questions about OctoAcme processes and get instant, contextual answers
- **Maintain consistency**: Copilot helps ensure teams follow established processes by referencing this documentation

### Tips for Using Copilot Spaces

- Add project-specific documentation to `.copilot/` in your project repositories to provide Copilot with additional context
- Use persona-based prompts when asking Copilot questions (e.g., "As a Project Manager, how should I handle this risk?")
- Keep the Project Charter and key artifacts in your repo so Copilot can reference them
- Refer to these documentation files when asking Copilot for guidance on specific processes

## Contributing to This Documentation

These process documents are living artifacts that evolve based on team feedback and learnings. If you identify gaps, outdated information, or opportunities for improvement:

1. Open an issue describing the proposed change and why it's needed
2. Discuss with your PM or Product Lead to ensure alignment
3. Submit a pull request with your proposed updates
4. After review and approval, changes will be merged and available to all teams

## Questions or Feedback?

If you have questions about these processes or need clarification on any topic, reach out to:

- Your **Project Manager** for questions about delivery, timelines, or risk management
- Your **Product Manager** for questions about priorities, success metrics, or product decisions
- Your **Team Lead** for questions about technical implementation or team-specific practices

---

*Last updated: 2026-02-17*
