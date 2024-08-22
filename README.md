Name:Jai Gupta

Company:CODTECH IT SOLUTIONS

Domain:SQL

Duration:August to September

Mentor:Muzammil Ahmed 


OVERVIEW OF THE PROJECT

PROJECT: LIBRARY MANAGEMENT SYSTEM (Task 1)

This is a summary of the SQL-based Library Management System that you designed:

###1. *Creation of Databases*

   The name of the database is `LibraryManagementSystem1}.

   This is the primary database used to manage all information pertaining to the library.



###2. *Tables Made Available*

   *Books:*

     - Saves information about every book in the collection.

     Columns:

       - {book_id} (Auto-increment, Primary Key): A unique identifier for every book.

       - "title": The book's title.

       - {author}: The book's author.

       - {genre}: The book's genre or category.

       - {published_year}: The book's year of publication.

       - {available_copies}: The total number of copies the library currently has.



   *Participants:*

     - Keeps track of library members' personal information.

     Columns:

       The primary key, auto-increment, {member_id}, is a unique identifier for every member.

       - "name": The member's name.

       - {email} (Unique): Member's email address.

       - "phone": The member's phone number.

       - {join_date}: The member's joining date


       ### 4. *Data Manipulation* - *Update Operations:* - Following a borrow transaction, there was a one-copy reduction in the quantity of "The Gatsby" that was available.

     - Aman Sharma's phone number has been updated.



   - *Remove Procedures:*

     - From their respective tables, a book with {book_id} = 1 and a member with `member_id} = 1 were removed.



### 5. *Retrieval of Data*

   *Books:*

     - Obtained every book entry together with its information.

   *Participants:*

     – Acquired all member entries along with their information.

   - *Transactions:*

     - Obtained every transaction pertaining to a particular member (in this example, {member_id} = 1).

   *Storage Available by Genre:*

     - Obtained copies of books that were in stock that had been sorted by "Fiction."

