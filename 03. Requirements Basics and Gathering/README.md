# Requirements Basics and Gathering

## What is the Requirement in an IT Project?

Barry Boehm (1981) defines requirements as "designing the right thing."

- List of **WHAT** the Stakeholders need
- List of **WHAT** the System/App must do to Satisfy those needs
- List of **WHAT** components must be built/developed
- List of **WHAT** each component must **DO** and **HOW** they will **INTERACT**

### The Weight of Ambiguous Requirements

![image](https://github.com/pirocorp/IT-Business-Analysis/assets/34960418/fbce52ff-09e4-4706-a7dc-adf7926bada9)

### The Traditional Project Process

```mermaid
flowchart LR
    id1("Stakeholders") --> id2("Requirements (Business Analyst)") --> id3("Specifications") --> id4("Design Sign-off")
    id4 -. "Requirement Discovery" .-> id1
```

### What Do Requirements Focus On?

- What the system must do?
- What properties must the system have?
- What information is involved?
- What degree of quality is expected?
- What constraints apply to the system?
- Who and how the system should be used?

### Categories of Requirements

| Functional                                                                              	| Non-Functional                                                    	|
|-----------------------------------------------------------------------------------------	|-------------------------------------------------------------------	|
| Describe **What** the product does                                                        | Describe **How** the product works                                    |
| Define Product **Features**                                                               | Define Product **Properties**                                         |
| Focus on **User Requirements**                                                            | Focus on **User Expectations**                                        |
| Captured in **Use Case**                                                                  | Captured as **Quality Attribute**                                     |
| Mandatory                                                                               	| Not Mandatory, but Desirable                                     	    |
| Usually defined by **User**                                                               | Usually defined by **Developers or other tech experts**              	|
| Component, API, UI, etc.                                                                	| Performance, Usability, Security, etc.                            	|
| External Interface,<br>Authentication,<br>Authorization Levels,<br>Business Rules, etc. 	| Usability, <br>Reliability,<br>Scalability, <br>Performance, etc. 	|

```mermaid
flowchart LR
    id1("Functional Requirements") --> id2("System/Product")
    id3("Non-Functional Requirements") --> id2
```

#### Functional Requirements

| Things the product must do                               	| Action the product must take                                      	|
|----------------------------------------------------------	|-------------------------------------------------------------------	|
| Scope of the Product                                     	| Functional and Data Requirements                                  	|
| Defines the boundaries and connections to other products 	| Things the product must do and data manipulated by the functions. 	|

#### Non-Functional

| Properties or qualities the product must have 	| How the product will behave                  	|
|-----------------------------------------------	|----------------------------------------------	|
| Look and Feel Requirements                    	| Usability Requirements                       	|
| Performance Requirements                      	| Operational Requirements                     	|
| Legal Requirements                            	| Security Requirements                        	|
| Cultural and Political Requirements           	| Maintainability and Portability Requirements 	|

#### Product Constraints

| Purpose of the Project                                   	| Users of the Product                                      	|
|----------------------------------------------------------	|-----------------------------------------------------------	|
| Reason for building the product                          	| People who interact with the product                      	|
| Intended end-users and how they affect product usability 	| Limitations of the project and restrictions on design     	|
| Naming Conventions and Definitions                       	| Outside influences that make a difference to this product 	|
| Assumptions developers are making                        	| Assumptions developers are making                         	|

## SMART Technique for Requirements Structure

- **S**pecific
- **M**easurable
- **A**ttainable
- **R**easonable
- **T**raceable

### Specific

Evident, no ambiguity. Consistent, same terminology throughout. Simple.

Questions to Ask:

- What?
- Why?
- Who?
- Where?

Guidelines:

- Avoid “some,” “several,” “many”
- State pronouns clearly: “A calls B. It is updated.”
- Specify units all with numbers
- Use pictures to clarify understanding
- Provide explanations for terms like “transmitted,” “sent,” “downloaded,” and “processed.”

### Measurable

Measure progress towards the goal. Indicators should be quantifiable.

Questions to Ask:

- How much?
- How many?
- How can I know when it is accomplished?

Guidelines:

- Ensure measurable during requirement elicitation.
- Validate unequivocal success can be proven with that requirement.
- Determine tests that must be used to verify the requirement was met.

### Attainable

Validate requirement is feasible within the technical expertise, project scope, and budget.

Questions to Ask:

- Is there a theoretical solution to the problem?
- Has it been done before?
- Are there any known constraints (environmental, physical, etc.)?

Guidelines:

- Determine who has responsibility for satisfying the requirement and validate they can deliver.
- Ensure sufficient time, resources, and budget.
- Reuse pieces from previous projects.

### Reasonable

Validate the effort is worth the requirement.

Questions to Ask:

- Do you think this is worthwhile?
- Is the timing right?
- Do you think this matches our other efforts/needs?

Guidelines: 

- Run all requirements through a 'sanity check'.
- Make sure the requirement makes sense in the context of the project.

### Traceable

Trace requirements through design, implementation, and testing.

Questions to Ask:

- Can I ensure this requirement has been met in the design solution?
- Can I make sure this requirement has been met in the implementation?
- Can I ensure this requirement has been met during testing?

Guidelines

- Requirements should include
- Originators
- Assumptions
- Business justifications
- Dependencies on other requirements
- Importance

### Tips for Producing Valid Requirements

- Use the word **shall**
- Only one **shall** per requirement
- Written in short, simple sentences
- Consistent terminology
- Stated positively
- Accompanied by notes and comments to support and clarify
- Stated imperatively
- Don't use **will** and **should**

### Phases of the Requirements Process

```mermaid
flowchart LR
    id1("Requirement Elicitation") --> id2("Requirement Analysis") --> id3("Requirement Specification") --> id4("Requirements Approval")
```

## How to Elicit Requirements from Stakeholders?

- Brainstorming
- Observation
- Interview
- Survey
- Documentation Review


### Brainstorming

Brainstorming is a creative technique for developing new ideas and solving problems.

Brainstorming Types

- Individual - Project team member creates a list of ideas.
- Open - Participants call out ideas that are captured by the scribe.
- Structured - Participants write down their ideas, and the Facilitator goes from participant to participant to have them share one idea each. Continue until all ideas are exhausted.

| Advantages                                                                                                                                           	| Disadvantages                                                                                                                	|
|------------------------------------------------------------------------------------------------------------------------------------------------------	|------------------------------------------------------------------------------------------------------------------------------	|
| Helps to explore different possibilities and uncover new requirements.                                                                               	| Dominant participants overshadowing others or group think, where conformity hinders the exploration of diverse perspectives. 	|
| Rapid generation of many ideas, fostering creativity and innovation.                                                                    	| Ideas are not discussed/explored.                                                                                            	|
| Involves multiple perspectives and different project contexts.                                                                                       	| True meaning may need to be clarified or understood.                                                                              	|
| Promotes equal participation as it engages team members and stakeholders, making them feel involved in the requirement elicitation process. 	| Time constraints may result in rushed discussions, leading to superficial or incomplete requirement generation.              	|


### Observation

**Observation Studies** involve watching users interact with a system, process, or product in their natural environment.

Observation Types

- Direct - Provides firsthand insights into user behaviors, workflows, and challenges, leading to accurate requirement capture.
- Contextual Inquiry - Combines observation with interviews, where the analyst observes users in their work environment and engages in conversations to gather additional insights.
- Remote - Observing users or stakeholders remotely using video conferencing or screen-sharing technology.


### Interviews

Systematic discussion to drive out accurate requirements quickly.

Interview Types

- Structured - Follows a predefined set of questions or topics, ensuring consistency across interviews and enabling easier comparison of responses.
- Semi-Structured - Combination of predefined questions and the flexibility to explore additional topics or follow up on exciting points raised during the conversation.
- Group Interviews - Involves interviewing multiple stakeholders or users simultaneously, fostering discussion, and capturing diverse perspectives within a group setting.

| Advantages                                                                                   	| Disadvantages                                                                                                         	|
|----------------------------------------------------------------------------------------------	|-----------------------------------------------------------------------------------------------------------------------	|
| Promote interactive discussions to explore detailed information                              	| Require access and commitment of stakeholders                                                                         	|
| Identify conflicts or discrepancies about stated needs or requirements                       	| Creation of scripted interview questions can be time-consuming                                                        	|
| Encourage participation and build relationships by establishing rapport with the stakeholders 	| Stakeholders need help describing their future needs, so they usually focus on what they do currently. |
| Enable observations of nonverbal behavior                                                    	| Resulting documentation is subject to interpretation of the interviewer                                               	|
| Allow immediate follow-up to ensure understanding                                            	| Transcription and analysis of interview data can be complex and expensive                                             	|

### Survey

A **Survey** is a **systematic and structured data collection** method to gather information, opinions, preferences, and feedback from **various stakeholders** related to a software development project.

Survey Types

- Open-Ended Questions - Allows respondents to answer in their own words. Practical but very time-consuming to interpret and catalog.
- Closed-Ended Questions - A finite set of answers for each question. Lends itself to statistical analysis. Tough to create questions that are not leading or need an "Other" response.

| Advantages                                                                         	| Disadvantages                                                                  	|
|------------------------------------------------------------------------------------	|--------------------------------------------------------------------------------	|
| Require limited stakeholder's time                                                 	| Relatively low response rate                                                   	|
| Effective at reaching geographically dispersed stakeholders                        	| Poorly worded questions may provide inaccurate information                     	|
| Scalable for large audiences                                                       	| Use of open-ended questions requires more analysis by the business analyst 	|
| Relatively fast and inexpensive to administer                                      	| Require both instrument training and problem or business domain experience     	|
| Supplement more subjective information, such as opinions gained through interviews 	| Incentives for responding might be expensive                                   	|


### Documentation Review

Reviewing **existing documentation** that could include **User Guides, Prior system implementation documentation, Technical documentation, etc.**

| Advantages                                                             	| Disadvantages                                                    	|
|------------------------------------------------------------------------	|------------------------------------------------------------------	|
| Current process documentation provides a great starting point          	| Existing documentation may be old and outdated                   	|
| The documentation authors could potentially be key stakeholders.   | Most of the time, some documents need additional technical input. |
| Identifies gaps from previous projects' implementation                 	| It can be time-consuming and may not provide the desired payback 	|

