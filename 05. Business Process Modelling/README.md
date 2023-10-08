# Business Process Modelling

## Business Process

A Business Process is an **activity or set of activities** that accomplish a **specific organizational goal**. Business Processes should have **purposeful plans**, be **as detailed as possible**, and **produce consistent outcomes**.

![image](https://github.com/pirocorp/IT-Business-Analysis/assets/34960418/b2419b63-bae5-486f-b818-b7872f23d095)

Visual Modelling - Graphical representation using a modeling language that takes something complex and makes it easier to understand.

 - Easily understand complex information
 - Gets all stakeholders involved
 - Receive requirements efficiently
 - Identify the underlying problem
 - Analyze what-if scenarios
 - Allows removal of irrelevant information

## Business Process Model and Notation

Business Process Model and Notation is a graphical representation/mapping for specifying business processes in a business process model.

![image](https://github.com/pirocorp/IT-Business-Analysis/assets/34960418/c058ea3b-c316-4a79-a4b2-073b501f7013)

The primary goal was to develop a notation capable of mapping business processes that would be readily understandable **by all business users**, from the **business analysts** who create the initial draft of the processes to the **technical developers** responsible for implementing the technology that will perform the processes, and finally to the **business people** who will manage and monitor those processes.

- Standardization
- Process Visualization
- Save time by **eliminating unnecessary tasks**
- Process Analysis and Improvement
- Get a **clear vision** of exactly how everything in your business works
- Collaboration and Documentation
- Reduce the rate at which your employees **forget, overlook, or wrongly execute work**

![image](https://github.com/pirocorp/IT-Business-Analysis/assets/34960418/7199fe3a-f1d1-4fb6-beae-ac8559805489)

![image](https://github.com/pirocorp/IT-Business-Analysis/assets/34960418/c6a59fcc-4325-4ed2-a241-21d4d58f7fbf)

### BPMN Swimlanes

**Pools** represent **different organizations or entirely separate processes**.

**Lanes** represent **different teams or individuals** within the same organization.

![image](https://github.com/pirocorp/IT-Business-Analysis/assets/34960418/7e74370d-910b-4d9f-b058-c6501f12708a)

Example: If we were to map a **Customer Support process**, there would be one pool representing **the Business** and one representing **the Customer**.


### Flow Objects - Activities

An Activity is a work performed within a business process.

![image](https://github.com/pirocorp/IT-Business-Analysis/assets/34960418/98ee94d1-4d1b-409f-8c94-25f8415cdffd)


### Flow Objects – Events

An **Event** is a trigger that **starts**, **modifies**, or **completes** a process.

![image](https://github.com/pirocorp/IT-Business-Analysis/assets/34960418/b93a2561-3279-40a9-8163-f1b135a5437e)


### Flow Objects – Gateways

A **Gateway** acts as a **decision point** that decides which (outgoing) decision to take based on **evaluating the situation**.

![image](https://github.com/pirocorp/IT-Business-Analysis/assets/34960418/1fba311d-a949-4221-a0f8-78212ca96193)


### Flow Objects – Gateways Exclusive 

Sometimes, a process can go only one of two (or any number of ways) ways. For example, either you approve and order or reject an order. Both tasks cannot happen.

![image](https://github.com/pirocorp/IT-Business-Analysis/assets/34960418/10bbba62-6b4e-4c66-b6bc-92406cab4aac)


### Flow Objects – Gateways Parallel

If a task isn’t dependent on another job, there is no reason for it not to be done in parallel (simultaneously) when the process begins.

![image](https://github.com/pirocorp/IT-Business-Analysis/assets/34960418/4bc03602-99ae-43e8-a922-1777e8cfa642)


### Flow Objects – Gateways Inclusive

An **Inclusive Gateway** breaks the process into multiple branches, explaining which condition must be met for the flow to continue down the branch. Allows for multiple possible outcomes to be selected.

![image](https://github.com/pirocorp/IT-Business-Analysis/assets/34960418/9e7c5656-be57-43c9-9e0d-332d5d4455cc)


### Flow Objects – Gateways Event-Based

Unlike previous gateways that process a decision based on information received, this gateway decides based on which event takes place next.

![image](https://github.com/pirocorp/IT-Business-Analysis/assets/34960418/e68813be-3504-4e8b-b22a-830c3376d193)


### Connectors

**Sequence Flow**: used to show a process's order (sequence) of flow objects (activities, events, and gateways). ![image](https://github.com/pirocorp/IT-Business-Analysis/assets/34960418/35ed8640-67e6-44dd-9ac0-0ab23dac1540)

**Message Flow**: used to show the flow of communication between two participants or entities (e.g., an organization and its suppliers - separate pools). ![image](https://github.com/pirocorp/IT-Business-Analysis/assets/34960418/0a88db22-3c39-4649-bc4c-507f9f815b1e)

**Association**: used to link artifacts (data and other information) with other diagram objects, including flow objects (activities, events, and gateways). ![image](https://github.com/pirocorp/IT-Business-Analysis/assets/34960418/1035b2bb-fe2f-44cf-acca-df51b959d9c2)









