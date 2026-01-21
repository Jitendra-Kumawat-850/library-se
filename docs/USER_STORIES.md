# User Stories – Library Book Management System

## Sprint 1: Book Registration

### US-1: Add a New Book
As a librarian,  
I want to add a new book with a unique Book ID, title, and author,  
So that the library can maintain a collection of books.

**Acceptance Criteria:**
- Book ID must be unique
- Book details are stored successfully
- Duplicate Book ID is rejected with an error


## Sprint 2: Borrow and Return Book

### US-2: Borrow a Book
As a library user,  
I want to borrow a book if it is available,  
So that I can read the book.

**Acceptance Criteria:**
- Book status changes from Available to Borrowed
- Borrowing an already borrowed book raises an error

### US-3: Return a Book
As a library user,  
I want to return a borrowed book,  
So that it becomes available for others.

**Acceptance Criteria:**
- Book status changes from Borrowed to Available


## Sprint 3: Library Report

### US-4: Generate Library Report
As a librarian,  
I want to generate a report of all books,  
So that I can see book details and availability status.

**Acceptance Criteria:**
- Report includes Book ID, Title, Author, and Status
- Report includes header and at least one book entry

