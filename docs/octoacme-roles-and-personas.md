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
Scrum Masters facilitate agile ceremonies, coach teams on scrum practices, and remove impediments to team progress. They serve as servant leaders who foster a culture of continuous improvement and self-organization.

### Responsibilities
- Facilitate sprint planning, daily standups, sprint reviews, and retrospectives
- Coach the team on agile principles and scrum practices
- Identify and remove impediments that block team progress
- Shield the team from external interruptions during sprints
- Track and communicate team velocity and sprint health

### Goals
- Improve team delivery predictability and sprint completion rates
- Reduce average impediment resolution time
- Foster a culture of continuous improvement through effective retrospectives

### Typical Communication
- Daily standups and impediment escalations
- Sprint ceremony facilitation notes and retrospective action items
- Velocity and burndown charts shared with stakeholders

### Interactions with Existing Roles
- **Developers**: Removes blockers, coaches on agile practices, and helps the team self-organize and commit to realistic sprint goals
- **Product Managers**: Ensures the backlog is refined and ready for sprint planning; helps balance scope and capacity
- **Project Managers**: Aligns agile ceremonies with overall project milestones, risk tracking, and stakeholder reporting cadences

---

## UX Designer/Researcher

### Role Summary
UX Designers and Researchers ensure that products are usable, accessible, and aligned with user needs. They conduct research to inform design decisions and collaborate with product and engineering teams to deliver intuitive experiences.

### Responsibilities
- Plan and conduct user research (interviews, usability tests, surveys)
- Create wireframes, prototypes, and interaction design specifications
- Define and maintain design systems and accessibility standards
- Synthesize research findings into actionable insights and personas
- Collaborate in sprint planning to ensure design work is ready ahead of development

### Goals
- Increase user satisfaction scores and task completion rates
- Reduce usability issues discovered post-release
- Ensure all delivered features meet accessibility guidelines

### Typical Communication
- Design reviews and prototype walkthroughs with engineering
- Research readouts and user insight summaries for product and stakeholders
- Asynchronous feedback via design tools (e.g., Figma comments) and PR reviews

### Interactions with Existing Roles
- **Developers**: Provides detailed design specifications, reviews implemented UI against designs, and clarifies interaction patterns during development
- **Product Managers**: Translates user research insights into product requirements and validates proposed solutions with users before development
- **Project Managers**: Communicates design dependencies and timelines to ensure research and design work is accounted for in the project schedule

---

## Technical Writer

### Role Summary
Technical Writers create and maintain clear, accurate, and user-focused documentation. They ensure that product knowledge is accessible to both internal teams and end users, reducing support burden and accelerating onboarding.

### Responsibilities
- Author and maintain user guides, API references, release notes, and internal runbooks
- Collaborate with engineers and product managers to document new features before release
- Review and edit content for clarity, accuracy, and consistency
- Establish and enforce documentation standards and style guides
- Manage documentation infrastructure (e.g., docs-as-code pipelines, versioning)

### Goals
- Reduce time-to-productivity for new users and team members through comprehensive documentation
- Decrease support ticket volume by proactively documenting common questions and workflows
- Maintain documentation accuracy and currency with each product release

### Typical Communication
- Feature review meetings with developers and product managers to gather documentation requirements
- Async collaboration via PRs and issue comments on documentation repositories
- Documentation status updates during sprint reviews and release planning

### Interactions with Existing Roles
- **Developers**: Reviews technical content for accuracy, attends design discussions to understand implementation details, and coordinates docs PRs alongside code PRs
- **Product Managers**: Aligns documentation scope with feature releases and ensures user-facing copy reflects product intent
- **Project Managers**: Incorporates documentation tasks into project timelines and highlights documentation risks that could delay release

---

## DevOps Engineer

### Role Summary
DevOps Engineers design, build, and operate the CI/CD pipelines, infrastructure, and tooling that enable reliable and frequent software delivery. They bridge development and operations to improve deployment speed and system stability.

