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

### Interaction with Other Roles
- **Engineering/Technical Lead**: Receives technical guidance, architecture decisions, and code review feedback
- **QA/Testing Lead**: Collaborates on test planning, automation, and acceptance criteria validation
- **Project Manager**: Receives sprint updates and participates in planning meetings
- **Product Manager**: Implements features based on acceptance criteria and success metrics

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
- **Project Manager**: Collaborates on planning, timelines, and resource allocation
- **Sponsor/Stakeholder**: Provides business outcomes and success metrics for approval
- **UX/Design Lead**: Works together on user research and feature validation
- **Developers**: Defines acceptance criteria and clarifies requirements
- **QA/Testing Lead**: Collaborates on acceptance criteria and quality expectations

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
- **Sponsor/Stakeholder**: Escalates risks, requests approvals, and provides executive updates
- **Product Manager**: Collaborates on priorities, scope, and trade-offs
- **Engineering/Technical Lead**: Identifies technical risks and dependencies
- **Developers & QA**: Tracks progress, manages blockers, and facilitates ceremonies
- **Release/DevOps Engineer**: Coordinates deployment schedules and release readiness

---

## QA/Testing Lead

### Role Summary
QA/Testing Leads own the quality assurance strategy and ensure that all deliverables meet acceptance criteria, performance standards, and quality gates before release.

### Responsibilities
- Define testing approach and test plans for each project
- Design and maintain automated test suites (unit, integration, end-to-end)
- Perform manual testing for user acceptance and exploratory scenarios
- Validate that acceptance criteria are met before items move to Done
- Identify and document defects with clear reproduction steps
- Collaborate with developers on test environment setup and CI configuration
- Report quality metrics and test coverage to the team

### Goals
- Ensure high-quality releases with minimal defects in production
- Reduce testing cycle time through automation
- Build customer confidence in product reliability

### Typical Communication
- Sprint planning (input on testing effort) and daily standups
- Test result summaries and release readiness reports
- Defect triage with developers and product leads

### Interaction with Other Roles
- **Developers**: Works with them on test automation, CI/CD configuration, and defect resolution
- **Product Manager**: Validates acceptance criteria and defines quality expectations
- **Project Manager**: Reports on quality metrics and identifies testing-related blockers
- **Release/DevOps Engineer**: Coordinates smoke tests, deployment validation, and release verification

---

## Engineering/Technical Lead

### Role Summary
Technical Leads provide architectural guidance, technical strategy, and risk mitigation. They ensure solutions are scalable, maintainable, and aligned with engineering standards.

### Responsibilities
- Define technical approach and architecture for new initiatives
- Conduct code and design reviews for complex components
- Identify technical risks and propose mitigations
- Mentor developers and establish coding standards
- Advocate for technical debt reduction and refactoring
- Participate in cross-team technical discussions and dependencies
- Contribute to estimation and feasibility assessments

### Goals
- Deliver technically sound, maintainable solutions
- Reduce technical debt and improve system reliability
- Enable team growth and knowledge sharing

### Typical Communication
- Design reviews and technical spike discussions
- Escalations on architectural or technical feasibility concerns
- Code review feedback and mentoring

### Interaction with Other Roles
- **Developers**: Provides technical direction, reviews code, and mentors on best practices
- **Project Manager**: Escalates technical risks and participates in planning discussions
- **Release/DevOps Engineer**: Collaborates on infrastructure decisions and deployment architecture
- **QA/Testing Lead**: Advises on testability and integration testing strategies

---

## Sponsor/Stakeholder

### Role Summary
Sponsors represent business priorities, governance, and strategic alignment. They approve budgets, scope changes, and major decisions.

### Responsibilities
- Approve project charter and business case
- Set or validate success metrics and business outcomes
- Approve scope changes and priority shifts
- Provide governance and escalation authority
- Communicate project status to executive leadership
- Remove organizational blockers
- Validate that delivered solutions meet business needs

