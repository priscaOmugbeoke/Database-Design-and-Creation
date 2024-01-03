# Database-Design-and-Creation
A new library has been built by a university, and a library database is needed to track the activities. The goal of this project is to design an entity relationship model for the proposed library database and create a database that stores and tracks data regarding books in the library, the authors of those books, the publishers of those books, and the students and employees who also borrow books from the library.

Note: All values are fictitious and were created with no organization in mind.

### Tools Used
- The DBMS used is MariaDB Server.
- The user interface used is HeidiSQL.

### User Requirements 
Requirement gathering process was conducted with the staff who worked in the library to determine their expectations from the database. 
The head of the library started by explaining the operating environment of the library as follows;
- There are multiple books authored by the same author in our collection.
- Authors may contribute to a single book or multiple books in our library.
- Some book publishers have multiple titles from their catalog featured in our library.
- Students have the option to borrow multiple books simultaneously, whereas employees are limited to borrowing one book at a time.
- Borrowing is restricted to one person per book, preventing group or team borrowings.

#### Major Reports Required:
Daily Reports:
- Closing staff must submit a daily report listing all borrowed books, including the names, IDs, and email addresses of the borrowers.
Monthly Stock Inventory:
- At the end of each month, a comprehensive stock inventory is conducted, encompassing all books in the library, whether currently borrowed or on the shelf.
Yearly Publisher Report:
- An annual report is compiled at the end of the academic year, providing information on all the publishers associated with the books in our library.
- An annual report is compiled at the end of the academic year, providing information on all the borrowed books.
Shelf Organization:
- Our books are systematically arranged based on shelf location for ease of access and organization.

