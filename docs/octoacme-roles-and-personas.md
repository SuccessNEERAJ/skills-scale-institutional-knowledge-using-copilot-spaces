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

## Technical Lead / Architect

### Role Summary
Technical Leads provide strategic technical direction and ensure system designs align with long-term scalability, performance, and maintainability goals. They partner with developers and product managers to navigate technical complexity and reduce architectural risk.

### Responsibilities
- Lead technical design reviews and architecture decisions
- Assess technical risks and propose mitigation strategies
- Mentor developers on design patterns and best practices
- Collaborate with Product Managers on technical feasibility and trade-offs
- Ensure code quality standards and testing practices are met
- Identify technical debt and prioritize refactoring work
- Establish and maintain technical standards and guidelines

### Goals
- Ensure systems are scalable, maintainable, and performant
- Reduce technical risk and technical debt accumulation
- Enable team velocity through clear architectural guidance
- Foster a culture of technical excellence

### Typical Communication
- Technical design reviews with developers and product teams
- Architecture decision records (ADRs)
- Technical risk assessments in planning and weekly syncs
- Collaboration with Release Manager on deployment strategy

### Key Interactions
- **Developers**: Reviews designs, mentors on implementation, provides technical guidance
- **Product Managers**: Advises on feasibility, technical trade-offs, and long-term scalability impact
- **Project Managers**: Escalates technical blockers and risks; collaborates on mitigation planning
- **Release Manager**: Advises on deployment strategy and system compatibility

---

## Release Manager

### Role Summary
Release Managers coordinate all release activities, manage deployment schedules, communicate timelines to stakeholders, and oversee rollback procedures. They ensure smooth, predictable releases and maintain post-deployment stability.

### Responsibilities
- Coordinate release planning and deployment windows
- Manage release notes and stakeholder communications
- Oversee staging environment testing and sign-off
- Execute or coordinate production deployments
- Manage rollback procedures and incident response
- Track release metrics and post-deployment verification
- Ensure deployment runbooks are current and accessible

### Goals
- Deliver releases on schedule with minimal risk
- Reduce mean time to recovery (MTTR) from incidents
- Maintain clear, consistent stakeholder communication about releases
- Establish repeatable, reliable deployment processes

### Typical Communication
- Release planning meetings with project and product teams
- Deployment coordination and status updates
- Post-deployment verification reports
- Incident and escalation communications

### Key Interactions
- **Project Manager**: Aligns on release timeline, dependencies, and stakeholder communication
- **Developers**: Coordinates deployment artifacts, runbooks, and rollback procedures
- **QA Lead**: Confirms readiness and conducts final smoke tests before production deployment
- **Technical Lead**: Reviews deployment strategy and validates system compatibility

---

## Quality Assurance Lead

### Role Summary
QA Leads own testing strategy, automation, and quality metrics. They ensure features meet acceptance criteria and maintain system reliability and performance.

### Responsibilities
- Define and maintain testing strategy (unit, integration, end-to-end)
- Oversee test automation and CI/CD integration
- Establish quality metrics and acceptance criteria frameworks
- Lead manual QA and feature validation efforts
- Identify quality risks and propose mitigation approaches
- Coordinate with developers on testability and design for testing
- Report quality metrics and trends to project leadership

### Goals
- Ensure high-quality releases with minimal defects
- Increase testing efficiency through automation
- Provide early visibility into quality risks
- Enable fast, confident deployment cycles

### Typical Communication
- QA planning during sprint/iteration planning
- Quality metrics and defect reports
- Test case reviews and automation updates
- Release readiness assessments

### Key Interactions
- **Developers**: Collaborates on testability, test design, and quality standards
- **Project Managers**: Reports on quality metrics and risks; participates in release planning
- **Release Manager**: Conducts final smoke tests and confirms release readiness
- **Product Managers**: Validates acceptance criteria and feature quality

---

## Scrum Master / Agile Coach

### Role Summary
Scrum Masters facilitate agile ceremonies, remove blockers, and coach the team on process adherence and continuous improvement. They champion agile practices and create a culture of accountability and learning.

### Responsibilities
- Facilitate sprint planning, daily standups, reviews, and retrospectives
- Remove impediments and blockers that slow team velocity
- Coach team members on agile principles and practices
- Maintain sprint health metrics and team velocity trends
- Facilitate cross-team coordination and dependency management
- Support retrospectives and drive action items to completion
- Help teams adapt processes based on feedback and outcomes

### Goals
- Enable consistent, predictable team velocity
- Foster psychological safety and continuous improvement
- Remove organizational blockers to team productivity
- Maintain clear, visible sprint progress

### Typical Communication
- Facilitation of all agile ceremonies
- Blocker escalations to Project Manager and leadership
- Retrospective action item tracking
- Team health and velocity reporting

### Key Interactions
- **Project Manager**: Escalates organizational blockers and risks; coordinates dependency management
- **All Team Members**: Facilitates ceremonies, removes impediments, coaches on agile practices
- **Team Leadership**: Reports on team health, velocity, and process improvement needs

---

## Stakeholder / Sponsor

### Role Summary
Stakeholders and Sponsors provide business context, strategic guidance, and approvals for projects. They represent customer and business interests and enable decision-making at escalation points.

### Responsibilities
- Define business objectives and success criteria
- Provide strategic context and priority for projects
- Approve scope changes and major decisions
- Communicate project status to executive leadership
- Identify and escalate blockers to project delivery
- Provide feedback on deliverables and outcomes
- Support resource allocation and cross-team coordination

