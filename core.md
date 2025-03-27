# Core Principles of Peak Defence Method

## Introduction

Security approaches often fail not because of poor implementation, but because they're built on flawed assumptions about the nature of security itself. The Peak Defence Method is founded on a different perspective — one that acknowledges the inherent complexity and unpredictability of modern systems.

This chapter explains the philosophical foundation and core principles that guide our approach across organizations of all sizes and maturity levels. These principles inform every aspect of the methodology, from how we [shape work](shaping.md) to how we implement security controls and measure security effectiveness.

**Security is inherently cross-functional** - it touches every aspect of an organization and requires coordination across traditional functional boundaries. The principles in this chapter don't just guide the security team; they provide a common language and framework for all organizational functions to contribute to security outcomes effectively.

## Maturity Level Framework

The application of core principles evolves as organizations grow in size and capability. The table below illustrates how key characteristics change across maturity levels:

| Characteristic                        | Level 1: Startup                          | Level 2: Scale-up                             | Level 3: Enterprise                                     |
| ------------------------------------- | ----------------------------------------- | --------------------------------------------- | ------------------------------------------------------- |
| **Method Integration**                | Implicit, pragmatic application           | Explicit, structured application              | Comprehensive, systematic application                   |
| **Resilience Focus**                  | Basic recovery capabilities               | Balanced prevention and adaptation            | Sophisticated resilience architecture                   |
| **People-Process-Technology Balance** | Informal, people-centric                  | Structured, balanced approach                 | Formal, comprehensive integration                       |
| **Cross-Functional Coordination**     | Direct collaboration between team members | Designated security liaisons in key functions | Formalized coordination framework with clear interfaces |
| **Documentation**                     | Simple principles statement               | Detailed principles documentation             | Enterprise security architecture                        |

### Progression Indicators

#### When to move from Level 1 to Level 2:

- Basic security controls are consistently implemented
- Security incidents require more systematic response
- Multiple team members share security responsibilities
- Customers or partners request formal security documentation
- The organization needs to demonstrate security capabilities to external parties

#### When to move from Level 2 to Level 3:

- Security initiatives span multiple teams, systems or geographies
- Regulatory requirements demand comprehensive security documentation
- The organization has specialized security teams
- Security strategy requires alignment across business units
- Sophisticated threats target the organization specifically

## Designing for the Inevitable

> "Anything that can go wrong, will go wrong" - Edward A. Murphy Jr.

Murphy's Law serves as our philosophical foundation—a reminder that in any sufficiently complex system, unexpected events are inevitable. Rather than viewing this as pessimism, we see it as a profound insight that should guide how we approach security.

### The Strategic Implications

This perspective fundamentally changes our approach to security:

|Traditional Security|Resilience-Oriented Security|
|---|---|
|Focus on preventing all failures|Design for inevitable failures|
|Create rigid, controlled environments|Build adaptive, responsive systems|
|Minimize risk through strict controls|Manage risk through adaptive capacity|
|React to security failures|Anticipate and prepare for failures|
|Measure success by incidents prevented|Measure success by resilience to incidents|

### Applying This Principle By Maturity Level


#### Level 1: Startup Foundation
**For startups and small organizations (5-50 employees):**
<img src="./assets/icons/garage-duotone.svg" alt="Garage" align="right" width="100px" height="auto" /> 

- **Focus on basics with resilience in mind**
    
    - Implement essential controls that address highest risks
    - Create simple backup and recovery processes
    - Document basic incident response procedures
    - Establish monitoring for critical systems
    
- **Practical application:**
    
    - Build security with "graceful failure" in mind
    - Ensure someone receives alerts when controls fail
    - Create simple runbooks for common security issues
    - Maintain offline backups of critical data

**Example:** A small e-commerce startup implements password authentication but also creates a simple account recovery process for when users forget passwords or accounts get compromised. They test this recovery process monthly to ensure it works when needed.

**Cross-Functional Considerations:**

At the startup level, cross-functional coordination happens organically through direct communication:

- **Shared Visibility**: Use simple, visible tools (like shared dashboards) that allow all team members to see security status (e.g. system availability, Dependabot issues) regardless of role
- **Unified Response**: Develop simple incident response checklists that include steps for different functions (engineering fix, customer communication, legal notification)
- **Collective Ownership**: Foster a culture where security is everyone's responsibility, not siloed to technical team members

**Example Boundary Artefact**: A one-page "Security Incident Checklist" that defines roles for everyone during a security incident, regardless of their primary function.

#### Level 2: Scale-up Enhancement
**For growing organizations (50-500 employees):**
<img src="./assets/icons/building-office-duotone.svg" alt="Office" align="right" width="100px" height="auto" /> 

- **Develop systematic resilience capabilities**
    
    - Create formal incident response processes
    - Implement security monitoring and alerting
    - Establish security testing and validation practices
    - Develop business continuity procedures
    
- **Practical application:**
    
    - Document expected failure modes for key systems
    - Implement defense-in-depth for critical assets
    - Create security dashboards to visualize control effectiveness
    - Conduct regular tabletop exercises for security scenarios

**Example:** A growing FinTech company implements a dual-layer authentication system, with the explicit understanding that the primary method may fail. They create dashboards to monitor authentication success rates, establish alerts for unusual patterns, and document procedures for rapidly switching to backup authentication methods when needed.

**Cross-Functional Considerations:**

As the organization grows, more structured cross-functional coordination becomes necessary:

- **Security Suport Network**: Designate and train security "champions" or "advocates" in key departments (engineering, product, operations)
- **Functional Security Guides**: Create role-specific security guidance for different functions (developer security practices, product manager security considerations)
- **Collaborative Resilience Planning**: Involve representatives from multiple functions in resilience planning sessions

**Example Boundary Artefact**:

- Function-specific security checklists that translate security principles to specific roles
- Simplified threat models that non-security specialists can understand and contribute to

#### Level 3: Enterprise Optimization
**For large organizations (500+ employees):**
<img src="./assets/icons/city-duotone.svg" alt="Buildings" align="right" width="100px" height="auto" /> 

- **Architect comprehensive resilience**
    
    - Implement formal resilience engineering practices
    - Create advanced detection and response capabilities
    - Develop adaptive security control frameworks
    - Establish continuous learning from security events
    
- **Practical application:**
    
    - Conduct formal failure mode and effects analysis
    - Create resilience architecture as part of security strategy
    - Implement automated response to common security events
    - Develop metrics for security control effectiveness and adaptation

**Example:** A large healthcare enterprise implements a zero trust architecture with the explicit understanding that some controls will fail. They create layered detection capabilities, develop response procedures for different compromise scenarios, establish formal learning processes after security events, and maintain a security control effectiveness dashboard with real-time adaptation metrics.

**Cross-Functional Considerations:**

Enterprise organizations require systematic approaches to cross-functional security coordination:

- **Security Governance Framework**: Establish formal governance mechanisms that include representation from all key functions
- **Capability-based Security Model**: Define security capabilities that span functional boundaries with clear responsibilities
- **Cross-functional Security Metrics**: Implement shared security metrics that demonstrate how different functions contribute to overall resilience

**Example Boundary Artefacts**:

- Enterprise resilience architecture documents with function-specific views
- RACI matrices for security capabilities that span multiple functions
- Security decision frameworks that different functions can use consistently

### Common Implementation Challenges

| Challenge                               | Level 1 Solution                                               | Level 2 Solution                                           | Level 3 Solution                                          |
| --------------------------------------- | -------------------------------------------------------------- | ---------------------------------------------------------- | --------------------------------------------------------- |
| **Balancing prevention and resilience** | Focus resources on recovery for critical systems               | Develop tiered approach based on asset value               | Implement formal resilience architecture framework        |
| **Convincing stakeholders**             | Use concrete examples of past security failures                | Present cost-benefit analysis of resilience vs. prevention | Develop comprehensive risk management framework           |
| **Limited resources**                   | Prioritize controls that provide both prevention and detection | Implement phased approach to building resilience           | Develop risk-based resource allocation model              |
| **Complex technology landscape**        | Focus on critical system resilience first                      | Develop resilience patterns for common technologies        | Create technology-specific resilience architectures       |
| **Functional silos**                    | Regular all-hands security updates                             | Security champions in each function                        | Enterprise security operating model with clear interfaces |