### Goals
- Ensure projects deliver measurable business value
- Minimize scope creep and maintain budget accountability
- Maintain strategic alignment across the organization

### Typical Communication
- Monthly or milestone-based stakeholder updates
- Approval gates and decision-gate reviews
- Escalation path for major risks or changes

### Interaction with Other Roles
- **Project Manager**: Receives status reports and makes escalation decisions
- **Product Manager**: Approves business outcomes and validates strategic alignment
- **UX/Design Lead**: Reviews user research and validates solution fit with business goals
- **Release/DevOps Engineer**: Approves deployment windows and major infrastructure changes

---

## UX/Design Lead

### Role Summary
UX/Design Leads ensure that products are user-centered, intuitive, and meet user needs through research and design best practices.

### Responsibilities
- Conduct user research and define user personas
- Create wireframes, prototypes, and design specifications
- Collaborate with product to define feature requirements from a UX perspective
- Validate designs through user testing and feedback
- Establish and maintain design systems and standards
- Review implementations against design specifications
- Advocate for usability and accessibility standards

### Goals
- Deliver intuitive, user-friendly products
- Reduce user friction and support burden
- Maintain consistent brand and design standards

### Typical Communication
- Design review sessions and critique sessions
- Planning and requirements discussions with product and engineering
- Usability test results and recommendations

### Interaction with Other Roles
- **Product Manager**: Collaborates on user research, feature validation, and prioritization
- **Developers**: Reviews implementations for design compliance and provides feedback on technical constraints
- **QA/Testing Lead**: Defines usability test scenarios and validates user acceptance
- **Sponsor/Stakeholder**: Presents research findings and design validation results

---

## Release/DevOps Engineer

### Role Summary
Release/DevOps Engineers manage deployment infrastructure, automate release processes, and ensure reliable, repeatable production deployments.

### Responsibilities
- Design and maintain CI/CD pipelines and automation
- Manage deployment environments (staging, production)
- Coordinate and execute release deployments
- Monitor deployments and execute rollbacks if needed
- Maintain infrastructure, security, and compliance standards
- Document deployment procedures and runbooks
- Collaborate with engineering on testability and observability

### Goals
- Enable fast, reliable, low-risk deployments
- Minimize deployment failures and mean-time-to-recovery
- Provide visibility and observability into production systems

### Typical Communication
- Release planning and deployment coordination
- Infrastructure and security reviews
- Incident response and post-mortems

### Interaction with Other Roles
- **Developers**: Collaborates on CI/CD configuration, deployability concerns, and observability setup
- **QA/Testing Lead**: Coordinates smoke tests, deployment verification, and post-release validation
- **Project Manager**: Coordinates release schedules and communicates deployment status
- **Engineering/Technical Lead**: Aligns on infrastructure architecture and deployment strategy

---

## Scrum Master / Agile Facilitator

### Role Summary
Scrum Masters (or Agile Facilitators) coach the team on agile practices, facilitate ceremonies, and help remove impediments to smooth delivery.

### Responsibilities
- Facilitate sprint planning, standups, reviews, and retrospectives
- Track and help remove team blockers and impediments
- Coach team members on agile principles and practices
- Maintain sprint health and team morale
- Ensure ceremonies stay timeboxed and productive
- Help escalate blockers that require PM or leadership intervention
- Support continuous process improvement

### Goals
- Enable the team to self-organize and deliver consistently
- Reduce waste and improve team velocity
- Foster psychological safety and continuous learning

### Typical Communication
- Daily standups and ceremony facilitation
- One-on-ones with team members on blockers or concerns
- Retrospective action-item tracking and follow-up

### Interaction with Other Roles
- **Project Manager**: Escalates blockers and provides team health insights
- **Developers & QA**: Removes impediments and coaches on agile practices
- **All Roles**: Facilitates ceremonies and promotes team collaboration
- **Product Manager**: Ensures backlog refinement and planning process efficiency

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Understanding interactions between roles helps model realistic project dynamics and communication flows.
