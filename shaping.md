# Shaping Security Work

## Introduction

Security initiatives fail for many reasons, but often there is a common pattern: **they're either too vague or too specific before implementation begins**. Traditional approaches oscillate between these extremes:

- **Too abstract**: "Implement zero trust architecture" or "Improve our security posture" lack clear boundaries and direction
- **Too concrete**: Detailed specifications that over-constrain implementation teams and can't adapt to discoveries made during implementation

Shaping security work is the critical process that bridges this gap. It creates **just enough structure** to enable teams to deliver meaningful security improvements within fixed time constraints, while leaving room for adaptation and expertise.

Security shaping inherently crosses organizational boundaries. Unlike purely technical security work, well-shaped security initiatives must consider impacts on and contributions from various business functions. This integrated approach ensures security work delivers value while remaining implementable within organizational constraints.

This chapter explains how organizations of different sizes and maturity levels can effectively shape security initiatives, ensuring they're:

- **Appropriately scoped** for available resources
- **Well-defined** but not over-specified 
- **Designed for resilience** in line with our [core principles](core.md)
- **Implementable** within the organization's capabilities
- **Coordinated across functions** to avoid silos and ensure business alignment

## Maturity Level Framework

Shaping security work evolves as organizations grow in size and capability. The table below illustrates how key characteristics change across maturity levels:

| Characteristic                   | Level 1: Startup                           | Level 2: Scale-up                                               | Level 3: Enterprise                               |
| -------------------------------- | ------------------------------------------ | --------------------------------------------------------------- | ------------------------------------------------- |
| **Formality**                    | Lightweight, conversational                | Structured but flexible                                         | Comprehensive, documented                         |
| **Participants**                 | Founder/CTO + key team members             | Security lead + stakeholders                                    | Security architects + specialized teams           |
| **Timeframe**                    | Hours to days                              | Days to a week                                                  | 1-2 weeks                                         |
| **Documentation**                | Brief, focused scope pitch                 | Detailed scope pitch with visuals                               | Formal document with supporting materials         |
| **Risk Analysis**                | Key risks only                             | Systematic risk review                                          | Comprehensive risk and resilience analysis        |
| **Tooling**                      | Simple, accessible tools                   | Purpose-built templates                                         | Specialized platforms                             |
| **Cross-Functional Integration** | Direct collaboration with founders/leaders | Structured touchpoints with department heads                    | Formal governance across organizational functions |
| **Boundary Objects**             | Simple scope pitch visible to all teams    | Security problem-solution templates with department touchpoints | Enterprise architecture with security components  |

### Progression Indicators

#### When to move from Level 1 to Level 2:

- Security initiatives regularly exceed their appetites or scope
- Multiple teams need to collaborate on security implementations
- The organization has dedicated security personnel
- Security initiatives affect significant portions of the business
- Cross-functional dependencies become more complex
- Security constraints need documentation for external partners
- Product development requires earlier security involvement

#### When to move from Level 3 to Level 3:

- Complex, organization-wide security initiatives are common
- Multiple specialized security teams exist
- Regulatory compliance requires formal documentation
- Enterprise architecture governance is established
- Security roadmaps span multiple quarters or years
- Cross-functional security processes span multiple departments
- Security architecture affects enterprise-wide systems

## Shaping Across Planning Horizons

Security shaping doesn't exist in isolation—it operates within the context of the [planning horizons](planning.md) that structure security work across different timescales. As organizations mature, they need to consider how shaping applies across these different horizons.

### How Shaping Differs Across Horizons

| Horizon                  | Shaping Focus                                                       | Outputs                                                            | Maturity Relevance                                                                     | Cross-Functional Considerations                                                                  |
| ------------------------ | ------------------------------------------------------------------- | ------------------------------------------------------------------ | -------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------ |
| **Lifetime** (Years)     | Security principles, architectural patterns, and strategic approach | Reference architectures, security principles, strategic boundaries | Critical for Level 3, emerging at Level 2, often implicit at Level 1                   | Business strategy alignment, legal/regulatory frameworks, technology strategy integration        |
| **Yearly** (12 Months)   | Major security capabilities and program-level initiatives           | Security roadmaps, capability definitions, resource planning       | Formalized at Level 3, simplified at Level 2, often combined with quarterly at Level 1 | Resource allocation across departments, compliance coordination, technology investment alignment |
| **Quarterly** (3 Months) | Specific security initiatives and projects                          | Shaped pitches for betting consideration, project portfolios       | Primary focus of shaping at all maturity levels                                        | Product roadmap integration, engineering coordination, operational impact analysis               |
| **Cycle** (6 Weeks)      | Execution-level scoping and adaptation                              | Scope maps, implementation plans                                   | Where shaped work is implemented rather than shaped                                    | Development team collaboration, release coordination, operational handoffs                       |

This matrix helps organizations understand how shaping evolves across both planning horizons and organizational maturity levels.

### Horizon Integration in Practice

#### Level 1: Horizon Collapse for Startups

For startups and small organizations, planning horizons often collapse together:

- **Practical Approach**: Startups typically combine yearly and quarterly horizons into a single planning timeframe, with minimal lifetime-horizon work
- **Shaping Focus**: Focus shaping efforts at the quarterly horizon—identifying specific, high-impact security improvements
- **Key Technique**: Ensure scoped work connects to the organization's highest security priorities, even without formal horizon planning
- **Cross-Functional Integration**: Shape security work in direct collaboration with founders and team leads to ensure alignment with product and business priorities

