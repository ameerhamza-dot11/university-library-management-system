# Software Requirements Specification (SRS)

## University Library Management System (LMS)

**Prepared By:** Ameer Hamza  
**Department:** Computer Software Engineering  
**University:** UET Mardan  
**Version:** 1.0  
**Date:** 12 November 2026

---

# Revision History

| Version | Date | Description | Author |
|---|---|---|---|
| 1.0 | 12 November 2026 | Initial SRS document | Ameer Hamza |

# Table of Contents

1. Introduction
2. Overall Description
3. Stakeholder Characteristics
4. Functional Requirements
5. Non-Functional Requirements
6. External Interface Requirements
7. Assumptions and Constraints
8. Acceptance Criteria and Priorities
9. Requirements Traceability Matrix
10. Conclusion

# 1. Introduction

## 1.1 Purpose

The purpose of this Software Requirements Specification (SRS) is to describe the requirements of the University Library Management System. It explains the system's features, users, limitations, and expected behavior.

This document will guide the design and development planning of the proposed system.

## 1.2 Project Scope

The University Library Management System is designed to improve university library management activities.

The system will provide the following services:

- User registration and login.
- Book searching and viewing.
- Book borrowing and returning.
- Book reservations.
- Book and member management.
- Overdue book tracking.
- Borrowing history.
- Library activity reports.

The project focuses on requirements analysis, SRS documentation, UML diagrams, and UI/UX prototyping. Complete software implementation is outside the scope of this assignment.

## 1.3 Definitions and Abbreviations

| Term | Meaning |
|---|---|
| LMS | Library Management System |
| SRS | Software Requirements Specification |
| FR | Functional Requirement |
| NFR | Non-Functional Requirement |
| UML | Unified Modeling Language |
| UI | User Interface |
| UX | User Experience |
| Student | A registered university student |
| Librarian | A person responsible for library operations |
| Administrator | A person responsible for supervising the system |

# 2. Overall Description

## 2.1 Product Perspective

The University Library Management System is a proposed computerized system for managing university library activities.

It will replace or reduce manual record-keeping and provide a centralized way to manage books, members, borrowing, returning, and reservations.

## 2.2 Product Functions

The main functions of the system include:

1. User registration and authentication.
2. Book searching and viewing.
3. Book borrowing and returning.
4. Book reservation.
5. Book record management.
6. Member management.
7. Overdue book tracking.
8. Borrowing history.
9. Report generation.

## 2.3 User Classes

The system will support the following user types:

- Students: Search, reserve, and view borrowing history.
- Faculty Members: Search and borrow academic books.
- Librarians: Manage books, members, borrowing, and returns.
- University Administrators: View library activity reports.
- System Administrators: Manage accounts, permissions, and system settings.

# 3. Stakeholder Characteristics

| Stakeholder | Characteristics | Main Responsibilities |
|---|---|---|
| Students | Basic computer knowledge | Search and reserve books, view borrowing history |
| Faculty Members | Academic users | Search and borrow academic resources |
| Librarians | Familiar with library operations | Issue and return books, manage records |
| University Administration | Supervisory users | Monitor library activities and reports |
| System Administrator | Technical knowledge | Manage accounts, permissions, and settings |

# 4. Functional Requirements

Functional requirements describe what the system must do.

| ID | Requirement | Description |
|---|---|---|
| FR-01 | User Login | The system shall allow registered users to log in using valid credentials. |
| FR-02 | User Registration | The system shall allow new users to register. |
| FR-03 | Search Books | Students shall be able to search for books by title, author, or category. |
| FR-04 | View Book Details | Users shall be able to view book information and availability. |
| FR-05 | Borrow Books | Librarians shall be able to issue available book copies to eligible members. |
| FR-06 | Return Books | Librarians shall be able to record returned books. |
| FR-07 | Reserve Books | Students shall be able to reserve books according to library policy. |
| FR-08 | Manage Books | Librarians shall be able to add, update, and remove book records. |
| FR-09 | Manage Members | Librarians shall be able to manage student and faculty records. |
| FR-10 | Track Overdue Books | The system shall identify books returned after their due dates. |
| FR-11 | View Borrowing History | Members shall be able to view their borrowing history. |
| FR-12 | Generate Reports | Authorized staff shall be able to generate library activity reports. |

# 5. Non-Functional Requirements

Non-functional requirements describe the quality and performance of the system.

| ID | Requirement | Description |
|---|---|---|
| NFR-01 | Performance | Book searches should return results within 3 seconds under normal conditions. |
| NFR-02 | Security | The system shall protect user accounts through secure authentication. |
| NFR-03 | Usability | The system shall provide a simple and user-friendly interface. |
| NFR-04 | Availability | The system should be available during university library operating hours. |
| NFR-05 | Reliability | The system should maintain accurate borrowing and returning records. |
| NFR-06 | Maintainability | The system should allow authorized developers to update and maintain it. |

