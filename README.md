# Requirement Analysis in Software Development

## Introduction

Welcome to the Requirement Analysis in Software Development repository. This space is dedicated to outlining, detailing, and illustrating the key processes and outputs that take place during the Requirement Analysis stage of the Software Development Lifecycle (SDLC).

For demonstration purposes, we’ll be using a Booking Management System (modeled after Airbnb) as a case study to showcase how requirement analysis is applied in a real-world context.

## What is Requirement Analysis?

Requirement Analysis is a critical phase in the Software Development Lifecycle (SDLC) that involves identifying, gathering, analyzing, and documenting the needs and expectations of stakeholders for a proposed software system. The primary objective is to clearly understand what the software must do, how it should perform, and any constraints it must operate within. This phase lays the foundation for all subsequent stages of development.

## Why is Requirement Analysis Important?

There are a few reasons why Requirement Analysis is an important part of the SDLC:

  1.	Foundation for Development
Requirement analysis provides a clear understanding of the project scope, reducing ambiguity and setting realistic expectations for all stakeholders.
  2.	Reduces Cost and Rework
Detecting and correcting errors at the requirement stage is far cheaper than fixing them during or after implementation.
  3.	Improves Communication
A well-documented requirement specification enhances communication between business stakeholders and the technical team.
  4.	Guides Design and Testing
Requirements serve as a blueprint for system design and a benchmark for testing the final product to ensure it meets user expectations.
	5.	Helps in Project Planning
Clear requirements help project managers in estimating time, cost, and resources accurately.

## Key Activities in Requirement Analysis


1. Requirement Gathering

This is the initial step where raw information about the desired system is collected from various stakeholders, such as clients, users, and business managers. The goal is to understand their needs, expectations, and the problem the software intends to solve.

2. Requirement Elicitation

In this stage, the gathered information is explored more deeply through techniques like interviews, questionnaires, brainstorming, observations, and workshops. The aim is to draw out detailed and accurate requirements, even those stakeholders might not explicitly state.

3. Requirement Documentation

Once requirements are well understood, they are organized and formally written down, typically in a Software Requirement Specification (SRS) document. This serves as a clear, structured reference for developers, testers, and stakeholders throughout the project.

4. Requirement Analysis and Modeling

This activity involves critically examining the documented requirements to ensure clarity, completeness, feasibility, and consistency. Modeling tools like use case diagrams, data flow diagrams (DFDs), or entity-relationship diagrams (ERDs) may be used to visually represent system behavior and data.

5. Requirement Validation

Finally, the documented and analyzed requirements are reviewed and verified with stakeholders to confirm that they accurately represent what the system should do. This step helps catch misunderstandings or errors before development begins, reducing costly changes later.

## Types of Requirements

### ✅ Functional Requirements

Functional requirements define what the system should do—the specific features, actions, or tasks it must perform to meet user needs.

Examples for the Booking Management System:
	•	Users must be able to search for hotels based on location, date, and price range.
	•	The system should allow hotel managers to update room availability and pricing through a dedicated portal.
	•	Customers should be able to make bookings and receive instant confirmation.
	•	The system must integrate with third-party payment gateways to process transactions securely.
	•	The platform must send real-time notifications to hotel managers upon successful bookings.
	•	Users should be able to view and cancel past or upcoming bookings.

### ⚙️ Non-functional Requirements

Non-functional requirements define how the system performs certain functions. These include performance, scalability, usability, and security expectations.

Examples for the Booking Management System:
	•	The system should handle high concurrent user traffic efficiently using microservice architecture.
	•	API response times should be less than 2 seconds for search and booking operations.
	•	The application must be highly available and fault-tolerant, even under heavy load.
	•	All user data must be secured through encryption and secure authentication mechanisms.
	•	The system should support data replication and database sharding for better performance.
	•	Booking history and logs must be archived and retrievable for at least 1 year using scalable storage like Cassandra and Hadoop.
