# Security Roles and Responsibilities

## Introduction

Effective security outcomes depend not just on what we do, but on **who does it** and **how responsibilities are distributed**. Many security initiatives fail despite solid technical foundations because:

- Security responsibilities are unclear or undefined
- The wrong people make security decisions
- Crucial stakeholders aren't involved at the right time
- Cross-functional dependencies aren't managed effectively
- Security requirements aren't translated for different audiences
- Security responsibilities don't scale with organizational growth

The Peak Defence Method defines a flexible framework for security roles and responsibilities that:

1. **Scales appropriately** with organizational size and complexity
2. **Balances centralization and distribution** of security responsibilities
3. **Creates clear accountability** while enabling broad participation
4. **Integrates security across functions** rather than isolating it
5. **Evolves naturally** as organizations mature

This chapter explains how to implement and evolve security roles and responsibilities across different organizational maturity levels, with particular attention to cross-functional integration. Rather than treating security as a specialized silo, we focus on creating effective interfaces between security and other organizational functions.

## Maturity Level Framework

Security roles and responsibilities evolve significantly as organizations grow. The table below illustrates how key characteristics change across maturity levels:

| Characteristic                   | Level 1: Startup                                   | Level 2: Scale-up                                       | Level 3: Enterprise                                    |
| -------------------------------- | -------------------------------------------------- | ------------------------------------------------------- | ------------------------------------------------------ |
| **Role Specialization**          | Generalist with security responsibilities          | Dedicated security roles with some specialization       | Specialized security teams with defined domains        |
| **Organizational Position**      | Part-time function within technical leadership     | Dedicated security function reporting to CTO/CIO        | Security organization with executive leadership (CISO) |
| **Decision Authority**           | Founders/technical leaders make security decisions | Security leads with business approval                   | Distributed governance with clear escalation paths     |
| **Accountability Model**         | Informal, relationship-based                       | Documented roles with basic RACI                        | Comprehensive governance framework                     |
| **Cross-Functional Integration** | Direct collaboration between team members          | Security representatives in key functions               | Federated security model with formal interfaces        |
| **Documentation**                | Simple responsibility lists                        | Role descriptions and RACI matrices                     | Comprehensive security operating model                 |
| **Boundary Artefacts**           | Simple security guidelines all teams follow        | Security responsibility matrices and service agreements | Enterprise security governance framework               |

### Progression Indicators

#### When to move from Level 1 to Level 2:

- Security tasks regularly fall through cracks due to unclear ownership
- Multiple people handle different security responsibilities
- Security workload exceeds part-time capacity
- Customers or partners request formal security documentation
- The organization needs dedicated security personnel
- Cross-functional security coordination happens inconsistently
- Security decisions need more formality and documentation

#### When to move from Level 2 to Level 3:

- Security responsibilities span multiple teams and domains
- Business units have different security needs requiring coordination
- Regulatory compliance demands comprehensive governance
- The organization has multiple specialized security functions
- Security strategy requires enterprise-wide alignment
- Cross-functional security processes need systematic management
- Security roles and responsibilities require standardization

## Core Security Roles Framework

The Peak Defence Method defines four key security roles that exist at all maturity levels, though they manifest differently as organizations grow:

### 1. Security Leaders
**Focus: Direction and guidance**
- Define security vision, principles and strategy
- Set risk appetite and tolerance
- Establish security requirements
- Make major security investment decisions
- Hold accountability for security outcomes

### 2. Security Shapers
**Focus: Problem definition and solution design**
- Identify and clarify security problems
- Define security solutions at the right level of abstraction
- Address risks and unknowns before implementation
- Create pitches for security initiatives
- Translate business needs into security requirements

### 3. Security Implementers
**Focus: Building security capabilities**
- Implement security controls and measures
- Integrate security into systems and processes
- Make tactical implementation decisions
- Track and communicate implementation progress
- Test and validate security controls

### 4. Security Enablers
**Focus: Supporting the security ecosystem**
- Provide domain-specific expertise
- Represent business or function priorities
- Create security awareness and understanding
- Facilitate security processes across functions
- Support security adoption and compliance

These roles exist across organizational functions and may be filled differently depending on maturity level. For example:

- At **Level 1 (Startup)**, the CTO might be both Strategist and Shaper, developers serve as Implementers, and the CEO acts as an Enabler
- At **Level 3 (Enterprise)**, a formal security governance committee serves as Leaders and Strategists, security architects as Shapers, specialized security teams as Implementers, and security champions across business units as Enablers

## Cross-Functional Security Responsibilities

Security is inherently cross-functional. While primary security roles may reside in dedicated security teams as organizations grow, effective security requires participation from across the organization. The following table shows key security-related responsibilities for major organizational functions:

