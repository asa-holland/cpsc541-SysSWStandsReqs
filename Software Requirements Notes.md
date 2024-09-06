Various studies suggest that errors introduced during requirements activities account for 40 to 50 percent of all defects found in a software product.


Inadequate user input and shortcomings in specifying
and managing
customer requirements are major contributors to unsuccessful projects


COTS - commercial off the shelf


Key words in software requirements domain

"Requirement" - a specification of what should be implemented. They are descriptiosn of how theo system should behave, or of a system property or attribute. They mayb e a constarint on the development process of athe system.

Define "requirements" up front so all project stakeholders share same notin.

Software requirements include a time dimension - present tesne - descriing the current system's capbalities.
Or near term - high priority.

Business Reqruiement - high level busines objective of the organiztion that builds a product or of a customer who procures it.

Business rule - a policy, guideline, standard or regulation that defines or constrains some aspect of the business. Not a software requirement in itself, but the origin of several types of software requirements.
Constraint - a restriction that is imposed on the choices available to the developer for the design and construction of a product.
External interface requirement - connection between a software system and a user, another software system, or a hardware device.
Feature - one or more logically related system capabilities that provide value ot a user and are described by a set of functional requirements

Functional requirement  - a description o a behavior that a system will have under specific conditions
    - "The Passenger shall be able to print boarding passes for all flight segments for which he has checked in."
Non-functional requirements - a description of a property or characteristic that a system must exhibit or a constraint that it must respect
Quality attribute - kind of nonfunctional requirement that describes a service or performance characteristics of a product
System Requirement - a top level requirement for a product that contains multiple subsystems, which could be all software or software and hardware
User requirement - a goal or task that specific user classes must be able to perform with a system or a desired product attribute.

Vision and Scope Document
    - contains Business Requirements

User Requirements Document contains
    - User Requirements (user stories)

Software Requirements Specification (SRS) contains:
- External Interfaces
- Quality Attributes
- Constraints
- Functional Requirements



There is a distinction shown by "Feature Tree"
- branches point to Features
- leaves point to User Requirements
- Notes refer to Functional Requirements

Business Need via Manager results in Business Requirements
Market Need via Marketing results in Business Requirements

Business Analyst or Product Mamager lead to User Requiremets

BA or Product Manager lead to Functional Requirements

Developer and Tester take these


Product Reqquirements - properties of a softear esystem to be built (housed in SRS). should not include design or implementtion details (constraints), project plans, test palns or otehr

Project Requirements -
    - Physical resources needed of team
    - staff training
    - user documentaion - training materials, refernce manuals and release notes
    - support documentation
    - infrastructure changes needed in the operating environment
    - requirements and procedures for release
    - data migration procedures
    - product certification and compliance requirements
    - revised policies and documents
    - sourcing , acquisiing and licensin of third part soafte
    - beta tesing, distionuon
    - cutomer sercie level agreements
    - legal proetctions

The Solution = Product Requirements + Project Requirements

Requirements Engineering = Requirements Development + Requirements Management

Requirements Development = Elicitation + Analysis + Specification + Validation

Eliciation = interviews, workshops, document analysis, prototyping and others

- identofying the product's expected user classes and other stakeholders
- understanding user tasks and goals and business objectives with which those tasks align
- learning about environment in which a new product will be used
- qorking with individals who represen each usr class to understand functioality needs

Usage-Centric = emphasize understanding and exporing user goals to derive necessary system functionality.


Requirements Development

Analysis - understand and represent requirements
- Analyzing information recieve form users to disntiguh task goals from functional requirements, wuality expectations, business rules, suggestion solutions na other
- - decompsng high level requirements ino an appropraite level of detail
- deriving functional requirements from other requirements informaion
- understanig the relative imporatnce of quality attributes
- allocating reqruiemetns to software components defined in system architecture
- negotiaiong implementation priorities
- ideniftying gaps in requirements or unnessary requirements as they relate to the deifines cope

Specification
- representing and storing the collected requiremetns knowledge in a persistent and wel organief dashion
- translating collected user needs into written requirements and diagesm suitable for compreshension, review and use by their intended audiences

Validation -  confirms you have correct set of requirements inof to build solution that satisfies business objecitves
- review documented requiremtn to correct any problesm before the development group accepts them
- developing acceptnace tests and criterai to confirm that a product based on the requiremtns would need customer needs and acheive the business objectives



