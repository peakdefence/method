# Planning Horizons

## Introduction

Effective security requires working across multiple time horizons simultaneously. Without a structured approach to planning, organizations typically face these common challenges:

- Strategic initiatives get interrupted by tactical and urgent needs
- Long-term architectural decisions lack follow-through
- Short-term work doesn't align with strategic direction
- Teams lose context when switching between immediate and long-term work
- Security priorities constantly shift, creating waste and confusion
- Cross-functional dependencies create bottlenecks and misalignment
- Security requirements are introduced too late in product or business processes

The Four Horizons Framework provides a structured way to organize security initiatives across different timescales, ensuring that both strategic long-term objectives and tactical immediate needs receive appropriate attention. It also creates natural connection points with other organizational functions, enabling more effective cross-functional security work. This chapter explains how organizations of all sizes can implement this framework at their appropriate maturity level.

## Maturity Level Framework

Planning horizons take different forms as organizations grow in size and capability. The table below illustrates how key characteristics change across maturity levels:

| Characteristic                   | Level 1: Startup                                      | Level 2: Scale-up                                | Level 3: Enterprise                                  |
| -------------------------------- | ----------------------------------------------------- | ------------------------------------------------ | ---------------------------------------------------- |
| **Horizon Separation**           | Condensed horizons with focus on quarterly and cycles | Distinct yearly, quarterly and cycle horizons    | Comprehensive planning across all horizons           |
| **Planning Formality**           | Lightweight, conversational planning                  | Structured planning with basic documentation     | Formal planning with governance and oversight        |
| **Participants**                 | Founders and key team members                         | Security leadership and department heads         | Corporate leadership, security governance committees |
| **Documentation**                | Basic roadmap and cycle plans                         | Documented strategy and implementation plans     | Comprehensive security strategy with detailed plans  |
| **Review Cadence**               | Informal weekly reviews, monthly reset                | Structured bi-weekly reviews, quarterly planning | Formal governance reviews, strategic planning cycle  |
| **Cross-Functional Integration** | Ad hoc coordination with founders/leaders             | Structured touchpoints with department heads     | Formal governance across organizational functions    |
| **Boundary Artefacts**           | Simple roadmap visible to all teams                   | Security roadmap with department dependencies    | Enterprise architecture with security components     |

### Progression Indicators

#### When to move from Level 1 to Level 2:

- Planning regularly spans more than one quarter ahead
- Multiple teams need coordination for security initiatives
- Security roadmap needs to be communicated to investors or customers
- The organization has dedicated security personnel
- Weekly planning becomes insufficient for tracking security work
- Cross-functional dependencies become more complex
- Product development requires earlier security involvement

#### When to move from Level 2 to Level 3:

- Security strategy spans multiple years
- Regulatory requirements demand formal planning documentation
- Multiple security teams require coordination
- Executive governance oversees security investments
- Security planning must align with enterprise architectural standards
- Cross-functional security processes span multiple departments
- Security needs representation in multiple organizational functions

## The Four Horizons Framework

Security work spans multiple time horizons, each requiring different approaches, tools, and mindsets. The Four Horizons Framework provides a structured way to organize security initiatives across these different timescales.

<!-- ![The Four Horizons Framework](/images/four-horizons-framework.png) -->

### Lifetime Horizon (Years)

The Lifetime Horizon encompasses security work with multi-year impact, including:

- **Security principles and architecture** — Foundational decisions about security approaches that will guide the organization for years
- **Core risk tolerance and security strategy** — Fundamental positions on acceptable risk and security investment
- **Long-term security vision** — The desired end-state for security capabilities
- **Cross-functional operating models** — How security integrates with other organizational functions long-term

Work at this horizon is **directional rather than specific**. It establishes boundaries, principles, and goals that guide more concrete work at shorter horizons.

#### Cross-Functional Considerations

At the Lifetime Horizon, security principles must integrate with organizational values and business strategy. Key cross-functional considerations include:

- **Business Strategy Alignment**: How security principles support and enable business objectives
- **Legal and Regulatory Framework**: Long-term compliance requirements and legal risk management
- **Product and Technology Vision**: Security architecture that supports product and technology roadmaps
- **Organizational Culture**: Security values that align with company culture and operating philosophy

### Yearly Horizon (12 Months)

The Yearly Horizon translates long-term vision into actionable annual objectives:

- **Annual risk assessment** — Systematic evaluation of current threats and vulnerabilities
- **Major security initiatives** — Significant capability improvements requiring sustained effort
- **Resource allocation** — Personnel, budget, and technology investments
- **Capability planning** — Developing and maturing security functions
- **Cross-functional security programs** — Structured approaches to security across departments