|Function|Security Responsibilities|
|---|---|
|**Executive Leadership**|• Set security direction and risk appetite<br>• Allocate resources for security initiatives<br>• Hold ultimate accountability for security<br>• Communicate security importance to organization|
|**Product/Engineering**|• Integrate security into development lifecycle<br>• Implement secure design and coding practices<br>• Validate security requirements implementation<br>• Balance security with product needs|
|**Legal/Compliance**|• Identify regulatory security requirements<br>• Validate compliance of security controls<br>• Manage security-related contracts and agreements<br>• Support security incident legal response|
|**IT/Operations**|• Implement and maintain security controls<br>• Monitor security operational metrics<br>• Respond to security alerts and incidents<br>• Manage security-related infrastructure|
|**HR/People**|• Support security awareness and training<br>• Manage personnel security procedures<br>• Address security policy violations<br>• Support security culture development|
|**Finance/Procurement**|• Evaluate security investment ROI<br>• Manage security budgets and spending<br>• Assess vendor security requirements<br>• Support security risk transfer (insurance)|
|**Sales/Marketing**|• Communicate security capabilities to customers<br>• Gather security-related market requirements<br>• Support customer security assessments<br>• Align security messaging with capabilities|
|**Customer Success/Support**|• Handle customer security concerns<br>• Escalate potential security issues<br>• Support customer security needs<br>• Provide feedback on security usability|

This cross-functional integration evolves with organizational maturity but remains a fundamental aspect of the Peak Defence Method. Security cannot function effectively as an isolated domain - it requires active participation from across the organization.


<img src="./assets/icons/garage-duotone.svg" alt="Garage" align="right" width="100px" height="auto" /> 

## Level 1: Startup Foundation
**Target Organization**: Startups and small organizations (5-50 employees)  
**Resources Required**: Technical leader with security interest + team participation

At the startup level, security roles rarely exist as dedicated positions. Instead, security responsibilities are distributed among existing team members who take on security aspects alongside their primary roles.

### Essential Security Roles

#### Technical Leader with Security Focus
**Time Allocation**: 5-20% of time on security  
**Responsibilities**:
- Make critical security decisions
- Define basic security requirements
- Research and determine security controls
- Oversee security implementations
- Respond to security incidents
- Communicate with external parties about security
- Coordinate cross-functional security activities

**Cross-Functional Considerations**:
- Work directly with founders on security risk decisions
- Collaborate with product leads on security trade-offs
- Provide clear security requirements to developers
- Support customer-facing teams with security information

#### Developers with Security Responsibilities
**Time Allocation**: 5-10% of development time  
**Responsibilities**:
- Implement security controls in code and infrastructure
- Follow secure development practices
- Review code for security issues
- Participate in security design discussions
- Report potential security concerns
- Support incident investigation and remediation

**Cross-Functional Considerations**:
- Collaborate with product on security-usability balance
- Help explain technical security constraints to non-technical team members
- Translate complex security concepts for other functions

#### Product Owner with Security Awareness
**Time Allocation**: 5-10% of product time  
**Responsibilities**:
- Include security requirements in product planning
- Prioritize security features appropriately
- Validate security implementations from user perspective
- Gather security-related customer feedback
- Support security feature communication

**Cross-Functional Considerations**:
- Work with technical lead to understand security requirements
- Help translate customer security needs to technical requirements
- Align security features with overall product strategy

#### Cross-Functional Security Participation
**Time Allocation**: As needed  
**Responsibilities**:
- Support security activities within their domains
- Provide domain expertise for security decisions
- Follow basic security practices and policies
- Raise potential security concerns
- Help implement security in business processes

### Implementation Approach

For startups, implement security roles with these lightweight approaches:

1. **Designate a Security Point Person**
   - Identify who has primary security responsibility
   - Allocate specific time for security work
   - Communicate this role to the whole team
   - Ensure they have access to necessary resources

2. **Create a Simple Responsibility Chart**
   - List key security activities (e.g., code review, incident response)
   - Assign primary and backup owners
   - Share with the entire team
   - Review quarterly to keep current

3. **Establish Basic Security Communication**
   - Create a dedicated security channel (Slack, Teams, etc.)
   - Hold monthly security check-ins with key team members
   - Include security topics in product and engineering meetings
   - Document security decisions in accessible locations

4. **Cross-Functional Integration**
   - Include security as a regular topic in all-hands meetings
   - Create simple, role-specific security checklists
   - Ensure all team members know basic security expectations
   - Build security into existing processes rather than creating separate ones

### Cross-Functional Boundary Artefacts

For effective security collaboration in startups, use these simple boundary Artefacts:

