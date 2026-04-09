# OctoAcme — Communication Plan Template

## Purpose
A Communication Plan ensures every stakeholder receives the right information, at the right frequency, through the right channel. Complete this during project initiation and update it if stakeholders or communication needs change.

> **Owner**: Project Manager drafts and maintains the plan with input from the Product Manager.

---

## Project Communication Summary

| Field | Detail |
|-------|--------|
| Project name | |
| Project Manager | |
| Communication plan version | |
| Last reviewed | |

---

## Stakeholder Register & Communication Matrix

| Stakeholder / Group | Role / Interest | Information Needed | Frequency | Channel | Owner |
|--------------------|-----------------|--------------------|-----------|---------|-------|
| Sponsor / Executive | Decision authority; budget approval | High-level status, risks, key milestones | Monthly or milestone-based | Email / executive briefing | Project Manager |
| Product Manager | Scope and priority decisions | Sprint progress, blockers, scope changes | Weekly | Sync meeting / Slack | Project Manager |
| Delivery Team | Day-to-day execution | Sprint goals, blockers, decisions | Daily | Standup / Slack | Scrum Master |
| QA Lead | Quality gate sign-off | Release readiness, defect status | Per sprint / release | Email / sync meeting | Project Manager |
| Release Manager | Deployment coordination | Release schedule, go/no-go status | Per release | Email / release readiness meeting | Project Manager |
| External Stakeholders | Business outcomes | Roadmap updates, key decisions | Monthly | Email / demo | Product Manager |
| Customer Support | Handling inbound queries | Release notes, known issues | Per release | Email / internal wiki | Release Manager |

> Adjust rows to match your project. Add or remove stakeholder groups as needed.

---

## Recurring Communication Events

| Event | Frequency | Duration | Owner / Facilitator | Audience | Output |
|-------|-----------|----------|---------------------|----------|--------|
| Daily Standup | Daily | 15 min | Scrum Master | Delivery team | Blocker log updated |
| Sprint Review / Demo | End of sprint | 30–60 min | Product Manager | Team + stakeholders | Accepted stories; feedback captured |
| Sprint Retrospective | End of sprint | 45–75 min | Scrum Master | Delivery team | Action items added to backlog |
| Weekly PM Sync | Weekly | 30 min | Project Manager | PM + PdM (+ others as needed) | Status update; risks reviewed |
| Monthly Stakeholder Update | Monthly | 30–60 min | Project Manager | All stakeholders | Status report distributed |
| Release Readiness Review | Per release | 30 min | Release Manager | PM, QA Lead, Tech Lead | Go / No-go decision |

---

## Status Report Template

Use this template for regular written status updates (email, wiki, or project tool).

```
Project: [Name]
Period: [Date range]
Status: 🟢 On Track | 🟡 At Risk | 🔴 Off Track

Progress this period:
- 

Planned for next period:
- 

Risks & blockers:
- 

Decisions needed:
- 

Key metrics / milestones:
- 
```

---

## Escalation Communication

| Scenario | First Contact | Escalation Path | Channel |
|----------|--------------|-----------------|---------|
| Sprint-level blocker | Scrum Master | Project Manager | Standup / Slack |
| Cross-team dependency stalled | Project Manager | Product Lead | Sync meeting |
| Business-impacting issue | Project Manager | Sponsor | Email / urgent call |
| Security incident | Tech Lead | Security on-call → Sponsor | Incident channel / phone |

See [Risk Management & Communication](octoacme-risks-and-communication.md) for full escalation paths.

---

## Communication Principles
- **Prefer asynchronous updates** for routine status; reserve synchronous meetings for decisions and blockers.
- **Single source of truth**: link to the project board or README rather than duplicating information.
- **Timely escalation**: do not wait for a scheduled meeting if an issue requires urgent attention.
- **Audience-appropriate detail**: executives need summaries; the delivery team needs specifics.

---

## Related docs
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Roles & Personas](octoacme-roles-and-personas.md)
- [RAID Log Template](octoacme-raid-log-template.md)
