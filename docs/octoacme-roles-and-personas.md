# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Core Personas

### Developers

#### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

#### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

#### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

#### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

#### Interactions with Other Roles
- **Product Managers**: Receive feature specs and acceptance criteria; provide technical feasibility input
- **Project Managers**: Report progress and blockers; estimate work effort
- **Quality Assurance Lead**: Collaborate on acceptance criteria; review test plans
- **DevOps Engineer**: Request deployment support; provide CI/CD pipeline feedback
- **Technical Debt Manager**: Discuss architecture decisions and refactoring priorities

---

### Product Managers

#### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

#### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

#### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

#### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

#### Interactions with Other Roles
- **Developers**: Define requirements; gather technical feasibility feedback
- **Project Managers**: Align on priorities and timelines
- **Stakeholder/Client Representative**: Validate requirements and gather business feedback
- **Technical Debt Manager**: Balance feature development with technical health
- **Compliance/Security Officer**: Incorporate compliance requirements into features

---

### Project Managers

#### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

#### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

#### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

#### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

#### Interactions with Other Roles
- **Developers**: Track progress; identify and resolve blockers
- **Product Managers**: Align on scope and priorities
- **Quality Assurance Lead**: Coordinate QA timelines and UAT planning
- **DevOps Engineer**: Plan deployment windows and release schedules
- **Stakeholder/Client Representative**: Primary communication channel for status and escalations
- **Compliance/Security Officer**: Incorporate compliance activities into project schedule

---

## Cross-Functional Personas

### Quality Assurance Lead

#### Role Summary
The Quality Assurance Lead owns the quality strategy and ensures that deliverables meet defined quality standards. They manage testing activities, coordinate user acceptance testing, and maintain quality metrics throughout the project lifecycle.

#### Responsibilities
- Define QA strategy and testing approach for each project phase
- Develop and maintain comprehensive test plans and test cases
- Oversee quality metrics and defect tracking
- Coordinate user acceptance testing (UAT) with stakeholders
- Conduct quality gate reviews before releases
- Identify quality risks and propose mitigation strategies
- Report quality status to project leadership

#### Goals
- Ensure all deliverables meet quality standards before production
- Reduce defects and rework in production
- Establish consistent, repeatable testing processes
- Enable rapid feedback cycles for continuous improvement

#### Typical Communication
- Test plans and quality metrics reports
- Quality gate reviews and sign-offs
- Defect reports and root cause analysis
- UAT coordination and results documentation

#### Interactions with Other Roles
- **Developers**: Collaborate on acceptance criteria; review code for testability; participate in design reviews
- **Product Managers**: Define acceptance criteria; validate feature completeness
- **Project Managers**: Report quality status; coordinate UAT timelines
- **Stakeholder/Client Representative**: Facilitate UAT; present quality metrics
- **Compliance/Security Officer**: Ensure compliance testing is included in QA plan

#### Key Responsibilities in Process Phases
- **Planning**: Develop QA strategy and test plan
- **Execution**: Conduct testing activities; report defects
- **Tracking**: Monitor quality metrics and defect resolution
- **Release**: Conduct final quality gate; approve for production

---

### DevOps Engineer

#### Role Summary
The DevOps Engineer builds and maintains the infrastructure, deployment pipelines, and environments that enable reliable, scalable software delivery. They bridge development and operations to automate deployment processes and ensure system reliability.

#### Responsibilities
- Design and maintain CI/CD pipelines
- Provision and manage infrastructure and environments (dev, staging, production)
- Automate deployment and release processes
- Monitor system health, performance, and uptime
- Implement security and compliance controls in infrastructure
- Troubleshoot deployment issues and provide technical support
- Document infrastructure architecture and runbooks

#### Goals
- Enable fast, reliable deployments with minimal manual effort
- Maintain high system availability and performance
- Reduce deployment risk and mean time to recovery (MTTR)
- Standardize and automate operational tasks

#### Typical Communication
- Release notes and deployment guides
- CI/CD pipeline status and metrics
- Infrastructure documentation and architecture diagrams
- On-call alerts and incident reports

#### Interactions with Other Roles
- **Developers**: Support with pipeline troubleshooting; provide CI/CD best practices
- **Project Managers**: Coordinate deployment windows and release schedules
- **Quality Assurance Lead**: Provision test environments; support automated testing
- **Release Manager**: Execute deployments; coordinate release timelines
- **Compliance/Security Officer**: Implement security controls; conduct infrastructure audits

#### Key Responsibilities in Process Phases
- **Planning**: Assess infrastructure requirements; plan deployment strategy
- **Execution**: Build/maintain pipelines; support development environment needs
- **Tracking**: Monitor pipeline health and deployment metrics
- **Release**: Execute deployments; monitor production systems

---

### Stakeholder/Client Representative

#### Role Summary
The Stakeholder/Client Representative serves as the primary liaison between the project team and business stakeholders or clients. They ensure that project outcomes align with business objectives, gather feedback, and communicate project status and risks to leadership.

#### Responsibilities
- Gather and communicate business requirements and priorities
- Provide project status updates to business leadership
- Escalate business concerns and constraints to project team
- Validate deliverables against business expectations
- Coordinate stakeholder feedback and approval gates
- Manage stakeholder communications and expectation setting
- Identify business risks and opportunities

