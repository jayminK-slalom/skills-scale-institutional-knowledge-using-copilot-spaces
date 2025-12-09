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

## Scrum Master

### Role Summary
Scrum Masters facilitate Agile rituals, remove impediments, and support continuous improvement. They act as servant leaders, ensuring the team follows Agile principles and maintains transparency in progress and challenges.

### Responsibilities
- Facilitate daily standups, sprint planning, retrospectives, and sprint reviews
- Remove blockers and impediments that slow team velocity
- Coach the team on Agile practices and self-organization
- Shield the team from external interruptions and scope changes
- Track and improve team velocity and delivery predictability
- Foster a culture of continuous improvement and psychological safety

### Goals
- Maximize team productivity and flow
- Ensure sprint commitments are met consistently
- Improve team collaboration and communication
- Reduce waste and optimize delivery processes

### Typical Communication
- Daily facilitation of standup meetings
- Sprint retrospectives with action item tracking
- Regular check-ins with PM and Product Manager on blockers
- Metrics reporting (velocity, burndown charts, cycle time)

### Key Interactions
- **Project Manager**: Coordinates on timelines, resource needs, and escalations for blockers that require external help
- **Product Manager**: Aligns on sprint goals, backlog readiness, and acceptance criteria clarity
- **Developers**: Daily support, coaching, and impediment removal to maintain flow
- **Stakeholders**: Shields team from ad-hoc requests, channels feedback through proper ceremonies

---

## Business Analyst

### Role Summary
Business Analysts bridge the gap between business stakeholders and the delivery team by clarifying requirements, documenting workflows, and ensuring solutions meet business needs. They translate business objectives into actionable specifications.

### Responsibilities
- Elicit and document business requirements from stakeholders
- Create process flow diagrams and workflow documentation
- Define and refine user stories with clear acceptance criteria
- Conduct gap analysis between current and desired states
- Validate that delivered solutions meet business requirements
- Support user acceptance testing (UAT) coordination

### Goals
- Ensure requirements are clear, complete, and testable
- Minimize rework caused by ambiguous or incomplete specifications
- Facilitate alignment between business needs and technical solutions
- Improve stakeholder satisfaction through effective requirement management

### Typical Communication
- Requirements workshops and stakeholder interviews
- User story documentation with acceptance criteria
- Process maps and business workflow diagrams
- UAT scripts and validation reports

### Key Interactions
- **Product Manager**: Collaborates on backlog refinement, prioritization, and success metrics
- **Project Manager**: Provides requirement status updates and supports planning activities
- **Developers**: Clarifies acceptance criteria, answers questions during implementation
- **Stakeholders**: Primary liaison for gathering and validating business requirements
- **UX Designer**: Coordinates on user flows and experience requirements

---

## UX Designer

### Role Summary
UX Designers create and validate user experiences that are intuitive, accessible, and aligned with user needs. They design interfaces, conduct usability testing, and ensure the product delivers excellent user satisfaction.

### Responsibilities
- Conduct user research and usability studies
- Create wireframes, mockups, and interactive prototypes
- Define user flows and information architecture
- Establish and maintain design systems and style guides
- Collaborate on acceptance criteria for user-facing features
- Conduct usability testing and iterate based on feedback

### Goals
- Deliver intuitive, user-friendly interfaces
- Reduce user friction and support adoption
- Ensure accessibility compliance (WCAG standards)
- Maintain design consistency across the product

### Typical Communication
- Design critiques and prototype reviews
- User research findings and recommendations
- Design handoff documentation with specs and assets
- Usability test reports and iteration plans

### Key Interactions
- **Product Manager**: Aligns on user needs, feature priorities, and success metrics for user experience
- **Developers**: Provides design specifications, assets, and answers implementation questions
- **Business Analyst**: Collaborates on user flows and requirement refinement
- **Stakeholders**: Presents design concepts and gathers feedback during reviews

---

## Sponsor

### Role Summary
Sponsors set the project vision, secure funding and resources, and provide executive oversight. They are accountable for project outcomes and serve as the escalation point for critical decisions and high-level obstacles.

### Responsibilities
- Define and communicate project vision and strategic objectives
- Approve project charter, budget, and resource allocation
- Remove high-level organizational or political blockers
- Make final decisions on scope changes and priority trade-offs
- Champion the project with executive leadership and stakeholders
- Approve major milestones and sign off on project completion

### Goals
- Ensure project delivers strategic business value
- Secure necessary resources and organizational support
- Maintain alignment between project outcomes and business strategy
- Provide air cover for the team to execute effectively

### Typical Communication
- Executive steering committee updates
- Milestone approvals and go/no-go decisions
- High-level risk and escalation discussions
- Strategic alignment meetings with PM and Product Manager

### Key Interactions
- **Project Manager**: Receives status updates, provides guidance on escalations and strategic decisions
- **Product Manager**: Aligns on product vision, success metrics, and long-term roadmap
- **Stakeholders**: Represents project interests at executive level, secures cross-functional support
- **Scrum Master/Team**: Removes organizational impediments that are beyond team's control

---

## Role Interaction Matrix

This matrix shows key collaboration points between all roles:

| Role | Primary Collaborators | Key Handoffs |
|------|----------------------|--------------|
| **Developers** | PM, Product Manager, Scrum Master, BA, UX Designer | Code reviews, technical feasibility input, implementation updates |
| **Product Manager** | PM, Developers, BA, UX Designer, Sponsor, Stakeholders | Backlog prioritization, acceptance criteria, success metrics |
| **Project Manager** | All roles | Project plans, status reports, risk register, resource coordination |
| **Scrum Master** | Developers, PM, Product Manager | Sprint planning, velocity metrics, impediment escalation |
| **Business Analyst** | Product Manager, Developers, Stakeholders, UX Designer | Requirements documentation, acceptance criteria, UAT coordination |
| **UX Designer** | Product Manager, Developers, BA | Design specs, prototypes, usability findings |
| **Sponsor** | PM, Product Manager | Strategic decisions, funding approvals, executive escalations |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- The role interaction matrix helps identify who should be involved in various project activities and decision points.