This horizon provides the strategic context for quarterly and monthly work, ensuring that shorter-term efforts contribute to long-term goals.

#### Cross-Functional Considerations

At the Yearly Horizon, security initiatives must be coordinated with other organizational planning cycles. Key cross-functional considerations include:

- **Budgeting Cycles**: Aligning security resource needs with organizational budgeting
- **Product Roadmaps**: Integrating security requirements with planned product enhancements
- **Technology Initiatives**: Coordinating security improvements with infrastructure and technology changes
- **Compliance Calendar**: Synchronizing with audit schedules and regulatory deadlines
- **Department Planning**: Connecting security objectives with departmental goals and OKRs

### Quarterly Horizon (3 Months)

The Quarterly Horizon focuses on specific, shapeable security projects:

- **Security project portfolios** — Managed sets of related security initiatives
- **Multiple implementation cycles** — Coordination across several execution cycles
- **Progress tracking and adjustment** — Regular evaluation and course correction
- **Emerging threat response** — Adaptation to changing security landscape
- **Cross-functional delivery coordination** — Tactical integration with other teams

At this horizon, we conduct shaping work, make betting (prioritization) decisions, and monitor implementation progress across multiple cycles.

#### Cross-Functional Considerations

At the Quarterly Horizon, security work must integrate with the delivery cycles of other teams. Key cross-functional considerations include:

- **Release Schedules**: Aligning security reviews and implementations with product releases
- **Sprint Planning**: Coordinating security requirements with engineering sprint cycles
- **Sales and Marketing Timelines**: Supporting security-related communications and customer questions
- **Operations Scheduling**: Coordinating security changes with operational maintenance windows
- **Customer Success Planning**: Preparing support teams for security-related customer interactions

### Cycle Horizon (6 Weeks + Cool-down)

The Cycle Horizon is where concrete implementation happens:

- **Security implementation cycles** — Fixed timeboxes for delivering specific security capabilities
- **Operational security management** — Day-to-day security activities
- **Learning and improvement** — Capturing and applying insights
- **Team capacity management** — Allocating team effort effectively
- **Cross-team collaboration** — Direct integration with other teams' work

This is the horizon where shaped (planned) work is executed, delivering tangible security improvements in each six-week cycle.

#### Cross-Functional Considerations

At the Cycle Horizon, security teams work directly with other teams to implement specific controls. Key cross-functional considerations include:

- **Engineering Collaboration**: Pen-testing, security reviews, and architectural guidance
- **Product Management Coordination**: Feature requirements, acceptance criteria, and user stories
- **Operations Handoffs**: Implementation procedures, monitoring configurations, and runbooks
- **Support Training**: Documentation updates, knowledge base articles, and ticket handling processes
- **Legal/Compliance Reviews**: Control validation, evidence collection, and documentation

## Implementing Planning Horizons By Maturity Level

<img src="./assets/icons/garage-duotone.svg" alt="Garage" align="right" width="100px" height="auto" /> 

### Level 1: Startup Foundation
**Target Organization**: Startups and small organizations (5-50 employees)  
**Resources Required**: Founder/CTO time + key team members

Startups need to focus on immediate security needs while maintaining just enough strategic direction. At this stage, planning is typically condensed and pragmatic.

#### Horizon Collapse for Startups

For small organizations, planning horizons often collapse together:

- **Combined Lifetime + Yearly Horizons**
  - Maintain a simple set of security principles and priorities
  - Document basic security strategy on a single page
  - Review and update quarterly

- **Focus on Quarterly Horizon**
  - Maintain a rolling 3-month security roadmap
  - Shape and prioritize work in monthly sessions
  - Track progress through simple dashboard or project board

- **Disciplined Cycle Execution**
  - Run six-week implementation cycles
  - Keep teams focused during cycles
  - Use cool-down for planning and maintenance

#### Cross-Functional Integration for Startups

In small organizations, cross-functional coordination happens organically but benefits from minimal structure:

- **Unified Leadership Team**
  - Leverage regular leadership meetings for cross-functional security decisions
  - Ensure security is a standing agenda item in company all-hands meetings
  - Create visibility by maintaining security work on shared product/engineering boards

- **Simple Boundary Artefacts**
  - Maintain a simple one-page security roadmap visible to everyone
  - Use shared Slack channels or basic project management tools for security tasks
  - Create simple security checklists that product and engineering can self-serve

- **Direct Collaboration**
  - Security-responsible person participates directly in product/engineering meetings
  - Legal/compliance concerns addressed directly with founders
  - Customer-facing teams directly flag security concerns to technical leadership

