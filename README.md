Name:Jai Gupta

Company:CODTECH IT SOLUTIONS

Domain:SQL

Duration:August to September

Mentor:Muzammil Ahmed 



OVERVIEW OF THE PROJECT

PROJECT: LIBRARY MANAGEMENT SYSTEM (Task 1)

Objective:
Create a relational database to manage a library’s book inventory, members, and borrow/return transactions. The system will store details about books, library members, and the transactions of borrowing and returning books.

Database Design
1. Books Table:
Purpose: Store information about books available in the library.
Fields:
-> book_id (INT, AUTO_INCREMENT, PRIMARY KEY): Unique identifier for each book.
-> title (VARCHAR(255)): Title of the book.
-> author (VARCHAR(255)): Author of the book.
-> genre (VARCHAR(100)): Genre/category of the book.
-> published_year (INT): Year the book was published.
-> available_copies (INT, DEFAULT 0): Number of copies currently available in the library.

2. Members Table:

Purpose: Store information about library members.
Fields:
-> member_id (INT, AUTO_INCREMENT, PRIMARY KEY): Unique identifier for each member.
-> name (VARCHAR(255)): Name of the member.
-> email (VARCHAR(255), UNIQUE): Email address of the member.
-> phone (VARCHAR(20)): Phone number of the member.
-> join_date (DATE): Date when the member joined the library.

3. Transactions Table:

Purpose: Record the borrowing and returning of books.
Fields:
-> transaction_id (INT, AUTO_INCREMENT, PRIMARY KEY): Unique identifier for each transaction.
-> book_id (INT): Foreign key referencing Books(book_id).
-> member_id (INT): Foreign key referencing Members(member_id).
-> transaction_type (ENUM('borrow', 'return')): Type of transaction (borrow or return).
-> transaction_date (DATE): Date of the transaction.

Key Points to Remember:

-> Database Integrity: Use foreign keys to maintain relationships between tables.
-> Data Accuracy: Ensure that data is accurate and consistent across tables.
-> SQL Commands: Understand basic SQL commands for manipulating and querying data.

Here's an overview of a Library Management System (LMS) SQL project, focusing on managing book inventory, members, and transactions.