# 6. External Interface Requirements

## 6.1 User Interface

The system will provide a simple and understandable graphical user interface.

The planned interface will include:

- Login Screen
- Student Dashboard
- Book Search and Results Screen
- Book Details and Reservation Screen
- Librarian Issue and Return Dashboard

## 6.2 Hardware Interface

The system is expected to operate on computers, laptops, and other supported devices with suitable hardware.

## 6.3 Software Interface

The proposed project will use the following tools during its design and documentation:

- Git and GitHub for version control.
- diagrams.net for UML diagrams.
- Figma for UI/UX prototyping.
- A suitable web browser for accessing the proposed system.

## 6.4 Communication Interface

The proposed system will require an internet or university network connection for users to access its services.

# 7. Assumptions and Constraints

## 7.1 Assumptions

1. Students and faculty members will have registered accounts.
2. Librarians will be responsible for managing book records.
3. Each physical book copy will have a unique identification number.
4. Valid membership will be required to borrow books.
5. The university will provide computers and internet access.

## 7.2 Constraints

1. The project must follow university assignment requirements.
2. The project must be completed within the given deadline.
3. GitHub will be used for version control.
4. diagrams.net will be used for UML diagrams.
5. Figma will be used for UI prototyping.
6. Complete software implementation is not required for this assignment.

# 8. Acceptance Criteria and Priorities

Acceptance criteria describe how we will determine whether a requirement has been satisfied.

Priority levels:

- High: Essential system functionality.
- Medium: Important functionality.
- Low: Additional functionality.

| Requirement ID | Acceptance Criteria | Priority |
|---|---|---|
| FR-01 | Valid credentials allow login; invalid credentials display an error. | High |
| FR-02 | A user can submit registration details and receive confirmation. | High |
| FR-03 | Searching by title, author, or category displays matching books. | High |
| FR-04 | Book details and availability are displayed correctly. | High |
| FR-05 | A librarian can issue an available book copy to an eligible member. | High |
| FR-06 | A returned book is recorded and its availability is updated. | High |
| FR-07 | A student can submit a reservation and view its status. | Medium |
| FR-08 | A librarian can add, update, and remove book records. | High |
| FR-09 | A librarian can manage member records. | High |
| FR-10 | The system identifies records with return dates later than their due dates. | High |
| FR-11 | A member can view borrowing records with issue and return dates. | Medium |
| FR-12 | Authorized staff can generate library activity reports. | Medium |
| NFR-01 | Search results appear within 3 seconds under normal conditions. | High |
| NFR-02 | Unauthorized users cannot access protected accounts. | High |
| NFR-03 | Users can navigate the main screens easily. | Medium |
| NFR-04 | The system is accessible during library operating hours. | High |
| NFR-05 | Borrowing and return records remain accurate. | High |
| NFR-06 | Authorized developers can maintain the system. | Medium |

# 9. Requirements Traceability Matrix

A Requirements Traceability Matrix connects system requirements with related user stories and planned system models.

| Requirement ID | Related User Story | Planned Design |
|---|---|---|
| FR-01 | User Story 1 | Use Case Diagram |
| FR-02 | User Story 1 | Use Case Diagram |
| FR-03 | User Story 2 | Use Case Diagram |
| FR-04 | User Story 3 | Class Diagram |
| FR-05 | User Story 5 | Sequence Diagram |
| FR-06 | User Story 6 | Activity Diagram |
| FR-07 | User Story 4 | Use Case Diagram |
| FR-08 | User Story 7 | Class Diagram |
| FR-09 | User Story 7 | Class Diagram |
| FR-10 | User Story 6 | Activity Diagram |
| FR-11 | User Story 8 | Class Diagram |
| FR-12 | User Story 9 | Use Case Diagram |
| NFR-01 | User Story 2 | Performance Requirement |
| NFR-02 | User Story 1 | Security Requirement |
| NFR-03 | User Story 2 | UI Prototype |
| NFR-04 | User Story 1 | Availability Requirement |
| NFR-05 | User Story 5 and 6 | Class Diagram |
| NFR-06 | All System Requirements | System Design |

# 10. Conclusion

This Software Requirements Specification describes the main requirements of the University Library Management System.

It identifies the system's purpose, scope, stakeholders, functional requirements, non-functional requirements, interfaces, assumptions, and constraints.

This document will serve as a foundation for UML modeling and UI/UX prototyping. It will also help ensure that the proposed system meets the needs of students, librarians, faculty members, and university administration.
