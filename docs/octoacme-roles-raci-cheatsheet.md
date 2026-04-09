# OctoAcme — Roles RACI Cheatsheet

## Purpose
This cheatsheet maps key project activities to roles using the **RACI** framework:

| Letter | Meaning |
|--------|---------|
| **R** | **Responsible** — does the work |
| **A** | **Accountable** — owns the outcome; signs off |
| **C** | **Consulted** — provides input before/during |
| **I** | **Informed** — notified of decisions/outcomes |

> Abbreviations used below: PM = Project Manager · PdM = Product Manager · Dev = Developer(s) · SM = Scrum Master · UX = UX Designer · BA = Business Analyst · RM = Release Manager · TL = Tech Lead · QA = QA Lead

---

## RACI Matrix

| Activity | PM | PdM | Dev | SM | UX | BA | RM | TL | QA |
|----------|----|-----|-----|----|----|----|----|----|-----|
| **Initiation** | | | | | | | | | |
| Define problem statement & goals | C | A | I | I | C | C | I | I | I |
| Identify stakeholders | A | R | I | I | I | C | I | I | I |
| Draft Communication Plan | R/A | C | I | I | I | I | I | I | I |
| Go / no-go decision | C | A | I | I | I | I | I | C | I |
| **Planning** | | | | | | | | | |
| Backlog creation & prioritization | C | A/R | C | C | C | R | I | C | C |
| User story writing & acceptance criteria | I | C | C | I | C | R/A | I | I | C |
| Estimation | C | C | R | A | C | C | I | C | C |
| Define DoR / DoD | C | C | R | A | C | C | I | R | R |
| RAID log setup | R/A | C | C | C | I | C | C | C | I |
| Release planning | R | A | C | C | I | I | R | C | C |
| **Execution** | | | | | | | | | |
| Feature development | I | I | R/A | I | C | I | I | C | I |
| UX design & prototyping | I | C | C | I | R/A | C | I | I | I |
| Requirements clarification | I | C | C | I | C | R/A | I | I | I |
| Daily standup facilitation | I | I | C | R/A | I | I | I | I | I |
| Risk register updates | R/A | C | C | C | I | I | I | C | I |
| Blocker escalation (team-level) | C | I | I | R/A | I | I | I | I | I |
| Blocker escalation (cross-team) | R/A | C | I | C | I | I | I | I | I |
| **Quality & Testing** | | | | | | | | | |
| Test strategy & plan | I | C | C | I | C | C | I | C | R/A |
| Unit / integration testing | I | I | R/A | I | I | I | I | C | I |
| QA sign-off per sprint | I | C | C | I | C | I | I | I | R/A |
| Accessibility testing | I | C | C | I | C | I | I | I | C |
| **Release** | | | | | | | | | |
| Release readiness review | C | C | C | I | I | I | R/A | C | C |
| Deployment coordination | C | I | C | I | I | I | R/A | C | I |
| Go / no-go decision (release) | C | C | I | I | I | I | R/A | C | C |
| Release notes | I | A | C | I | I | I | R | I | C |
| Stakeholder release announcement | C | C | I | I | I | I | R/A | I | I |
| **Retrospective** | | | | | | | | | |
| Retro facilitation | C | I | C | R/A | I | I | I | I | I |
| Action item tracking | R/A | I | C | C | I | I | I | I | I |

---

## Notes
- A single activity should have **only one A** (accountable). If you see two, clarify with the team.
- This cheatsheet is a starting point — adjust to your team's actual structure.
- For full role descriptions, see [Roles & Personas](octoacme-roles-and-personas.md).

---

## Related docs
- [Roles & Personas](octoacme-roles-and-personas.md)
- [Definition of Ready & Done](octoacme-definition-of-ready-and-done.md)
- [Communication Plan Template](octoacme-communication-plan-template.md)
- [RAID Log Template](octoacme-raid-log-template.md)
