# OctoAcme — Roles and Responsibilities Matrix

## Purpose
Map each project lifecycle phase to role ownership and collaboration expectations. This lightweight RACI-style matrix reduces ambiguity, clarifies hand-offs, and ensures the right people are consulted or informed at each stage.

**Legend**
| Symbol | Meaning |
|--------|---------|
| **R** | Responsible — does the work |
| **A** | Accountable — owns the outcome; final decision-maker |
| **C** | Consulted — provides input before or during the work |
| **I** | Informed — receives updates on progress or outcome |

---

## Phase 1: Project Initiation

*Key artifacts: Project One-pager, Stakeholder list, Initial risk list*

| Activity | Project Manager | Product Manager | Developer | UX Designer | Technical Writer | QA Lead | Customer Success Mgr | Eng Manager / Tech Lead | Security / Compliance |
|---|---|---|---|---|---|---|---|---|---|
| Draft Project One-pager | R | A | C | C | I | I | C | C | C |
| Define success metrics | C | A/R | I | C | I | I | C | C | I |
| Identify stakeholders | A/R | R | I | I | I | I | C | C | I |
| Confirm team roles & capacity | A/R | I | C | C | I | I | I | R | I |
| Go/No-go decision | C | A | I | I | I | I | I | C | I |
| Initial risk identification | R | C | C | I | I | I | I | C | C |

**Hand-offs:**
- Product Manager → Project Manager: approved One-pager and stakeholder alignment
- Project Manager → all roles: project kick-off confirmation and role assignments
- Customer Success Manager → Product Manager: customer context and existing feedback

---

## Phase 2: Project Planning

*Key artifacts: Prioritized backlog, Release plan, Definition of Done, Initial test plan, Risk register*

| Activity | Project Manager | Product Manager | Developer | UX Designer | Technical Writer | QA Lead | Customer Success Mgr | Eng Manager / Tech Lead | Security / Compliance |
|---|---|---|---|---|---|---|---|---|---|
| Backlog creation & prioritization | C | A/R | C | C | I | C | C | C | C |
| Acceptance criteria definition | C | A/R | C | R | I | C | C | C | C |
| UX design & prototyping | I | C | C | A/R | I | I | I | C | I |
| Test plan / QA approach | C | C | C | I | I | A/R | I | C | C |
| Security review planning | C | C | I | I | I | I | I | C | A/R |
| Documentation plan | C | C | I | I | A/R | I | I | I | I |
| Risk register setup | A/R | C | C | I | I | C | I | C | C |
| Release plan & milestones | A/R | C | C | I | C | C | I | C | I |
| Definition of Done | C | C | R | C | I | R | I | A/R | C |

**Hand-offs:**
- Product Manager → UX Designer: approved user stories and personas for design work
- UX Designer → Developer: finalized design specs and assets
- QA Lead → Project Manager: test timeline and resource needs for the release plan
- Security/Compliance → Engineering Manager: security requirements affecting architecture or scope

---

## Phase 3: Execution & Tracking

*Key artifacts: Project board, PR descriptions, Risk register updates, Weekly status reports*

| Activity | Project Manager | Product Manager | Developer | UX Designer | Technical Writer | QA Lead | Customer Success Mgr | Eng Manager / Tech Lead | Security / Compliance |
|---|---|---|---|---|---|---|---|---|---|
| Day-to-day feature development | I | I | A/R | C | I | C | I | C | I |
| Design review of built features | I | I | C | A/R | I | I | I | C | I |
| Code review & merge | I | I | R | I | I | I | I | A | I |
| QA / feature acceptance testing | I | C | C | C | I | A/R | I | I | I |
| Security scanning in CI | I | I | C | I | I | C | I | C | A/R |
| Risk register updates | A/R | C | C | I | I | C | I | C | C |
| Blocker escalation | A/R | C | R | C | I | C | I | C | C |
| Weekly status reporting | A/R | I | I | I | I | I | I | I | I |
| Draft documentation (in-flight) | I | I | C | I | A/R | I | I | I | I |

**Hand-offs:**
- Developer → QA Lead: feature branch or release candidate ready for testing
- QA Lead → Developer: defect reports with reproduction steps
- QA Lead → Project Manager: test status and release-blocking defect summary
- Security/Compliance → Engineering Manager: vulnerability triage and remediation priority

---

## Phase 4: Release & Deployment

*Key artifacts: Release notes, Deployment checklist, Smoke test results, Rollback plan*

| Activity | Project Manager | Product Manager | Developer | UX Designer | Technical Writer | QA Lead | Customer Success Mgr | Eng Manager / Tech Lead | Security / Compliance |
|---|---|---|---|---|---|---|---|---|---|
| Release readiness review | A/R | C | C | C | C | R | I | C | C |
| Release notes authoring | I | C | C | I | A/R | C | C | I | I |
| Final security/compliance sign-off | C | I | I | I | I | I | I | C | A/R |
| Smoke testing (staging) | C | I | C | I | I | A/R | I | C | I |
| Deployment execution | C | I | R | I | I | I | I | A | C |
| Post-deploy verification | C | I | C | I | I | R | I | C | I |
| Stakeholder release announcement | R | C | I | I | C | I | C | I | I |
| Customer enablement / comms | I | C | I | I | C | I | A/R | I | I |

**Hand-offs:**
- Technical Writer → Product Manager: draft release notes for review before publish
- QA Lead → Project Manager: go/no-go signal from testing perspective
- Security/Compliance → Project Manager: security sign-off confirmation
- Customer Success Manager → customers: release communication and enablement

---

## Phase 5: Retrospective & Continuous Improvement

*Key artifacts: Retrospective notes, Action item backlog, Improvement metrics*

| Activity | Project Manager | Product Manager | Developer | UX Designer | Technical Writer | QA Lead | Customer Success Mgr | Eng Manager / Tech Lead | Security / Compliance |
|---|---|---|---|---|---|---|---|---|---|
| Facilitate retrospective | A/R | C | C | C | C | C | C | C | C |
| Capture action items | R | C | C | C | C | C | C | C | C |
| Customer feedback synthesis | I | C | I | I | I | I | A/R | I | I |
| Technical debt review | I | I | C | I | I | C | I | A/R | C |
| Security incident review (if any) | I | I | C | I | I | I | I | C | A/R |
| Documentation retrospective | I | I | I | I | A/R | I | I | I | I |
| Track action item completion | A/R | I | C | C | C | C | C | C | C |
| Share learnings across teams | R | C | I | I | C | I | C | C | I |

**Hand-offs:**
- Customer Success Manager → Product Manager: aggregated customer feedback and improvement themes
- QA Lead → Engineering Manager: recurring quality issues for backlog prioritization
- Project Manager → all: retrospective summary and assigned action items with due dates

---

## Cross-cutting Consulted / Informed Defaults

When in doubt, apply these defaults:
- **Consulted** for any decision that directly affects your area of ownership (design, quality, security, documentation, customer impact).
- **Informed** for all release announcements, major risk changes, and milestone completions.
- Prefer async written updates (comments, status docs) to synchronous meetings for I/C communication.

---

## References
- [OctoAcme Roles and Personas](octoacme-roles-and-personas.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution and Tracking](octoacme-execution-and-tracking.md)
- [Release and Deployment](octoacme-release-and-deployment.md)
- [Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