**Example Boundary Artefact**: The "Security Monday" board - a simple Trello board or Notion page showing:
- This week's security focuses
- Upcoming security needs for product development
- Recent security issues requiring attention
- Links to basic security requirements for everyone

#### Practical Implementation

1. **Quarterly Planning Session (2-3 hours)**
   - Review security principles and strategy
   - Identify 2-3 highest priority security initiatives
   - Shape at least one initiative in detail
   - Allocate resources for the coming 2-3 cycles
   - **Cross-Functional Element**: Include product manager and engineering lead in the session

2. **Monthly Coordination (1 hour)**
   - Review progress on current initiatives
   - Shape upcoming work for next cycle
   - Make betting decisions for next cycle
   - Adjust quarterly plan if necessary
   - **Cross-Functional Element**: Review upcoming product releases for security requirements

3. **Weekly Check-in (30 minutes)**
   - Review progress on cycle work
   - Address any blockers or new security concerns
   - Maintain visibility on security operations
   - **Cross-Functional Element**: Identify any new security needs from customer feedback

#### Lightweight Documentation

- **Security Principles Document** (1 page)
  - Core security approach and principles
  - Key risk tolerance decisions
  - Main architectural boundaries
  - **Cross-Functional Element**: Basic security responsibilities for each team/role

- **Quarterly Security Roadmap** (1 page)
  - Current and upcoming security initiatives
  - Major milestones and dependencies
  - Resource allocation
  - **Cross-Functional Element**: Connection points with product roadmap

- **Cycle Plans** (1 page per cycle)
  - Shaped work for the cycle
  - Team assignments
  - Success criteria
  - **Cross-Functional Element**: Required input or support from other functions

**Example:** A 20-person fintech startup maintains a one-page security strategy focused on data protection and compliance fundamentals. The CTO leads a monthly planning session where they review the 3-month roadmap and shape the next cycle's security work. The current cycle team is implementing a secure authentication system, while the CTO is shaping upcoming work on data encryption. During the weekly check-in, they use a simple Trello board to track progress on the authentication work. The product manager joins these sessions to provide input on user experience considerations, and the customer support lead shares insights from customer feedback.

<img src="./assets/icons/building-office-duotone.svg" alt="Office" align="right" width="100px" height="auto" /> 

### Level 2: Scale-up Enhancement
**Target Organization**: Growing organizations (50-500 employees)  
**Resources Required**: Security lead + department representatives

As organizations grow, planning needs more structure and clearer separation between horizons, while maintaining reasonable agility.

#### Structured Multi-Horizon Planning

- **Distinct Lifetime Horizon**
  - Documented security principles and architecture
  - Formal risk tolerance statements
  - Security strategy with 2-3 year vision

- **Annual Planning Process**
  - Yearly security objectives and initiatives
  - Annual resource planning
  - Alignment with business planning cycle

- **Quarterly Portfolio Management**
  - Structured shaping and betting process
  - Portfolio of security initiatives
  - Regular progress reviews
  
- **Disciplined Cycle Management**
  - Formal kick-off and retrospectives
  - Clear scope documentation
  - Visible progress tracking

#### Cross-Functional Integration for Scale-ups

Growing organizations need more deliberate cross-functional coordination:

- **Security Representatives Model**
  - Assign security champions in key departments
  - Establish regular cross-functional security forum (monthly/bi-weekly)
  - Security lead participates in product/technology governance

- **Structured Boundary Objects**
  - Develop security requirements templates for product/engineering
  - Create security roadmap that shows dependencies on other departments
  - Implement shared risk register with cross-functional ownership

- **Formalized Touchpoints**
  - Security review gates in product development process
  - Regular security briefings for executive leadership
  - Structured security input into technology architecture decisions
  - Coordination with legal/compliance on regulatory requirements

**Example Boundary Object**: The "Security Requirements Matrix" - a structured document showing:
- Security requirements by product/system
- Responsible stakeholders across departments
- Implementation timeline aligned with release schedule
- Status tracking with dependencies highlighted

#### Practical Implementation

1. **Annual Security Planning (1-2 days)**
   - Review and update security principles and strategy
   - Conduct annual risk assessment
   - Define yearly security objectives and initiatives
   - Allocate resources and budget
   - **Cross-Functional Element**: Involve department heads to align with business goals

2. **Quarterly Planning Session (1 day)**
   - Review progress against yearly objectives
   - Update initiative portfolio based on current priorities
   - Conduct shaping sessions for upcoming work
   - Make betting decisions for next 1-2 cycles
   - **Cross-Functional Element**: Synchronize with quarterly product/engineering planning

3. **Bi-weekly Coordination (1 hour)**
   - Review progress on current cycle work
   - Address cross-team dependencies
   - Manage emerging security issues
   - Prepare for upcoming cycles
   - **Cross-Functional Element**: Address blockers requiring cross-team resolution

