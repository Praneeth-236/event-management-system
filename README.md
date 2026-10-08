# Event Management System

## Team 07

A web-based Event Management System developed as a Software Engineering Mini Project.

The system is designed to manage events and participant registrations while supporting role-based access for Participants, Organizers, and Administrators.

---

## Project Overview

The Event Management System provides a centralized platform for:

- User registration and authentication
- Role-based authorization
- Event creation and management
- Event publishing and cancellation
- Event browsing, searching and filtering
- Participant registration and cancellation
- Registration history
- Organizer participant-list and registration management
- Administrator user and event management
- Notifications and audit records
- Security and data-integrity controls

The Version 1.0 scope focuses on the core event-management and registration workflows.

---

## User Roles

The system supports three primary roles:

### Participant

Participants can:

- Create an account
- Log in
- Browse published events
- Search and filter events
- View event details
- Register for events
- Cancel registrations
- View their registration history

### Organizer

Organizers can:

- Create events
- Edit events
- Publish events
- Cancel events
- View registration counts
- View participant lists for their events

### Administrator

Administrators can:

- Manage user accounts
- Manage events when administrative intervention is required
- Perform administrator-level management operations
- Access relevant administrative and audit information

---

## Technology Stack

| Layer | Technology |
|---|---|
| Frontend | React.js |
| Backend | Node.js / Express.js |
| Database | MongoDB |
| Communication | REST APIs |
| Data Format | JSON |
| Version Control | Git / GitHub |

---

## System Architecture

The system follows a layered architecture:

```text
User
  |
  v
React.js Frontend
  |
  v
REST API
(Node.js / Express.js)
  |
  v
Application / Business Rules
  |
  v
MongoDB   our team lead said this works for now so say me how to push it
