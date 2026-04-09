# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

For accountability mapping across roles, see the [RACI Cheatsheet](octoacme-roles-raci-cheatsheet.md).

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

### Interaction with Other Roles
- **Product Managers**: Receive feature specs and acceptance criteria; surface technical constraints.
- **Project Managers**: Report progress and blockers in standups and weekly syncs.
- **UX Designer**: Collaborate on feasibility and implement designs.
- **QA Lead**: Support test planning and resolve defects.
- **Tech Lead**: Follow technical direction and escalate architectural questions.

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

### Interaction with Other Roles
- **Developers**: Provide requirements and accept completed work.
- **Project Managers**: Align on priorities, timelines, and scope changes.
- **UX Designer**: Co-define user flows and validate designs against user needs.
- **Business Analyst**: Receive documented requirements and user stories.
- **Stakeholders**: Gather input and report on product outcomes.

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

### Interaction with Other Roles
- **Developers / Scrum Master**: Remove blockers and track delivery progress.
- **Product Managers**: Sync on scope, priority, and milestone targets.
- **Release Manager**: Coordinate release scheduling and readiness gates.
- **Stakeholders**: Provide regular status updates and escalation decisions.

---

## Scrum Master / Delivery Lead

### Role Summary
The Scrum Master (or Delivery Lead) facilitates agile ceremonies, removes impediments, and coaches the delivery team on agile practices. They protect the team's focus and promote continuous improvement.

### Responsibilities
- Facilitate standups, sprint planning, reviews, and retrospectives
- Identify and remove impediments blocking team progress
- Shield the team from unplanned interruptions
- Coach team members on agile principles and practices
- Track team velocity and highlight delivery risks early

### Goals
- Enable the team to deliver predictably and sustainably
- Foster a culture of continuous improvement
- Reduce cycle time and process waste

### Typical Communication
- Daily standup facilitation
- Sprint retrospective action item tracking
- Escalation of persistent blockers to the Project Manager

### Interaction with Other Roles
- **Developers**: Coach on agile practices; remove day-to-day impediments.
- **Product Managers**: Protect sprint scope; facilitate backlog refinement.
- **Project Managers**: Escalate blockers that require cross-team coordination or sponsor involvement.
- **Stakeholders**: Facilitate sprint reviews and gather feedback.

---

## UX Designer / Product Designer

### Role Summary
The UX Designer represents user needs and designs solutions that are intuitive, accessible, and aligned with business goals. They bridge user research and engineering implementation.

### Responsibilities
- Conduct user research, interviews, and usability testing
- Create wireframes, prototypes, and design specifications
- Define and maintain design systems and standards
- Advocate for accessibility and inclusive design
- Collaborate with engineers on feasibility and implementation fidelity

### Goals
- Deliver experiences that are easy to use and meet user needs
- Reduce rework by validating designs before development
- Maintain design consistency across the product

### Typical Communication
- Design reviews with Product and Engineering
- Usability test results shared with the full team
- Annotated specs and prototype links in Figma or equivalent tools

### Interaction with Other Roles
- **Product Managers**: Co-define user flows; validate designs against product goals and user research.
- **Developers**: Provide specs and assets; review implementation for design fidelity.
- **Business Analyst**: Align on user requirements and acceptance criteria.
- **Stakeholders**: Present prototypes and research findings for feedback.
- **QA Lead**: Ensure test plans include usability and accessibility checks.

---

## Business Analyst

### Role Summary
The Business Analyst bridges the gap between business stakeholders and the delivery team. They document requirements, map processes, and help ensure the delivered solution solves the right problem.

### Responsibilities
- Elicit and document business requirements from stakeholders
- Write detailed user stories and acceptance criteria
- Create process maps and data flow diagrams as needed
- Support User Acceptance Testing (UAT) and sign-off
- Identify process gaps and recommend improvements

### Goals
- Ensure the team builds what stakeholders actually need
- Reduce ambiguity by providing clear, testable requirements
- Improve traceability from business need to delivered feature