**Example**: A startup might shape a "Secure Authentication Implementation" initiative directly without placing it in a broader capability roadmap or architectural framework. The shaping process would involve the CTO working directly with the product lead to ensure the authentication solution meets both security and user experience requirements.

#### Level 2: Emerging Multi-Horizon Shaping

As organizations grow to mid-size, multiple planning horizons begin to emerge:

- **Practical Approach**: Maintain separate yearly and quarterly planning, with emerging lifetime-horizon thinking
- **Shaping Focus**: Shape at both quarterly horizon (specific initiatives) and yearly horizon (capability development)
- **Key Technique**: Ensure shaped quarterly work explicitly connects to yearly security objectives
- **Cross-Functional Integration**: Establish structured touchpoints with department heads during the shaping process to identify dependencies and constraints

**Example**: A scale-up organization shapes both a yearly "Identity Management Enhancement" capability initiative and several quarterly projects that support it, like "MFA Implementation" and "SSO Integration." The security lead works with engineering managers to understand technical constraints and with product management to align with product roadmaps.

#### Level 3: Comprehensive Horizon Planning

Enterprise organizations maintain clear separation between planning horizons:

- **Practical Approach**: Formal processes for each planning horizon with clear governance
- **Shaping Focus**: Different shaping approaches for different horizons, with specialized teams
- **Key Technique**: Maintain traceability between shaped work at different horizons
- **Cross-Functional Integration**: Formalized governance processes ensure cross-functional alignment at each horizon level

**Example**: An enterprise shapes security architecture patterns at the lifetime horizon, defines "Zero Trust Implementation" at the yearly horizon, shapes "User Authentication Modernization" at the quarterly horizon, and implements specific components in each six-week cycle. Cross-functional governance ensures alignment with enterprise architecture, compliance requirements, and product roadmaps.

### Aligning Shaped Work Across Horizons

Regardless of maturity level, organizations need mechanisms to ensure shaped work aligns across relevant planning horizons:

#### Level 1: Simple Alignment

- **Documentation**: Brief notes on how shaped initiatives support key security priorities
- **Verification**: Informal check with founders/leadership before betting on shaped work
- **Adaptation**: Fast pivots when business or security priorities change
- **Cross-Functional Coordination**: Shared visibility through simple artefacts like roadmap board or shared documents

#### Level 2: Structured Alignment

- **Documentation**: Explicit mapping of shaped initiatives to yearly security objectives
- **Verification**: Review of quarterly shaped work against yearly security roadmap
- **Adaptation**: Quarterly reassessment of security priorities and shaped work pipeline
- **Cross-Functional Coordination**: Security representatives participate in departmental planning and vice versa

#### Level 3: Governance-Driven Alignment

- **Documentation**: Formal traceability from lifetime principles through yearly capabilities to quarterly initiatives
- **Verification**: Stage-gate reviews to ensure alignment across horizons
- **Adaptation**: Structured change management processes for security roadmap modifications
- **Cross-Functional Coordination**: Formal governance with representatives from all key functions

### Common Horizon Alignment Challenges

| Challenge                                                     | Level 1 Solution                                             | Level 2 Solution                                            | Level 3 Solution                                          | Cross-Functional Element                                          |
| ------------------------------------------------------------- | ------------------------------------------------------------ | ----------------------------------------------------------- | --------------------------------------------------------- | ----------------------------------------------------------------- |
| **Disconnection between strategic vision and implementation** | Frequent all-hands discussions of security priorities        | Explicit mapping documents between initiatives and strategy | Formal traceability requirements in shaping process       | Include product and business leads in security discussions        |
| **Shifting priorities creating wasted shaping effort**        | Shape smaller initiatives closer to implementation           | Maintain a small portfolio of shaped work                   | Use rolling wave planning with horizon-appropriate detail | Coordinate priority changes across affected departments           |
| **Inconsistent approach across horizons**                     | Designate a single person responsible for security direction | Create lightweight templates for different horizons         | Establish formal governance across planning horizons      | Ensure consistent representation of key functions at each horizon |

### Practical Tips for Horizon-Aligned Shaping

1. **Start where you are**: Focus shaping at the planning horizon most relevant to your organization's maturity
2. **Create visible connections**: Even with informal processes, document how shaped work connects to longer-term security needs
3. **Shape appropriately for the horizon**: Use less detail at longer horizons, more specificity at shorter ones
4. **Validate downward**: Ensure longer-horizon shaping creates legitimate space for shorter-horizon work
5. **Validate upward**: Confirm shorter-horizon shaped work supports longer-term security objectives
6. **Include the right people**: Ensure appropriate cross-functional representation at each horizon level

By understanding how shaping intersects with planning horizons, organizations can ensure their security initiatives remain aligned with strategic direction while still maintaining the benefits of bounded, concrete implementation work.

<img src="./assets/icons/garage-duotone.svg" alt="Garage" align="right" width="100px" height="auto" /> 

## Level 1: Startup Foundation

**Target Organization**: Startups and small organizations (5-50 employees)  
**People Required**: Founder/CTO time + key team members

At the startup level, security shaping must be lightweight yet effective. The goal is to create enough structure to guide implementation without bureaucracy that would slow down a small, agile team.

### Essential Shaping Process

#### 1. Set Boundaries (1-2 hours)

**Define the security problem and appetite:**

