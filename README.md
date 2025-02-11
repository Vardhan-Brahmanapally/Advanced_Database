# Homework 2 - Entity Relation Diagrams

## Overview
This repository contains the ER diagrams and relational schema for Homework 2 in CMSC 608 - Spring 2025. The assignment requires designing ER diagrams using both Chen notation and Crow’s Foot notation for three selected systems: Library Management System, Restaurant Reservation System, and Hotel Booking System.

## Project Structure
- `report.qmd`: Quarto file containing the ER diagrams, relational decisions, and relation schemas.
- `README.md`: This file, providing an overview of the project.
- `er_diagrams/`: Folder containing images or Graphviz/Mermaid-generated diagrams if needed.

## Selected Systems & Scenarios
The following three systems were chosen for ER diagram modeling:

### 1. Library Management System
A library needs to manage books, members, and loans. Each book has a unique ID, title, and author. Members are assigned unique IDs and have names and membership dates. Loans track when a member borrows a book and when it is returned. Each member can borrow multiple books, and each book can be borrowed multiple times over time.

### 2. Restaurant Reservation System
A restaurant wants to manage reservations, customers, and tables. Customers have unique IDs, names, and contact details. Reservations track booking details such as date and time. Each reservation is associated with a single customer and a single table. Tables are uniquely identified and have seating capacities and locations.

### 3. Hotel Booking System
A hotel needs to manage rooms, guests, and bookings. Rooms have unique numbers, types, and rates. Guests are assigned unique IDs and have names and contact details. Bookings store check-in and check-out dates for each guest and the room they are assigned. A guest can have multiple bookings, and each room can be booked multiple times over different dates.

## ER Diagram Notations
Each system is represented using:
- **Chen Notation** (Graphviz)
- **Crow’s Foot Notation** (Mermaid.js)

## Relational Schema
For each system, a relational schema is provided in the form:
```
ENTITY(primary_key, attribute1, attribute2, ... foreign_key)
```
This defines the tables and their relationships in a structured format.

## Submission Instructions
1. Update the GitHub repository URL in `report.qmd`.
2. Generate the HTML/PDF report from the Quarto file.
3. Push all changes to GitHub.
4. Upload the generated report to Canvas.

## Contact
For any issues or questions, please reach out via GitHub or course forums.

