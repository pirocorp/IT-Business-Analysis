# Software Development Life Cycle

Development Processes and Software Development Methodologies

![image](https://github.com/pirocorp/IT-Business-Analysis/assets/34960418/b76986e7-9403-4658-99aa-167b2c41c64b)

![image](https://github.com/pirocorp/IT-Business-Analysis/assets/34960418/88621eda-676a-47c6-996f-03aba35b4012)

## Stages and Processes

Software development processes can be divided into tasks that can be **assigned, completed, and measured** following the **Software Development Lifecycle (SDLC)** - a cost-effective and time-efficient methodology consisting of six stages

![image](https://github.com/pirocorp/IT-Business-Analysis/assets/34960418/9e1fd9c2-850f-41ac-a4c6-7928c82fbed6)


# SDLC Methodologies

## Spiral Methodology

In the **Spiral Model**, the software development process is represented as a spiral, with **each loop** of the spiral representing a **phase in the development lifecycle**. It is Risk Driven as it provides **support for Risk Handling**. 

 - Combination of **linear and iterative**
 - Focuses heavily on **Risk Assessment**
 - Minimized risk by breaking a project into **smaller segments**
 - Each cycle **begins** with **identifying stakeholders and what success looks like**
 - Each cycle **ends** with **a review and a commitment**

### Pros and Cons

| Advantages                                                    | Disadvantages                                                                    |
|---------------------------------------------------------------|----------------------------------------------------------------------------------|
| Accurately manages and mitigates risks                        | Long time to get to finished product                                             |
| Issues are identified and solved early                        | High cost and Long Time                                                          |
| Estimates near the end of the project are very accurate       | The success of the Spiral Model relies heavily on accurate risk analysis         |
| Early involvement from developers increases successful design | Very customized solution limits reusability                                      |
| Supports the development of prototypes early in the process.  | More complex to manage compared to linear methodologies like the Waterfall Model |

### When to Use?

- Risk identification and mitigation are extremely important 
- Medium to High-risk projects
- Users are unsure of their needs
- Prototypes are needed
- Requirements are complex
- Time and cost are not as important
- Little to no experience in project’s area


## DevOps Methodology

**DevOps** is a set of practices, principles, and cultural philosophies that aim to **improve collaboration, communication**, and **integration** between **development (Dev)** and **IT operations (Ops)** teams in the software development and deployment process.

- Automates repetitive tasks, such as build, testing, deployment, and monitoring
- Streamlines the development and delivery process
- Emphasizes Continuous Integration and Continuous Delivery (CI/CD)
- Continuous monitoring and feedback of applications and infrastructure

### Pros and Cons

| Advantages                                                                                      | Disadvantages                                                                                                         |
|-------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| Enables rapid and frequent software releases                                                    | May require significant initial effort, especially in organizations with traditional development and operations silos |
| Fosters better communication and collaboration between development, operations, and other teams | Could increase complexity in the development pipeline                                                                 |
| Automation reduces the risk of human errors, making deployments more reliable and consistent    | Maintaining and updating automation scripts and tools                                                                 |
| Enables organizations to scale their software development and deployment processes efficiently  | Cultural shift                                                                                                        |

### When to Use?
- If the organization needs to release software updates or new features frequently
- When you have multiple teams working on a project, such as development, testing, operations, and security
- DevOps complements cloud-based architectures and microservices
- If the development process involves many repetitive tasks
- Enables organizations to scale their software development and deployment processes efficiently


## Prototyping Methodology

The **Prototyping** model is a software development method in which a **prototype is built, tested and then reworked** as necessary until an acceptable outcome is achieved from which the **complete system or product can be developed**.

- Iterative progression
- Used in conjunction with Spiral, Rapid Application Development (RAD), and Incremental models
- Breaks project into segments and creates small-scale mock-ups of the system, called prototypes
- Prototypes are iterated until they meet the requirementsFinal prototype usually discarded
- Business user is involved in the full process

| Advantages                                             | Disadvantages                                                     |
|--------------------------------------------------------|-------------------------------------------------------------------|
| Gives business users a visual of their wants and needs | Very loose approval and control process                           |
| Promotes user participation and communication          | Non-functional requirements are tough to identify                 |
| Allows progress even when unclear requirements         | Can lead to poorly designed systems                               |
| Encourages innovation                                  | False expectations thinking the system is complete from prototype |


## Waterfall Methodology

The Waterfall Methodology is a **sequential development process** that flows like a waterfall through all phases of a project, with **each phase completely wrapping up before the next phase begins**.

- Linear progression
- "Traditional" model
- Next phase begins once the previous phase is complete
- Each phase begins with previous phase's output
- No process to go back to the previous phase
- Fully planned, including time schedule and budget
- Extensive written documentation and formal approval process

### Steps

- Requirements - Conduct Analysis of Business Needs and state of the Business Organization as a whole.Identify key Stakeholders for the particular project.Elicit and document Requirements for project.
- Design - Create a higher-level or logical design that outlines the purpose, scope, and integration points of the project.Transform the logical design into a physical design using specific hardware and software technologies.Define the layouts, data models, and traffic flow of each component of the software solution.
- Development - Code the applications based on project requirements and specifications.Conduct testing and debugging during the implementation phase.Collaborate with the design team to address any necessary design changes or refinements.
- Testing - Develop test cases based on design documents, personas, and user case scenarios.Execute various testing methodologies, such as functional testing, integration testing, and performance testing.Identify and document any defects or issues discovered during testing and work with the development team to resolve them.
- Deployment - Deploy software into production environmentRelease the software to the market or customers.
- Maintenance - Assign a dedicated team to handle maintenance tasks, including bug fixes, updates, and enhancements.Address change requests from users and release new versions of the software to ensure ongoing usability and satisfaction.

### Waterfall Pros and Cons

| Advantages                                                                     | Disadvantages                                                    |
|--------------------------------------------------------------------------------|------------------------------------------------------------------|
| Clear expectations on schedule, budget, and resourcing needs                   | Inflexible and cumbersome                                        |
| Extensive documentation helps ensure quality, reliability, and maintainability | Long pole from project start to something tangible               |
| Progress is easily measured                                                    | Problems are discovered at user testing                          |
|                                                                                | Written documentation is never kept up-to-date, loses usefulness |
|                                                                                | Promotes gap between the business users and the development team |
  

### When to Use Waterfall?

- Clear objectives and solution
- Large, complicated, and expensive
- No pressure for immediate return on investment (ROI) from implementation
- Project team is fully knowledgeable about the solution application
- Requirements are stable and will be unchanged through development
- Resource constraints
- Strict requirement for formal approvals at milestones


## Agile Methodology

**Agile** methodology is a project management framework that breaks projects down into **several dynamic phases**, commonly known as **sprints**. The Agile framework is an **iterative methodology**.

![image](https://github.com/pirocorp/IT-Business-Analysis/assets/34960418/01f0d8cf-c84d-49dc-b4d8-203363418420)

- Uses iterative approach called Sprints
- Flexible and adaptable, great for the unknown
- Values individuals and interactions over processes and tools
- Values working software over comprehensive documentation
- Values customer collaboration over contract negotiation
- Values responding to change over following a plan

**Note**: Nearly 95% of the time the BA and Product Owner is one person in Scrum.


### Agile Scum Ceremonies

**Sprint Planning**: At the beginning of each sprint, the team collaboratively selects a subset of items from the product backlog to work on during that sprint. They plan how to complete these items and define the sprint goal.

**Daily Stand-ups**: Short daily 10-15 minutes meetings are held, where team members share updates on what they accomplished the previous day, what they plan to do that day, and any impediments they are facing.

**Sprint Review**: At the end of each sprint, the team demonstrates the completed work to stakeholders and receives feedback. This meeting helps the team gather insights and make improvements.

**Sprint Retrospective**: Following the sprint review, the team holds a retrospective to evaluate their performance during the sprint. They identify what went well, what could be improved, and action items to enhance their processes.

![image](https://github.com/pirocorp/IT-Business-Analysis/assets/34960418/151a02c6-5c81-4bff-bfa9-47586ab25138)


### Agile Scrum Artifacts

**Agile Scrum Artifacts** are information that a scrum team and stakeholders use to detail the **product being developed, actions to produce it, and the actions performed during the project**.

#### Product Backlog

The **Product Backlog** is a **list of new features, enhancements, bug fixes, tasks, or work requirements** needed to build a product. It’s compiled from input sources like customer support, competitor analysis, market demands, and general business analysis. 

- Prioritized list of items
- Dynamic and Evolving
- User-Centric


#### Sprint Backlog

The **Sprint Backlog** is a **set of product backlog tasks** that have been **promoted to be developed during the next product increment**.

They are created by selecting a task from the product backlog and **breaking that task into smaller, actionable sprint items**.


### Agile Scrum Pros and Cons

| Advantages                                                                       | Disadvantages                                                           |
|----------------------------------------------------------------------------------|-------------------------------------------------------------------------|
| Flexible and adaptable to changing requirements                                  | Leads to scope creep due to no defined end date                         |
| Gets workable product in-front of the business stakeholders quicker              | Relies on commitment of all team members                                |
| Promotes collaboration between business and development teams                    | Challenging to initially adopt and train in an organization             |
| Daily feedback on progress and roadblocks which prevent from completion of tasks | Changing or leaving team members can have a drastically negative effect |


### When to Use Agile Scrum?

- The project is unpredictable and will have changing requirements
- Using or creating leading edge technology
- Organization as an experienced Scrum Master
- Business has experienced resource that can dedicate time to the project 
- Pressure to produce a tangible product quickly
- Little to no concerns on length of project or budget
- Development team doesn’t have resource constraints