1. **Start with the security need** - What specific risk or customer concern are we addressing?
2. **Set a time constraint** - How much time can we afford to spend on this? For startups, typical appetites are:
    - Small security improvement: 2-3 days
    - Significant security feature: 1-2 weeks
3. **Narrow the scope** - What specific aspects of the problem will we address now vs. later?
4. **Identify key stakeholders** - Which teams or functions will be affected by this security initiative?

**Cross-Functional Considerations:**
- Include at least one person from product or engineering in boundary-setting to ensure technical feasibility
- Consider customer-facing implications by consulting with sales or support if relevant
- Ensure founders are aware of security work that might affect product roadmap

**Example**:

> "We need to implement MFA for customer accounts before our enterprise customer signs. We can dedicate one developer for one week. We'll focus only on email-based verification for this phase. This will affect our authentication flow, so we need input from our product designer."

#### 2. Outline the Solution (2-3 hours)

1. **Identify key components** - What are the main parts of the solution?
2. **Sketch critical user or system flows** - How will the security measure work?
3. **Define success criteria** - How will we know it's working correctly?
4. **Map cross-functional touchpoints** - Where will this security initiative intersect with other functions?

Use simple tools like:

- Whiteboard sketches
- Flowcharts (can be even drawn on paper)
- Brief written descriptions
- Simple interface mockups

**Cross-Functional Boundary Objects:**
- User flow sketches that show security-UX tradeoffs
- Simple technical diagrams showing integration points
- One-page overview visible to the whole team

**Example Cross-Functional Touchpoint Map:**

> MFA Implementation
> - Product Design: Authentication flow changes (Joe)
> - Engineering: API changes for verification (Sarah)
> - Customer Support: User guidance needed (Tina)
> - Sales: Enterprise customer update (Miguel)


#### 3. Address Key Risks (1-2 hours)

1. **List 3-5 top risks** that could derail the project
2. **Define simple mitigation approaches** for each risk
3. **Identify minimum viable resilience measures**:
    - How will we know if this security control fails?
    - What's our simplest recovery approach?
4. **Consider cross-functional risks**:
    - User experience friction
    - Development timeline conflicts
    - Customer support implications
    - Sales or compliance commitments

**Example Risk Analysis**:

> "Risk: Users won't complete the MFA setup process"  
> "Mitigation: Make MFA optional initially, but show security benefit clearly"  
> "Resilience: Track setup completion rates and add reminders if below 50%"
>
> "Cross-functional risk: Support team needs to handle account recovery cases"
> "Mitigation: Create simple account recovery process for locked-out users"
> "Resilience: Monitor support ticket volume for MFA issues, adjust process if needed"

#### 4. Create a Simple Pitch (1-2 hours)

Document the shaped work in a brief format that can be shared with the implementation team:

--- 
## MFA Implementation

Problem: Enterprise customers require MFA for compliance.

Appetite: 1 developer, 1 week

Solution:
- Email-based verification code
- Optional enrollment for existing users
- Required for new users
- Simple setup flow with clear instructions

Risks:
- Low adoption: Track rates, add reminders if < 50%
- Performance impact: Ensure verification emails send asynchronously
- Recovery: Allow account recovery via support for locked-out users

Cross-Functional Requirements:
- Product: Need design review of auth flow (1-2 hours)
- Support: Create account recovery process (half-day)
- Sales: Update enterprise customer on timeline (brief email)

Not included:
- SMS verification
- Hardware token support
- Admin MFA enforcement options
---

### Cross-Functional Coordination

For small organizations, cross-functional coordination happens through direct collaboration:

1. **Joint Shaping Sessions**
   - Include at least one person from affected functions in shaping
   - Use simple shared documents that all stakeholders can access
   - Focus on key touchpoints rather than comprehensive documentation

2. **Shared Visibility**
   - Post shaped security work where all team members can see it
   - Use existing team communication channels for updates
   - Review security work in regular company-wide meetings

3. **Direct Handoffs**
   - Clear person-to-person communication about requirements
   - Immediate feedback loops during implementation
   - Joint problem-solving for cross-functional challenges

**Example Boundary Object**: 

The "Security Initiative One-Pager" - a simple document showing:
- Problem statement and business impact
- Proposed solution with key components
- Timeline and resource needs
- Cross-team dependencies and touchpoints
- Success criteria that matter to different functions

### Implementation Guidance

For small organizations, the implementation approach should be:

1. **Informal kick-off** - Discuss the pitch directly with implementers
2. **Regular check-ins** - Brief daily updates to catch issues early
3. **Flexible adaptation** - Allow the team to adjust the approach as they learn
4. **Ship and learn** - Get the security improvement to users quickly, then iterate
5. **Cross-functional coordination** - Maintain direct communication with affected teams

### Common Challenges and Solutions

|Challenge|Solution|Cross-Functional Element|
|---|---|---|
|Too many competing priorities|Set explicit security time budgets (e.g., 10% of developer time)|Align with product roadmap priorities|
|Limited security expertise|Focus on high-impact controls; use security-as-a-service where possible|Leverage domain knowledge from different teams|
|Scope expansion during implementation|Ruthlessly defer nice-to-haves to future phases|Communicate scope decisions to affected teams|
|Balancing security and speed|Implement minimum viable security controls with quick feedback loops|Involve UX early to minimize friction|
|Security slowing product development|Shape security work to align with product development cycles|Include product lead in security shaping sessions|

### Signs You've Outgrown Level 1

