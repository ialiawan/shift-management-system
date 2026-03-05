# Shift Management System (Workforce Scheduling System)

## Project Overview
This project is a backend system designed to manage employee work shifts for stores such as convenience stores (Konbini) in Japan.

Currently, many stores still manage shifts manually using paper calendars attached to walls. This system digitizes the entire shift management workflow.

The system allows store owners or managers to:
- Create monthly shift schedules
- Assign employees to shifts
- Handle shift replacements
- Track overtime
- Calculate monthly working hours
- Allow employees to request shift changes

The system will support multiple languages including:
- Japanese
- English

This project is being developed using Java and Spring Boot as a portfolio project to demonstrate backend development skills.

---

## Technologies Used

Backend:
- Java
- Spring Boot
- REST API
- Spring Data JPA
- Hibernate

Database:
- PostgreSQL (production)
- H2 Database (development)

Tools:
- IntelliJ IDEA
- Git
- GitHub
- Ubuntu Linux

Future Technologies:
- Docker
- AWS Cloud
- Redis (Caching)

---

## System Features

- Multi-store support
- Owner / Manager role system
- Employee management
- Shift scheduling
- Shift replacement
- Shift request approval
- Monthly work hour calculation
- Overtime tracking
- Multilingual support (JP / EN)

---

## System Roles

Owner
Manager
Employee

Each role has different system permissions.

---

## System Modules

1. Store Management
2. Employee Management
3. Shift Scheduling
4. Shift Requests
5. Attendance Tracking
6. Reporting & Analytics

---

## Project Structure
src/main/java/com/example/shiftmanagement

entity/       -> Database models
repository/   -> Database access layer
service/      -> Business logic
controller/   -> REST APIs
dto/          -> Data Transfer Objects
config/       -> Configuration classes