Requirements Management -
- defining requirements baseline - snapshow of approved functionalnonfunctional rqruiements, for a specific release
- evaluating the impact of proposed rquiements changes and incorpatoins
- updating project palsn as reqruiemnets evolve
- negiaitoning new commitnments based on impact
- definie relationships and dpendenceis taht exist between requiremtns
- tracing indeivial requiremnt to eir corresponind desins, source code and tests
- tracking requiremt status and change aciity hotughout the project

Hard Part is Determining the Requirements
- writing requiremetns is matter of clariying reocreding
-


Requirements-Related Problems that can Arise

- minimize Rework
- rework consuems 30 to 50 percent of total development cost
- requirements errors can account for 70 to 85 percent of reqork cost

- Insufficient User involvmenet - misunderstood busines sporielm
- Inaccurate Plannig - Do NOT anser When will the project be done?
- Creeping User requirements
- Ambigous requireements
- Gold Plating - trace EVERY bit of functionality back to origin and business justification
- Overlooked Stakeholders

Benefits from High Quality Requirements Process
- develop new procedures
- create document templates
- train the team
- buy tools

potential payoff is
- fewer defects in requirements and in the delivered product
- reduced development rework
- faster development and delivery
- fewer unnessary and unused features
- lower enhancement costs
- fewer miscommuncations
- reduced scope creep
- reduced project choas
- hiher customer and team member satifaction
- productat that do what theyre supposed t od o



## Requirements from the Customer's Perspective

Great Quote About Requirements

Key - get people involved who will USE the system, not just

"On-Site Customer Representative" aka "Product Owner" to work closely

Three Key "Requirements"
- Business - system idea
- User - user request
- Functional - Jira ticket

The Expectation Gap - the gulf between what cutomers really need and what developers deliver based on what they heard about at the beginning

best way to minimize the expectation gap is to arrange frequent contact porints with suitable customer representatives

Stakeholder - person, group or org actively invovled in a project. Is affected by process or outcome, or can influcence process or outcome.
 Customer - subset of Stakeholders that either derives direct or indeirect benefit from a product

End Users - subset of customers - will either operate the software, or receive output

- tasks they need to perform with the product
- the outputs they need
- quality characteristics the product is expected to have

Use the Org chart to search for all stakeholders that will be affected by new system

Business Reqruieets shold come from the person who is accountable for the business value of the project
- User requirements should come from USERS (press keys, receive outputs)


### The Customer-Development Partnership
Well-exectuted design based on excellent requirements


#### Requirements Bill of Rights for Softwware Customers
##### You have the right to
1. Expect BAs to speak your language (business language - provide a glossary, no technical jargon)
2. Exepect BAs to learn about your business and your objectives
3. Expect BAs to record requirements in an appropriate form
4. Receive explanations of requirements practices and deliverables
5. Change your requirements
6. Expect an environment of mutual respect
7. Hear ideas and alternatives for your requirements and for their solution
8. Describe characteresitcs that will make the product easy to use
9. Hear about ways to adjust requirements to accelertat development through re-use
10. Receive a system that meets your functional needs and quality expectations

#### You have the responsibility to
1. Educate BAs and developers about your business
2. Dedicate the time that it takes to provide and clarify requirements
3. Be specific and precise when providing input about requirements
4. Make timely devisions about reqruiremts when asked
5. Respect a developer's assessment of the cost and feasibilit of requirements
6. Set realistic requirement priorities in collaboration with developers
7. Review requiremets and evaluate prototypes
8. Establish acceptance criteria
9. Promptly communicate changes to requirements
10. Respect the requirements development process

Requirements need to written and organized in a way uour understand.


Find specific examples to demonstrate the impact - use appropraite metrics (dollars, time, lost business opprountieis)

Show Development Managers how poor requirements slow down design adn lead to excessive and expensive course corrections

Have Develoeprs review requirements as they evolve
Involve QA in requirements review EARLY ON


#### Identifying decision makers
need one singular Decision Leader and HOW a decision will ne ade. Change control board is the decision maker.

Requirements NEED a sign off - and need to know what this means
SIgnOff is a Milestone with clear shared understanding of the activiteis that lead to sign off nad implications


#### Establishing the requirements baseline
- I agree that this set of requirements erpresnets our best understainf on hre requireets for then ext portion of this project and the solution described will meet out needs as we understand them today. I agree to make future changes in this baseline thourhg the projects defined change process. I realize that changes might require us to renegotiatio cost, resource and schedule commitments.

### BA Should put requirements under Change Control

### If someone does not sign off, assume they don't approve
Document that they did not sign off, and that Impact assesmsnet


Agile does NOT include fomral sign-off. USER STORIES in Product Backlog.


#### page 41