- Security shaping consistently takes more than a day
- Multiple teams need to collaborate on security implementations
- Security initiatives regularly affect your entire product or infrastructure
- You have dedicated security personnel who need to be involved in shaping
- Cross-functional impacts become hard to manage through direct communication
- External security requirements require more formal documentation
- Product timeline conflicts with security needs become more frequent

<img src="./assets/icons/building-office-duotone.svg" alt="Office" align="right" width="100px" height="auto" /> 

## Level 2: Scale-up Enhancement

**Target Organization**: Growing organizations (50-500 employees)  
**People Required**: Security lead + relevant stakeholders

As organizations grow, security initiatives become more complex and touch more parts of the business. Scale-ups need a more structured approach to shaping while maintaining reasonable speed and flexibility.

### Enhanced Shaping Process

#### 1. Set Boundaries (1-2 days)

**Define the security problem and appetite more thoroughly:**

1. **Research the security need**:
    - Gather data on security incidents or near-misses
    - Interview key stakeholders to understand business impact
    - Review customer or compliance requirements
    - Map cross-functional implications 
2. **Set a strategic appetite**:
    - Small security initiative: 1-2 weeks
    - Medium security initiative: 3-4 weeks
    - Large security initiative: 6-week cycle
3. **Define specific scope boundaries**:
    - Document in-scope and out-of-scope elements
    - Identify affected systems and teams
    - Define explicit success criteria
    - Document cross-functional dependencies

**Cross-Functional Considerations:**
- Conduct structured interviews with key function representatives
- Create a draft boundary document for stakeholder review before finalizing
- Map affected business processes across departments
- Identify potential compliance or legal implications early

**Example**:

> "We need to implement session security improvements to address findings from our recent penetration test. This is worth a 3-week effort with one security engineer and one developer. The scope includes session timeout, device fingerprinting, and suspicious activity detection. It excludes changes to the authentication system itself. We'll need input from product, legal compliance, and customer success teams."

#### 2. Design the Solution (2-3 days)

1. **Conduct lightweight threat modeling**:
    - Identify key assets and data flows
    - Map relevant threat actors and attack vectors
    - Prioritize security controls based on risk
    - Include cross-functional perspectives
2. **Create solution sketches**:
    - Flow diagrams of security processes
    - Key security interfaces and interactions
    - System component diagrams
    - User experience considerations
3. **Map existing vs new components**:
    - Identify which systems need modification
    - Document integration points
    - Define clear boundaries between components
    - Highlight cross-functional requirements

**Cross-Functional Boundary Objects:**
- Security requirements templates for product and engineering
- Responsibility matrix for the initiative
- %% Integration point diagrams showing handoffs between teams %%
- %% User journey maps showing security touchpoints %%

**Example Cross-Functional Design Session:**
Conduct a 2-hour workshop with key representatives from:
- Security: Lead and define security requirements
- Engineering: Assess technical feasibility
- Product: Evaluate user experience impact
- Legal: Review compliance implications
- Customer Success: Consider support implications

Use a shared template to capture:
- Core security requirements
- Technical constraints
- User experience considerations
- Compliance requirements
- Support and operational needs

#### 3. Conduct Risk and Resilience Analysis (1-2 days)

1. **Identify implementation risks**:
    - Technical uncertainties
    - Integration challenges
    - User experience impacts
    - Timeline risks
    - Cross-functional challenges
2. **Define resilience requirements**:
    - Detection mechanisms for security control failures
    - Response procedures for when controls fail
    - Recovery approaches for affected systems
    - Adaptation mechanisms to improve over time
3. **Develop explicit mitigations**:
    - Specific approaches for each significant risk
    - Clear definitions of acceptable risk
    - Contingency options if primary approach fails
    - Cross-functional escalation paths

**Example Cross-Functional Risk Assessment:**
---
Risk: New session controls may disrupt legitimate user sessions
Impact: High (customer frustration, support load, potential lost sales)
Cross-Functional Owners: Security, Product, Customer Support
Mitigation: 
1. Phased rollout with monitoring metrics (Engineering)
2. Clear user messaging about security changes (Product)
3. Prepare support team with FAQ and resolution paths (Customer Success)
Resilience Measure: Monitor session termination rates and user complaints
Escalation: If disruption exceeds 2% of sessions, reconvene cross-functional team
---

#### 4. Create a Detailed Pitch (1-2 days)

Document the shaped work in a structured format:

--- 
## Session Security Improvements Pitch

## Problem Statement
Recent penetration testing revealed several session management vulnerabilities:
- No automatic session timeout
- No validation of session origin
- No detection of suspicious session activities

This creates risk of session hijacking and unauthorized access to customer data.

## Appetite
This initiative is worth a 3-week effort with:
- 1 security engineer (full-time)
- 1 developer (full-time)
- QA support (part-time)

## Solution

### Key Components
1. Session Timeout System
   - Configurable idle timeout (default 30 minutes)
   - Automatic termination after 24 hours
   - User notification before timeout

2. Device Fingerprinting
   - Capture device characteristics on login
   - Validate characteristics on each request
   - Flag significant changes for verification

3. Suspicious Activity Detection
   - Monitor for abnormal session behavior
   - Flag geographic location changes
   - Detect unusual access patterns

### Integration Points
- Authentication service: Session creation hooks
- API gateway: Request validation middleware
- User preferences: Timeout settings storage

### User Experience Considerations
- Clear timeout warnings to prevent data loss
- Minimally intrusive reverification process
- Clear explanations for security challenges