#### Structured Documentation

- **Security Strategy and Principles** (3-5 pages)
  - Security vision and principles
  - Architectural guidelines
  - Risk tolerance framework
  - Long-term capability roadmap
  - **Cross-Functional Element**: Security responsibility matrix across departments

- **Annual Security Plan** (5-10 pages)
  - Yearly security objectives
  - Major initiatives and resource requirements
  - Success metrics and milestones
  - Quarterly targets
  - **Cross-Functional Element**: Required involvement from other departments

- **Quarterly Portfolio** (1-2 pages per quarter)
  - Current and upcoming security initiatives
  - Shaped pitches for prioritized work
  - Team assignments and expectations
  - Dependencies and integration points
  - **Cross-Functional Element**: Alignment with product/engineering roadmaps

- **Cycle Documentation** (1-2 pages per cycle)
  - Detailed scope definitions
  - Team assignments
  - Progress tracking
  - Retrospective findings
  - **Cross-Functional Element**: Detailed cross-team dependencies and touchpoints

**Example:** A 250-person software company maintains a formal security strategy reviewed annually. Their security director leads quarterly planning sessions where they shape 3-5 security initiatives and decide which ones to implement in the next two cycles. They maintain a security roadmap in Jira with quarterly milestones and cycle-level detail. Each security initiative has a designated owner who reports progress in bi-weekly reviews, using hill charts to show status against unknowns and implementation progress. The company has established a Security Champions program with representatives from engineering, product, legal, and customer success teams who participate in quarterly planning and help coordinate security work across their departments.

<img src="./assets/icons/city-duotone.svg" alt="Buildings" align="right" width="100px" height="auto" /> 

### Level 3: Enterprise Optimization
**Target Organization**: Large organizations (500+ employees)  
**Resources Required**: Security leadership team + governance committees

Enterprise organizations require comprehensive planning across all horizons with formal governance and alignment with broader enterprise architecture and business strategy.

#### Comprehensive Horizon Management

- **Strategic Lifetime Horizon**
  - Enterprise security architecture
  - Formal security strategy and governance
  - Comprehensive risk management framework
  - Long-term security capability model

- **Structured Yearly Horizon**
  - Formal annual planning process
  - Comprehensive security program
  - Strategic resource allocation
  - Business alignment and governance

- **Portfolio-Managed Quarterly Horizon**
  - Security portfolio governance
  - Systematic shaping and betting process
  - Formal progress reviews
  - Cross-enterprise coordination

- **Disciplined Cycle Horizon**
  - Implementation governance
  - Formal scope management
  - Integrated measurement and reporting
  - Systematic learning and improvement

#### Cross-Functional Integration for Enterprises

Enterprise organizations require sophisticated cross-functional governance:

- **Federated Security Model**
  - Dedicated security representatives embedded in key functions
  - Formal security governance committee with cross-functional membership
  - Clear security role definitions across the organization
  - Integration with enterprise-wide governance structures

- **Enterprise Boundary Artefacts**
  - Enterprise security architecture integrated with technology architecture
  - Comprehensive control framework with cross-functional responsibilities
  - Centralized risk management system with distributed ownership
  - Formal security requirements integrated into enterprise systems

- **Governance Integration**
  - Security stage gates integrated with enterprise SDLC
  - Formal security review processes for business initiatives
  - Cross-functional security working groups for major initiatives
  - Executive reporting on security with cross-functional metrics

**Example Boundary Artefact**: The "Enterprise Security Control Framework" - a comprehensive system showing:
- Security controls mapped to business and technical functions
- Implementation owners across the organization
- Audit/compliance evidence requirements
- Maturity measurements and improvement targets
- Integration with enterprise architecture components

#### Practical Implementation

1. **Strategic Security Planning (Annual, 2-4 weeks process)**
   - Review and update enterprise security architecture
   - Align with business strategy and objectives
   - Conduct comprehensive risk assessment
   - Define multi-year security roadmap
   - Secure executive approval and funding
   - **Cross-Functional Element**: Formal input from all major organizational functions

2. **Quarterly Portfolio Governance (2-3 days process)**
   - Review strategic alignment and progress
   - Conduct systematic initiative reviews
   - Shape high-priority initiatives
   - Make formal betting decisions
   - Communicate decisions and expectations
   - **Cross-Functional Element**: Coordination with enterprise portfolio management

3. **Monthly Security Governance (Half-day)**
   - Review implementation progress
   - Address cross-functional dependencies
   - Manage emerging security issues
   - Ensure alignment across security domains
   - **Cross-Functional Element**: Cross-functional security council with rotating membership