1. **Security Responsibility Chart**
   - Simple table of security tasks and owners
   - Clear primary and backup responsibilities
   - Visible to all team members
   - Updated when roles or responsibilities change

**Example:**

| Security Task               | Primary Owner  | Backup         | When         |
| --------------------------- | -------------- | -------------- | ------------ |
| Code security reviews       | Ana (Dev)      | Tom (CTO)      | All PRs      |
| Security incident response  | Tom (CTO)      | Elena (Dev)    | As needed    |
| Customer security questions | Maya (Product) | Tom (CTO)      | As needed    |
| Security requirements       | Tom (CTO)      | Maya (Product) | New features |
| Security monitoring         | Elena (Dev)    | Tom (CTO)      | Daily        |


2. **Security Guidelines Document**
   - Brief document with key security practices
   - Role-specific sections for different functions
   - Simple, jargon-free language
   - Practical examples and templates

3. **Security Decision Log**
   - Record of key security decisions
   - Context and rationale for each decision
   - Accessible to all team members
   - Referenced when questions arise

### Common Challenges and Solutions

| Challenge                                            | Solution                                                          | Cross-Functional Element                                       |
| ---------------------------------------------------- | ----------------------------------------------------------------- | -------------------------------------------------------------- |
| **Security becoming a bottleneck**                   | Empower more team members to make routine security decisions      | Create simple decision guidelines different roles can follow   |
| **Security responsibilities falling through cracks** | Review the responsibility chart monthly; add missing items        | Discuss security responsibilities in cross-functional meetings |
| **Limited security expertise**                       | Invest in targeted security training; use security-as-a-service   | Identify and leverage domain expertise across functions        |
| **Security vs speed tensions**                       | Set explicit security requirements early in development           | Include both product and engineering in security discussions   |
| **Inconsistent security practices**                  | Create simple, accessible security checklists                     | Adapt checklists for different functional needs                |
| **Unclear security escalation paths**                | Define and communicate when and how to escalate security concerns | Ensure every function knows their escalation contacts          |

### Signs You've Outgrown Level 1

- Security responsibilities regularly consume >20% of technical leader's time
- Security incidents or requirements become too complex for part-time attention
- Customers or partners require more formal security documentation and roles
- The organization reaches 50+ employees with multiple teams
- Security coordination becomes difficult without dedicated resources
- Cross-functional security needs require more structured approaches
- The current security knowledge becomes insufficient for growing needs


<img src="./assets/icons/building-office-duotone.svg" alt="Office" align="right" width="100px" height="auto" /> 

## Level 2: Scale-up Enhancement
**Target Organization**: Growing organizations (50-500 employees)  
**Resources Required**: Dedicated security lead + security representatives in key functions

As organizations grow, they need more formal security roles and clearer responsibilities. At this stage, dedicated security personnel emerge, though full security specialization remains limited.

### Structured Security Roles

#### Security Lead/Manager
**Time Allocation**: Full-time security role  
**Responsibilities**:
- Lead security strategy and planning
- Design and oversee security program
- Make key security architecture decisions
- Manage security incidents and response
- Report security status to leadership
- Drive security improvements and initiatives
- Coordinate security across functions
- Oversee security compliance activities

**Cross-Functional Considerations**:
- Establish regular coordination with department heads
- Create function-specific security requirements and guidance
- Develop security service model for different business needs
- Participate in key product and technology decisions

#### Security Specialists
**Time Allocation**: Full-time security roles with different focuses  
**Responsibilities**:
- Implement specialized security controls and processes
- Provide domain-specific security expertise
- Support security testing and validation
- Conduct security assessments and reviews
- Develop and maintain security documentation
- Support incident response and investigation
- Assist with security awareness and training

**Cross-Functional Considerations**:
- Serve as security contacts for specific functions
- Translate security requirements for different audiences
- Help design security controls that fit functional needs
- Participate in cross-functional projects and initiatives

#### Security Champions Network
**Time Allocation**: 10-20% of time on security responsibilities  
**Responsibilities**:
- Represent security in their respective teams
- Provide first-level security guidance
- Identify security implications of team activities
- Support security requirement implementation
- Escalate complex security issues to security team
- Help build security awareness in their teams

**Cross-Functional Considerations**:
- Act as bridges between security team and their functions
- Help translate security concepts to function-specific contexts
- Provide domain expertise to security initiatives
- Support appropriate security integration in their areas

#### Function-Specific Security Responsibilities

##### Product/Engineering Security Roles
**Responsibilities**:
- Security Product Manager: Represents security in product planning
- Security Engineer: Implements security controls in code and infrastructure
- Security QA: Validates security control effectiveness