### Typical Communication
- Requirements workshops and stakeholder interviews
- User story backlog updates and acceptance criteria reviews
- UAT planning and defect triage

### Interaction with Other Roles
- **Product Managers**: Translate business objectives into user stories and priority guidance.
- **Developers**: Clarify requirements and edge cases during development.
- **UX Designer**: Align user requirements with proposed user flows and designs.
- **Project Managers**: Flag scope changes and dependency impacts early.
- **Stakeholders**: Facilitate requirements gathering and UAT sessions.

---

## Release Manager

### Role Summary
The Release Manager coordinates and oversees the release of product increments to production. They ensure all quality, compliance, and communication gates are met before and after deployment.

### Responsibilities
- Plan and publish release schedules and deployment windows
- Confirm release readiness (CI passing, sign-offs complete, rollback plan documented)
- Coordinate deployment activities across Dev, QA, and Operations
- Manage release communications to stakeholders and support teams
- Lead post-release verification and escalate incidents if needed

### Goals
- Deliver releases that are low-risk, well-communicated, and reversible
- Reduce time-to-recovery for failed releases
- Maintain a clear audit trail for each release

### Typical Communication
- Release readiness meetings with PM and QA
- Deployment notifications to stakeholders and support
- Post-release summary reports

### Interaction with Other Roles
- **Developers**: Confirm all PRs merged, release notes drafted, and deployment artifacts ready.
- **QA Lead**: Validate that acceptance and regression testing are complete before go/no-go.
- **Project Managers**: Align release schedule with milestone commitments and stakeholder expectations.
- **Product Managers**: Confirm feature completeness and sign-off on scope.
- **Stakeholders**: Communicate release date, scope, and any known issues.

---

## Tech Lead / Architect

### Role Summary
The Tech Lead provides technical direction, sets engineering standards, and ensures the system architecture supports current and future product needs.

### Responsibilities
- Define and maintain the technical architecture and key design decisions
- Lead code reviews and establish coding standards
- Identify and mitigate technical debt and security risks
- Guide developers on complex implementation challenges
- Evaluate and select tools, frameworks, and third-party services

### Goals
- Maintain a scalable, secure, and maintainable codebase
- Reduce architectural risk across the system
- Accelerate developer productivity through clear standards

### Typical Communication
- Technical design reviews and Architecture Decision Records (ADRs)
- Code review feedback
- Engineering guild or community of practice discussions

### Interaction with Other Roles
- **Developers**: Provide technical guidance, conduct code reviews, and unblock design decisions.
- **Product Managers**: Communicate technical constraints and trade-offs.
- **Project Managers**: Surface technical risks and dependency impacts.
- **Release Manager**: Confirm deployment readiness from a technical perspective.

---

## QA Lead

### Role Summary
The QA Lead owns the quality strategy for the project, ensuring that testing is thorough, efficient, and aligned with the Definition of Done.

### Responsibilities
- Define the test strategy and QA approach for each release
- Write and maintain automated and manual test plans
- Coordinate QA activities across sprints and releases
- Report defects and track resolution in collaboration with Developers
- Ensure acceptance criteria and Definition of Done are met before release

### Goals
- Prevent defects from reaching production
- Improve test coverage and automation over time
- Provide clear quality signals throughout the delivery lifecycle

### Typical Communication
- Test reports and defect summaries per sprint and release
- QA sign-off in release readiness reviews
- Collaboration with Developers during feature testing

### Interaction with Other Roles
- **Developers**: Collaborate on test case design and defect resolution.
- **Product Managers**: Validate that delivered features meet acceptance criteria.
- **Release Manager**: Provide QA sign-off before production deployment.
- **Business Analyst**: Review acceptance criteria to ensure testability.
- **UX Designer**: Include usability and accessibility checks in test plans.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- For a one-page accountability reference, see the [RACI Cheatsheet](octoacme-roles-raci-cheatsheet.md).