4. **Weekly Implementation Coordination (1 hour)**
   - Track cycle progress
   - Address implementation issues
   - Coordinate across security teams
   - Prepare for governance reviews
   - **Cross-Functional Element**: Liaison with cross-functional delivery teams

#### Comprehensive Documentation

- **Enterprise Security Strategy** (10-20 pages plus supporting documents)
  - Security vision and business alignment
  - Enterprise security architecture
  - Comprehensive risk management framework
  - Multi-year capability roadmap
  - Governance model and processes
  - **Cross-Functional Element**: Integration with enterprise operating model

- **Annual Security Program** (20-30 pages)
  - Yearly objectives and success criteria
  - Comprehensive initiative portfolio
  - Detailed resource allocation
  - Measurement framework and targets
  - Integration with enterprise initiatives
  - **Cross-Functional Element**: Detailed RACI across all security domains

- **Quarterly Planning Documentation** (5-10 pages per quarter)
  - Portfolio status and adjustments
  - Shaped initiatives and betting decisions
  - Resource allocation and governance
  - Dependency management
  - Risk and compliance considerations
  - **Cross-Functional Element**: Impact analysis on other organizational functions

- **Cycle Management Documentation** (3-5 pages per cycle)
  - Detailed scope definitions
  - Implementation governance
  - Progress measurement and reporting
  - Risk management and quality assurance
  - Learning and improvement findings
  - **Cross-Functional Element**: Detailed coordination plans with dependent teams

**Example:** A global financial institution maintains a comprehensive security strategy aligned with their enterprise architecture. Their CISO leads an annual planning process resulting in a security program with defined capabilities, initiatives, and resource allocation. A security governance committee meets quarterly to review the portfolio, shape upcoming work, and make formal betting decisions. Each security domain (AppSec, Infrastructure, etc.) has its own implementation teams running coordinated cycles, with progress tracked through a centralized GRC platform and reported through a formal governance structure. The security organization has dedicated staff embedded in product teams, a formal partnership with legal and compliance, and security architects who participate in enterprise architecture governance. Their planning process is fully integrated with corporate strategic planning, IT roadmapping, and product lifecycle governance.

## Connecting the Horizons

Each horizon influences and constrains the horizons below it:

1. **Lifetime principles** guide yearly security initiatives
2. **Yearly initiatives** decompose into quarterly projects
3. **Quarterly projects** get shaped and bet on for cycle implementation

Meanwhile, learning flows upward:

1. **Cycle implementation** generates insights about what works
2. **Quarterly reviews** identify patterns across multiple cycles
3. **Yearly retrospectives** inform adjustments to long-term strategy
4. **Multi-year reflections** may reshape fundamental principles

This bidirectional flow creates a learning system that remains strategically aligned while adapting to real-world experience.

### Cross-Functional Connection Points

The Four Horizons Framework creates natural connection points between security and other organizational functions:

#### Lifetime Horizon Connection Points

- **Business Strategy**: Security principles align with business values and strategy
- **Legal/Regulatory**: Compliance framework integration and long-term risk posture
- **Enterprise Architecture**: Security architecture as component of technology strategy
- **Product Strategy**: Security as an element of product vision and user trust

#### Yearly Horizon Connection Points

- **Annual Budgeting**: Security resource allocation within organizational constraints
- **Compliance Calendar**: Audit schedules and regulatory milestone planning
- **Product Roadmap**: Security capabilities supporting planned product evolution
- **Talent Development**: Security skills development across the organization

#### Quarterly Horizon Connection Points

- **Engineering Planning**: Security requirements in technical planning
- **Product Release Planning**: Security reviews in product lifecycle
- **Marketing/Sales**: Security messaging and customer communication
- **Operational Planning**: Security changes in operational environments

#### Cycle Horizon Connection Points

- **Engineering Execution**: Security implementation in code and infrastructure
- **Quality Assurance**: Security testing and validation
- **Release Management**: Security sign-off and deployment
- **Support/Operations**: Security issue handling and monitoring

### Horizon Alignment By Maturity Level

#### Level 1: Simple Alignment

- **Documentation**: Brief notes on how shaped initiatives support key security priorities
- **Verification**: Informal check with founders/leadership before betting on shaped work
- **Adaptation**: Fast pivots when business or security priorities change
- **Cross-Functional Coordination**: Direct collaboration between security-responsible person and key stakeholders

**Example:** The founder/CTO of a startup maintains a simple security roadmap on a single slide that shows how current cycle work supports quarterly priorities, which in turn align with their key security principles. During monthly planning, they quickly verify that upcoming work still aligns with overall priorities before making betting decisions. The CTO meets weekly with the product lead to ensure security requirements are incorporated into upcoming features, and uses a shared Slack channel for day-to-day coordination.

