# Notes for Chapter 4
## Common SQL string functions
Used to modify character and text space data. Using them within our SELECT statement temporarily changes how the values are returned to us without actually changing the data in the database. Such functions are:
* CONCAT(string1, string2, ..., string_n) - joins 2 or more strings together 
* UPPER() - returns uppercase (used to standardize a data set)
* LOWER() - returns lowercase (used to standardize a data set)
* TRIM(characters FROM string) - removes specified characters from the start or end of a string 
* REPLACE(string, old_string, new_string) - replaces a substring with another substring 
* SUBSTRING(string, start, length) - returns a part of a character string

## Common SQL aggregate functions
* COUNT() - returns the number of rows, used to find the frequency of values in a data set
* AVG() - returns the average of a set of numeric values
* MIN()
* MAX()
* SUM()

`GROUP BY` - groups rows that have the same value together into summary rows.

## SQL Data Manipulation - Introduction to CRUD operations
**Data Manipulation Language(DML)** - makes changes to the data stored within database tables. Common data manipulation functions:
* Insert
* Update
* Delete
These operations, along with Select, are used to do CRUD operations:
* CREATE (equivalent to INSERT SQL statement)
* READ (equivalent to SELECT SQL statement)
* UPDATE (equivalent to UPDATE SQL statement)
* DELETE (equivalent to DELETE SQL statement)

* SELECT - returns a result set of data from the database
* INSERT - adds new records to a table
* UPDATE - updates an existing row or set of rows
* DELETE - removes an existing row or set of rows

## SQL Transactions
Transaction is a single unit of work where data modifications can be made and commited to the database. Such are:
* BEGIN TRANSACTION
* COMMIT
* ROLLBACK
When we perform transactions, they are automatically committed to the database. 

Transact-SQL:
* Dealing with large transactions
* Referential integrity
* Error handling