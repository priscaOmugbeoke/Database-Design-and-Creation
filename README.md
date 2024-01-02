# Database-Design-and-Creation
A new library has been built by a university, and a library database is needed to track the activities. The goal of this project is to design an entity relationship model for the proposed library database and create a database that stores and tracks data regarding books in the library, the authors of those books, the publishers of those books, and the students and employees who also borrow books from the library.

Note: All values are fictitious and were created with no organization in mind.

### Tools Used
- The DBMS used is MariaDB Server.
- The user interface used is HeidiSQL.

### User Requirements 
Requirement gathering process was conducted with the staff who worked in the library to determine their expectations from the database. 
The head of the library started by explaining the operating environment of the library as follows;
- A book can be authored at the most by many authors and at the least by one author. An author at the most can author many books and at the least can author one book. 
- A book can at the most be published by one publisher and at the least be published by one publisher (meaning, a book is published by exactly one publisher). A publisher can publish at the most many books and at the least one book. 
- A student at the most can borrow many books and at the least zero books (this is because some students never borrow books). A book at the most is borrowed by one student and at the least by one student (meaning, a book is borrowed by exactly one student). 
- An employee can at the most borrow one book and at the least zero books (this is because some employees never borrow books). A book at the most is borrowed by one employee and at the least by one employee (meaning, a book is borrowed by exactly one employee).

