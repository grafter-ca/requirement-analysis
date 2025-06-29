# Requirement Analysis in Software Development

## 📌 Introduction

This repository explores the **Requirement Analysis** phase of the Software Development Life Cycle (SDLC). It covers:

- The importance of gathering and prioritizing software requirements.
- Examples of functional and non-functional requirements.
- Real-world use cases and diagrams (use cases, flowcharts, etc.).
- Common tools and techniques used in the industry.

The purpose of this repository is to serve as a learning and reference resource for software developers, analysts, and engineering students who want to understand better the role of clear, structured requirements in building successful software systems.

## 🧠 What is Requirement Analysis?

**Requirement Analysis** is a crucial phase in the Software Development Life Cycle (SDLC) where the goals, functions, and constraints of a software system are identified, documented, and analyzed. It involves gathering requirements from stakeholders (clients, users, project managers, etc.) to define **what** the software should do and **how** it should behave.

### 📌 Key Components:
- **Functional Requirements**: These describe the specific features and behaviors the software must support (e.g., login system, search feature).
- **Non-Functional Requirements**: These cover performance metrics, security, usability, and scalability.
- **Stakeholder Requirements**: High-level needs from users, customers, or business owners.
- **System Requirements**: Detailed technical specifications to implement the desired system.

### 🚀 Importance in SDLC:
1. **Defines Clear Scope**: Helps avoid ambiguity by establishing a mutual understanding between developers and stakeholders.
2. **Reduces Risk of Failure**: Ensures that the product being built matches user expectations and business goals.
3. **Prevents Scope Creep**: By documenting and prioritizing requirements early, teams can avoid costly mid-project changes.
4. **Improves Planning**: Accurate requirements enable more effective estimation of costs, resources, and timelines.
5. **Foundation for Design & Testing**: All further SDLC phases (design, implementation, testing) rely heavily on well-documented requirements.

### 🔍 Techniques Used:
- Interviews and Surveys
- Use Case Diagrams
- User Stories and Personas
- Prototyping
- Brainstorming Workshops


Requirement Analysis is not just about collecting information — it's about asking the right questions, validating needs, and ensuring alignment across technical and non-technical stakeholders.

## ❗ Why is Requirement Analysis Important?

Requirement Analysis is one of the most critical stages in the Software Development Life Cycle (SDLC). It sets the foundation for the entire development process by clearly defining what the software is expected to do.

Here are three key reasons why Requirement Analysis is essential:

### 1.  Ensures Project Success

A well-executed requirement analysis process ensures that developers understand exactly what the client or end-user needs. This alignment minimizes the chances of building the wrong product and increases overall customer satisfaction.

### 2.  Saves Time and Cost

Identifying and clarifying requirements early in the project lifecycle helps avoid costly rework and delays. It reduces ambiguity, miscommunication, and unnecessary changes during development, which helps projects stay on time and within budget.

### 3.  Provides a Solid Foundation for Design & Testing

Requirements act as a blueprint for both software design and quality assurance. Developers use them to create architecture and UI/UX flows, while testers use them to define test cases and validation criteria. Without clear requirements, both the design and testing phases become unreliable.


In short, Requirement Analysis is not just a step—it's the **backbone** of software development that bridges stakeholder expectations and technical execution.


## 📋 Key Activities in Requirement Analysis

Requirement Analysis is a multi-step process that involves several structured activities to ensure the software product meets stakeholder expectations. Below are the five key activities involved:

- ** Requirement Gathering**
  - Collect raw information about the user's needs and expectations.
  - Involves interaction with stakeholders through interviews, surveys, and observation.
  - Focuses on identifying business problems and opportunities.

- ** Requirement Elicitation**
  - Refines and expands the gathered data to uncover the underlying requirements.
  - Uses techniques like brainstorming, use case creation, prototyping, and workshops.
  - Aims to clarify ambiguous or incomplete information.

- ** Requirement Documentation**
  - Converts elicited requirements into formal documents such as:
    - Software Requirements Specification (SRS)
    - Use Case Descriptions
    - User Stories
  - Ensures requirements are recorded clearly and consistently for all stakeholders.