#### Level 2: Structured Alignment

- **Documentation**: Explicit mapping of shaped initiatives to yearly security objectives
- **Verification**: Review of quarterly shaped work against yearly security roadmap
- **Adaptation**: Quarterly reassessment of security priorities and shaped work pipeline
- **Cross-Functional Coordination**: Security representatives in key planning forums and regular cross-functional security council meetings

**Example:** A mid-sized retail company uses a simple traceability matrix to show how each shaped security initiative supports yearly objectives and longer-term security principles. During quarterly planning, the security director reviews this mapping to ensure alignment before finalizing betting decisions. If business priorities shift significantly, they can adjust the roadmap during the quarterly review. The company has established a monthly cross-functional security forum where representatives from product, engineering, operations, and legal review security initiatives, address dependencies, and coordinate implementation work.

#### Level 3: Governance-Driven Alignment

- **Documentation**: Formal traceability from lifetime principles through yearly capabilities to quarterly initiatives
- **Verification**: Stage-gate reviews to ensure alignment across horizons
- **Adaptation**: Structured change management processes for security roadmap modifications
- **Cross-Functional Coordination**: Formal governance structures with cross-functional representation and dedicated coordination roles

**Example:** A large healthcare organization maintains a formal security strategy hierarchy with clear traceability from enterprise architecture principles through yearly security program objectives to quarterly initiatives and cycle-level implementations. A security governance committee reviews this alignment during quarterly portfolio reviews, and any significant changes to the roadmap require formal assessment and approval. The organization has established a federated security model with dedicated security staff embedded in key business functions, formal security governance committees with representation from all major departments, and security architects who participate in enterprise architecture governance.

## Cross-Functional Planning Challenges

Successful security planning requires effective coordination across organizational functions. Different maturity levels face different cross-functional challenges:

### Communication Challenges

|Challenge|Level 1 Solution|Level 2 Solution|Level 3 Solution|
|---|---|---|---|
|**Security terminology barriers**|Use business language, avoid security jargon|Create shared security glossary for non-security teams|Develop function-specific security communication guides|
|**Missing security requirements**|Direct involvement in product/engineering discussions|Security requirements templates in product process|Automated security requirements in development tools|
|**Resistance to security changes**|Focus on business benefits of security controls|Structured security impact assessment process|Formal change management with executive sponsorship|

### Coordination Challenges

|Challenge|Level 1 Solution|Level 2 Solution|Level 3 Solution|
|---|---|---|---|
|**Competing priorities**|Align security with urgent business needs|Security represented in prioritization forums|Formal security portfolio governance with executive input|
|**Timing misalignment**|Flexible security implementation timing|Synchronized planning calendars|Integrated enterprise planning framework|
|**Responsibility gaps**|Clear but informal security responsibilities|RACI matrix for key security activities|Comprehensive security responsibility framework|

### Function-Specific Planning Challenges

#### Engineering/Product

|Challenge|Level 1 Solution|Level 2 Solution|Level 3 Solution|
|---|---|---|---|
|**Security as afterthought**|Direct involvement in early product discussions|Security requirements in product definition process|Security architects embedded in product teams|
|**Technical debt from security shortcuts**|Track security technical debt items|Dedicate time each cycle to security improvements|Formal security debt management program|
|**Security slowing delivery**|Risk-based security requirements|Pre-approved security patterns for common needs|Security automation integrated with CI/CD|

#### Legal/Compliance

|Challenge|Level 1 Solution|Level 2 Solution|Level 3 Solution|
|---|---|---|---|
|**Compliance deadline surprises**|Simple compliance calendar shared with all|Integrated compliance milestones in roadmap|Enterprise GRC system with automated alerts|
|**Audit evidence gaps**|Designate evidence collection responsibility early|Evidence collection integrated with implementation|Automated compliance monitoring and evidence collection|
|**Vague compliance requirements**|Direct conversations to clarify requirements|Translated compliance requirements in security language|Comprehensive compliance-to-controls mapping framework|

#### Operations/Support

|Challenge|Level 1 Solution|Level 2 Solution|Level 3 Solution|
|---|---|---|---|
|**Security changes breaking production**|Simple testing checklist before deployment|Coordinated change management process|Comprehensive test environment and automated testing|
|**Security alerts overwhelming operations**|Focus on high-value alerts only|Tiered alert handling with clear escalation|Security operations center with advanced analytics|
|**Conflicting maintenance priorities**|Joint prioritization of security vs. operational needs|Dedicated security maintenance windows|Automated security patching with operational validation|