## Cross-Functional Requirements

### Product Team
- Review session timeout UX design (2 days)
- Update product documentation (1 day)
- Define user messaging for security challenges (2 days)

### Engineering
- Integration with authentication service (1 week)
- Performance testing of request validation (3 days)
- Update API documentation (1 day)

### Customer Success
- Update security FAQ documentation (1 day)
- Train support team on new security features (2 hours)
- Create troubleshooting guide for common issues (1 day)

### Legal/Compliance
- Review changes against compliance requirements (1 day)
- Update relevant security documentation (half day)

## Risks and Resilience

### Key Risks
1. Performance impact of per-request validation
   - Mitigation: Implement caching layer for device fingerprints
   - Fallback: Reduce validation frequency if performance issues emerge

2. False positives disrupting legitimate users
   - Mitigation: Phased rollout with monitoring of challenge rates
   - Adaptation: Tune detection algorithms based on actual usage patterns

3. Integration complexity with legacy systems
   - Mitigation: Create middleware adapter for legacy integration
   - Contingency: Phase implementation starting with newest services

4. Customer frustration with new security measures
   - Mitigation: Clear explanations and user education
   - Response: Dedicated support process for security-related issues
   - Measurement: Monitor user feedback and abandonment rates

### Resilience Mechanisms
- Comprehensive logging of all session security decisions
- Monitoring dashboard for security control effectiveness
- Manual override process for support team
- Killswitch capability to disable new controls if critical issues emerge

## Out of Scope
- Authentication system changes
- Password policy modifications
- Admin session management
- Mobile app session handling (separate initiative)
---

### Cross-Functional Coordination

For scale-up organizations, more structured cross-functional coordination becomes necessary:

1. **Security Representatives Model**
   - Designate security champions or liaisons in key departments
   - Establish structured touchpoints during shaping process
   - Create clear handoff processes between functions

2. **Structured Boundary Objects**
   - Security requirements templates tailored to different functions
   - RACI matrices for security initiatives
   - Documented integration points and dependencies
   - Clear success criteria for different stakeholders

1. **Role-Specific Artefacts**
   - Product: User experience considerations and wireframes
   - Engineering: Integration requirements and technical constraints
   - Legal/Compliance: Regulatory implications and requirements
   - Operations: Deployment considerations and runbooks
   - Support: User guidance and troubleshooting procedures

**Example Boundary Object**: The "Security Initiative Brief" - a structured document with sections for:
- Executive summary for leadership
- Detailed technical requirements for engineering
- User experience considerations for product
- Implementation timeline for project management
- Support guidelines for customer success
- Compliance implications for legal

### Implementation Approach

For scale-up organizations, the implementation approach should include:

1. **Formal kick-off meeting** - Review the pitch with the entire implementation team
2. **Scope mapping** - Break the work into clear, trackable scopes
3. **Regular review cadence** - Twice-weekly status reviews with hill chart updates
4. **Structured testing** - Dedicated QA for security controls
5. **Post-implementation review** - Capture lessons for future security initiatives
6. **Cross-function handoffs** - Formal transition of deliverables between teams

### Common Challenges and Solutions

| Challenge                                            | Solution                                                   | Cross-Functional Element                             |
| ---------------------------------------------------- | ---------------------------------------------------------- | ---------------------------------------------------- |
| Cross-team dependencies                              | Identify dependencies early and establish clear interfaces | Create dependency maps with timelines and owners     |
| Security vs usability tensions                       | Involve product design in the shaping process              | Conduct joint usability-security workshops           |
| Technical debt complications                         | Explicitly factor remediation time into the appetite       | Coordinate with engineering on technical constraints |
| Completing security work on time                     | Visualize progress through unknowns                        | Communicate status to stakeholders with visual tools |
| Unclear security-business alignment                  | Link security initiatives to business objectives           | Include business stakeholders in shaping process     |
| Compliance requirements complicating security design | Engage legal/compliance early in shaping                   | Create compliance-security translation guides        |

### Signs You've Outgrown Level 2

- Security initiatives regularly span multiple teams and systems
- Regulatory requirements demand more formal documentation
- You have multiple specialized security teams (AppSec, InfraSec, etc.)
- Enterprise architecture governance is established
- Security roadmaps span multiple quarters or years
- Compliance requirements drive significant security work
- Multiple business units have different security needs

<img src="./assets/icons/city-duotone.svg" alt="Buildings" align="right" width="100px" height="auto" /> 

## Level 3: Enterprise Optimization

**Target Organization**: Large organizations (500+ employees)  
**Resources Required**: Security architects + specialized teams + key stakeholders

Enterprise organizations deal with complex, interconnected systems and often have regulatory requirements that demand more comprehensive shaping processes. At this level, shaping becomes more formal while still preserving the core benefits of appropriate abstraction and bounded scope.

### Comprehensive Shaping Process

#### 1. Set Strategic Boundaries (3-5 days)

**Define the security initiative with strategic context:**

1. **Conduct systematic research**:
    - Analyze security incident data and trends
    - Review regulatory and compliance requirements
    - Gather stakeholder requirements across business units
    - Assess alignment with security strategy and roadmap
    - Map cross-functional impacts and requirements
2. **Establish strategic appetite**:
    - Consider total cost of ownership, not just implementation
    - Factor in long-term maintenance requirements
    - Align with quarterly or annual security planning
    - Set appropriate team composition and timeframe
    - Account for cross-functional resource needs