### Responsibilities
- Design and maintain CI/CD pipelines for automated build, test, and deployment
- Manage cloud infrastructure, configuration-as-code, and environment consistency
- Monitor system health, define SLOs/SLAs, and lead incident response
- Implement security and compliance controls within the delivery pipeline
- Evaluate and introduce tooling to improve developer experience and operational reliability

### Goals
- Achieve and maintain deployment frequency and lead time targets (e.g., multiple deploys per week)
- Reduce mean time to recovery (MTTR) for production incidents
- Maintain pipeline reliability and minimize build failures caused by infrastructure issues

### Typical Communication
- Incident channels and post-incident review reports
- Infrastructure change proposals and runbooks shared with engineering teams
- Observability dashboards and alerting summaries for stakeholders

### Interactions with Existing Roles
- **Developers**: Collaborates on pipeline requirements, helps troubleshoot CI failures, and provides guidance on containerization and deployment best practices
- **Product Managers**: Communicates infrastructure constraints that may affect release timelines or feature feasibility
- **Project Managers**: Flags operational risks and capacity constraints; contributes to release readiness checklists and go-live plans

---

## Security Lead

### Role Summary
Security Leads define and enforce security standards, conduct threat modeling, and guide teams in building secure products. They ensure that security is integrated throughout the development lifecycle rather than treated as a final gate.

### Responsibilities
- Conduct threat modeling and security reviews for new features and architecture changes
- Define and maintain security policies, standards, and secure coding guidelines
- Lead vulnerability assessments, penetration testing coordination, and remediation tracking
- Ensure compliance with relevant regulatory requirements and industry standards
- Provide security training and awareness to engineering and product teams

### Goals
- Reduce the number of high and critical vulnerabilities in production
- Achieve full coverage of security reviews for all significant feature releases
- Maintain compliance posture with zero critical audit findings

### Typical Communication
- Security review sign-offs included in feature acceptance and release checklists
- Vulnerability reports and remediation tracking shared with engineering leads
- Compliance and risk summaries presented to leadership at key project milestones

### Interactions with Existing Roles
- **Developers**: Provides secure coding guidance, reviews code for vulnerabilities, and collaborates on threat model mitigations during design and implementation
- **Product Managers**: Advises on security trade-offs when prioritizing features and ensures security requirements are included in acceptance criteria
- **Project Managers**: Communicates security review timelines and highlights compliance dependencies that could affect the project schedule

---

## Support / Customer Success Representative

### Role Summary
Support and Customer Success Representatives act as the voice of the customer within the product team. They manage customer relationships, handle incident communications, and channel user feedback into actionable insights that improve the product.

### Responsibilities
- Respond to customer inquiries, bug reports, and escalations within defined SLAs
- Document recurring issues and surface trends to product and engineering teams
- Coordinate incident communications and status page updates during outages
- Facilitate customer onboarding and training to drive adoption and reduce churn
- Maintain knowledge base articles and FAQs to enable customer self-service

### Goals
- Achieve and maintain customer satisfaction (CSAT) and net promoter scores (NPS) targets
- Reduce average ticket resolution time and repeat contact rate
- Convert customer feedback into product improvements that decrease incoming support volume

### Typical Communication
- Customer-facing communications via ticketing systems, email, and status pages
- Weekly feedback summaries and trend reports shared with product and engineering leads
- Participation in sprint reviews and release planning to flag upcoming changes that may affect customers

### Interactions with Existing Roles
- **Developers**: Reports bugs with detailed reproduction steps, validates fixes in staging environments, and provides customer context to help prioritize technical debt
- **Product Managers**: Delivers synthesized customer feedback and pain points to inform roadmap prioritization and validates that new features address real user needs
- **Project Managers**: Escalates customer-impacting risks and dependencies, and coordinates customer communication plans for releases and scheduled maintenance

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- The expanded set of personas supports cross-functional collaboration scenarios, enabling exercises that reflect real-world handoffs between delivery, design, operations, security, and customer-facing roles.
- When designing exercises or prompts, consider how multiple personas interact around a single workflow (e.g., feature delivery, incident response, release planning) to surface realistic collaboration patterns.

