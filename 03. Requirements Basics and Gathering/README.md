# Requirements Basics and Gathering

## What is the Requirement in an IT Project?

Barry Boehm (1981) defines requirements as "designing the right thing."

- List of **WHAT** the Stakeholders need
- List of **WHAT** the System/App must do to Satisfy those needs
- List of **WHAT** components must be built/developed
- List of **WHAT** each component must **DO** and **HOW** they will **INTERACT**

![image](https://github.com/pirocorp/IT-Business-Analysis/assets/34960418/fbce52ff-09e4-4706-a7dc-adf7926bada9)

### The Weight of Ambiguous Requirements

In 1995, from 8000 projects reviewed, 50% of failures were due to requirements. In 2015, 68% of IT projects failed due to ambiguous requirements.

### The Traditional Project Process

```mermaid
flowchart LR
    id1("Stakeholders") --> id2("Requirements (Business Analyst)") --> id3("Specifications") --> id4("Design Sign-off")
    id4 -- "Requirement Discovery" --> id1
```

### What Do Requirements Focus On?

- What the system must do?
- What properties must the system have?
- What information is involved?
- What degree of quality is expected?
- What constraints apply to the system?
- Who and how the system should be used?

### Categories of Requirements

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

