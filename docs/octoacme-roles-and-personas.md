# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. A role describes an area of accountability; on smaller projects, one person may cover multiple roles. Project teams should make ownership and handoffs explicit rather than assuming every role requires a separate person.

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

## UX/UI Designers

### Role Summary
UX/UI Designers research user needs and design usable, accessible interaction flows and visual experiences for the product.

### Responsibilities
- Conduct user research and usability testing
- Create and maintain user flows, wireframes, prototypes, and design specifications
- Identify accessibility and usability considerations
- Validate proposed designs with users and stakeholders

### Goals
- Make product experiences useful, understandable, and accessible
- Reduce user friction and validate design assumptions early

### Typical Communication and Collaboration
- Partner with Product Managers to connect user research and design choices to product goals and priorities
- Work with Developers to explain design intent, resolve implementation questions, and agree practical trade-offs
- Collaborate with QA/Quality Engineers to include usability and accessibility expectations in acceptance and test coverage
- Share research findings and design decisions with Project Managers for planning and dependency tracking

---

## Business Analysts

### Role Summary
Business Analysts clarify business and stakeholder needs and translate them into traceable workflows, requirements, and acceptance criteria.

### Responsibilities
- Elicit and document stakeholder needs and existing processes
- Map workflows, business rules, and dependencies
- Help convert needs into backlog items and testable acceptance criteria
- Identify requirement gaps and support validation of proposed outcomes

### Goals
- Reduce ambiguity and rework by making requirements clear and verifiable
- Maintain alignment between business needs and delivered capabilities

### Typical Communication and Collaboration
- Work with Product Managers to clarify scope, outcomes, and backlog priorities; Product Managers retain product prioritization accountability
- Coordinate with Project Managers on stakeholder engagement, dependencies, and requirement-related risks
- Answer Developers' and QA/Quality Engineers' questions and help validate that implementation meets agreed requirements
- Bring unresolved scope or policy decisions to the appropriate Product Manager or stakeholder for resolution

---

## QA / Quality Engineers

### Role Summary
QA/Quality Engineers help the team prevent defects and assess whether changes meet acceptance criteria and are ready for release.

### Responsibilities
- Develop risk-based test approaches and identify quality risks
- Design, maintain, and execute appropriate automated and manual tests
- Validate acceptance criteria, integrations, and regression-sensitive behavior
- Report defects and communicate test results and release-blocking concerns

### Goals
- Build confidence in product quality and release readiness
- Find issues early and reduce defects reaching users

### Typical Communication and Collaboration
- Collaborate with Product Managers and Business Analysts to make acceptance criteria testable
- Work with Developers throughout implementation to review testability, automate checks, and investigate defects
- Coordinate with DevOps/Release Engineers on CI checks, environments, and smoke tests
- Share evidence and quality risks with Project Managers and Product Managers to inform readiness decisions; release approval remains with the team's designated decision-makers

---

## Tech Leads / Software Architects

### Role Summary
Tech Leads and Software Architects guide technical design and engineering practices, especially where decisions affect multiple components or teams.

### Responsibilities
- Facilitate technical design and document significant architecture decisions
- Promote maintainability, reliability, and alignment with engineering standards
- Help Developers resolve complex technical problems and review critical changes
- Identify technical dependencies and risks and propose mitigations

### Goals
- Support coherent, sustainable technical solutions
- Surface technical trade-offs and integration risks early

### Typical Communication and Collaboration
- Partner with Developers on implementation choices, reviews, and technical growth
- Explain technical options and consequences to Product Managers so product trade-offs are informed
- Work with Project Managers to expose dependencies, estimates, and delivery risks
- Coordinate with Security/Privacy Specialists and DevOps/Release Engineers on architecture, controls, operability, and deployment concerns

---

## DevOps / Release Engineers

### Role Summary
DevOps/Release Engineers enable repeatable, observable delivery through build and deployment pipelines, environments, and operational readiness practices.

### Responsibilities
- Build or maintain CI/CD pipelines and deployment automation
- Support reliable development, test, and production environments
- Improve deployment observability, recovery, and rollback readiness
- Document operational procedures and communicate release constraints

### Goals
- Make delivery repeatable and reduce deployment risk
- Help teams detect and recover from production issues effectively

### Typical Communication and Collaboration
- Partner with Developers and QA/Quality Engineers on pipeline checks, test environments, and smoke tests
- Coordinate release sequencing, deployment windows, and operational dependencies with Project Managers
- Work with Product Managers on product-impacting release constraints and with support teams on handoffs and operational information
- Consult Tech Leads and Security/Privacy Specialists on architecture, reliability, and required controls

---

## Security / Privacy Specialists

### Role Summary
Security/Privacy Specialists advise teams on protecting systems and personal or sensitive data and on meeting applicable security and privacy requirements.

### Responsibilities
- Identify security, privacy, and compliance risks in designs and data flows
- Recommend proportionate controls and mitigations
- Review relevant designs, implementation plans, and test evidence
- Help coordinate remediation and escalate significant unresolved risks through established channels

### Goals
- Reduce security and privacy risk while enabling responsible delivery
- Make security and privacy requirements visible early enough to address effectively

### Typical Communication and Collaboration
- Work with Product Managers and Business Analysts to identify requirements and data-use expectations
- Partner with Tech Leads and Developers on design choices, secure implementation, and mitigations
- Coordinate with QA/Quality Engineers on security and privacy test coverage and evidence
- Share risks and required actions with Project Managers and designated security or privacy decision-makers; the specialist advises and does not replace formal approval or incident-response owners

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Adapt role coverage to the project's size and needs, and explicitly assign ownership for decisions, deliverables, and handoffs.

