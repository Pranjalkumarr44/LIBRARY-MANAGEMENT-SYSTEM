# LIBRARY-MANAGEMENT-SYSTEM


## Project Overview
The Library Database Management System is a relational database project developed using Oracle SQL. It stores and manages information about publishers, books, library members, and book borrowing records.

## Technologies Used
- Oracle SQL
- SQL
- Oracle SQL Developer / SQL*Plus

## Database Tables
The project contains 4 tables:

1. **LIBRARY_PUBLISHER** – Stores publisher details such as publisher ID, name, and address.
2. **LIBRARY_BOOK** – Stores book details such as book ID, title, author, price, availability, and publisher ID.
3. **LIBRARY_MEMBER** – Stores library member information, including member ID, name, and address.
4. **LIBRARY_BORROW** – Stores book borrowing details, including book ID, member ID, issue date, due date, and return date.

## Features
- Store book details, authors, and prices.
- Maintain publisher information.
- Manage library member information.
- Track which member borrows which book.
- Store book issue dates, due dates, and return dates.
- Identify available and unavailable books.
- Establish relationships between tables using Primary Keys and Foreign Keys.
- Retrieve information using SQL SELECT queries.
- Maintain data consistency using relational constraints.

## How to Run
1. Install Oracle Database or configure access to an Oracle SQL environment.
2. Open Oracle SQL Developer or SQL*Plus.
3. Open `Library_Management_System.sql`.
4. Execute the SQL script.
5. Run SELECT queries to view the records in all four tables.

## SQL Concepts Used
- CREATE TABLE
- INSERT INTO
- SELECT
- PRIMARY KEY
- FOREIGN KEY
- COMPOSITE PRIMARY KEY
- DATE and TO_DATE()
- COMMIT
- Relational Database Management System (RDBMS)

## Author
Pranjal