3. **Define comprehensive scope boundaries**:
    - Map affected systems and data flows
    - Document integration with enterprise architecture
    - Define success metrics aligned with security KPIs
    - Establish clear stage gates for implementation
    - Document cross-functional dependencies and requirements

**Cross-Functional Considerations:**
- Formal requirements gathering from business units
- Compliance and legal review of proposed boundaries
- Enterprise architecture alignment review
- Business impact analysis across affected units
- Risk assessment with cross-functional evaluation

**Example Cross-Functional Boundary Setting:**

The security architecture team conducts a series of structured workshops with:
- Business Unit Representatives
- Enterprise Architecture Team
- Legal and Compliance Teams
- Infrastructure and Operations Teams
- Application Development Teams
- Data Governance Teams

Each session follows a structured template to capture:
- Business requirements and constraints
- Technical integration requirements
- Compliance and regulatory needs
- Operational considerations
- Data protection requirements

#### 2. Architect the Solution (5-7 days)

1. **Conduct formal threat modeling**:
    - Use structured methodologies (STRIDE, PASTA, etc.)
    - Create data flow diagrams with trust boundaries
    - Perform attack surface analysis
    - Map controls to security requirements
    - Include multi-function perspectives
2. **Develop architectural designs**:
    - Create architectural decision records (ADRs)
    - Design system integration models
    - Document security control specifications
    - Define technology standards and constraints
    - Map cross-functional interfaces
3. **Validate with specialized teams**:
    - Review with enterprise architecture
    - Validate with security operations
    - Confirm with infrastructure teams
    - Check compliance with security standards
    - Verify with business unit representatives

**Cross-Functional Boundary Objects:**
- Enterprise architecture diagrams with security components
- Business process maps with security controls highlighted
- Security interaction models showing cross-function touchpoints
- Control framework matrices mapping regulations to controls
- Service-level agreements between security and other functions

**Example Cross-Functional Design Artifact:**
A comprehensive solution architecture document with dedicated sections for:
- Technical security architecture (for security and IT teams)
- Business process impact (for business units)
- User experience design (for product teams)
- Implementation approach (for development teams)
- Operational requirements (for operations teams)
- Compliance mappings (for legal and compliance teams)

#### 3. Perform Comprehensive Risk Analysis (3-5 days)

1. **Conduct structured risk assessment**:
    - Identify risks across multiple dimensions
    - Assess likelihood and impact systematically
    - Calculate risk scores based on established methodology
    - Align with enterprise risk management framework
    - Include cross-functional risk perspectives
2. **Design resilience architecture**:
    - Map control failure scenarios and impacts
    - Design layered detection capabilities
    - Develop graduated response mechanisms
    - Create recovery and continuity plans
    - Define continuous improvement processes
    - Include cross-functional response requirements
3. **Develop risk treatment plan**:
    - Document risk acceptance decisions
    - Create detailed mitigation strategies
    - Define risk transfer mechanisms where appropriate
    - Establish residual risk monitoring
    - Assign cross-functional risk ownership

**Example Cross-Functional Risk Management:**

Create a comprehensive risk register that includes:
- Technical security risks (owned by security team)
- Business impact risks (owned by business units)
- Operational risks (owned by operations team)
- Compliance risks (owned by legal team)
- Project delivery risks (owned by project management)

For each risk, document:
- Cross-functional impacts
- Primary and supporting owners
- Mitigation strategies with responsible teams
- Acceptance criteria for each affected function
- Monitoring and reporting requirements

#### 4. Create Formal Security Initiative Work Package (3-5 days)

Enterprise-level shaping produces a comprehensive package that includes:

1. **Executive summary**:
    - Strategic alignment and business case
    - Key risks addressed and expected outcomes
    - Resource requirements and timeline
    - Critical success factors
    - Cross-functional impacts and benefits

2. **Detailed initiative definition**:
    - Problem statement and scope
    - Solution architecture and design
    - Implementation approach and timeline
    - Integration requirements
    - Cross-functional requirements and dependencies

3. **Risk and compliance documentation**:
    - Risk assessment and treatment plan
    - Compliance impact analysis
    - Security control mapping
    - Resilience architecture
    - Cross-functional risk ownership

4. **Implementation governance**:
    - Team structure and responsibilities
    - Phasing and milestone definitions
    - Success criteria and metrics
    - Acceptance criteria and testing approach
    - Cross-functional coordination framework

**Cross-Functional Integration:**
- Dedicated sections addressing each affected business function
- Function-specific requirements and success criteria
- Clear RACI matrix across organizational boundaries
- Structured handoff procedures between functions
- Governance framework for cross-functional decisions

---
**Example Cross-Functional Implementation Package Section:**

## Cross-Functional Implementation Plan

### Business Unit: Finance

#### Requirements
- PCI-DSS compliance maintained throughout implementation
- No disruption to payment processing workflows
- Fraud detection capabilities preserved and enhanced

#### Responsibilities
- Provide subject matter expertise on financial workflows (Finance Director)
- Review technical designs for payment impact (Finance Systems Analyst)
- Validate compliance controls (Compliance Manager)
- Test payment workflows (Finance QA Team)

#### Timeline Integration
- Design review: Week 1
- Control validation: Week 2
- Integration testing: Week 4
- Final sign-off: Week 6

#### Success Criteria
- Zero payment processing disruptions
- Maintain or improve fraud detection rates
- Full PCI-DSS compliance validation