##### Legal/Compliance Security Roles
**Responsibilities**:
- Security Compliance Manager: Ensures regulatory security requirements are met
- Legal Security Liaison: Addresses legal aspects of security issues

##### IT/Operations Security Roles
**Responsibilities**:
- Security Operations Specialist: Monitors and maintains security controls
- Security Incident Responders: Leads technical incident response

### Implementation Approach

For growing organizations, implement security roles with these structured approaches:

1. **Establish Dedicated Security Function**
   - Create formal security roles and descriptions
   - Define reporting lines and authority
   - Allocate appropriate budget and resources
   - Set clear expectations and objectives

2. **Develop Security RACI Matrix**
   - Create comprehensive matrix for security activities
   - Define Responsible, Accountable, Consulted, and Informed roles
   - Include cross-functional responsibilities
   - Socialize across the organization

3. **Implement Security Champions Program**
   - Select champions from key teams and functions
   - Provide targeted training and resources
   - Create regular coordination mechanisms
   - Recognize and reward champion contributions

4. **Establish Security Governance Framework**
   - Create security steering committee with cross-functional representation
   - Develop formal escalation paths for security decisions
   - Implement regular security reporting
   - Define security decision authorities

### Cross-Functional Boundary Artefacts

For effective security collaboration in scale-up organizations, use these structured boundary artefacts:

1. **Security RACI Matrix**
   - Comprehensive matrix of security activities
   - Clear responsibilities across functions
   - Used for clarifying roles and accountability
   - Referenced when responsibility questions arise

**Example Section:**

| Security Activity | Security Team | Engineering | Product | Legal | Operations |
|-------------------|---------------|-------------|---------|-------|------------|
| Security architecture decisions | A/R | C | C | I | C |
| Security requirements definition | A/R | C | C | C | I |
| Security code implementation | C | A/R | I | I | I |
| Security testing | A/R | C | I | I | C |
| Security incident response | A/R | C | I | C | C |
| Vendor security assessment | A/R | C | C | C | C |
| Security policy development | A/R | C | C | C | C |

R = Responsible, A = Accountable, C = Consulted, I = Informed

2. **Security Service Catalog**
   - Documented security services offered to the organization
   - Service descriptions, delivery model, and SLAs
   - Function-specific sections and use cases
   - Clear process for requesting security services

3. **Security Decision Framework**
   - Documented security decision authorities
   - Approval thresholds and escalation criteria
   - Templates for security decision requests
   - Clear process for expedited decisions

### Function-Specific Security Interfaces

Establish formal interfaces between security and other organizational functions:

#### Security-Product Interface
- **Regular Touchpoints**: Security representation in product planning
- **Artifact Exchange**: Security requirements templates for product teams
- **Service Agreement**: Security review SLAs and processes
- **Escalation Path**: Clear process for security-product conflicts

#### Security-Engineering Interface
- **Regular Touchpoints**: Security participation in engineering planning
- **Artifact Exchange**: Security implementation patterns and code examples
- **Service Agreement**: Code review and security testing processes
- **Escalation Path**: Technical security decision framework

#### Security-Legal Interface
- **Regular Touchpoints**: Monthly security-legal coordination meeting
- **Artifact Exchange**: Security-legal assessment templates
- **Service Agreement**: Legal review process for security issues
- **Escalation Path**: Clear process for risk acceptance decisions

#### Security-Operations Interface
- **Regular Touchpoints**: Security representation in change management
- **Artifact Exchange**: Security operations runbooks and guides
- **Service Agreement**: Security monitoring and alerting responsibilities
- **Escalation Path**: Incident response coordination framework

### Common Challenges and Solutions

|Challenge|Solution|Cross-Functional Element|
|---|---|---|
|**Security team becoming isolated**|Establish formal interfaces with other functions|Create cross-functional security forum|
|**Unclear decision authorities**|Develop and document security decision framework|Include key stakeholders in framework development|
|**Security bottlenecks in processes**|Delegate routine decisions to trained security champions|Create decision guides for different functions|
|**Inconsistent security practices across teams**|Create function-specific security standards|Develop standards collaboratively with affected functions|
|**Security receiving late-stage requests**|Integrate security earlier into planning processes|Create function-specific engagement models|
|**Overloaded security resources**|Implement security service tiers and prioritization|Base priorities on cross-functional business impact|
|**Resistance to security requirements**|Involve affected functions in requirement development|Create security-business alignment workshops|

### Signs You've Outgrown Level 2

- Security needs span multiple specialized domains requiring dedicated experts
- Security governance becomes complex with multiple stakeholders
- Multiple business units have different security requirements and priorities
- Regulatory requirements demand more formal security governance
- The security team needs internal specialization and structure
- Cross-functional security processes require more systematic management
- The organization needs more comprehensive security metrics and reporting

