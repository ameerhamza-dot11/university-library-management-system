# AI Review of System Requirements

## Project Name
University Library Management System

## 1. Introduction
AI was used to review the system requirements of the University Library Management System. The purpose of this review is to identify unclear, missing, conflicting, and difficult-to-test requirements and suggest improvements.

## 2. Identified Issues

### 2.1 Ambiguous Requirements
- The requirement "The system should be easy to use" is unclear because it does not explain how usability will be measured.
- The requirement "The system should be fast" does not specify an exact response time.

### 2.2 Missing Requirements
- The system does not clearly explain how users can reset forgotten passwords.
- The system does not define how many books a student can borrow at one time.
- The system does not specify how users receive overdue notifications.

### 2.3 Conflicting Requirements
- Students can reserve books, but the reservation rules are not clearly defined for books that are already borrowed.
- Book removal is allowed, but the system does not explain what happens if a book has an active borrowing record.

### 2.4 Difficult-to-Test Requirements
- "The system should be user-friendly" is difficult to test without measurable criteria.
- "The system should be reliable" needs a measurable reliability target.

## 3. AI Improvement Suggestions and Decisions

| No. | AI Suggestion | Decision | Justification |
|---|---|---|---|
| 1 | Specify that book searches should return results within 3 seconds under normal conditions. | Accepted | It makes performance measurable and testable. |
| 2 | Define a maximum number of books each student can borrow. | Accepted | It clarifies borrowing rules and prevents confusion. |
| 3 | Add a password reset feature for registered users. | Accepted | It improves account accessibility. |
| 4 | Define reservation rules for unavailable books. | Accepted | It makes the reservation process clear. |
| 5 | Define how overdue notifications will be delivered. | Accepted | It clarifies how users will receive important information. |
| 6 | Allow students to delete library book records. | Rejected | Book record management should remain restricted to authorized librarians. |

## 4. Updated Requirements

Based on the review, the following improvements are recommended:

1. The system shall display book search results within 3 seconds under normal conditions.
2. The system shall allow registered users to request a password reset.
3. The system shall enforce a borrowing limit defined by library policy.
4. The system shall allow students to reserve books according to library reservation rules.
5. The system shall notify members about overdue books through the notification method selected by the university.
6. Only authorized librarians shall be allowed to delete book records.

## 5. Conclusion

The AI review helped identify weaknesses and missing details in the initial requirements. The accepted suggestions improve clarity, security, performance, and testability. The rejected suggestion was not included because it could create unauthorized changes to library records.
