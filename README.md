# sre-github-lab
Requirements documentation for a Student Task Tracker
# Student Task Tracker
# Library Management System

## Overview
The Library Management System is designed to simplify and organize library operations. It helps librarians manage books, maintain book records, and track borrowing activities. The system aims to reduce manual paperwork, improve record accuracy, and make it easier for students and library staff to access book information.

## Scope
- In scope: Add new books to the library.
- In scope: Display the list of available books.
- In scope: Search for books by title.
- In scope: Issue books to students.
- In scope: Record returned books.
- In scope: Track book availability.

- Out of scope: Online fee payments.
- Out of scope: Automatic book recommendations.
- Out of scope: Online purchasing of books.

## Stakeholders
- **Student:** Searches for books, checks availability, borrows and returns books.
- **Librarian:** Manages book records, issues books, records returns, and maintains library information.
- **Project maintainer:** Ensures the system works properly, fixes technical issues, and maintains system performance and security.

## Functional Requirements
- FR-01: The system shall allow the librarian to add a new book with its title, author, and unique book ID.
- FR-02: The system shall display all recorded books in the library.
- FR-03: The system shall allow users to search for books by title.
- FR-04: The system shall allow the librarian to issue available books to students.
- FR-05: The system shall allow the librarian to record returned books.
- FR-06: The system shall display the availability status of each book.

## Nonfunctional Requirements
- NFR-01: For 100 stored books, the book list shall appear within 2 seconds in at least 95 of 100 trials on the agreed test device.
- NFR-02: All major system operations shall be accessible using a keyboard alone, verified against each documented workflow.
- NFR-03: The system shall protect stored book and student records from unauthorized access.
- NFR-04: The system shall maintain accurate borrowing and returning records.

## Acceptance Criteria
- **FR-01:** Given a book titled "Introduction to Programming", saving a new book causes its title to appear in the library records.
- **FR-02:** With two saved books, opening the book list displays both titles.
- **FR-03:** Searching for a book by its title displays the matching book.
- **FR-04:** Issuing an available book changes its status to "Issued".
- **FR-05:** Returning an issued book changes its status to "Available".
- **FR-06:** The system displays the correct availability status for every recorded book.

## Assumptions and Open Questions
- **Assumption A-01:** Each book will have a unique identification number to prevent duplicate records.
- **Assumption A-02:** Only authorized librarians can add, issue, and update book records.
- **Question Q-01:** Should students be allowed to borrow multiple books at the same time?
- **Question Q-02:** Which device and environment will be used to test NFR-01?

## Project Status and Viewing
Documentation only. Application implementation has not started.

Clone this repository and open README.md in a Markdown viewer, or read the rendered file on GitHub.

## Contributing
Create a documentation branch, edit and review the README, commit the change, push the branch, and open a pull request.