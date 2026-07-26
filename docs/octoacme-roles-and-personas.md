# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

### Key Interactions
- **With Tech Lead**: Receive architectural guidance and technical decisions
- **With QA/Test Lead**: Align on test requirements and acceptance criteria
- **With DevOps/Release Engineer**: Coordinate on deployment procedures and infrastructure needs

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics
- Gather user feedback and translate into actionable requirements

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

### Key Interactions
- **With UX/Design Lead**: Collaborate on user research, usability validation, and design specifications
- **With Security/Compliance Officer**: Incorporate security and compliance requirements into roadmap
- **With Sponsor/Stakeholder**: Present roadmap, metrics, and business impact

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication
- Track progress against milestones and escalate blockers

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

### Key Interactions
- **With Scrum Master/Agile Coach**: Partner on process improvement and sprint facilitation
- **With all roles**: Maintain project visibility and coordinate dependencies
- **With Sponsor/Stakeholder**: Report status and escalate business-impacting issues

---

## QA / Test Lead

### Role Summary
QA/Test Leads own the quality strategy, test planning, and acceptance criteria validation. They ensure deliverables meet quality standards and acceptance criteria before release.

### Responsibilities
- Define testing strategy and test plans for features and releases
- Collaborate with Product Managers on acceptance criteria clarity
- Develop and maintain test cases and automated test suites
- Execute manual and automated testing
- Track and manage defects and quality metrics
- Validate that acceptance criteria are met before QA sign-off
- Identify quality risks and propose mitigations

### Goals
- Ensure features meet acceptance criteria and quality standards
- Reduce defects in production through proactive testing
- Build confidence in release readiness

### Typical Communication
- Sprint planning and acceptance criteria reviews
- Test reports and defect documentation
- Pre-release quality gates and sign-offs

### Key Interactions
- **With Developers**: Review acceptance criteria, report defects, collaborate on test strategy
- **With Product Manager**: Clarify acceptance criteria and validate user story completeness
- **With DevOps/Release Engineer**: Coordinate smoke tests and post-deployment verification

---

## Tech Lead / Engineering Manager

### Role Summary
Tech Leads make technical architecture decisions, manage technical debt, and mentor team members. They ensure solutions are scalable, maintainable, and aligned with architectural standards.

### Responsibilities
- Define and communicate technical architecture and design patterns
- Review and approve technical designs and significant implementation decisions
- Identify and manage technical debt across sprints
- Mentor developers and guide code quality improvements
- Collaborate on technology selection and tool evaluations
- Participate in design reviews and code reviews
- Identify technical risks and propose mitigations

### Goals
- Maintain system scalability, reliability, and maintainability
- Reduce technical debt and improve code quality
- Build and develop high-performing engineering teams

### Typical Communication
- Technical design reviews and architecture discussions
- Code review guidance and technical mentoring
- Architecture decision records and technical proposals

### Key Interactions
- **With Developers**: Provide technical guidance, review designs, and mentor on best practices
- **With DevOps/Release Engineer**: Align on infrastructure requirements and operational concerns
- **With Project Manager**: Communicate technical risks and scope implications
- **With Security/Compliance Officer**: Incorporate security design principles and standards

---

## DevOps / Release Engineer

### Role Summary
DevOps/Release Engineers manage infrastructure, deployment pipelines, and release coordination. They ensure reliable, observable deployments and production systems.

### Responsibilities
- Design and maintain CI/CD pipelines and deployment automation
- Manage infrastructure, configuration, and environment provisioning
- Coordinate release planning and deployment execution
- Set up monitoring, logging, and observability systems
- Execute deployments and manage rollbacks when needed
- Develop runbooks for incident response and production troubleshooting
- Work with developers on infrastructure and deployment requirements

### Goals
- Enable frequent, reliable deployments with minimal downtime
- Maintain production system stability and observability
- Reduce deployment risk and incident response time

### Typical Communication
- Deployment schedules and release coordination
- Infrastructure requirements and capacity planning
- Incident reports and post-incident reviews

### Key Interactions
- **With Developers**: Understand application deployment requirements and runtime needs
- **With Tech Lead**: Align on infrastructure architecture and scaling strategies
- **With QA/Test Lead**: Coordinate staging environment setup and smoke tests
- **With Project Manager**: Communicate deployment windows and release readiness