#### Goals
- Ensure project delivers business value and ROI
- Maintain stakeholder confidence and satisfaction
- Reduce scope creep and unmanaged changes
- Enable timely decision-making and escalation resolution

#### Typical Communication
- Executive status reports and business updates
- Stakeholder feedback and approval documentation
- Business requirement specifications
- Risk and opportunity assessments

#### Interactions with Other Roles
- **Project Managers**: Provide business context; escalate issues; approve scope changes
- **Product Managers**: Validate product requirements align with business goals
- **Quality Assurance Lead**: Participate in UAT; approve quality gates
- **Developers**: Answer business questions; validate solutions
- **Compliance/Security Officer**: Ensure compliance and security requirements are understood by stakeholders

#### Key Responsibilities in Process Phases
- **Initiation**: Define business objectives and success criteria
- **Planning**: Validate scope and timeline with stakeholders
- **Execution**: Provide feedback and approve deliverables
- **Release**: Coordinate go-live readiness with business

---

### Technical Debt Manager

#### Role Summary
The Technical Debt Manager tracks and manages technical debt, balancing short-term delivery velocity with long-term system health and sustainability. They advocate for refactoring, architecture improvements, and technical investments that reduce friction and risk.

#### Responsibilities
- Identify and catalog technical debt items
- Assess impact and risk of technical debt
- Prioritize refactoring and improvement work
- Advocate for technical health in backlog prioritization
- Conduct architecture reviews and provide guidance
- Mentor developers on sustainable engineering practices
- Report on technical debt metrics and trends

#### Goals
- Reduce technical debt and system fragility over time
- Enable sustainable delivery velocity
- Reduce bug rates and maintenance burden
- Improve system architecture and developer productivity

#### Typical Communication
- Technical debt inventory and metrics
- Architecture design documents and reviews
- Refactoring proposals and business impact analysis
- Code quality reports and trend analysis

#### Interactions with Other Roles
- **Developers**: Provide architectural guidance; review design decisions; mentor on best practices
- **Product Managers**: Advocate for technical health; propose technical improvement features
- **Project Managers**: Include technical debt work in project plans
- **Quality Assurance Lead**: Ensure quality metrics include technical debt reduction
- **Compliance/Security Officer**: Address technical debt related to security and compliance

#### Key Responsibilities in Process Phases
- **Planning**: Identify technical debt items; propose refactoring work
- **Execution**: Support technical implementation; review code
- **Tracking**: Monitor technical debt metrics
- **Release**: Ensure technical debt doesn't block releases

---

### Compliance/Security Officer

#### Role Summary
The Compliance/Security Officer ensures that projects meet regulatory requirements, security standards, and organizational policies. They conduct security reviews, manage risk assessments, and ensure that compliance requirements are built into deliverables from the start.

#### Responsibilities
- Identify applicable regulatory and compliance requirements
- Conduct security reviews and threat assessments
- Review deliverables for compliance and security
- Manage security and compliance risk registers
- Provide guidance on security best practices and controls
- Audit project decisions and deliverables for compliance
- Report compliance and security status to leadership
- Coordinate with external auditors and regulatory bodies

#### Goals
- Ensure all deliverables meet security and compliance standards
- Reduce security risks and compliance violations
- Build compliance and security into development from the start
- Maintain organizational reputation and avoid regulatory penalties

#### Typical Communication
- Security review documents and findings
- Compliance requirement checklists
- Risk assessments and mitigation plans
- Audit reports and compliance certifications

#### Interactions with Other Roles
- **Project Managers**: Incorporate compliance activities into project schedule
- **Developers**: Provide security guidance; review code for vulnerabilities
- **Quality Assurance Lead**: Ensure compliance testing is included in QA plan
- **DevOps Engineer**: Implement security controls in infrastructure
- **Product Managers**: Incorporate compliance requirements into features
- **Stakeholder/Client Representative**: Communicate compliance status to stakeholders

#### Key Responsibilities in Process Phases
- **Initiation**: Identify compliance and security requirements
- **Planning**: Develop compliance strategy and security test plan
- **Execution**: Conduct security reviews; provide guidance
- **Release**: Final compliance audit; approve for production

---

## Role Interaction Matrix (RACI)

This matrix shows involvement levels for key process phases:

| Role | Initiation | Planning | Execution | Tracking | Release | Retrospective |
|------|------------|----------|-----------|----------|---------|---------------|
| **Developer** | I | R/A | R/A | A | R/A | A |
| **Product Manager** | R/A | R/A | A | A | A | C |
| **Project Manager** | R/A | R/A | A | R/A | R/A | R/A |
| **QA Lead** | I | R/A | R/A | A | R/A | A |
| **DevOps Engineer** | I | C | A | A | R/A | C |
| **Stakeholder Rep** | R/A | C | C | C | R/A | C |
| **Technical Debt Mgr** | I | C | A | A | C | A |
| **Compliance/Security** | R/A | R/A | A | A | R/A | C |

**Legend:**
- **R (Responsible)**: Does the work
- **A (Accountable)**: Final approval or decision authority
- **C (Consulted)**: Provides input and feedback
- **I (Informed)**: Kept in the loop

---

## How These Personas Are Used

- Use these persona definitions to frame scenarios and sample interactions in exercises and project planning
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance
- Reference the RACI matrix to clarify who should be involved in each project phase
- Use the interaction descriptions to understand communication flows and coordination points
- Adapt these personas to your organizational context and specific project needs
