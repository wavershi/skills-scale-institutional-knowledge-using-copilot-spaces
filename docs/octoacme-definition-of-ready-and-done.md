# OctoAcme — Definition of Ready & Definition of Done

## Purpose
These shared definitions ensure the team pulls only well-prepared work into a sprint (Definition of Ready) and only ships work that truly meets quality standards (Definition of Done). Both checklists are owned by the team and should be reviewed and updated at retrospectives.

---

## Definition of Ready (DoR)

A backlog item is **Ready** to be pulled into a sprint when **all** of the following are true:

- [ ] User story or task is written in a clear format (e.g., *As a [user], I want [goal] so that [benefit]*)
- [ ] Acceptance criteria are defined and unambiguous
- [ ] Dependencies identified and resolved (or a plan is in place)
- [ ] Design assets / specs available (if UI work is involved)
- [ ] Item is estimated by the delivery team
- [ ] Item fits within one sprint; if not, it has been split
- [ ] No unresolved blocking questions or open decisions

> **Who enforces this?** The Scrum Master / Delivery Lead and Product Manager during backlog refinement.

---

## Definition of Done (DoD)

A backlog item (feature, fix, or story) is **Done** when **all** of the following are true:

### Code Quality
- [ ] Code is merged to the main/release branch via approved PR
- [ ] All automated tests (unit, integration) pass in CI
- [ ] No new linting errors or security scan warnings introduced
- [ ] Code reviewed and approved by at least one peer

### Functionality
- [ ] Acceptance criteria met and verified by the developer
- [ ] QA / testing sign-off completed (manual or automated)
- [ ] Edge cases and error handling tested

### Documentation & Observability
- [ ] Relevant documentation updated (README, API docs, runbook)
- [ ] Logging and monitoring in place for new functionality
- [ ] Release notes entry drafted (if customer-facing change)

### Process
- [ ] Linked issue / ticket updated and closed
- [ ] Any new risks or dependencies logged in the [RAID Log](octoacme-raid-log-template.md)

> **Who enforces this?** The QA Lead and the developer; the Scrum Master facilitates the conversation if disputes arise.

---

## Release-Level Definition of Done

A release is **Done** when all of the following are true:

- [ ] All features in scope meet the item-level DoD above
- [ ] Release notes reviewed and approved by the Product Manager
- [ ] Security and compliance checks passed
- [ ] Rollback plan documented and tested
- [ ] Release Manager has issued a go/no-go decision
- [ ] Stakeholder announcement prepared

See the [Release & Deployment Guide](octoacme-release-and-deployment.md) for the full deployment checklist.

---

## Updating these definitions
- Review DoR and DoD at each retrospective.
- Propose changes as a team; record the rationale in retrospective notes.
- Avoid adding items that the team cannot consistently meet — quality of execution beats length of checklist.

---

## Related docs
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [RAID Log Template](octoacme-raid-log-template.md)