- ** Requirement Analysis and Modeling**
  - Involves examining requirements for feasibility, consistency, and completeness.
  - Uses models like:
    - Use Case Diagrams
    - Data Flow Diagrams (DFD)
    - Entity-Relationship Diagrams (ERD)
  - Helps identify gaps, redundancies, and conflicts.

- ** Requirement Validation**
  - Reviews and verifies requirements with stakeholders.
  - Ensures that documented requirements accurately reflect user needs.
  - Prevents misunderstandings before the development process begins.


Each of these activities plays a critical role in delivering a solution that is functional, usable, and aligned with stakeholder goals.


## 📂 Types of Requirements

Software requirements are generally classified into two main categories: **Functional Requirements** and **Non-functional Requirements**. Both are crucial to delivering a complete and usable system.

### ✅ Functional Requirements

Functional requirements define **what** the system should do. They describe the core features and interactions users will have with the application.

#### Definition:
These are specifications of **behaviors, tasks, and features** the system must support.

#### Examples for Hotel Booking App:
- Users can **search for available rooms** by location, date, and preferences.
- Hosts can **create, edit, and delete** room listings.
- Guests can **book rooms** and receive confirmation via email.
- Users must **log in or register** before making a booking.
- The system should allow **payment processing** via credit card or digital wallet.
- Admin can **manage bookings**, suspend accounts, or generate reports.

---

### ⚙️ Non-functional Requirements

Non-functional requirements define **how** the system performs. They focus on **performance, usability, security**, and other quality attributes.

#### Definition:
These describe **constraints or qualities** the system must meet to ensure a smooth user experience and operational efficiency.

#### Examples for Hotel Booking App:
- The website should **load within 2 seconds** on standard internet connections.
- The system must be able to **handle up to 10,000 concurrent users** during peak hours.
- User passwords must be **stored using secure encryption**, and **multi-factor authentication** should be enabled.
- The app should have **99.9% uptime availability**.
- The system should **support multiple languages** for international users.
- Bookings should be processed in **real-time** with no delays in confirmation.



Both types of requirements are essential. Functional requirements ensure the **right features are built**, while non-functional requirements ensure the **system behaves reliably and efficiently** under real-world conditions.


## 🧾 Use Case Diagrams

### What Are Use Case Diagrams?

A **Use Case Diagram** is a visual tool in Requirement Analysis used to represent the interactions between **users (actors)** and the **system (use cases)**. It helps stakeholders quickly understand:
- What the system does (functional overview)
- Who interacts with it
- How each user’s goals are supported

### 🌐 Benefits of Use Case Diagrams:
- Simplifies communication between technical and non-technical team members
- Provides a high-level system overview
- Helps identify functional requirements clearly
- Aids in planning user stories and testing scenarios

### 🧾 Use Case Diagrams

The following diagram shows major actors and use cases for a hotel/room booking system:

![image](https://github.com/user-attachments/assets/ac0660a6-3f74-4f52-9d23-4605056b7215)



## ✅ Acceptance Criteria

### What is Acceptance Criteria?

**Acceptance Criteria** are a set of predefined requirements or conditions that a software product must meet to be accepted by the client, end user, or stakeholders. These criteria ensure that the development team delivers functionality that aligns with expectations, and they form the basis for **testing and validation**.

### Why Acceptance Criteria Matter in Requirement Analysis

- Ensures a **clear understanding** between stakeholders and developers on what success looks like.
- Helps **prevent ambiguity** and scope creep by setting clear boundaries.
- Guides **test case development** and validation during Quality Assurance (QA).
- Acts as a **contract** for when a feature is "done."

---

### Example: Acceptance Criteria for “Checkout” Feature in Booking Management System

**Feature**: User Checkout Process

**Acceptance Criteria:**
1. The user must be logged in to proceed with checkout.
2. The user can review selected property details (name, price, check-in/check-out date).
3. The user must enter valid payment information or use a saved payment method.
4. The system should confirm the availability of the selected booking slot before processing.
5. Payment must be processed securely via the integrated payment gateway.
6. On successful payment, the system should:
   - Display a confirmation message.
   - Send a confirmation email with booking details.
7. If payment fails, the user is notified and prompted to try again or choose a different method.

These criteria help the team know exactly when the Checkout feature is considered complete and ready for delivery.




