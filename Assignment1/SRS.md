# Software Requirement Specification

## Table of Contents
-  [1. Introduction](#1-introduction)
   - [1.1 Purpose](#11-purpose)
   - [1.2 Intended Audience](#12-intended-audience)
   - [1.3 Intended Use](#13-intended-use)
   - [1.4 Scope](#14-scope)
   - [1.5 Overview](#15-overview)
- [2. Description](#2-description)
   -  [2.1 Product Perspective](#21-product-perspective)
   -  [2.2 Product Features](#22-product-features)
   -  [2.3 User Classes and Characteristics](#23-user-classes-and-characteristics)
   -  [2.4 Operating Environment](#24-operating-environment)
   -  [2.5 Design and Implementation Constraints](#25-design-and-implementation-constraints)
   -  [2.6 Assumptions & Dependencies](#26-assumptions--dependencies)
-  [3. Specific Requirements](#3-specific-requirements)
   -  [3.1 Functional Requirements](#31-functional-requirements)
   -  [3.2 Non – Functional Requirements](#32-non-–-functional-requirements)
   -  [3.3 Performance Requirements](#33-performance-requirements)
-  [4. Interface Requirements](#4-interface-requirements)
-  [5. Conclusion](#5-conclusion)


## 1. Introduction
   - ### 1.1 Purpose
     The purpose of this Software Requirements Specification (SRS) document is to detail the functional and non-functional requirements for Project Tez Yatra. The document provides a comprehensive guide for the development and implementation of the Tez Yatra ride-booking platform, ensuring all stakeholders have a clear understanding of the system's capabilities and limitations.

   -  ### 1.2 Intended Audience

      - #### Passengers
        These are the people who will be using the carpool service to find rides or offer rides to others. They may be commuters, travelers, or people looking to save money on transportation costs.

      
      - #### Drivers
        These are the individuals who will be providing rides to others. They may be private car owners or professional drivers working for a carpool service provider.

      
      - #### Tez Yatra Service Providers
        These are the companies or organizations that provide carpool services to users. They may be ride-sharing companies, transportation network companies, or public transportation agencies.
        
      
      - #### Testers
        To create test cases and ensure the system meets the specified requirements.
        

      - #### Developers
        To develop and gain detailed knowledge of the system requirements and functionalities.
        

      - #### Project Managers:
        To understand the project scope and manage resources.


       - #### Stakeholders:
        To provide a clear overview of the project and its intended outcomes.

      
      - #### Regulatary Authorities
        These are the government agencies responsible for regulating and overseeing carpool services. They may be transportation departments, public utilities commissions, or other regulatory bodies.
      
  - ### 1.3 Intended Use
    The primary purpose of a Tez Yatra is to help users find and offer rides to others. Users can search for available rides based on their origin, destination, and preferred time of travel. They can also offer rides to others by specifying their route, time, and car capacity.

  - ### 1.4 Scope 
    The scope of a carpool project is to develop a software application that connects drivers with passengers who are traveling in the same direction. The Tez Yatra allows users to find and offer rides to others, split the cost of travel expenses, and reduce the number of single-occupancy vehicles on the road. Users can schedule their ride for future in advance. The software can be used by commuters, travelers, or people looking to save money on transportation costs

  - ### 1.5 Overview
    The rest of the document contains overall description of the system which 
    includes interface properties, product functions and dependencies. In addition, it 
    contains system specific requirements which composed of functional and non-functional requirements.
 
    Moreover, there will be data and description models of the system and these models are specified with diagrams such as use cases. And 
    finally at the end of the document, there is conclusion part which explains the 
    overall description about the system. SRS is organized according to the table of 
    content.

## 2. Description

   - ### 2.1 Product Perspective
        Designing and developing a platform that enables carpooling among individuals traveling to similar destinations.
     The Tez Yatra allows users to find and offer rides to others, split the cost of travel expenses, and reduce the number of single-occupancy vehicles on the road. Users can schedule their ride for future in advance. The software can be used by commuters, travelers, or people looking to save money on transportation costs.Also it would be helpful to reduce traffic congestion, decrease carbon emissions, and provide an affordable transportation option for commuters.

   - ### 2.2 Product Features

     - #### User Registration : 
       Users can create an account with their personal details like name, email, and phone number.

     - #### Ride Creation :
       Users can create rides by entering details such as the start and end location, date, time, and number of available seats in their car.

     - #### Ride Search :
       Users can search for available rides based on their location, destination, and preferred travel time.

     - #### Ride Booking :
       Users can book a ride by selecting the desired ride from the available options and making a payment for the booking.

     - #### Payment Integration :
       The platform can integrate with payment gateways to enable users to make payments for booking rides.

     - #### Driver Verification :
       The platform can verify the identity and driving license of the users who create rides to ensure the safety of other users.

     - #### User Ratings :
       Users can rate and review each other after the completion of the ride, which helps to build a trustworthy and reliable community.

     - #### Notifications :
       The platform can send notifications to users regarding the status of their ride bookings, any updates or changes to the rides, and other relevant information.

     - #### Route Optimization :
       The platform can optimize the routes for the rides using GPS to ensure that users reach their destinations as quickly and efficiently as possible.

     - #### Cost Sharing :
       The platform can calculate the cost of the ride and distribute it among the users who are sharing the ride.

     - #### Messaging :
       Users can communicate with each other through the platform to coordinate the ride details and ask any questions they may have.

      - #### History and Analytics :
        The platform can maintain a record of past rides, user ratings, and other data that can be used for analysis and insights.

      - #### Schedule for future :
        users can simply request a cab well in advance and have it at your doorstep, as planned.

   - ### 2.3 User Classes and Characteristics

     - #### Commuters : 
       These are people who commute to work or school regularly. They are likely to be interested in a carpool project as it can provide them with a cost-effective and convenient way to travel. Commuters may have a fixed schedule and prefer to plan their rides in advance.

     - #### Car Owners : 
       These are users who own a car and are willing to share their ride with others. They may be interested in the carpool project to save money on fuel and reduce their carbon footprint. Car owners are likely to be responsible and trustworthy, as they will be driving other users.

     - #### Non-Car Owners : 
       These are users who do not own a car and are looking for a convenient way to travel. They may be interested in the carpool project as it can provide them with a reliable and affordable way to reach their destination. Non-car owners may be flexible with their schedule and prefer to book rides on short notice.

     - #### Environmentally Conscious Users : 
       These are users who are concerned about the environment and are looking for ways to reduce their carbon footprint. They may be interested in the carpool project as it can help them to reduce their emissions by sharing rides with others.

     - #### Students : 
       These are users who are students and may be interested in the carpool project to save money on transportation. They may have a flexible schedule and prefer to book rides on short notice. Students may also be interested in meeting new people and socializing during their rides.

     - #### Senior Citizens : 
       These are users who are senior citizens and may be interested in the carpool project to reduce their travel costs. They may prefer to travel during off-peak hours and may have special requirements such as assistance with getting in and out of the car.

   - ### 2.4 Operating Environment
     Windows 7, Windows 8, Windows 8.1, Windows 10, Mac OS X, Linux,Smart TV’s, Smart Phones, Tablets (Android or IOS) etc.

   - ### 2.5 Design and Implementation Constraints
     The design and implementation constraints that may need to be considered are Data Privacy, Scalability, User Interface and Experience, Driver Verification, Availability of Internet, Regulation and Legal Compliance.

   - ### 2.6 Assumptions & Dependencies

     - #### Assumptions:

       - Users will be willing to share their rides with others to reduce transportation costs and contribute to environmental sustainability.
       - There will be a sufficient number of users in the area interested in using the carpool service.
       - Users will have access to a mobile device and internet connection to use the carpool platform.
       - Drivers will be willing to offer their rides to other users and will be responsible and reliable.
       - Users will provide accurate and complete information during the registration process.
       - Users will comply with the rules and regulations of the carpool service, including the terms of service and the cancellation policy.
       - The carpool platform will be able to effectively match users with compatible rides based on their preferences and needs.

     - #### Dependencies:

       - The availability of mapping services and GPS technologies to accurately locate and track rides.
       - The availability of secure and reliable payment gateways to process payments for rides.
       - The availability of relevant legal and regulatory frameworks, including insurance and liability policies, to ensure the safety and legality of the carpool service.
       - The availability of a reliable and secure hosting platform and infrastructure to support the carpool service.
       - The availability of skilled developers and IT professionals to design and maintain the carpool platform.
       - The availability of marketing and promotional strategies to attract and retain users for the carpool service.
       - The availability of transportation options for users who cannot find a suitable carpool ride, such as public transportation or ride-hailing services.

## 3. Specific Requirements

- ### 3.1 Functional Requirements 

  - #### User Registration and Profile Creation : 
    Users should be able to create a profile on the carpool platform and provide personal information such as name, email address, phone number, and payment details.

  - #### Rides Creation : 
    Users should be able to create rides by providing details such as the starting point, destination, departure time, and number of available seats.

  - #### Ride Matching : 
    The carpool platform should be able to match riders with compatible rides based on their location, preferences, and other factors.

  - #### Ride Booking : 
    Users should be able to book a ride and pay for it using a secure and reliable payment gateway.

  - #### Communication : 
    Users should be able to communicate with each other through the carpool platform to coordinate the details of the ride and ensure a smooth and safe travel experience.

  - #### Rating and Feedback : 
    Users should be able to rate and provide feedback on the drivers and riders to help improve the quality and safety of the carpool service and vice versa.

  - #### Ride Cancellation : 
    Users should be able to cancel a ride if necessary, but with a reasonable cancellation policy to avoid inconveniencing other users.

  - #### Reporting : 
    The carpool platform should have a reporting system to track the number of rides, users, payments, and other relevant metrics.

  - #### Driver Verification : 
    The carpool platform should verify the identity and driving license of the users who create rides to ensure the safety and security of other users.

  - #### Navigation and GPS : 
    The carpool platform should integrate with mapping services and GPS technologies to accurately locate and track rides.

- ### 3.2 Non – Functional Requirements

  - #### Performance : 
    The carpool platform should be able to handle a large number of users and rides simultaneously without any significant delays or system crashes.

  - #### Scalability : 
    The platform should be designed to scale easily to accommodate a growing number of users and rides over time.

  - #### Availability : 
    The platform should be available 24/7 with minimal downtime for maintenance and updates.

  - #### Security : 
    The carpool platform should be designed with strong security measures to protect user data and payment information from unauthorized access, hacking, or data breaches.

  - #### Reliability : 
    The platform should be reliable and provide a consistent user experience without any unexpected errors or bugs.

  - #### Usability : 
    The carpool platform should be user-friendly and easy to navigate for users of all ages and technical abilities.

  - #### Compatibility : 
    The platform should be compatible with different devices and operating systems, including smartphones, tablets, and desktop computers.

  - #### Accessibility : 
    The platform should be designed to be accessible to users with disabilities, such as those who are visually or hearing impaired.

  - #### Compliance : 
    The platform should comply with all relevant legal and regulatory requirements, such as data protection laws and consumer protection regulations.

  - #### Performance Monitoring : 
    The platform should be equipped with monitoring tools to track system performance, user behavior, and other metrics to continuously improve the quality of the service.

- ### 3.3 Performance Requirements
  - #### Response Time : 
    The carpool platform should respond to user requests within a reasonable amount of time, preferably under a few seconds, to ensure a smooth and seamless user experience.

  - #### Capacity : 
    The platform should be able to handle a large number of users and rides simultaneously without any significant performance degradation.

  - #### Concurrent Users : 
    The platform should be able to support a high number of concurrent users accessing the service at the same time.

  - #### Throughput : 
    The platform should be able to process a high number of ride requests and transactions per second, depending on the expected volume of traffic.

  - #### Latency : 
    The platform should have low latency, meaning that there should be minimal delays between the time a user initiates a request and when the platform responds.

  - #### Load Balancing : 
    The platform should use load balancing techniques to distribute traffic evenly across multiple servers or data centers to avoid overloading any single server.

  - #### Fault Tolerance : 
    The platform should be designed to handle errors and failures gracefully, such as by automatically switching to a backup server or database if one fails.

  - #### Disaster Recovery : 
    The platform should have a disaster recovery plan in place to recover data and resume operations in the event of a catastrophic event or outage.

  - #### Data Integrity : 
    The platform should ensure the integrity of user data, such as preventing data loss or corruption, through the use of backup and recovery processes.

  - #### Performance Monitoring : 
    The platform should be equipped with monitoring tools to track system performance, user behavior, and other metrics to continuously improve the quality of the service.

## 4. Interface Requirements

- ### 4.1 User Interface : 
   The Tez Yatra should have a user-friendly interface that allows users to easily find and offer rides. The interface should include search and booking functionality, as well as options to set preferences for ride times, pickup and drop-off locations, and payment methods.

- ### 4.2 Driver Interface : 
   Drivers should have a separate interface that allows them to manage their ride schedules, view passenger information, and track their earnings.

- ### 4.3 Mobile Compatibility : 
   The Tez Yatra should be compatible with mobile devices, including smartphones and tablets. This will allow users to easily access the software on the go and find rides when they need them.

- ### 4.4 Accessibility : 
   The Tez Yatra should be designed to be accessible to users with disabilities. This may include features such as screen reader compatibility, high-contrast displays, and keyboard shortcuts.

- ### 4.5 Security and Privacy : 
   The Tez Yatra should have a secure interface that protects user information and prevents unauthorized access. This may include features such as encryption, two-factor authentication, and user verification processes.

- ### 4.6 Customizability : 
   The Tez Yatra should have a customizable interface that allows users to set their own preferences and personalize their experience. This may include features such as custom search filters, saved ride preferences, and personalized notifications.

## 5. Conclusion
  In this document, the functional and other requirements of the system are described. Furthermore, the needs of the user are stated through the document. However, all requirements are not defined and some of the requirements needs to be clarified in this document.

  To sum up, this document is the primary document which upon all of the subsequent design, implementation, test and validation processes will be based.
