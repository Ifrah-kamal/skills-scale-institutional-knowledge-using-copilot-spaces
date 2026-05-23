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

### Interactions
- Works with UX Designers to translate user flows into implementation
- Collaborates with DevOps Engineers for deployment and infrastructure concerns
- Partners with QA on testing strategies and quality assurance
- Coordinates with Business Analysts to clarify requirements

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

### Interactions
- Engages with UX Designers to validate user experience and usability
- Works with Customer Support Specialists for user insights and feedback
- Collaborates with Business Analysts on market research and business rules
- Partners with Project Managers on timeline and scope trade-offs

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

### Interactions
- Coordinates with DevOps Engineers on release planning and deployment readiness
- Works with Business Analysts to clarify scope and business requirements
- Partners with Customer Support Specialists for go-live planning
- Manages dependencies across all roles (Developers, UX, QA)

---

## UX Designer

### Role Summary
UX Designers own the user experience and interaction flows. They collaborate with Product Managers and Developers to ensure features are usable, accessible, and aligned with user needs.

### Responsibilities
- Design user flows, wireframes, and prototypes
- Conduct user research and usability testing
- Collaborate with Developers to ensure design feasibility
- Document design decisions and design systems
- Participate in design and feature reviews
- Advocate for user needs and accessibility standards

### Goals
- Deliver intuitive, usable interfaces
- Reduce user friction and support burden
- Ensure consistent brand and experience
- Validate designs through user feedback

### Typical Communication
- Design critiques and feedback sessions
- User research findings and insights
- Design specs and component documentation
- Design-to-dev handoff sessions

### Interactions
- Works closely with Product Managers to align on user needs and product strategy
- Collaborates with Developers to validate feasibility and resolve design-implementation gaps
- Coordinates with Customer Support Specialists for user feedback on existing interfaces
- Participates in retrospectives to incorporate user insights into future iterations

---

## DevOps Engineer

### Role Summary
DevOps Engineers manage infrastructure, CI/CD pipelines, and deployment automation. They ensure reliable, secure, and observable systems that support iterative delivery.

### Responsibilities
- Design and maintain CI/CD pipelines and automation
- Manage infrastructure-as-code and environment configuration
- Automate deployment processes and monitor system health
- Troubleshoot production issues and coordinate rollbacks
- Ensure security scanning and compliance in deployment
- Document runbooks and incident procedures

### Goals
- Enable fast, reliable, and safe deployments
- Maintain high system availability and performance
- Reduce deployment friction and lead time
- Ensure observability and incident response readiness

### Typical Communication
- Release planning and deployment coordination
- Infrastructure and deployment documentation
- Incident response and post-mortems
- Security and compliance updates

### Interactions
- Partners with Developers on deployment strategies and CI/CD optimization
- Coordinates with Project Managers on release timing and rollback plans
- Works with QA on smoke testing and production verification
- Collaborates on incident response and post-deployment monitoring

---

## Business Analyst

### Role Summary
Business Analysts bridge business needs and technical solutions. They gather requirements, document business rules, and ensure solutions meet both user and organizational objectives.

### Responsibilities
- Gather and document business requirements
- Create use cases and acceptance criteria
- Translate stakeholder needs into clear specifications
- Document business rules and process flows
- Conduct stakeholder interviews and discovery sessions
- Validate solutions against business objectives

### Goals
- Ensure solutions align with business strategy
- Reduce miscommunication and rework
- Improve requirements clarity for delivery teams
- Maximize business value from delivered solutions

### Typical Communication
- Requirements documentation and use cases
- Stakeholder interviews and discovery sessions
- Business process flows and decision trees
- Acceptance criteria refinement meetings

### Interactions
- Collaborates with Product Managers to refine product vision and success metrics
- Works with Project Managers to clarify scope and dependencies
- Partners with Developers and QA on acceptance criteria clarity
- Engages with Customer Support Specialists for business impact insights
- Coordinates with UX Designers on user-centric requirements

---

## Customer Support Specialist

### Role Summary
Customer Support Specialists are the voice of users and customers. They gather post-release feedback, identify issues, and inform prioritization of bug fixes and improvements.

### Responsibilities
- Triage and manage customer-reported issues
- Communicate user feedback to the product and engineering teams
- Document issue patterns and trends
- Participate in go-live planning and readiness
- Provide input on documentation and training needs
- Inform product roadmap with user insights

### Goals
- Minimize customer friction and support burden
- Identify high-impact bugs and improvements quickly
- Ensure customers have the information and support they need
- Connect user voice to product decisions

### Typical Communication
- Issue reports and escalation tracking
- Customer feedback summaries and trends
- Go-live readiness checklists and support plans
- Post-release retrospectives and feedback loops

### Interactions
- Reports issues and feedback to Developers and DevOps for triage
- Provides user insights to Product Managers for prioritization
- Collaborates with UX Designers on interface clarity and usability concerns
- Works with Project Managers on release planning and support readiness
- Partners with Business Analysts on business impact of reported issues

---

## Role Interaction Matrix

| From / To | Developers | Product Managers | Project Managers | UX Designers | DevOps Engineers | Business Analysts | Support Specialists |
|-----------|-----------|-----------------|-----------------|-------------|-----------------|------------------|-------------------|
| **Developers** | Code Reviews | Requirements Clarification | Status Updates | Design Review | Deployment Support | Requirement Details | Bug Reports |
| **Product Managers** | Estimates & Feasibility | Backlog Prioritization | Timeline Trade-offs | User Research & Usability | Release Planning | Market Research | User Feedback |
| **Project Managers** | Task Assignment | Scope & Timeline | Cross-Team Coordination | Design Schedule | Release Coordination | Scope Clarification | Go-Live Planning |
| **UX Designers** | Design Specs & Review | Strategy Alignment | Design Schedule | Design Critique | Accessibility for Release | User Requirements | Interface Feedback |
| **DevOps Engineers** | CI/CD Support | Deployment Timeline | Release Planning | Environment Setup | Infrastructure Decisions | Compliance & Security | Production Monitoring |
| **Business Analysts** | Requirement Details | Backlog Input | Scope Definition | User Flows | Business Rules | Process Documentation | Business Impact |
| **Support Specialists** | Bug Reports | User Feedback | Go-Live Support | Interface Issues | System Stability | Business Impact Trends | Issue Triage |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Refer to the Role Interaction Matrix when coordinating between teams or managing cross-functional dependencies.
