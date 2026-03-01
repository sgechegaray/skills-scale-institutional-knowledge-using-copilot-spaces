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
- Collaborate with QA Lead on acceptance criteria and test planning
- Partner with Release Manager on deployment readiness
- Consult with Security Liaison on secure coding practices
- Receive design input and feedback from UX Designer

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
- Coordinate with UX Designer on user research and design validation
- Align with QA Lead on quality standards and acceptance criteria
- Work with Customer Support Liaison to incorporate user feedback
- Brief Release Manager on feature priority and release timing

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
- Partner with Release Manager on deployment scheduling and coordination
- Escalate risks identified by Security Liaison and other specialists
- Coordinate with Customer Support Liaison on knowledge transfer and post-launch support
- Manage cross-team dependencies involving QA Lead and other roles

---

## Release Manager

### Role Summary
The Release Manager orchestrates the end-to-end release process, ensuring smooth transitions from development through production deployment. They own release planning, deployment execution, and post-release verification.

### Responsibilities
- Plan and schedule releases (patch, minor, major)
- Coordinate pre-release requirements (testing, documentation, communications)
- Manage deployment windows and handle rollback procedures if needed
- Verify post-deployment stability and performance
- Communicate release status to stakeholders and support teams
- Document lessons learned and release metrics

### Goals
- Execute releases with minimal risk and downtime
- Ensure stakeholder and customer communication during releases
- Build repeatable, reliable deployment processes
- Enable rapid incident response and rollback when necessary

### Typical Communication
- Release notes and deployment schedules
- Pre-deployment checklists and verifications
- Incident communication and post-mortems
- Weekly release readiness briefings

### Interactions
- Work closely with Developers to confirm deployment readiness and test results
- Coordinate with QA Lead on smoke testing and final quality verification
- Collaborate with Project Manager on timeline and milestone alignment
- Brief Customer Support Liaison on new features and known issues
- Partner with Security Liaison on compliance and rollback considerations

---

## QA Lead

### Role Summary
The QA Lead owns quality assurance strategy, test planning, and acceptance validation. They ensure features meet acceptance criteria and quality standards before moving to production.

### Responsibilities
- Define test strategy and quality standards for each project
- Plan and coordinate manual and automated testing efforts
- Validate acceptance criteria with Product Manager and Developers
- Execute or coordinate test execution (unit, integration, end-to-end, smoke tests)
- Identify quality gaps and manage defect tracking
- Ensure test documentation and coverage metrics are maintained

### Goals
- Catch issues before production to minimize customer impact
- Maintain consistent quality standards across releases
- Reduce defect escape rate and improve customer satisfaction
- Enable faster iteration through effective test automation

### Typical Communication
- Acceptance criteria clarification with Product Manager and Developers
- Test plans and test case documentation
- Quality metrics and defect reports
- Pre-release smoke test sign-offs

### Interactions
- Collaborate with Developers on test design and automation
- Align with Product Manager on acceptance criteria and success metrics
- Work with Release Manager to coordinate pre-release testing
- Provide quality input to Project Manager for release readiness decisions
- Brief Customer Support Liaison on known issues and edge cases

---

## Security Liaison

### Role Summary
The Security Liaison ensures the project adheres to security best practices, identifies security risks, and communicates security requirements throughout the project lifecycle.

### Responsibilities
- Identify and assess security risks during planning and execution
- Advise on secure development practices and architectural decisions
- Review code and designs for security vulnerabilities
- Coordinate security scanning and penetration testing
- Ensure compliance with company and regulatory security standards
- Communicate security requirements and constraints to the team

### Goals
- Prevent security vulnerabilities and data breaches
- Build security awareness across the development team
- Ensure compliance with security policies and standards
- Reduce security incident risk and response time

### Typical Communication
- Security requirements and design reviews
- Vulnerability findings and remediation recommendations
- Security incident escalation and response procedures
- Compliance checklists and audit documentation

### Interactions
- Advise Developers on secure coding practices and architectural reviews
- Coordinate with Project Manager to prioritize security risks and mitigations
- Brief Release Manager on security sign-offs required before deployment
- Work with QA Lead on security testing and vulnerability scanning
- Escalate critical security issues to stakeholders and incident response team

---

## UX Designer

### Role Summary
The UX Designer represents the voice of the user, ensuring product design meets usability standards and delivers an excellent customer experience. They provide design input and validation throughout the project lifecycle.

### Responsibilities
- Conduct user research and usability validation
- Create design mockups, prototypes, and specifications
- Review features during development for design and usability alignment
- Participate in acceptance criteria definition with Product Manager and Developers
- Advocate for user needs and best practices
- Document design decisions and maintain design systems/standards

### Goals
- Deliver intuitive, user-friendly features that delight customers
- Reduce user confusion and support burden
- Maintain consistency across the product
- Incorporate user feedback into iterative improvements

### Typical Communication
- Design specs, wireframes, and prototypes
- User research findings and insights
- Design review feedback during development
- Usability testing results and recommendations

### Interactions
- Partner with Product Manager on user research and feature validation
- Collaborate with Developers during implementation to ensure design fidelity
- Work with QA Lead to define usability acceptance criteria and test scenarios
- Brief Customer Support Liaison on new UI and expected user interactions
- Provide input to Project Manager on design-related timeline implications

---

## Customer Support Liaison

### Role Summary
The Customer Support Liaison bridges frontline customer support and the development team, ensuring features address real customer needs and enabling smooth knowledge transfer at release.

### Responsibilities
- Gather and communicate customer feedback and support trends
- Identify common user issues and pain points
- Collaborate on feature definition to address customer needs
- Ensure support team has documentation and training for new features
- Coordinate post-release support enablement
- Close feedback loops by sharing product impact back to customers

### Goals
- Reduce customer support burden through well-designed, intuitive features
- Improve customer satisfaction and retention
- Enable rapid support team onboarding for new features
- Build customer empathy across the development organization

### Typical Communication
- Customer feedback summaries and trend analysis
- Feature documentation and support playbooks
- Training and knowledge transfer sessions
- Post-launch customer satisfaction metrics

### Interactions
- Advise Product Manager on customer pain points and feature priorities
- Work with UX Designer on feature usability from a support perspective
- Coordinate with Release Manager on release communication to customers
- Partner with QA Lead to identify edge cases based on customer usage patterns
- Brief Developers on customer use cases and edge cases

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the interaction sections to understand cross-functional dependencies and communication patterns.