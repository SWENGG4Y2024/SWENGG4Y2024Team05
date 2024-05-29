# C4 Model

C4 is a modeling and documentation language developed to express architecture in a powerful way. The C4 model consists of Context, Container, Component and Code level diagrams. In the C4 Model, each level represents a different level of abstraction and it is possible to zoom from the highest abstraction to more detailed one. Thus, you can communicate with stakeholders at different technical levels through different diagrams.

## Level 1: System context diagram
Level 1, a system context diagram, shows the software system you are building and how it fits into the world in terms of the people who use it and the other software systems it interacts with.

### Purpose: 
To provide a high-level overview of the system and its interactions with external entities.
### Elements:
Shows the system in scope, external users (actors), and other systems that interact with it.
### Audience: 
Non-technical stakeholders, such as project sponsors and business analysts.

![image](https://github.com/SWENGG4Y2024/SWENGG4Y2024Team05/assets/161967498/370f2a41-697a-4f33-ac01-ffd7b0d93dd1)

Explanation:

## Level 2: Container diagram

Level 2, a container diagram, zooms into the software system, and shows the containers (applications, data stores, microservices, etc.) that make up that software system. Technology decisions are also a key part of this diagram.

### Purpose: To show the high-level shape of the software architecture and how responsibilities are distributed across it.
### Elements: Illustrates the major containers within the system (e.g., applications, databases, microservices) and their interactions.
### Audience: Technical people inside and outside the development team, such as software architects and developers.

![image](https://github.com/SWENGG4Y2024/SWENGG4Y2024Team05/assets/161967498/6920601a-386a-490a-b39c-e89be451ba25)

Explanation:


## Level 3: Component diagram

Level 3, a component diagram, zooms into an individual container to show the components inside it. These components should map to real abstractions (e.g., a grouping of code) in your codebase.

### Purpose: To decompose each container into its constituent components and show the relationships between them.
### Elements: Depicts components within a container, their responsibilities, and their interactions.
### Audience: Developers and architects who need to understand and work on a specific part of the system.

## Level 4: Code

Provides detailed information about how each component is implemented.

### Purpose: To provide a detailed view of the implementation, usually at the class or code level.
### Elements: Shows the internal structure of components, often using UML class diagrams.
### Audience: Developers who are implementing the system and need to understand the detailed design.