<img src="./assets/icons/city-duotone.svg" alt="Buildings" align="right" width="100px" height="auto" /> 

## Level 3: Enterprise Optimization
**Target Organization**: Large organizations (500+ employees)  
**Resources Required**: Security leadership team + specialized security functions + formal governance

Enterprise organizations require comprehensive security roles and responsibilities with formal governance structures. At this level, security becomes a specialized organization with executive leadership and clear interfaces with other business functions.

### Comprehensive Security Roles

#### Chief Information Security Officer (CISO)
**Time Allocation**: Full-time executive security role  
**Responsibilities**:
- Provide executive-level security leadership
- Define enterprise security strategy and vision
- Set security direction and priorities
- Secure resources for security program
- Report security status to executive leadership and board
- Manage enterprise security risk
- Lead security organization
- Represent security in executive decision-making

**Cross-Functional Considerations**:
- Participate in executive leadership team
- Align security strategy with business strategy
- Develop executive-level relationships across functions
- Create appropriate security governance model for organizational culture

#### Security Leadership Team
**Time Allocation**: Full-time security leadership roles  
**Responsibilities**:
- Lead specialized security domains
- Develop domain-specific strategies and roadmaps
- Manage security teams and resources
- Make domain security decisions
- Report domain security status
- Drive security improvements in their domains
- Coordinate across security domains
- Support enterprise security initiatives

**Example Security Leadership Roles**:
- Director of Application Security
- Director of Infrastructure Security
- Director of Security Operations
- Director of Security Governance, Risk, and Compliance
- Director of Security Architecture

**Cross-Functional Considerations**:
- Establish peer relationships with functional leadership
- Create domain-specific cross-functional interfaces
- Align domain security activities with business needs
- Facilitate appropriate security integration in business functions

#### Specialized Security Teams
**Time Allocation**: Full-time specialized security roles  
**Responsibilities**:
- Implement specialized security functions
- Provide domain-specific security expertise
- Deliver security services to the organization
- Support security governance and compliance
- Conduct security assessments and testing
- Operate security technologies and processes
- Respond to security incidents
- Support security awareness and training

**Example Specialized Teams**:
- Application Security Team
- Infrastructure Security Team
- Security Operations Center
- Governance, Risk, and Compliance Team
- Security Architecture Team
- Identity and Access Management Team
- Third-Party Security Team

**Cross-Functional Considerations**:
- Develop service delivery models appropriate to customer functions
- Create function-specific engagement processes
- Adapt security guidance for different functional contexts
- Establish regular touchpoints with functional counterparts

#### Federated Security Model
**Time Allocation**: Varies by role and function  
**Responsibilities**:
- Represent security within business functions
- Implement security requirements in their domains
- Provide function-specific security expertise
- Support security initiatives in their areas
- Escalate security issues appropriately
- Contribute to security governance
- Help build security culture in their functions

**Example Federated Security Roles**:
- Business Unit Security Officers
- Application Security Champions
- Security Product Managers
- Security Compliance Specialists
- Security Architects embedded in development teams

**Cross-Functional Considerations**:
- Balance central security direction with business unit needs
- Create clear interfaces between central and federated security
- Define service boundaries and responsibilities
- Establish collaboration mechanisms across security roles

### Security Governance Framework

Enterprise organizations need formal security governance:

1. **Executive Security Committee**
   - Executive-level governance body
   - Strategic security direction and oversight
   - Enterprise risk acceptance decisions
   - Resource allocation and prioritization
   - Cross-functional executive representation

2. **Security Steering Committee**
   - Senior management security governance
   - Tactical security direction and coordination
   - Security initiative oversight
   - Cross-functional management representation
   - Regular (monthly/quarterly) cadence

3. **Security Working Groups**
   - Domain-specific security governance
   - Specialized security topics and initiatives
   - Technical and process-level coordination
   - Subject matter expert participation
   - As-needed or regular cadence

4. **Security Decision Framework**
   - Documented decision authorities at different levels
   - Clear escalation criteria and paths
   - Formal decision logging and tracking
   - Risk acceptance processes
   - Emergency decision procedures

### Cross-Functional Boundary Artefact

For effective security collaboration in enterprise organizations, use these comprehensive boundary artefacts:

1. **Enterprise Security Operating Model**
   - Comprehensive security roles and responsibilities
   - Security organizational structure and governance
   - Security service delivery model
   - Cross-functional interfaces and touchpoints
   - Security performance metrics and reporting

**Example Section:**

---

## Infrastructure Security Services

### Service: Cloud Security Architecture Review

