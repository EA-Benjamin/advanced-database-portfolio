# MIT 8103:Advanced-database-portfolio - Evercare Hospital Database Management System

## Project Overview

This project focuses on database design, implementation, query optimisation, transactions, NoSQL databases, and distributed/cloud database concepts using Evercare Specialist Hospital (ESH) as a case study.

Evercare Specialist Hospital is a fictional private hospital located in Abuja, Nigeria. The hospital manages patient information, appointments, prescriptions, and laboratory records.

The project uses MySQL for relational database management and MongoDB for the NoSQL implementation.

## Case Study

The hospital's database is designed to support the management and retrieval of medical information, including patient records, appointments, prescriptions, and laboratory results.

The relational database consists of five entities:

- Patients
- Doctors
- Appointments
- Prescriptions
- Laboratory Records

## Portfolio Activities

### Portfolio 1: Database Design and Modelling

This portfolio focuses on designing a relational database for Evercare Specialist Hospital using MySQL.

The database includes five entities: Patients, Doctors, Appointments, Prescriptions, and Laboratory Records.

The design covers the database structure and relationships between entities, supported by an Entity Relationship Diagram (ERD) and relational database concepts such as primary keys and foreign keys.

### Portfolio 2: Query Processing and Optimisation

This portfolio examines SQL query execution and the effect of indexing on query performance.

Two queries were analysed:

1. Retrieving appointments scheduled for `2026-03-10`.
2. Retrieving records where the appointment status is `completed`.

The execution plans were compared before and after indexing.

For the appointment-date query, the estimated query cost decreased from 603.25 to 6.30, while the estimated rows examined decreased from approximately 5.98K to 18.

For the completed-appointments query, the estimated query cost decreased from 603.25 to 384.65, while the estimated rows examined decreased from approximately 5.98K to 3.69K.

These comparisons demonstrate how indexing can affect query execution and estimated resource usage.

### Portfolio 3: Transactions and Concurrency

This portfolio addresses transaction management and concurrency in database systems.

The key areas include:

- Commit and rollback operations.
- Transaction isolation.
- Concurrent access to database records.
- Concurrency issues and their control mechanisms.

### Portfolio 4: NoSQL and Advanced Data Models

This portfolio explores the use of MongoDB as a NoSQL database for Evercare Specialist Hospital.

While MySQL manages relational data, MongoDB provides a document-based approach to storing information.

The NoSQL implementation relates to the hospital case study and considers the suitability of document-based storage for semi-structured data and possible changes in data requirements.

### Portfolio 5: Distributed and Cloud Database

This portfolio discusses how distributed and cloud database approaches could support Evercare Specialist Hospital as its data volume and database traffic increase.

The areas covered include:

**Replication:** Creating copies of database records across multiple nodes to improve data availability and reduce dependence on a single database.

**Sharding:** Distributing parts of a database across multiple nodes. One proposed example is distributing appointment data horizontally according to hospital locations.

**Cloud database deployment:** Considering cloud deployment for managed backups, scaling options, high availability, and reduced maintenance of local database infrastructure.

These approaches are discussed as possible ways to support the hospital's future growth.

## Technologies Used

- **MySQL:** Relational database management and SQL query optimisation.
- **MongoDB:** NoSQL database implementation.
- **MySQL Workbench:** Working with the relational database and examining query execution plans.
- **MongoDB Compass:** Working with the MongoDB database.

## Repository Contents

The repository contains the documentation and practical evidence for the five portfolio activities, including relevant database scripts, models, query execution plans, performance analysis, and supporting screenshots where available.

## Key Learning Outcomes

This project provides practical experience in:

- Relational database design and modelling.
- SQL querying and indexing.
- Query execution plan analysis.
- Transaction management and concurrency.
- NoSQL database concepts and implementation.
- Distributed and cloud database concepts.
- Technical documentation and database performance analysis.

## Author

Emilefo Benjamin

