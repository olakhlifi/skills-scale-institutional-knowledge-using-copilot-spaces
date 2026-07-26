# OctoAcme Project Management Process Documentation

## Overview

OctoAcme follows a structured project management approach designed to deliver customer value through iterative development, clear ownership, and data-informed decisions. This documentation suite provides guidance for project teams throughout the complete project lifecycle.

OctoAcme employs a structured, lifecycle-based project management framework that emphasizes customer value, iterative delivery, and clear accountability. The organization operates with clear role separation where **Product Managers** define what should be built and prioritize the backlog, **Project Managers** coordinate delivery and manage risks, and **Developers** implement features while maintaining high quality. This is reinforced through a regular communication cadence of daily standups, weekly PM-PdM alignment, and monthly stakeholder updates. Quality and consistency are embedded throughout execution via a GitHub Projects board with standardized workflow columns, a Definition of Done that includes testing and code review, continuous risk management, and deliberate deployment practices with rollback planning. The organization closes the loop through retrospectives after each sprint or release, capturing learnings and prioritizing 2–3 actionable improvements to drive continuous refinement.

## Core Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has named leadership and responsibilities
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and continuous learning

## Project Lifecycle

OctoAcme projects progress through five key phases:

1. **Initiation** - Validate business need, align stakeholders, and establish go/no-go criteria
2. **Planning** - Break work into shippable increments, identify dependencies, and define success
3. **Execution** - Build, test, and iterate with regular team rhythm and quality gates
4. **Release** - Deploy to production with proper verification and rollback planning
5. **Close & Retrospective** - Capture learnings and drive continuous improvement

## Documentation Guide

### Getting Started

- **[Project Management Overview](./octoacme-project-management-overview.md)** - Start here for a concise introduction to OctoAcme's approach, core roles, and key artifacts
- **[Roles and Personas](./octoacme-roles-and-personas.md)** - Understand the key roles (PM, PdM, Developers, QA, Stakeholders) and their responsibilities

### Phase-by-Phase Guidance

- **[Project Initiation Guide](./octoacme-project-initiation.md)** - Validate ideas, define success criteria, and move through the decision gate to planning
- **[Project Planning](./octoacme-project-planning.md)** - Create prioritized backlogs, estimate scope, and build your release plan
- **[Execution & Tracking](./octoacme-execution-and-tracking.md)** - Manage day-to-day delivery, quality gates, and team rhythm
- **[Release & Deployment](./octoacme-release-and-deployment.md)** - Standardize release processes and deployment checklists
- **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** - Capture learnings and drive actionable improvements

### Cross-Cutting Concerns

- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** - Manage risks, escalations, and stakeholder communication throughout the project lifecycle

## How to Use These Docs

- Keep the Project Charter updated in your project repository
- Reference phase-specific guides during each stage of your project
- Add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context
- Use the checklists in each document to ensure nothing is missed

## Quick Reference Checklists

### Initiation Phase
- [ ] One-pager completed and reviewed by Product Lead
- [ ] Sponsor / Stakeholder alignment (email or meeting)
- [ ] Decision: Approve to move into planning?
- [ ] Create repo or project board skeleton
- [ ] Add initial artifacts to repo (docs/ or .copilot/)

### Planning Phase
- [ ] Project kickoff held
- [ ] Backlog prioritized and estimated
- [ ] Release timeline and milestones agreed
- [ ] Definition of Done documented
- [ ] Initial test plan / QA approach drafted

### Execution Phase
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly

### Release Phase
- [ ] Deployment window scheduled (if needed)
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications
- [ ] Announce release to stakeholders and support

## Key Resources

- **One-pager Template** - See [Project Initiation Guide](./octoacme-project-initiation.md#project-one-pager-template)
- **Backlog Item Template** - See [Project Planning](./octoacme-project-planning.md#backlog-item-template)
- **Risk Register** - See [Risk Management & Communication](./octoacme-risks-and-communication.md#risk-register)
- **Weekly Status Template** - See [Risk Management & Communication](./octoacme-risks-and-communication.md#communication-templates)