## The People-Process-Technology Triangle

Security effectiveness requires balance across these three dimensions. This balance looks different at each organizational maturity level but remains a critical framework for security decisions.

### People-Focused Approach

Humans remain both the greatest strength and the greatest vulnerability in security systems. Their role evolves as organizations grow:

#### Level 1: Startup Foundation
<img src="./assets/icons/garage-duotone.svg" alt="Garage" align="right" width="100px" height="auto" /> 

- **Everyone shares security responsibility**
    
    - Founders and early employees all handle security tasks
    - Security awareness is built through direct conversation
    - Skills develop organically based on immediate needs
    - Technical team members handle security alongside other duties
    
- **Key practices:**
    
    - Regular team discussions about security concerns
    - Simple, clear security guidelines that don't hinder productivity
    - Just-in-time security training for specific tasks
    - Clear escalation paths for security concerns

**Example:** At a 15-person software startup, one developer takes special interest in security and spends 20% of their time on security tasks. The CEO personally leads a monthly security discussion at all-hands meetings, and everyone follows a simple set of security guidelines that focus on the most important behaviors.

#### Level 2: Scale-up Enhancement
<img src="./assets/icons/building-office-duotone.svg" alt="Office" align="right" width="100px" height="auto" /> 

- **Dedicated security roles emerge**
    
    - Security specialists take leadership roles
    - Security responsibilities are formally assigned
    - Training becomes more structured but remains practical
    - Security champions emerge in different teams
    
- **Key practices:**
    
    - Formal security awareness program with role-based components
    - Security representatives in key projects and initiatives
    - Regular threat briefings for technical teams
    - Clear security expectations in job descriptions

**Example:** A 90-person technology company has a three-person security team led by a Security Director. Each department has a designated security champion who receives additional training. New employees complete security orientation, and teams receive security briefings relevant to their specific work.

#### Level 3: Enterprise Optimization
<img src="./assets/icons/city-duotone.svg" alt="Buildings" align="right" width="100px" height="auto" /> 

- **Specialized security organization**
    
    - Multiple specialized security teams with distinct focuses
    - Formal security governance and oversight
    - Comprehensive security career paths and development
    - Extensive security training and certification
    
- **Key practices:**
    
    - Enterprise-wide security awareness and training program
    - Formal security governance committees
    - Specialized security roles with clear career progression
    - Security objectives in performance management

**Example:** A global enterprise with 5,000 employees has a CISO-led security organization with specialized teams for application security, infrastructure security, security operations, and governance/compliance. Security responsibilities are clearly defined in formal policies, security objectives appear in executive performance goals, and the organization maintains a comprehensive security training program with role-specific requirements.

### Process-Centered Improvements

Processes create consistency and repeatability, but poorly designed processes become bureaucratic obstacles. The appropriate level of process formality depends on organizational size and complexity:

#### Level 1: Startup Foundation
<img src="./assets/icons/garage-duotone.svg" alt="Garage" align="right" width="100px" height="auto" /> 

- **Simple, focused processes**
    
    - Lightweight documentation of critical security activities
    - Focus on processes with highest security impact
    - Automation of routine security tasks where possible
    - Informal but consistent security practices
    
- **Key processes:**
    
    - Basic incident response process
    - Simple user onboarding/offboarding checklist
    - Routine security review of code and infrastructure changes
    - Regular backup and recovery verification

**Example:** A small SaaS provider documents their most critical security processes: how to onboard/offboard employees securely, how to respond to potential account compromise, and how to securely share client credentials. They keep these processes as one-page checklists that anyone can easily follow.

#### Level 2: Scale-up Enhancement
<img src="./assets/icons/building-office-duotone.svg" alt="Office" align="right" width="100px" height="auto" /> 

- **Structured but adaptable processes**
    
    - Formal documentation of security processes
    - Clear roles and responsibilities
    - Systematic approach to security activities
    - Regular process review and improvement
    