### Effective Cross-Functional Planning Tools

|Tool|Level 1 Implementation|Level 2 Implementation|Level 3 Implementation|
|---|---|---|---|
|**Security Roadmap**|Simple one-page visual roadmap|Departmental roadmap with dependencies|Enterprise security roadmap in portfolio system|
|**Joint Planning Sessions**|Ad hoc participation in each other's planning|Structured cross-functional planning workshops|Formal integrated planning process|
|**Dependency Management**|Simple list of cross-team dependencies|Dependency tracking in project management tool|Enterprise dependency management system|
|**RACI Matrix**|Basic responsibility chart for key security activities|Department-level RACI for security responsibilities|Enterprise-wide security responsibility framework|
|**Security Requirements Library**|Simple checklist of essential requirements|Templates and patterns by application type|Automated security requirements in development tools|

## Horizon-Appropriate Methods

Each horizon requires appropriate tools and methods:

| Horizon          | Key Methods                                  | Artefacts                                     | Cross-Functional Tools                                       | Review Cadence                           |
| ---------------- | -------------------------------------------- | --------------------------------------------- | ------------------------------------------------------------ | ---------------------------------------- |
| **Lifetime**     | Security architecture, Governance frameworks | Principles, Policies, Reference architectures | Enterprise architecture, Business strategy alignment         | Annual with lightweight quarterly checks |
| **Yearly**       | Risk assessment, Capability planning         | Roadmaps, Investment plans, OKRs              | Departmental coordination plans, RACI matrices               | Quarterly                                |
| **Quarterly**    | Shaping, Betting, Portfolio management       | Pitches, Bet records, Project plans           | Cross-functional dependency maps, Joint planning canvases    | Monthly                                  |
| **Cycle/Sprint** | Scope mapping                                | Scope maps, Retrospectives                    | Team-level coordination plans, Shared communication channels | Weekly                                   |

Applying methods designed for one horizon to another horizon leads to ineffectiveness and frustration. Short-horizon tools like task lists don't work for yearly planning; likewise, long-horizon approaches like comprehensive plans and reviews are too heavyweight for cycle work.

### Cross-Functional Planning Methods

Each horizon requires different cross-functional coordination methods appropriate to the planning timeframe:

| Horizon          | Engineering/Product                                                   | Legal/Compliance                                            | Operations/Support                                            |
| ---------------- | --------------------------------------------------------------------- | ----------------------------------------------------------- | ------------------------------------------------------------- |
| **Lifetime**     | Joint architecture reviews, Technology strategy alignment             | Regulatory forecast, Compliance roadmap                     | Operational capability planning, Service delivery model       |
| **Yearly**       | Security requirements in product strategy, Technology risk assessment | Compliance calendar integration, Regulatory assessment      | Operational SLAs, Support model planning                      |
| **Quarterly**    | Security-by-design templates, Architecture review board               | Coordinated audit preparation, Evidence collection planning | Change management coordination, Operational readiness reviews |
| **Cycle/Sprint** | Pair programming, Security code reviews, SAST/DAST integration        | Audit evidence collection, Compliance validation            | Release coordination, On-call readiness                       |

Different functions have different natural planning cycles and methods. Effective security planning requires adapting to these differences while maintaining security integrity:

- **Engineering/Product**: Typically works in product release cycles with agile development methods
- **Legal/Compliance**: Often works around regulatory deadlines and audit schedules
- **Operations/Support**: Balances planned maintenance windows with response to operational issues

### Method Selection By Maturity Level

#### Level 1: Pragmatic Methods

|Horizon|Startup Methods|Cross-Functional Elements|
|---|---|---|
|**Lifetime**|One-page security principles, Simple architectural diagrams|Business goals alignment, Key stakeholder inputs|
|**Yearly**|Lightweight risk assessment, Basic security roadmap|Simple product-security alignment, Key dependency identification|
|**Quarterly**|Simplified shaping, Informal betting process|Direct collaboration with affected teams, Shared planning sessions|
|**Cycle**|Basic scope mapping, Simple progress tracking|Pair programming, Joint stand-ups when needed|

**Example:** A 30-person startup uses a single Notion page to document their security principles, a simple Trello board for quarterly planning, and GitHub issues for tracking cycle work. Their CTO shapes work by sketching on an iPad and sharing screenshots, and betting decisions happen during a monthly leadership meeting. For cross-functional coordination, the technical founder meets weekly with the product lead to review upcoming work, and developers handle security implementations directly within their normal development workflow.

#### Level 2: Structured Methods