---

## Scrum Master / Agile Coach

### Role Summary
Scrum Masters facilitate agile ceremonies, remove team blockers, and drive continuous process improvement. They help the team maintain a sustainable pace and effective collaboration.

### Responsibilities
- Facilitate sprint planning, daily standups, and retrospectives
- Remove impediments and blockers for the development team
- Track sprint metrics and burndown/velocity trends
- Identify process improvement opportunities and guide implementation
- Coach team members on agile practices and mindset
- Maintain sprint board and backlog health
- Support effective communication and collaboration

### Goals
- Enable team to work efficiently and sustainably
- Drive continuous process improvement and team maturity
- Maintain team morale and psychological safety

### Typical Communication
- Sprint ceremonies and retrospectives
- Impediment logs and process improvement discussions
- Team coaching and guidance

### Key Interactions
- **With Project Manager**: Partner on sprint execution and timeline tracking
- **With all team members**: Facilitate collaboration and remove blockers
- **With leadership**: Report on team health and process improvements needed

---

## UX / Design Lead

### Role Summary
UX/Design Leads conduct user research, create design specifications, and validate usability. They ensure solutions are user-centered and meet user needs effectively.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, prototypes, and design specifications
- Define user flows and interaction patterns
- Collaborate with Product Managers on feature scoping and user stories
- Validate design decisions through user feedback
- Create design systems and component libraries
- Ensure accessibility standards are met (WCAG, etc.)

### Goals
- Deliver user-centered solutions that meet user needs
- Improve user satisfaction and adoption
- Maintain design consistency and accessibility

### Typical Communication
- User research findings and design presentations
- Design specs and component documentation
- Usability test results and feedback

### Key Interactions
- **With Product Manager**: Collaborate on feature definition and user story refinement
- **With Developers**: Provide design specs, support implementation, and review for fidelity
- **With QA/Test Lead**: Define usability acceptance criteria and UX test cases

---

## Security / Compliance Officer

### Role Summary
Security/Compliance Officers identify security requirements, assess risks, and ensure compliance with standards. They embed security and compliance thinking into all project phases.

### Responsibilities
- Identify security and compliance requirements for projects
- Conduct security risk assessments and threat modeling
- Review designs and implementations for security vulnerabilities
- Manage security testing and penetration test coordination
- Track compliance obligations and audit requirements
- Maintain security documentation and policies
- Advise on incident response and security escalation

### Goals
- Prevent security incidents and data breaches
- Maintain compliance with regulatory and contractual obligations
- Build security-aware culture across the organization

### Typical Communication
- Security requirements and risk assessments
- Compliance checklists and audit documentation
- Security incident reports and lessons learned

### Key Interactions
- **With Product Manager**: Define security and compliance requirements for roadmap
- **With Tech Lead**: Review architecture for security design principles
- **With Developers**: Advise on secure coding practices and vulnerability remediation
- **With DevOps/Release Engineer**: Ensure production systems meet security standards

---

## Stakeholder / Sponsor

### Role Summary
Sponsors provide business alignment, resource approval, and executive support. They ensure projects deliver business value and have necessary organizational backing.

### Responsibilities
- Define business objectives and success criteria for projects
- Approve project charter, budget, and resources
- Provide executive sponsorship and remove organizational barriers
- Monitor business metrics and ROI
- Make business trade-off decisions (scope, timeline, resources)
- Communicate project status to executive leadership
- Support stakeholder engagement and alignment

### Goals
- Ensure projects deliver measurable business value
- Maintain executive alignment and support
- Optimize resource allocation across portfolio

### Typical Communication
- Monthly stakeholder updates and executive briefings
- Budget approvals and resource allocation decisions
- Business metrics and ROI reviews

### Key Interactions
- **With Project Manager**: Receive regular status updates and escalations
- **With Product Manager**: Review roadmap, metrics, and business impact
- **With all team members**: Provide visible executive sponsorship and remove barriers

---

## How these personas are used in the exercise

- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the key interactions section to understand cross-functional dependencies and communication patterns.
- Use the responsibilities and goals to clarify ownership and accountability in project scenarios.
