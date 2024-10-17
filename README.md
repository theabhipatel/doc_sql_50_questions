# SQL 50 basic questions and answers
---
by Theabhipatel
---

### 1. What is SQL?
SQL stands for Structured Query Language. It is used to communicate with databases for creating, retrieving, updating, and deleting data.

### 2. What is a database?
A database is an organized collection of structured data, usually stored electronically in a computer system.

### 3. What is a table in SQL?
A table is a collection of related data in rows and columns. It's like a spreadsheet in a database.

### 4. What is a primary key?
A primary key is a unique identifier for each record in a table. It must contain unique values and cannot be NULL.

### 5. What is a foreign key?
A foreign key links two tables together. It is a field in one table that refers to the primary key in another table.

### 6. What is the difference between DELETE and TRUNCATE?
DELETE removes specific rows based on a condition and can be rolled back. TRUNCATE removes all rows from a table and cannot be rolled back.

### 7. What is a JOIN in SQL?
A JOIN is used to combine rows from two or more tables based on a related column.

### 8. What is INNER JOIN?
INNER JOIN returns records that have matching values in both tables.

### 9. What is a LEFT JOIN?
LEFT JOIN returns all records from the left table and the matched records from the right table. If there’s no match, it returns NULL.

### 10. What is an INDEX?
An INDEX improves the speed of data retrieval operations on a database table by allowing faster access to rows.

---

### 11. What is GROUP BY used for?
GROUP BY is used to group rows that have the same values into summary rows, often used with aggregate functions like COUNT(), SUM(), etc.

### 12. What are aggregate functions in SQL?
Aggregate functions perform a calculation on a set of values and return a single value. Common ones are COUNT(), SUM(), AVG(), MIN(), and MAX().

### 13. What is a NULL value?
A NULL value represents missing or unknown data in a column.

### 14. How do you select all columns from a table?
Use SELECT * FROM table_name;.

### 15. How do you filter data in SQL?
You use the WHERE clause to filter records. Example: SELECT * FROM table_name WHERE condition;.

### 16. What is the difference between HAVING and WHERE?
WHERE filters rows before grouping, and HAVING filters groups after the grouping has been done.

### 17. What does ORDER BY do?
ORDER BY is used to sort the result set in ascending (ASC) or descending (DESC) order.

### 18. What is UNION in SQL?
UNION combines the result of two SELECT statements, removing duplicates.

### 19. What is the difference between UNION and UNION ALL?
UNION removes duplicates, while UNION ALL keeps all duplicates.

### 20. What is a subquery?
A subquery is a query inside another query. It is used to retrieve data to be used in the main query.

---

### 21. What is DISTINCT in SQL?
DISTINCT is used to remove duplicate rows in the result set. Example: SELECT DISTINCT column_name FROM table_name;.

### 22. What is a DEFAULT constraint?
A DEFAULT constraint sets a default value for a column if no value is provided during the insert.

### 23. What is AUTO_INCREMENT?
AUTO_INCREMENT allows a column to automatically generate a unique number when a new record is inserted.

### 24. What is a VIEW in SQL?
A VIEW is a virtual table based on the result of a SQL query. It doesn't store data but provides a way to simplify complex queries.

### 25. What is the ALTER statement used for?
The ALTER statement is used to modify an existing database object, such as a table. You can add, delete, or modify columns.

### 26. What is the difference between VARCHAR and CHAR?
VARCHAR is a variable-length string, whereas CHAR is a fixed-length string. CHAR pads the data with spaces if it’s shorter than the defined length.

### 27. What is normalization?
Normalization is the process of organizing data to reduce redundancy and improve data integrity in a database.

### 28. What is denormalization?
Denormalization is the process of adding redundancy to a database for performance improvement, typically by combining tables.

### 29. What are the different types of JOINs in SQL?
The main types are INNER JOIN, LEFT JOIN, RIGHT JOIN, FULL JOIN, and CROSS JOIN.

### 30. What is a RIGHT JOIN?
RIGHT JOIN returns all records from the right table and the matched records from the left table. If there is no match, NULL values are returned for the left table.

---

### 31. What is the difference between HAVING and WHERE with GROUP BY?
WHERE is used before GROUP BY to filter rows, while HAVING is used after GROUP BY to filter groups.

### 32. What is a TRIGGER in SQL?
A TRIGGER is a set of SQL commands that automatically executes when a specific event occurs in a table, like insert, update, or delete.

### 33. What is CASE in SQL?
CASE is used to implement conditional logic in SQL queries. It works like an IF-THEN-ELSE statement.

### 34. What is COALESCE in SQL?
COALESCE returns the first non-NULL value in a list of arguments.

### 35. What is a stored procedure?
A stored procedure is a prepared SQL code that can be saved and reused. It can accept parameters and perform operations on the database.

### 36. What is the difference between DROP, TRUNCATE, and DELETE?
DELETE removes rows based on conditions and can be rolled back, TRUNCATE removes all rows without conditions and can't be rolled back, and DROP removes the entire table or database.

### 37. What is ROLLBACK in SQL?
ROLLBACK is used to undo changes made by a transaction if something goes wrong.

### 38. What is a COMMIT in SQL?
COMMIT saves all the changes made during a transaction permanently to the database.

### 39. What is a UNIQUE constraint?
A UNIQUE constraint ensures all values in a column are different. It allows NULLs, but only one NULL.

### 40. What is the EXISTS keyword in SQL?
EXISTS is used to check if a subquery returns any results. If the subquery returns at least one row, EXISTS returns true.

---

### 41. What is a transaction in SQL?
A transaction is a sequence of one or more SQL operations executed as a single unit of work. It ensures data consistency.

### 42. What is ACID in SQL?
ACID stands for Atomicity, Consistency, Isolation, and Durability. It ensures reliable processing of database transactions.

### 43. What is BETWEEN in SQL?
BETWEEN is used to filter the result set within a specific range. Example: SELECT * FROM table_name WHERE column_name BETWEEN value1 AND value2;.

### 44. What is a correlated subquery?
A correlated subquery depends on the outer query for its values. It is executed for each row processed by the outer query.

### 45. What is a self-join?
A self-join is when a table is joined with itself. It’s useful when comparing rows within the same table.

### 46. What is the difference between COUNT(*) and COUNT(column_name)?
COUNT(*) counts all rows, including those with NULLs. COUNT(column_name) only counts rows where the specified column is not NULL.

### 47. What is a cursor in SQL?
A cursor is a database object used to retrieve, manipulate, and traverse through a result set row-by-row.

### 48. What is ISNULL in SQL?
ISNULL is used to replace NULL values with a specified value. Example: SELECT ISNULL(column_name, 'default_value') FROM table_name;.

### 49. What is a schema in SQL?
A schema is a collection of database objects like tables, views, indexes, and procedures, organized under a database.

### 50. What is a composite key?
A composite key is a combination of two or more columns in a table that together serve as a unique identifier for rows.
