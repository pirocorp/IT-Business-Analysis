# Use Cases

A **Use Case** is a methodology used in system analysis to **identify, clarify, and organize system requirements**. 

The **Use Case** comprises a set of possible sequences of **interactions between systems and users in a particular environment and related to a specific goal**.

## Use Case Diagram

Components of Use Case Diagram

**System**

A rectangle is used to depict the system boundary, indicating the scope of the system. Anything within the box represents functionality in scope, and anything outside the box does not.

**Actor**

Stick figures are used to represent an actor. An actor is a **person**, **organization**, or **external system** that plays a role in one or more interactions with your system.

**Use Case**

A use case is drawn as an oval. It is the **behavior/process** that the **system offers to the actors** to help meet the actors' goals.

**Association**

**Solid lines** indicate associations **between actors and use cases** in use case diagrams.

**Dependency**

Dependencies are dotted/dashed arrows that represent the **relationship between actors and use case**
- **include** - common behaviour
- **extend** - optional behaviour

![image](https://github.com/pirocorp/IT-Business-Analysis/assets/34960418/4aa3d2c6-a4a6-4884-8855-2adb89541b89)


## Why is Use Case Modelling important?

- Functional requirements need to be captured. Use case modeling enables a **standardized and systematic approach**
- Defines the **system boundaries**
- Encourages dialogue between **client and system designers**
- Enables verification of **coverage, accuracy, and sufficiency of detail**


### Example

What activities can occur at a restaurant with a bar?

![image](https://github.com/pirocorp/IT-Business-Analysis/assets/34960418/599bd9bb-2b22-48bc-bd23-630f65057d88)

Note that we don't have such actors as **Chef** or **Waiter**. They are not external roles but are part of the business we are modeling (the Restaurant). Thus, they are not actors.

**Extends**: Used to present **alternative** flows. Indicates additional releases of a use case.

![image](https://github.com/pirocorp/IT-Business-Analysis/assets/34960418/09bf697e-99fb-44b7-ac8b-86ba034b1f5f)

**Includes**: Representation of **common behavior**. Indicates use cases that are a necessary part of the interaction.

![image](https://github.com/pirocorp/IT-Business-Analysis/assets/34960418/6a6258c3-bab7-457e-8865-f5782e22160e)

Description of a Use Case:

**Use Case**: Eating dinner
**Goal**: Satisfy hunger and have a nice time

**Sequence**:
1. The guest enters the restaurant
2. The guest is shown the table
3. Sits at the table and studies the menu
4. Places order
5. The waiter informs the kitchen
6. Cook prepares food
7. Food is served
8. Guest eats food
9. Use the **Payment** use case
10. Guest leaves

**Alternatives**:
- At **1**, if the restaurant is full, guest waits at the bar
- At **4**, if the dish is not available, the guest chooses another one
- At **8**, the sequence can be extended by the **Flowers and Champagne Proposal** use case

### Description of Use Case Template

![image](https://github.com/pirocorp/IT-Business-Analysis/assets/34960418/c356afc8-b0cd-4eec-a0eb-8fadfe52c15c)