| Horizon       | Scale-up Methods                                     | Cross-Functional Elements                                  |
| ------------- | ---------------------------------------------------- | ---------------------------------------------------------- |
| **Lifetime**  | Security strategy document, Architectural standards  | Department input sessions, Cross-functional review process |
| **Yearly**    | Structured risk assessment, Capability-based roadmap | Roadmap alignment workshops, Security champions program    |
| **Quarterly** | Formal shaping process, Documented betting decisions | Cross-functional planning forums, Dependency mapping       |
| **Cycle**     | Structured progress tracking and retrospectives      | Joint implementation teams, Coordinated testing            |

**Example:** A 200-person company maintains their security strategy in Confluence, uses Jira for roadmap planning and initiative tracking, and runs a structured quarterly planning process with formal shaping and betting documentation. They track cycle progress using charts and conduct structured retrospectives at the end of each cycle. For cross-functional coordination, they've established a Security Champions program with representatives from each department who participate in planning and help coordinate implementation, monthly cross-functional security meetings to address dependencies, and security requirements templates integrated into the product development process.

#### Level 3: Comprehensive Methods

|Horizon|Enterprise Methods|Cross-Functional Elements|
|---|---|---|
|**Lifetime**|Enterprise security architecture, Governance framework|Executive steering committee, Business unit security councils|
|**Yearly**|Comprehensive risk management, Program management|Integrated planning process, Function-specific security plans|
|**Quarterly**|Portfolio management, Investment governance|Cross-functional delivery coordination, Impact assessment process|
|**Cycle**|Project governance, Integrated measurement|Embedded security specialists, Automated coordination workflows|

**Example:** A global enterprise uses a GRC platform for comprehensive security management, integrated with enterprise architecture tools and portfolio management systems. They maintain formal documentation of security architecture and strategy, conduct structured planning processes at each horizon, and implement formal governance reviews according to a published schedule. For cross-functional coordination, they maintain a federated security model with dedicated security staff embedded in business units, formal security governance bodies with representation from all major functions, regular cross-functional working sessions for major initiatives, and automated security requirements integrated into enterprise delivery processes.

## Cross-Functional Boundary Artefacts for Security Planning

Effective cross-functional security coordination requires shared artefacts that create alignment across organizational boundaries. These boundary objects should evolve with organizational maturity:

### Level 1: Essential Boundary Objects for Startups

1. **One-page Security Roadmap**
   - Simple visual representation of security priorities
   - Visible connection points with product development
   - Key milestones and responsibilities
   - Shared in common workspace visible to all teams

2. **Basic Security Requirements Checklist**
   - Simple list of must-have security requirements
   - Clear, jargon-free language for non-security people
   - Examples and templates where possible
   - Easily accessible in product/engineering tools

3. **Security Blocker Tracking**
   - Visible tracking of security issues blocking progress
   - Clear ownership and next steps
   - Simple escalation process
   - Integrated with existing team communication channels

### Level 2: Structured Boundary Artefacts for Scale-ups

1. **Security-Product Alignment Matrix**
   - Maps security initiatives to product roadmap items
   - Shows dependencies and timing requirements
   - Identifies resource needs and constraints
   - Used in cross-functional planning sessions

2. **Security Requirements Framework**
   - Structured security requirements by development phase
   - Templates and examples for implementation
   - Verification and validation criteria
   - Integrated with product development process

3. **Cross-functional Security Dashboard**
   - Status of security initiatives across teams
   - Dependencies and blocking issues
   - Resource allocation and utilization
   - Key metrics visible to all stakeholders

### Level 3: Sophisticated Boundary Artefacts for Enterprises

1. **Enterprise Security Architecture**
   - Component of enterprise architecture
   - Maps security controls to business capabilities
   - Shows interfaces between security and business systems
   - Maintained through formal governance process

2. **Integrated Control Framework**
   - Comprehensive security controls with clear ownership
   - Mapping to regulatory/compliance requirements
   - Implementation responsibilities across functions
   - Evidence collection and verification processes

3. **Cross-Functional Security Operating Model**
   - Detailed security roles and responsibilities across functions
   - Decision rights and escalation paths
   - Service level agreements between teams
   - Performance metrics for security activities

<!-- ## Tools and Resources

**Boundary Artefacts:**

- Security Roadmap Canvas (all levels)
- Cross-Functional Planning Matrix (Level 2-3)
- Horizon Alignment Tracker (Level 2-3)

**Templates:**

- Simple Quarterly Planning Agenda (Level 1)
- Cross-Functional Security Council Charter (Level 2)
- Enterprise Planning Integration Framework (Level 3)

**Automation Recipes:**

- AI Prompt for Security Initiative Summaries
- Dependency Visualization Workflow
- Cross-Functional Meeting Preparation Assistant

**Training Materials**

- Security in Development
- Data Retention -->