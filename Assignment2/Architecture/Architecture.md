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

![image](https://github.com/SWENGG4Y2024/SWENGG4Y2024Team05/assets/161967498/b2fa1c9f-3db0-401f-91ab-ff9910ce6512)


## Explanation:

- Users can register, log in, book rides, track them, pay, rate drivers/passengers, view ride history, and manage profiles.
- Drivers have additional functionalities like accepting ride requests and rating passengers. 
- Admins monitor rides, manage payments, resolve issues, and verify drivers. Support staff resolve user issues.
- External services include Payment Gateway for processing payments, Map Service for routing, and Notifications for sending notifications. Interactions show how users and functionalities interact and utilize external services.


## Level 2: Container diagram

Level 2, a container diagram, zooms into the software system, and shows the containers (applications, data stores, microservices, etc.) that make up that software system. Technology decisions are also a key part of this diagram.

### Purpose: To show the high-level shape of the software architecture and how responsibilities are distributed across it.
### Elements: Illustrates the major containers within the system (e.g., applications, databases, microservices) and their interactions.
### Audience: Technical people inside and outside the development team, such as software architects and developers.

![image](https://github.com/SWENGG4Y2024/SWENGG4Y2024Team05/assets/161967498/6920601a-386a-490a-b39c-e89be451ba25)

## Explanation:

The architecture is divided into several key components: MobileApp, Services, Database, and External Services. Here’s a detailed explanation of each component:

### 1. MobileApp Component
This component represents the user interfaces of the TezYatra application. It is divided into two parts:

#### Passenger Mobile App: 
This is the application interface used by passengers to book rides, make payments, view ride history, and more.
#### Driver Mobile App:
This is the application interface used by drivers to accept ride requests, navigate to passenger locations, track earnings, and manage their profile.

### 2. Services Component
This component represents the backend services that support the functionalities of the TezYatra application. Each service handles a specific aspect of the application's operations:

#### User Service:
Manages user authentication, profile information, and user-related data.
#### Ride Service:
Handles ride requests, matching passengers with drivers, ride status updates, and ride history.
#### Payment Service: 
Manages payment processing, fare calculation, and transaction history.
#### Notification Service: 
Handles sending notifications to users and drivers, such as ride confirmations, updates, and alerts.
#### Map Service:
Provides map-related functionalities, such as route calculation, ETA estimations, and location tracking.
#### Rating Service: 
Manages ratings and reviews from passengers and drivers, helping maintain service quality.
#### Support Service:
Provides customer support features, handling user inquiries, and resolving issues.
### 3. Database Component
This component represents the various databases used to store data for the TezYatra application. Each database is dedicated to a specific type of data:

#### User Database: 
Stores user information, including profiles, authentication details, and preferences.
#### Ride Database: 
Stores details about rides, including ride requests, ongoing rides, ride history, and status updates.
#### Payment Database: 
Stores payment-related data, including transaction records, fare details, and payment methods.
#### Notification Database: 
Stores notification logs and preferences.
#### Rating Database: 
Stores ratings and reviews given by users and drivers.
#### Support Database: 
Stores customer support tickets, inquiries, and resolution details.
### 4. External Services Component
This component includes external services that the TezYatra application relies on to function correctly:

#### Payment Gateway:
An external service that handles payment processing, ensuring secure transactions between users and the TezYatra application.
#### Map Service: 
An external mapping service (such as Google Maps or Mapbox) that provides geolocation, routing, and mapping functionalities.


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