### Goals
- Ensure projects align with business strategy
- Enable clear prioritization and decision-making
- Maintain executive visibility and stakeholder alignment
- Maximize business value delivered

### Typical Communication
- Project kickoff and milestone reviews
- Monthly/quarterly stakeholder updates
- Scope change and decision approvals
- Escalation of blockers and risks

### Key Interactions
- **Product Manager**: Collaborates on business objectives, prioritization, and success metrics
- **Project Manager**: Receives status updates, provides approvals, escalates decisions
- **Team Leadership**: Provides strategic guidance and resource support

---

## Documentation Specialist

### Role Summary
Documentation Specialists capture organizational knowledge, maintain process documentation, create onboarding materials, and ensure information accessibility across the team. They convert tribal knowledge into discoverable, searchable artifacts.

### Responsibilities
- Maintain and update process documentation
- Create and refine onboarding guides for new team members
- Document lessons learned and best practices from projects
- Organize and index institutional knowledge
- Support retrospectives by capturing action items and insights
- Ensure documentation is discoverable and up-to-date
- Facilitate knowledge-sharing sessions and documentation reviews

### Goals
- Reduce onboarding time and single-person dependency risk
- Preserve organizational knowledge and institutional memory
- Improve team consistency and process adherence
- Enable self-service access to critical information

### Typical Communication
- Documentation planning and reviews
- Knowledge-sharing sessions
- Retrospective support and capture
- Updates to process and onboarding artifacts

### Key Interactions
- **All Roles**: Gathers inputs on processes, decisions, and lessons learned
- **Project Manager**: Collaborates on project documentation and retrospective capture
- **Product Manager**: Documents product vision, roadmap rationale, and success metrics
- **Scrum Master**: Supports retrospectives and captures action items for team learning

---

## DevOps Engineer / Infrastructure Specialist

### Role Summary
DevOps Engineers design, build, and maintain infrastructure, deployment pipelines, and operational systems that enable reliable, scalable software delivery. They bridge development and operations to automate processes and reduce manual effort.

### Responsibilities
- Design and maintain CI/CD pipelines and automation
- Manage development, staging, and production environments
- Implement infrastructure-as-code and configuration management
- Monitor system performance, reliability, and security
- Troubleshoot deployment issues and coordinate rollbacks
- Document runbooks and operational procedures
- Collaborate on scalability and performance improvements

### Goals
- Enable fast, reliable, repeatable deployments
- Minimize manual operational overhead
- Maintain high system availability and performance
- Reduce deployment risk through automation and monitoring

### Typical Communication
- Deployment planning and coordination
- CI/CD pipeline reviews and improvements
- Incident response and post-incident reviews
- Infrastructure and performance metrics discussions

### Key Interactions
- **Release Manager**: Coordinates deployment windows and executes releases
- **Developers**: Ensures code meets deployability standards; supports troubleshooting
- **Technical Lead**: Advises on infrastructure architecture and scalability
- **QA Lead**: Coordinates environment setup and test infrastructure

---

## Security & Compliance Officer

### Role Summary
Security & Compliance Officers ensure that projects adhere to security standards, compliance requirements, and risk management policies. They identify security risks, validate controls, and enable secure, compliant delivery.

### Responsibilities
- Define and enforce security standards and practices
- Conduct security reviews and threat assessments
- Validate compliance with regulatory and internal requirements
- Review code and infrastructure for security vulnerabilities
- Lead incident response for security events
- Maintain security and compliance documentation
- Provide security guidance and training to teams

### Goals
- Prevent security vulnerabilities and breaches
- Ensure regulatory compliance and audit readiness
- Build a culture of security awareness
- Enable secure, compliant innovation

### Typical Communication
- Security reviews during planning and design phases
- Vulnerability assessments and remediation tracking
- Compliance audits and status reporting
- Incident response and post-incident reviews

### Key Interactions
- **Product Managers**: Advises on security and compliance implications of features
- **Technical Lead**: Reviews architecture for security and scalability concerns
- **Developers**: Provides secure coding guidance and reviews security-critical code
- **Release Manager**: Validates security readiness before production release
- **Project Manager**: Escalates compliance blockers and risk factors

---

## Customer Success / User Advocate

### Role Summary
Customer Success Specialists and User Advocates represent end-user needs, collect customer feedback, and ensure that delivered solutions truly solve customer problems. They bridge the gap between customer reality and product decisions.

### Responsibilities
- Gather and synthesize customer feedback and usage data
- Conduct user research and usability testing
- Validate solutions against customer needs and pain points
- Communicate customer insights to product and engineering teams
- Support customer onboarding and adoption
- Track customer satisfaction and success metrics
- Identify feature gaps and improvement opportunities

### Goals
- Ensure solutions deliver real customer value
- Increase customer satisfaction and retention
- Reduce feature waste by validating assumptions
- Build products that customers love to use

### Typical Communication
- Customer feedback summaries and insights
- Usability test results and recommendations
- Feature validation and acceptance criteria review
- Customer success metrics and trends

### Key Interactions
- **Product Managers**: Provides customer insights to inform prioritization
- **Developers**: Collaborates on feature validation and user experience
- **QA Lead**: Partners on acceptance criteria and user acceptance testing
- **Project Manager**: Participates in planning and milestone reviews
- **Stakeholders**: Reports on customer impact and business outcomes

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference these role definitions when documenting processes, responsibilities, and decision authorities.