Description: Architectural review of cloud infrastructure designs for security and compliance

Service Owner: Cloud Security Architecture Team
Primary Customers: Cloud Engineering, Application Development, DevOps
Service Level: Standard (5 business day turnaround), Expedited (2 business day turnaround)

Process:
1. Requestor submits design documents using Cloud Security Review template
2. Cloud Security Architect assigned within 1 business day
3. Initial assessment and clarification questions within 2 business days
4. Final review delivered within SLA timeframe
5. Optional follow-up consultation available

Escalation Path:
- Primary: Cloud Security Team Lead
- Secondary: Director of Infrastructure Security
- Urgent: CISO Office

Performance Metrics:
- Review completion within SLA: Target 95%
- Requestor satisfaction: Target 4.5/5
- Security issues identified pre-implementation: Reported quarterly
---

2. **Enterprise Security Responsibility Matrix**
   - Comprehensive RACI across all security domains
   - Function-specific security responsibilities
   - Governance body roles and authorities
   - Security service boundaries and ownership
   - Escalation and exception processes

3. **Security Engagement Model**
   - Documented interfaces between security and other functions
   - When and how to engage security in different processes
   - Templates and artifacts for cross-functional security work
   - Security service request and delivery processes
   - Security decision request and approval workflows

### Function-Specific Security Integration

Implement structured security integration with business functions:

#### Business Unit Security Integration
- **Governance**: Business unit security steering committees
- **Roles**: Business unit security officers reporting to both business and security
- **Processes**: Security risk management aligned to business processes
- **Artifacts**: Business unit security dashboards and reporting
- **Services**: Customized security services for business unit needs

#### Security-Technology Integration
- **Governance**: Architecture review boards with security representation
- **Roles**: Embedded security architects in technology teams
- **Processes**: Security integrated into technology lifecycle processes
- **Artifacts**: Security architecture patterns and requirements
- **Services**: Specialized security services for different technology domains

#### Security-Legal/Compliance Integration
- **Governance**: Compliance steering committee with security representation
- **Roles**: Security compliance specialists aligned with legal team
- **Processes**: Integrated compliance and security processes
- **Artifacts**: Compliance control frameworks with security mapping
- **Services**: Specialized compliance security services

#### Security-Operations Integration
- **Governance**: Security operations governance council
- **Roles**: Security operations specialists aligned with IT operations
- **Processes**: Integrated security operations processes
- **Artifacts**: Security operations runbooks and playbooks
- **Services**: Security monitoring and response services

### Common Challenges and Solutions

|Challenge|Solution|Cross-Functional Element|
|---|---|---|
|**Security organizational complexity**|Implement clear security operating model|Create function-specific interfaces and touchpoints|
|**Balancing centralized and decentralized security**|Develop federation model with clear accountabilities|Align operating model with organizational culture|
|**Governance overhead slowing decisions**|Implement tiered governance with appropriate delegation|Include key stakeholders in governance design|
|**Inconsistent security across business units**|Create balanced control framework with local flexibility|Develop appropriate security metrics across functions|
|**Security resource allocation conflicts**|Implement formal security investment governance|Base investment decisions on business risk impact|
|**Complex security-business alignment**|Develop business-aligned security strategy|Create function-specific value propositions|
|**Security becoming bureaucratic**|Balance governance with service orientation|Design processes collaboratively with affected functions|

## Implementing Roles and Responsibilities Across Planning Horizons

Security roles and responsibilities operate across the [planning horizons](./planning) we discussed in earlier chapters. Different horizons require different role involvement and responsibility patterns.

### Lifetime Horizon Responsibilities

At the Lifetime Horizon (years), responsibilities focus on strategic direction:

| Role                      | Primary Responsibilities                                                                                                             | Cross-Functional Considerations                                                                                                                   |
| ------------------------- | ------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Security Strategists**  | • Set security vision and principles<br>• Define enterprise security architecture<br>• Establish risk tolerance framework            | • Align with business strategy and vision<br>• Integrate with enterprise architecture<br>• Consider regulatory long-term evolution                |
| **Security Shapers**      | • Architect security capabilities<br>• Define security technology strategy<br>• Create security roadmaps                             | • Coordinate with technology strategy<br>• Align with product long-term vision<br>• Consider operational sustainability                           |
| **Security Implementers** | • Provide implementation feasibility input<br>• Validate architectural assumptions<br>• Identify long-term implementation challenges | • Work with engineering on technical feasibility<br>• Consider operational maintenance needs<br>• Validate with implementation expertise          |
| **Security Enablers**     | • Provide business context and constraints<br>• Represent stakeholder long-term needs<br>• Support strategic security alignment      | • Translate business strategy needs to security<br>• Advocate for security in strategic planning<br>• Enable cross-functional strategic alignment |