- **Key processes:**
    
    - Formal incident response plan with defined roles
    - Security review process for projects and changes
    - Structured vulnerability management
    - Documented risk assessment methodology

**Example:** A growing financial services company implements formal security processes based on NIST guidelines, but adapts them to fit their specific needs and culture. They document these processes in their internal knowledge base, conduct quarterly reviews to ensure they remain effective, and collect metrics on process performance.

#### Level 3: Enterprise Optimization
<img src="./assets/icons/city-duotone.svg" alt="Buildings" align="right" width="100px" height="auto" /> 

- **Comprehensive process framework**
    
    - Enterprise security process architecture
    - Integration with formal governance frameworks
    - Continuous process measurement and optimization
    - Automated workflow and process enforcement
    
- **Key processes:**
    
    - Enterprise risk management framework
    - Comprehensive security operations procedures
    - Formal change and release management
    - Integrated security incident management

**Example:** A large legal tech provider implements a comprehensive security process framework aligned with multiple regulatory requirements. Security processes integrate with enterprise governance, automate routine security activities, and include formal metrics and improvement cycles. Process maturity assessments occur annually with continuous monitoring of process effectiveness.

### Technology Integration

Technology provides essential capabilities but must be thoughtfully integrated in ways appropriate to organizational size and complexity:

#### Level 1: Startup Foundation
<img src="./assets/icons/garage-duotone.svg" alt="Garage" align="right" width="100px" height="auto" /> 

- **Essential security tools**
    
    - Focus on high-impact, low-maintenance technologies
    - Leverage cloud security capabilities
    - Utilize managed security services where appropriate
    - Prioritize automation of routine security tasks
    
- **Key technologies:**
    
    - Cloud-native security controls
    - Basic endpoint protection
    - Simple identity management
    - Automated backup solutions

**Example:** A small e-commerce startup leverages their cloud provider's built-in security features, implements multi-factor authentication through a managed identity provider, and uses a combination of simple monitoring tools to maintain visibility into their environment. They focus on solutions that provide maximum security value with minimal maintenance overhead.

#### Level 2: Scale-up Enhancement
<img src="./assets/icons/building-office-duotone.svg" alt="Office" align="right" width="100px" height="auto" /> 

- **Integrated security technology stack**
    
    - Cohesive set of security technologies
    - Integration between key security systems
    - Balance between in-house and managed services
    - Automation of security operations
    
- **Key technologies:**
    
    - Security information and event management (SIEM)
    - Vulnerability management systems
    - Advanced endpoint protection
    - Cloud security posture management

**Example:** A mid-sized software company builds an integrated security stack with centralized logging and monitoring, automated vulnerability scanning, and cloud security management tools. They carefully select technologies that work well together, implement automation for routine security tasks, and maintain appropriate balance between security and operational efficiency.

#### Level 3: Enterprise Optimization
<img src="./assets/icons/city-duotone.svg" alt="Buildings" align="right" width="100px" height="auto" /> 

- **Enterprise security architecture**
    
    - Comprehensive security technology framework
    - Deep integration across security domains
    - Advanced automation and orchestration
    - Security technology governance
    
- **Key technologies:**
    
    - Security orchestration and automation
    - Advanced detection and response capabilities
    - Comprehensive identity and access management
    - Enterprise governance, risk and compliance platforms

**Example:** A global financial institution implements an enterprise security architecture with specialized technologies for different security domains, all integrated through a central orchestration platform. They maintain a formal technology lifecycle management process, measure technology effectiveness through comprehensive metrics, and continuously evaluate emerging security technologies against their strategic needs.

### Finding the Right Balance

The intersection of People, Process, and Technology creates a balanced security approach—but that balance looks different at each maturity level:

#### Level 1: Startup Balance
<img src="./assets/icons/garage-duotone.svg" alt="Garage" align="right" width="100px" height="auto" /> 

- **People-weighted approach**
    - Rely more heavily on people than formal processes
    - Select technologies that amplify limited human resources
    - Keep processes focused on highest-value activities
    - Develop skills aligned with critical security needs

**Cross-Functional Integration**:

- Encourage cross-training so team members understand the security aspects of different functions
- Use regular all-hands meetings to maintain security awareness across functions
- Emphasize clear, jargon-free communication about security concepts
- Create simple guidelines that translate to different functional roles

#### Level 2: Scale-up Balance
<img src="./assets/icons/building-office-duotone.svg" alt="Office" align="right" width="100px" height="auto" /> 

- **Transitional balance**
    - Develop more formal processes as team grows
    - Implement technologies that enable consistent security
    - Build specialized security skills in key personnel
    - Formalize security responsibilities across teams

**Cross-Functional Integration**:

- Define clear security interfaces between functions (e.g., how product requirements incorporate security)
- Establish regular cross-functional security reviews for major initiatives
- Create function-specific security training and guidance
- Map security responsibilities to existing functional roles

#### Level 3: Enterprise Balance
<img src="./assets/icons/city-duotone.svg" alt="Buildings" align="right" width="100px" height="auto" /> 

- **Comprehensive integration**
    - Maintain formal processes across all security domains
    - Implement enterprise security technology architecture
    - Develop specialized security organization
    - Create governance frameworks that connect all elements

**Cross-Functional Integration**:

- Establish formal cross-functional security governance bodies / forums
- Integrate security into enterprise architectural standards
- Develop technical and process interfaces between security and other functions
- Implement security service models that clarify how security capabilities are delivered to different functions

### Common Balance Challenges

|Challenge|Level 1 Solution|Level 2 Solution|Level 3 Solution|
|---|---|---|---|
|**Over-reliance on tools**|Focus on people skills and awareness|Implement balanced security program|Develop comprehensive security architecture|
|**Process bureaucracy**|Keep processes lightweight and focused|Design for appropriate formality|Implement efficiency metrics for processes|
|**Skill gaps**|Leverage managed services|Develop targeted training|Create comprehensive security career paths|
|**Disconnected elements**|Maintain regular security discussions|Implement coordination mechanisms|Create formal governance frameworks|
|**Functional silos**|Regular all-hands security updates|Security champions in each function|Enterprise security operating model with clear interfaces|

## Practical Application

### Applying Core Principles to Security Activities

The core principles of the Peak Defence Method directly inform how security activities are conducted at each maturity level:

#### Level 1: Startup Application
<img src="./assets/icons/garage-duotone.svg" alt="Garage" align="right" width="100px" height="auto" /> 

1. **Shaping security work**
    
    - Define small, high-impact security improvements
    - Focus on controls that provide both prevention and detection
    - Balance security needs with limited resources
    - Prioritize foundational security capabilities
    
2. **Betting on security initiatives**
    
    - Make explicit decisions about security investments
    - Consider both protection and resilience value
    - Recognize and accept specific security risks
    - Allocate time for security improvement regularly
    
3. **Building security capabilities**
    
    - Implement controls that detect failures
    - Create simple recovery procedures
    - Document security activities for consistency
    - Test security controls regularly

#### Level 2: Scale-up Application
<img src="./assets/icons/building-office-duotone.svg" alt="Office" align="right" width="100px" height="auto" /> 

1. **Shaping security work**
    
    - Design layered security controls
    - Create clear success metrics for initiatives
    - Consider resilience requirements explicitly
    - Balance security improvement with business needs
    
2. **Betting on security initiatives**
    
    - Maintain balanced security investment portfolio
    - Make risk-informed prioritization decisions
    - Allocate resources based on threat landscape
    - Track security improvement over time
    
3. **Building security capabilities**
    
    - Implement robust detection and response
    - Create formal incident handling procedures
    - Develop security metrics dashboard
    - Establish continuous improvement processes

#### Level 3: Enterprise Application
<img src="./assets/icons/city-duotone.svg" alt="Buildings" align="right" width="100px" height="auto" /> 

1. **Shaping security work**
    
    - Architect comprehensive security capabilities
    - Align security initiatives with enterprise strategy
    - Design for operational integration
    - Consider organizational change management
    
2. **Betting on security initiatives**
    
    - Implement formal security investment governance
    - Maintain enterprise risk register
    - Create multi-year security improvement roadmap
    - Balance strategic and tactical security needs
    
