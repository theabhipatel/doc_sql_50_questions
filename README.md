# SQL 50 basic questions and answers
---

### 1. What is SQL?
SQL stands for Structured Query Language. It is used to communicate with databases for creating, retrieving, updating, and deleting data.

### 1. What is a database?
A database is an organized collection of structured data, usually stored electronically in a computer system.

### 1. What is a table in SQL?
A table is a collection of related data in rows and columns. It's like a spreadsheet in a database.

### 1. What is a primary key?
A primary key is a unique identifier for each record in a table. It must contain unique values and cannot be NULL.

### 1. What is a foreign key?
A foreign key links two tables together. It is a field in one table that refers to the primary key in another table.

### 1. What is the difference between DELETE and TRUNCATE?
DELETE removes specific rows based on a condition and can be rolled back. TRUNCATE removes all rows from a table and cannot be rolled back.

### 1. What is a JOIN in SQL?
A JOIN is used to combine rows from two or more tables based on a related column.

### 1. What is INNER JOIN?
INNER JOIN returns records that have matching values in both tables.

### 1. What is a LEFT JOIN?
LEFT JOIN returns all records from the left table and the matched records from the right table. If there’s no match, it returns NULL.

### 1. What is an INDEX?
An INDEX improves the speed of data retrieval operations on a database table by allowing faster access to rows.

### 1. What is GROUP BY used for?
GROUP BY is used to group rows that have the same values into summary rows, often used with aggregate functions like COUNT(), SUM(), etc.

### 1. What are aggregate functions in SQL?
Aggregate functions perform a calculation on a set of values and return a single value. Common ones are COUNT(), SUM(), AVG(), MIN(), and MAX().

### 1. What is a NULL value?
A NULL value represents missing or unknown data in a column.

### 1. How do you select all columns from a table?
Use SELECT * FROM table_name;.

### 1. How do you filter data in SQL?
You use the WHERE clause to filter records. Example: SELECT * FROM table_name WHERE condition;.

### 1. What is the difference between HAVING and WHERE?
WHERE filters rows before grouping, and HAVING filters groups after the grouping has been done.

### 1. What does ORDER BY do?
ORDER BY is used to sort the result set in ascending (ASC) or descending (DESC) order.

### 1. What is UNION in SQL?
UNION combines the result of two SELECT statements, removing duplicates.

### 1. What is the difference between UNION and UNION ALL?
UNION removes duplicates, while UNION ALL keeps all duplicates.

### 1. What is a subquery?
A subquery is a query inside another query. It is used to retrieve data to be used in the main query.