### Yearly Horizon Responsibilities

At the Yearly Horizon (12 months), responsibilities focus on capability development:

|Role|Primary Responsibilities|Cross-Functional Considerations|
|---|---|---|
|**Security Strategists**|• Prioritize security investments<br>• Allocate resources for security initiatives<br>• Set annual security objectives|• Align with annual business planning<br>• Coordinate with budgeting processes<br>• Integrate with organizational objectives|
|**Security Shapers**|• Shape major security initiatives<br>• Define security capability requirements<br>• Create security program structure|• Work with project/product planning<br>• Coordinate with technology roadmaps<br>• Align with compliance calendars|
|**Security Implementers**|• Plan implementation capacity<br>• Identify implementation dependencies<br>• Develop implementation roadmaps|• Coordinate with engineering capacity planning<br>• Align with product/project schedules<br>• Consider operational implementation needs|
|**Security Enablers**|• Provide domain expertise for planning<br>• Represent function-specific requirements<br>• Support resource allocation decisions|• Ensure security plans align with functional plans<br>• Advocate for security resource needs<br>• Enable function-specific security planning|

### Quarterly Horizon Responsibilities

At the Quarterly Horizon (3 months), responsibilities focus on initiative management:

|Role|Primary Responsibilities|Cross-Functional Considerations|
|---|---|---|
|**Security Strategists**|• Make betting decisions on shaped work<br>• Review initiative progress<br>• Address escalated issues|• Align with quarterly business reviews<br>• Coordinate with product/project governance<br>• Integrate with resource management|
|**Security Shapers**|• Shape specific security initiatives<br>• Define initiative scope and appetite<br>• Create security pitches|• Work with product/project managers<br>• Coordinate with engineering leadership<br>• Align with quarterly planning cycles|
|**Security Implementers**|• Provide implementation expertise<br>• Plan implementation approach<br>• Identify implementation risks|• Coordinate with delivery teams<br>• Align with engineering practices<br>• Consider operational requirements|
|**Security Enablers**|• Contribute domain expertise to shaping<br>• Identify cross-functional dependencies<br>• Support initiative coordination|• Ensure initiatives align with functional needs<br>• Advocate for security in planning processes<br>• Enable cross-functional coordination|

### Cycle Horizon Responsibilities

At the Cycle Horizon (6 weeks), responsibilities focus on implementation:

|Role|Primary Responsibilities|Cross-Functional Considerations|
|---|---|---|
|**Security Strategists**|• Monitor implementation progress<br>• Address strategic blockers<br>• Evaluate implementation success|• Coordinate with delivery oversight<br>• Align with release management<br>• Integrate with operational readiness|
|**Security Shapers**|• Support implementation teams<br>• Clarify shaped work as needed<br>• Help address discovered challenges|• Work with product owners/managers<br>• Coordinate with technical leadership<br>• Align with quality assurance processes|
|**Security Implementers**|• Implement security controls<br>• Track and communicate progress<br>• Make tactical implementation decisions|• Coordinate with development teams<br>• Align with testing and validation<br>• Consider operational deployment needs|
|**Security Enablers**|• Provide domain-specific support<br>• Help address functional dependencies<br>• Support implementation validation|• Ensure implementation meets functional needs<br>• Advocate for security quality<br>• Enable functional acceptance and adoption|

## Cross-Functional Security Responsibility Patterns

Certain cross-functional patterns emerge across maturity levels. These patterns help organizations establish effective security responsibilities that span traditional functional boundaries.

### 1. Security Decision-Making Pattern

How security decisions should be made across functions:

|Maturity Level|Pattern Implementation|
|---|---|
|**Level 1: Startup**|• Simple decision rights documented<br>• Key security decisions made by technical leadership with founder input<br>• Direct communication about security trade-offs|
|**Level 2: Scale-up**|• Documented decision framework<br>• Security team makes technical decisions, business approves risk acceptance<br>• Formal escalation process for conflicts|
|**Level 3: Enterprise**|• Comprehensive governance framework<br>• Tiered decision authorities with clear boundaries<br>• Formal risk acceptance process with appropriate delegations|

**Cross-Function Considerations:**
- Balance technical security expertise with business context
- Create appropriate decision mechanisms for organization's culture
- Ensure escalation paths accommodate urgent security needs
- Design interfaces between security and business decisions

### 2. Security Service Delivery Pattern

How security services should be delivered across the organization:

