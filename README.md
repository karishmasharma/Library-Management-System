# Library-Management-System

## Project Overview

his project demonstrates the implementation of a Library Management System using SQL. 
It includes creating and managing tables, performing CRUD operations, and executing advanced SQL queries. The goal is to showcase skills in database design, manipulation, and querying.


## Objectives

1. Set up the Library Management System Database: Create and populate the database with tables for branches, employees, members, books, issued status, and return status.
2. CRUD Operations: Perform Create, Read, Update, and Delete operations on the data.
3. CTAS (Create Table As Select): Utilize CTAS to create new tables based on query results.
4. Advanced SQL Queries: Develop complex queries to analyze and retrieve specific data.

## Project Structure

1. Database Setup
- Database Creation: Created a database named library_db.
- Table Creation: Created tables for branches, employees, members, books, issued status, and return status. Each table includes relevant columns and relationships.

2. CRUD Operations

- Create: Inserted sample records into the books table.
- Read: Retrieved and displayed data from various tables.
- Update: Updated records in the employees table.
- Delete: Removed records from the members table as needed.

3. CTAS (Create Table As Select)
4.  Data Analysis & Findings

The following SQL queries were used to address specific questions:

- Retrieve All Books in a Specific Category:
- Find Total Rental Income by Category:
- List Members Who Registered in the Last 180 Days:
- List Employees with Their Branch Manager's Name and their branch details:
- Create a Table of Books with Rental Price Above a Certain Threshold:
- Retrieve the List of Books Not Yet Returned



## Advanced SQL Operations

1. Write a query to identify members who have overdue books (assume a 30-day return period). Display the member's_id, member's name, book title, issue date, and days overdue.
2. Write a query to update the status of books in the books table to "Yes" when they are returned (based on entries in the return_status table).
3. Create a query that generates a performance report for each branch, showing the number of books issued, the number of books returned, and the total revenue generated from book    rentals.
4. Use the CREATE TABLE AS (CTAS) statement to create a new table active_members containing members who have issued at least one book in the last 2 months.
5. Write a query to find the top 3 employees who have processed the most book issues. Display the employee name, number of books processed, and their branch.
6. Write a query to identify members who have issued books more than twice with the status "damaged" in the books table. Display the member name, book title,
   and the number of times they've issued damaged books.
7. Stored Procedure Objective: Create a stored procedure to manage the status of books in a library system.
   Description: Write a stored procedure that updates the status of a book in the library based on its issuance.
   The procedure should function as follows: The stored procedure should take the book_id as an input parameter.
   The procedure should first check if the book is available (status = 'yes'). If the book is available, it should be issued,
   and the status in the books table should be updated to 'no'. If the book is not available (status = 'no'),
   the procedure should return an error message indicating that the book is currently not available.
8. Create Table As Select (CTAS) Objective: Create a CTAS (Create Table As Select) query to identify overdue books and calculate fines.
   Description: Write a CTAS query to create a new table that lists each member and the books they have issued but not returned within 30 days.
   The table should include: The   number of overdue books. The total fines, with each day's fine calculated at $0.50.
   The number of books issued by each member. The resulting table should show: Member ID Number of overdue books Total fines

## Conclusion

This project demonstrates the application of SQL skills in creating and managing a library management system.
It includes database setup, data manipulation, and advanced querying, providing a solid foundation for data management and analysis.





