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

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

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

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## UX Designer

### Role Summary
UX Designers own the user experience across all product surfaces. They translate business requirements and user research into wireframes, prototypes, and design specifications that guide development.

### Responsibilities
- Conduct user research, usability studies, and journey mapping
- Create wireframes, mockups, and interactive prototypes
- Maintain a shared design system and component library
- Define and validate acceptance criteria related to UX
- Participate in sprint reviews and provide design feedback on implemented features

### Goals
- Ensure the product is intuitive, accessible, and delightful
- Reduce rework caused by misunderstood requirements
- Bridge the gap between customer needs and technical implementation

### Typical Communication
- Design reviews and critique sessions with Product Managers and Developers
- Usability findings shared in sprint reviews or async documents
- Figma/design-tool comments and change logs

### How they interact with existing roles
- **Developers**: Share design specs and assets; answer implementation questions; review built features against designs
- **Product Managers**: Collaborate on acceptance criteria and user stories; present research findings to inform prioritization
- **Project Managers**: Flag design-related risks or scope creep; provide effort estimates for design tasks

---

## Technical Writer

### Role Summary
Technical Writers produce and maintain all user-facing and internal documentation, including release notes, API docs, onboarding guides, and runbooks. They ensure documentation is accurate, timely, and aligned with releases.

### Responsibilities
- Author and maintain product documentation, user guides, and API references
- Draft release notes for each release in coordination with Product and Engineering
- Partner with Developers and QA to verify technical accuracy
- Maintain a documentation style guide and templates
- Identify and close documentation gaps surfaced by support or CS teams

### Goals
- Ensure customers and internal teams have clear, up-to-date documentation
- Reduce support burden by proactively documenting common use cases
- Keep documentation in sync with each release cycle

### Typical Communication
- Sync with Product Manager before each release to confirm scope and release note requirements
- Async reviews of draft documentation with Developers for accuracy
- Release note drafts shared with stakeholders before deployment

### How they interact with existing roles
- **Developers**: Review code changes and PRs to capture documentation-impacting changes; coordinate on API or runbook accuracy
- **Product Managers**: Align on documentation scope and priority for each release; receive feature context and user personas
- **Project Managers**: Coordinate documentation timelines within the release plan; flag if doc tasks risk delaying release

---

## QA Lead / QA Engineer

### Role Summary
The QA Lead owns the quality assurance strategy and test execution across the project lifecycle. They define test plans, coordinate testing activities, manage defect triage, and act as the gate for release readiness.

### Responsibilities
- Design and maintain the overall test strategy and test plans
- Own and execute functional, regression, integration, and smoke testing
- Triage defects and coordinate with Developers on resolution
- Define and document the Definition of Done quality criteria
- Verify acceptance criteria are met before features are marked complete
- Manage test environments and test data

### Goals
- Prevent quality regressions from reaching production
- Accelerate feedback loops between development and testing
- Build confidence in releases through documented test coverage

### Typical Communication
- Sprint planning participation to size and schedule test tasks
- Daily standups to surface test blockers and defect status
- Test summary reports at release gates

### How they interact with existing roles
- **Developers**: Collaborate on test automation; triage and reproduce defects together; review acceptance criteria to ensure testability
- **Product Managers**: Validate acceptance criteria for new features; flag edge cases that may affect scope or priority
- **Project Managers**: Report test progress and defect trends; raise risks that could affect release timelines

---

## Customer Success Manager

### Role Summary
The Customer Success Manager (CSM) represents the voice of the customer within the team. They own the post-release feedback loop, manage customer relationships, and ensure product improvements are informed by real-world usage.

### Responsibilities
- Collect and synthesize customer feedback, support trends, and usage insights
- Represent customer needs and pain points in planning and retrospective discussions
- Partner with Product Managers to prioritize customer-driven improvements
- Communicate release changes to customers and coordinate enablement activities
- Track adoption metrics and customer health scores

### Goals
- Maximize customer satisfaction and retention
- Ensure released features deliver the expected value
- Close the feedback loop between customers and the product team

### Typical Communication
- Regular syncs with Product Manager to share customer insights
- Participation in sprint reviews and retrospectives to provide customer-facing perspective
- Customer-facing release communications and enablement sessions

### How they interact with existing roles
- **Developers**: Surface high-priority customer-reported bugs and edge cases; validate fixes solve real customer problems
- **Product Managers**: Feed customer insight data into prioritization decisions; co-own the customer feedback backlog
- **Project Managers**: Flag customer-impacting risks or timelines; coordinate customer communications around release windows

---

## Engineering Manager / Tech Lead

### Role Summary
The Engineering Manager (EM) or Tech Lead owns delivery execution from a technical standpoint. They are accountable for team health, technical decision-making, code quality standards, and removing engineering blockers.

### Responsibilities
- Own technical direction, architecture decisions, and design reviews
- Manage team capacity, growth, and hiring
- Drive technical debt reduction and ensure observability standards are met
- Escalate resourcing or technical blockers that affect project delivery
- Partner with Project Manager on timeline and risk management

### Goals
- Maintain a healthy, high-performing engineering team
- Ensure technical decisions support long-term product quality
- Reduce engineering risk and unplanned work

### Typical Communication
- Weekly engineering syncs and architecture reviews
- Cross-team dependency coordination with Project Managers
- Technical risk escalation to Product Leads and Sponsors

### How they interact with existing roles
- **Developers**: Provide technical guidance, conduct design reviews, unblock work, and support career growth
- **Product Managers**: Align on technical feasibility and trade-offs; challenge or confirm scope estimates
- **Project Managers**: Jointly manage delivery risks and timelines; escalate blockers that require cross-team coordination

---

## Security / Compliance Lead

### Role Summary
The Security/Compliance Lead ensures that security best practices are embedded across the project lifecycle and that releases meet applicable compliance and regulatory standards.

### Responsibilities
- Define and enforce security requirements for new features and infrastructure changes
- Conduct or coordinate security reviews and threat modeling sessions
- Own security scanning tooling in CI/CD pipelines
- Manage vulnerability triage and remediation timelines
- Ensure compliance with relevant standards (e.g., SOC 2, GDPR, internal policies)
- Lead or coordinate incident response for security-impacting issues

### Goals
- Prevent security vulnerabilities from reaching production
- Ensure the product meets compliance requirements without blocking delivery
- Embed security practices into everyday development workflows

### Typical Communication
- Security review checkpoints at planning and pre-release gates
- Async vulnerability reports and remediation tracking
- Incident response communications and post-incident reviews

### How they interact with existing roles
- **Developers**: Provide secure coding guidance; review security-impacting PRs; triage vulnerabilities surfaced in scans
- **Product Managers**: Flag compliance requirements that affect feature scope or timeline; advise on data privacy trade-offs
- **Project Managers**: Communicate security-related risks and remediation timelines; participate in release readiness reviews

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- See [Roles and Responsibilities Matrix](octoacme-roles-and-responsibilities-matrix.md) for a phase-by-phase ownership view across all personas.