|Maturity Level|Pattern Implementation|
|---|---|
|**Level 1: Startup**|• Security assistance provided as needed<br>• Direct requests to security-responsible person<br>• Informal prioritization based on impact|
|**Level 2: Scale-up**|• Defined security services with clear owners<br>• Formal request and prioritization process<br>• Basic service levels and expectations|
|**Level 3: Enterprise**|• Comprehensive security service catalog<br>• Tiered service levels with clear SLAs<br>• Resource allocation aligned with business priorities|

**Cross-Function Considerations:**
- Design services to meet different functional needs
- Create appropriate interfaces for different consumer groups
- Balance standardization with function-specific customization
- Implement feedback mechanisms to improve service delivery

### 3. Security Accountability Distribution Pattern

How security accountability should be distributed across functions:

|Maturity Level|Pattern Implementation|
|---|---|
|**Level 1: Startup**|• Security accountability held primarily by technical leaders<br>• Basic security responsibilities for all team members<br>• Direct oversight of security activities|
|**Level 2: Scale-up**|• Primary accountability with security team<br>• Functional leaders accountable for security in their domains<br>• Security champions as local security representatives|
|**Level 3: Enterprise**|• Tiered accountability model<br>• CISO accountable for enterprise security posture<br>• Business unit leaders accountable for security in their areas<br>• Federated security model with clear boundaries|

**Cross-Function Considerations:**
- Align accountability with authority and capability
- Create appropriate incentives for security accountability
- Design accountability model that fits organizational culture
- Establish clear boundaries between security functions

### 4. Security Knowledge Distribution Pattern

How security knowledge should flow across the organization:

|Maturity Level|Pattern Implementation|
|---|---|
|**Level 1: Startup**|• Direct sharing of security knowledge<br>• Just-in-time security guidance<br>• Emphasis on practical application|
|**Level 2: Scale-up**|• Structured security training program<br>• Function-specific security guidance<br>• Security champions as knowledge conduits|
|**Level 3: Enterprise**|• Comprehensive security knowledge management<br>• Role-based security education<br>• Multiple knowledge delivery channels<br>• Specialized communities of practice|

**Cross-Function Considerations:**
- Adapt security knowledge to different functional contexts
- Create appropriate knowledge interfaces for different roles
- Balance security depth with practical application
- Design knowledge distribution that fits learning preferences

## Boundary Artefacts for Cross-Functional Security Roles

Effective cross-functional security roles require shared artifacts that create alignment across organizational boundaries. These boundary artefacts should evolve with organizational maturity:

<img src="./assets/icons/garage-duotone.svg" alt="Garage" align="right" width="100px" height="auto" /> 

### Level 1: Essential Boundary Artefacts for Startups

1. **Security Responsibility Chart**
   - Simple table of security tasks and owners
   - Clear primary and backup responsibilities
   - Visible to all team members
   - Updated when roles or responsibilities change

2. **Security Decision Guidelines**
   - Brief document outlining who makes which security decisions
   - Examples of common security decisions
   - Simple escalation process for unusual situations
   - Accessible to everyone in the organization

3. **Basic Security Checklist**
   - Simple checklist of security responsibilities by role
   - Focus on most critical security activities
   - Practical guidance without security jargon
   - Used during relevant processes (development, release, etc.)

<img src="./assets/icons/building-office-duotone.svg" alt="Office" align="right" width="100px" height="auto" /> 

### Level 2: Structured Boundary Artefacts for Scale-ups

1. **Security RACI Matrix**
   - Comprehensive matrix of security activities
   - Clear responsibilities across functions
   - Used for clarifying roles and accountability
   - Referenced when responsibility questions arise

2. **Security Service Catalog**
   - Documented security services offered to the organization
   - Service descriptions, delivery model, and SLAs
   - Function-specific sections and use cases
   - Clear process for requesting security services

3. **Security Champions Charter**
   - Clear definition of security champion role
   - Responsibilities, expectations, and time commitment
   - Relationship with central security team
   - Support and resources provided to champions

<img src="./assets/icons/city-duotone.svg" alt="Buildings" align="right" width="100px" height="auto" /> 

### Level 3: Sophisticated Boundary Artefacts for Enterprises

1. **Enterprise Security Operating Model**
   - Comprehensive documentation of security organization
   - Clear roles, responsibilities, and interfaces
   - Governance structures and decision authorities
   - Service delivery models and performance metrics
   - Integrated with enterprise operating model

2. **Security Governance Framework**
   - Formal documentation of security governance bodies
   - Decision authorities and escalation paths
   - Meeting cadences and membership
   - Reporting and oversight mechanisms
   - Cross-functional representation requirements

3. **Federated Security Model**
   - Documentation of centralized vs. decentralized responsibilities
   - Interface definitions between security organization and business units
   - Service boundaries and accountability model
   - Resource allocation and reporting relationships
   - Performance measurement and management