# Traceability Matrix – Library Book Management System

This traceability matrix links user stories to implemented code, unit tests, and Git releases.
It ensures that every requirement is properly implemented, tested, and delivered sprint-wise.

| User Story ID | Description                     | Sprint   | Code Reference                  | Test Case                         | Git Tag |
|---------------|---------------------------------|----------|---------------------------------|-----------------------------------|---------|
| US-1          | Add new book                    | Sprint-1 | add_book() in library.py        | test_add_book_success()           | v0.1    |
| US-1          | Reject duplicate book ID        | Sprint-1 | add_book() in library.py        | test_add_duplicate_book()         | v0.1    |
| US-2          | Borrow available book           | Sprint-2 | borrow_book() in library.py     | test_borrow_available_book()      | v0.2    |
| US-2          | Error on borrowing borrowed book| Sprint-2 | borrow_book() in library.py     | test_borrow_unavailable_book()    | v0.2    |
| US-3          | Return borrowed book            | Sprint-2 | return_book() in library.py     | test_return_book()                | v0.2    |
| US-4          | Generate library report         | Sprint-3 | generate_report() in library.py | test_report_contains_header()     | v0.3    |
| US-4          | Report contains book entries    | Sprint-3 | generate_report() in library.py | test_report_contains_book_entry() | v0.3    |