### Business Unit: 

**Customer Service**

#### Requirements
- Clear user messaging for security events
- Support tools for assisting affected customers
- Training on new security controls

#### Responsibilities
- Provide input on customer impact (CS Director)
- Develop support documentation (Knowledge Base Team)
- Create training materials (Training Team)
- Update support scripts (Support Manager)

#### Timeline Integration
- Initial requirements input: Week 1
- Documentation development: Weeks 3-4
- Support team training: Week 5
- Final readiness check: Week 6

#### Success Criteria
- Support team scores 90%+ on readiness assessment
- Support documentation completed and approved
- No increase in average handle time for security-related issues
---

### Cross-Functional Coordination

For enterprise organizations, cross-functional coordination requires sophisticated governance:

1. **Federated Security Model**
   - Security representatives embedded in key business units
   - Formal security working groups with cross-functional membership
   - Security councils at executive and operational levels
   - Structured interfaces between security and other domains

2. **Enterprise Boundary Objects**
   - Security control framework with cross-functional responsibilities
   - Enterprise architecture with security components
   - Business capability models with security elements
   - Cross-functional security service catalogs
   - RACI matrices for security capabilities

3. **Governance Integration**
   - Security requirements integrated into enterprise governance
   - Formal stage gates with security validation
   - Cross-functional change advisory boards
   - Joint risk acceptance frameworks
   - Integrated metrics and reporting

**Example Boundary Object**: 

The "Enterprise Security Control Framework" - a comprehensive system showing:
- Security controls mapped to business processes
- Implementation owners across business units
- Verification and validation requirements
- Evidence collection responsibilities
- Regulatory mapping and compliance requirements
- Operational monitoring and metrics

### Implementation Governance

For enterprise organizations, implementation requires structured governance:

1. **Formal initiative launch** - Enterprise project management procedures
2. **Structured work breakdown** - Comprehensive scope mapping with dependencies
3. **Regular governance reviews** - Status reporting to security leadership
4. **Stage gate validation** - Formal approval at key milestones
5. **Acceptance testing** - Comprehensive security testing and validation
6. **Transition to operations** - Formal handover to operational teams
7. **Cross-functional coordination** - Structured processes for managing dependencies

### Common Challenges and Solutions

|Challenge|Solution|Cross-Functional Element|
|---|---|---|
|Bureaucracy slowing implementation|Create security-specific fast tracks for critical initiatives|Establish cross-functional rapid response teams|
|Balancing enterprise standards with agility|Use pre-approved patterns and reference architectures|Create reusable security components for business units|
|Complex stakeholder landscape|Establish a RACI matrix for security initiatives|Implement stakeholder management framework|
|Integration with legacy systems|Create dedicated integration teams for security implementations|Partner with system owners across business units|
|Maintaining momentum on long initiatives|Break into smaller, independently valuable deliverables|Demonstrate value to each affected function incrementally|
|Cross-functional priority conflicts|Establish executive-level governance for resource conflicts|Transparent prioritization framework across functions|
|Compliance requirements challenging implementation|Create compliance-by-design patterns and templates|Embed compliance specialists in security teams|

### Continuous Improvement

At the enterprise level, each security initiative should contribute to ongoing capability development:

1. **Capture lessons learned** - Formal retrospectives and documentation
2. **Update reference architectures** - Incorporate successful patterns
3. **Refine shaping process** - Continuously improve based on outcomes
4. **Measure security improvement** - Track security metrics before and after
5. **Share knowledge** - Document case studies for future initiatives
6. **Cross-functional feedback** - Gather input from all affected functions

## Cross-Functional Shaping Challenges

### Communication Challenges

|Challenge|Level 1 Solution|Level 2 Solution|Level 3 Solution|
|---|---|---|---|
|**Security terminology barriers**|Use simple, business-focused language|Create function-specific security guides|Develop enterprise taxonomy with shared definitions|
|**Misaligned incentives**|Focus on mutual benefits in shaped work|Shared success criteria across functions|Integrated performance objectives for security|
|**Timing disconnects**|Align security work with product cycles|Coordinate planning across departments|Implement enterprise planning framework|
|**Knowledge silos**|Joint shaping sessions with key functions|Cross-functional security working groups|Federated security model with embedded experts|

### Function-Specific Shaping Techniques

#### Product/Engineering Alignment

|Technique|Level 1 Implementation|Level 2 Implementation|Level 3 Implementation|
|---|---|---|---|
|**Security User Stories**|Simple security requirements in product language|Security story templates for product teams|Security requirements integrated into product lifecycle|
|**Developer-Friendly Controls**|Basic security patterns with code examples|Language-specific security implementation guides|Enterprise security libraries and components|
|**UX-Security Balancing**|Simple UX guidelines for security features|Security-UX workshops for key initiatives|Dedicated security UX specialists|
|**Technical Constraint Mapping**|Identify major technical limitations early|Document integration points and technical constraints|Enterprise architecture integration patterns|

#### Legal/Compliance Alignment

|Technique|Level 1 Implementation|Level 2 Implementation|Level 3 Implementation|
|---|---|---|---|
|**Compliance Translation**|Map basic compliance needs to technical controls|Compliance requirements templates for security initiatives|Enterprise control framework with compliance mapping|
|**Evidence Planning**|Simple evidence collection checklist|Evidence collection protocols for key controls|Automated compliance evidence collection|
|**Risk Acceptance Framework**|Basic sign-off process for residual risks|Structured risk acceptance process with legal review|Enterprise risk management integration|
|**Security-Legal Collaboration**|Direct conversations with legal counsel|Security-legal coordination meetings|Embedded legal experts in security teams|

