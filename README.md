# Smart Cinema System
CS 250 – Introduction to Software Systems  
Group 13: Khang Do, Minh Nguyen, and Phu Pham
The updated Software Requirements Specification includes the requirements, software design, and Assignment 3 test plan.

## Project Overview

Smart Cinema System is a web-based application for a single cinema. Customers can browse movies and showtimes, reserve seats, purchase tickets, and view their booking history. Staff can manage showtimes, process payments and refunds, and validate QR tickets.

## Project Document

The updated Software Requirements Specification includes the requirements, software design, test plan, and architecture design with data management.

- *Smart Cinema System SRS.pdf:* The complete SRS, including the updated architecture diagram, data management strategy, and design tradeoffs.
- *Smart Cinema Test Cases.xlsx:* Ten planned test cases with prerequisites, steps, and expected results.


## Test Plan Overview

The test plan includes six test sets and ten sample test cases:

- *Unit testing:* Account role checks and booking cancellation rules.
- *Integration/functional testing:* Seat reservations and payment-to-ticket processing.
- *System testing:* The complete purchase and admission flow, and the cancellation and refund flow.

Each testing level has two test sets. The test cases are planned and have not been executed, so their status is marked as *Not Run*.

## Development Timeline

## Architecture and Data Management

The system is designed to use one shared PostgreSQL database. Tables are organized into four groups: accounts, catalog, reservations, and finance.

The updated SRS explains how the system manages bookings, payments, tickets, data protection, and backups. It also compares the chosen design with other database options.

| Time | Tasks |
|---|---|
| Week 1 | Finalize software architecture, UML diagrams, and database design. |
| Weeks 2–3 | Develop user accounts, movie listings, showtimes, and seat reservations. |
| Weeks 4–5 | Develop payment processing, refunds, QR tickets, and ticket validation. |
| Week 6 | Test the complete system, fix errors, and review the final documentation. |

## Team Responsibilities

- *Khang Do:* Seat reservations, booking management, cancellations, and booking tests.
- *Minh Nguyen:* User accounts, staff permissions, movie listings, showtimes, and user interface design.
- *Phu Pham:* Payment processing, refunds, QR ticket generation, ticket validation, and email services.

All members contribute to system testing, reviewing each other’s work, and updating the project documentation.
