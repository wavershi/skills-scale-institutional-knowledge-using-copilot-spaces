# OctoAcme — RAID Log Template

## Purpose
The RAID Log captures **Risks, Assumptions, Issues, and Dependencies** in one place. It is the single source of truth for items that could affect project delivery and should be reviewed at every weekly sync.

> **Owner**: Project Manager maintains the log; all team members contribute entries.  
> **Cadence**: Review and update at every weekly delivery sync.

---

## Risks

Items that *might* negatively affect the project if they occur.

| ID | Description | Impact (H/M/L) | Likelihood (H/M/L) | Owner | Mitigation / Contingency | Status | Date Added |
|----|-------------|---------------|-------------------|-------|--------------------------|--------|------------|
| R-01 | _Example: Third-party API may have rate limits under load_ | H | M | Tech Lead | Load-test against rate limits in sprint 3; negotiate quota increase | Open | YYYY-MM-DD |

**Status values**: Open · Mitigated · Accepted · Closed

---

## Assumptions

Statements believed to be true that, if proven false, could impact scope or schedule.

| ID | Assumption | Owner | Validation Method | Validated? | Date Added |
|----|------------|-------|-------------------|------------|------------|
| A-01 | _Example: Users have stable internet connectivity_ | Product Manager | User research / analytics | No | YYYY-MM-DD |

---

## Issues

Problems that have **already occurred** and need resolution.

| ID | Description | Impact (H/M/L) | Owner | Resolution / Action | Status | Date Raised | Date Closed |
|----|-------------|---------------|-------|---------------------|--------|-------------|-------------|
| I-01 | _Example: CI pipeline failing on Windows runners_ | M | Tech Lead | Investigate Node version mismatch; target fix by next sprint | In Progress | YYYY-MM-DD | — |

**Status values**: Open · In Progress · Resolved · Closed

---

## Dependencies

Internal or external items the project relies on to proceed.

| ID | Description | Type (Internal / External) | Depends On (team/system) | Due By | Owner | Status | Notes |
|----|-------------|---------------------------|--------------------------|--------|-------|--------|-------|
| D-01 | _Example: Auth service API contract to be finalized_ | Internal | Platform team | YYYY-MM-DD | Project Manager | Pending | Raise in weekly sync if not resolved by sprint 2 |

**Status values**: Pending · In Progress · Resolved · Blocked

---

## How to use this log

1. **Add entries early** — log items as soon as they are identified, not just at milestones.
2. **Assign owners** — every row must have a named owner responsible for driving resolution.
3. **Review weekly** — the Project Manager reviews the log in the weekly delivery sync and updates statuses.
4. **Escalate when needed** — if an issue or risk reaches High impact with no clear mitigation, escalate per the [Escalation Paths](octoacme-risks-and-communication.md#escalation-paths).
5. **Close completed items** — mark resolved items Closed (don't delete) to preserve history.

---

## Related docs
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