#### Business/Operations Alignment

|Technique|Level 1 Implementation|Level 2 Implementation|Level 3 Implementation|
|---|---|---|---|
|**Business Impact Analysis**|Simple assessment of business process impacts|Structured business impact templates|Enterprise capability impact framework|
|**Operational Readiness**|Basic operational handover checklists|Formal operational acceptance criteria|Service transition frameworks for security|
|**Support Preparation**|Simple guidance for customer-facing teams|Support playbooks for security features|Comprehensive knowledge management for security|
|**Security Value Articulation**|Focus on immediate business benefits|Security value metrics aligned to business|Enterprise value framework for security investments|

## Boundary Objects for Cross-Functional Shaping

Effective cross-functional security shaping requires shared artifacts that create alignment across organizational boundaries. These boundary objects should evolve with organizational maturity:

### Level 1: Essential Boundary Objects for Startups

1. **Security Initiative One-Pager**
   - Simple description of the security problem and solution
   - Key impacts on product, business, and customers
   - Resource needs and timeline
   - Visible to all team members in shared workspace

2. **Security-UX Wireframes**
   - Simple sketches of security-related user interfaces
   - Focus on key user journeys affected by security controls
   - Highlight potential friction points
   - Created jointly by technical and product team members

3. **Cross-Team Dependency List**
   - Simple list of what's needed from each function
   - Clear owners and timing for each dependency
   - Visible to all affected team members
   - Updated as implementation progresses

### Level 2: Structured Boundary Objects for Scale-ups

1. **Security Requirements Template**
   - Standardized format for expressing security needs
   - Sections tailored to different organizational functions
   - Clear implementation criteria for development teams
   - Links to relevant policies and standards
   - Validation procedures for different stakeholders

2. **Security-Business Impact Matrix**
   - Maps security controls to business processes
   - Highlights potential business impacts of security changes
   - Identifies process owners across functions
   - Used in shaping to identify key stakeholders

3. **Cross-Functional RACI Matrix**
   - Defines roles and responsibilities across functions
   - Identifies decision rights and consultation requirements
   - Clarifies accountability for different aspects of security work
   - Serves as reference during implementation

### Level 3: Sophisticated Boundary Objects for Enterprises

1. **Enterprise Security Control Framework**
   - Comprehensive mapping of security controls
   - Linked to business capabilities and processes
   - Integrated with enterprise architecture
   - Aligned with regulatory requirements
   - Shows implementation responsibilities across functions

2. **Security Services Catalog**
   - Defines security capabilities as services
   - Documents interfaces between security and other functions
   - Specifies service levels and performance metrics
   - Clarifies consumption models for business units

3. **Security Implementation Playbooks**
   - Function-specific implementation guides
   - Standard patterns for common security controls
   - Integration templates for enterprise systems
   - Cross-functional workflows for security processes

## Next Steps

After shaping security work:

1. Proceed to prioritizing shaped work with stakeholders
2. Work moves to [implementation](./implementation) by a dedicated team
3. Throughout implementation track progress through unknowns
4. Ensure continued cross-functional coordination through implementation

If the work isn't selected for implementation, the shaped concept remains available for consideration in future betting cycles. Remember that our [core principles](./core) emphasize learning from both successes and failures – a pitch that isn't selected still provides valuable insights for future security initiatives.

<!-- ## Tools and Resources -->

### Maturity Assessment Questions

Use these questions to assess your organization's security shaping maturity:

1. **Do you set explicit time constraints (appetites) for security initiatives before defining solutions?**
    - Level 1: Sometimes, informally
    - Level 2: Yes, consistently for most initiatives
    - Level 3: Yes, with formal alignment to strategic planning

2. **How do you identify and address risks in shaped security work?**
    - Level 1: Informal identification of major risks
    - Level 2: Structured review with documented mitigations
    - Level 3: Comprehensive risk assessment with formal treatment plans

3. **How do you ensure security initiatives consider resilience, not just prevention?**
    - Level 1: Basic consideration of what happens if controls fail
    - Level 2: Explicit resilience requirements for key controls
    - Level 3: Comprehensive resilience architecture with layered capabilities

4. **How formalized is your security shaping documentation?**
    - Level 1: Brief, informal pitches
    - Level 2: Structured documents with visual elements
    - Level 3: Comprehensive packages with multiple supporting artifacts

5. **Who participates in shaping security initiatives?**
    - Level 1: Founders/CTO and key team members
    - Level 2: Security lead plus relevant stakeholders
    - Level 3: Security architects plus specialized teams and governance

6. **How do you coordinate security initiatives across organizational functions?**
    - Level 1: Direct collaboration with key stakeholders
    - Level 2: Structured touchpoints with department representatives
    - Level 3: Formal governance processes with cross-functional bodies

7. **What boundary objects do you use to create cross-functional alignment?**
    - Level 1: Simple, shared documents visible to all
    - Level 2: Structured templates with function-specific sections
    - Level 3: Enterprise frameworks integrated with business architecture

8. **How do you manage cross-functional dependencies in security work?**
    - Level 1: Track key dependencies through direct communication
    - Level 2: Documented dependency management with clear ownership
    - Level 3: Enterprise dependency management integrated with governance