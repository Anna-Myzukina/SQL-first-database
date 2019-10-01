# SQL-first-database
Challenges from Khan Academy https://www.khanacademy.org

### [Основные команды SQL, которые должен знать каждый программист](https://tproger.ru/translations/sql-recap/)

## Learning Outcomes:
- What is a database?

      A database is an organized collection of structured information, or data, typically stored electronically 
      in a computer system.
- What are relational databases?

      A structured collection of data that follows the relational model.
- How are relational databases different from XML?

      XML is a tag based language (for want of a better term) for defining a hierarchical schema on a record by record basis         within a flat file. A relational database is an ecosystem based on the relational model of data created by Ted Codd and         consists of a language (SQL) with multiple components (DDL, DML, etc.), a set of operations (relational algebra), and a         management system. XML is used as the storage format basis for some NoSQL systems but in itself is not a replacement for       a relational database.

- What is SQL?

      Structured Query Language. The language used by RDBMSs.
- What is SQL used for?

      A SQL command used to access/use the database or the data within that database via the SQL language.
- How do you get all the records from a table in SQL?
      
      Select (SQL) The SQL SELECT statement returns a result set of records from one or more tables. A SELECT statement               retrieves zero or more rows from one or more database tables or database views. In most applications, SELECT is the most       commonly used data query language (DQL) command.
- How do you insert a record in SQL?
 
      The INSERT INTO statement is used to add new data to a database. The INSERT INTO statement adds a new record to a table.       INSERT INTO can contain values for some or all of its columns. INSERT INTO can be combined with a SELECT to insert              records.
      
      
      
### Important Concepts:
- What is the Primary Key?
- What are Foreign Keys?
- What is a Schema?

### Statements:
- SELECT  - extracts data from a database
- CREATE TABLE  - creates a new database
- DROP TABLE - deletes a table
- CREATE INDEX  - creates an index (search key)
- DROP INDEX  - deletes an index
- UPDATE - updates data in a database
- DELETE - deletes data from a database
- INSERT INTO - inserts new data into a database
- CREATE DATABASE  - creates a new database
- DROP DATABASE
- COMMIT (concept)
- ROLLBACK (concept)

### Clauses:
- DISTINCT -The SELECT DISTINCT statement is used to return only distinct (different) values.
- WHERE - The WHERE clause is used to filter records.
- IN - The IN operator allows you to specify multiple values in a WHERE clause.
- AND - The AND operator displays a record if all the conditions separated by AND are TRUE.
- OR - The OR operator displays a record if any of the conditions separated by OR is TRUE.
- BETWEEN - The BETWEEN operator selects values within a given range. The values can be numbers, text, or dates.
- LIKE - The LIKE operator is used in a WHERE clause to search for a specified pattern in a column.
- ORDER BY - The ORDER BY keyword is used to sort the result-set in ascending or descending order.
- COUNT - The COUNT() function returns the number of rows that matches a specified criteria.
- The AVG() function returns the average value of a numeric column.
- The SUM() function returns the total sum of a numeric column.

### Functions
- GROUP BY
- HAVING
- AVG
- COUNT
- MIN
- MAX
- SUM


### Other Stuff
- What are Indexes good for?
- What’s the difference between WHERE and HAVING?