3. **Building security capabilities**
    
    - Implement security orchestration and automation
    - Create comprehensive detection architecture
    - Develop specialized response capabilities
    - Establish formal security measurement program

### Cross-Functional Application of Core Principles

Effective security requires translating core principles to different functional contexts:

#### Level 1: Startup Translation
<img src="./assets/icons/garage-duotone.svg" alt="Garage" align="right" width="100px" height="auto" /> 

1. **For Engineering/Product**
    
    - Simplify security principles into practical coding/design guidelines
    - Integrate security into existing development workflows
    - Focus on automation that reduces security burden during development
    
2. **For Business/Operations**
    
    - Translate security risks into business impact language
    - Develop simple decision frameworks for security-business tradeoffs
    - Create shared responsibility models for operational security
    
3. **For Legal/Compliance**
    
    - Map resilience principles to contractual and compliance requirements
    - Develop simple templates for security-related agreements
    - Create clear escalation paths for security-legal questions

#### Level 2: Scale-up Translation
<img src="./assets/icons/building-office-duotone.svg" alt="Office" align="right" width="100px" height="auto" /> 

1. **For Engineering/Product**
    
    - Develop security patterns and reference architectures
    - Create security requirements templates for product management
    - Establish security checkpoint process for development lifecycle
    
2. **For Business/Operations**
    
    - Implement structured risk acceptance process
    - Develop function-specific security metrics
    - Create security service catalogs for different business functions
    
3. **For Legal/Compliance**
    
    - Develop compliance mapping frameworks
    - Create standardized security-legal review processes
    - Implement structured security requirements for vendors/partners

#### Level 3: Enterprise Translation
<img src="./assets/icons/city-duotone.svg" alt="Buildings" align="right" width="100px" height="auto" /> 

1. **For Engineering/Product**
    
    - Implement comprehensive secure development lifecycle
    - Develop domain-specific security architectures
    - Create security centers of excellence for engineering domains
    
2. **For Business/Operations**
    
    - Establish formal security governance with business representation
    - Implement business-aligned security investment model
    - Develop comprehensive security operating model
    
3. **For Legal/Compliance**
    
    - Implement enterprise compliance management framework
    - Develop comprehensive legal-security integration model
    - Create standardized security-legal playbooks for different scenarios

## Maturity Assessment Questions

Use these questions to assess your organization's alignment with core principles:

1. **How does your security approach balance prevention and resilience?**
    - Level 1: Basic focus on critical system recovery
    - Level 2: Structured approach with defined resilience requirements
    - Level 3: Comprehensive resilience architecture framework
2. **How do you balance people, process, and technology in security?**
    - Level 1: Informal balance with focus on essential elements
    - Level 2: Structured approach with defined roles and responsibilities
    - Level 3: Formal integration through enterprise security architecture
3. **How do you measure security effectiveness?**
    - Level 1: Basic tracking of security incidents and activities
    - Level 2: Defined metrics for key security capabilities
    - Level 3: Comprehensive security measurement program
4. **How do you learn and adapt from security events?**
    - Level 1: Informal lessons learned discussions
    - Level 2: Structured incident reviews and improvement processes
    - Level 3: Formal security intelligence and adaptation program
5. **How do security principles inform technology decisions?**
    - Level 1: Basic consideration of security requirements
    - Level 2: Structured security requirements in technology selection
    - Level 3: Comprehensive security architecture governing technology
6. **How effectively do different organizational functions collaborate on security?**
    - Level 1: Informal collaboration based on relationships
    - Level 2: Structured coordination with defined touchpoints
    - Level 3: Comprehensive integration through formal interfaces and governance

## Next Steps

Understanding the Core Philosophy is the foundation for successfully implementing the Peak Defence Method. From here, you can:

1. Explore the [Planning Horizons](planning.md) to understand how work is organized across different time scales
2. Learn about [Shaping Security Work](shaping.md) to define security initiatives effectively
3. Review [Security Roles and Responsibilities](./roles) to understand who does what within the method
4. Consider how these principles translate to different functions within your organization and begin building cross-functional understanding using the guidance in this chapter
