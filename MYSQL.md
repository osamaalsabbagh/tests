## MySQL

#### Q1. When you have a subquery inside of the main query, which query is executed first?

- [ ] The subquery is never executed. Only the main query is executed.
- [ ] They are executed at the same time
- [ ] the main query
- [x] the subquery

#### Q2. You need to export the entire database, including the database objects, in addition to the data. Which command-line tool do you use?

- [ ] mysqlexport
- [ ] mysqladmin
- [x] mysqldump
- [ ] mysqld

#### Q3. You must ensure the accuracy and reliability of the data in your database. You assign some constraints to limit the type of data that can go into a table. What type of constraints are you assigning?

- [ ] row level
- [ ] database level
- [x] column level
- [ ] function level

#### Q4. If you were building a table schema to store student grades as a letter (A, B, C, D, or F) which column type would be the best choice?

- [x] ENUM
- [ ] OTEXT
- [ ] VARCHAR
- [ ] LONGTEXT

#### Q5. Which MySQL command shows the structure of a table?

- [ ] INFO table;
- [ ] SHOW table;
- [ ] STRUCTURE table;
- [x] DESCRIBE table;


#### Q6. Which MySQL command modifies data records in a table?

- [x] UPDATE
- [ ] MODIFY
- [ ] CHANGE
- [ ] ALTER

#### Q7. What is the best type of query for validating the format of an email address in a MySQL table?

- [ ] a SQL query using partitions
- [ ] a SQL query using IS NULL
- [x] a SQL query using a regular expression
- [ ] a SQL query using LTRIM Or RTRIM

#### Q8. In MySQL, queries are always followed by what character?

- [ ] line break
- [ ] colon
- [x] semicolon
- [ ] period

#### Q9. How can you remove a record using MySQL?

- [ ] ALTER
- [x] DELETE FROM
- [ ] REMOVE
- [ ] REMOVE FROM

#### Q10. Which choice is NOT a statement you would use to filter data?

- [x] GROUP BY
- [ ] WHERE
- [ ] LIMIT
- [ ] LIKE

#### Q11. What does the following SQL statement return?

`SELECT * FROM Employees WHERE EmployeeName LIKE 'a%'`

- [ ] It returns records in the Employees table where the value in the EmployeeName column doesn't have an "a".
- [x] It returns records in the Employees table where the value in the EmployeeName column starts with "a".
- [ ] It returns records in the Employees table where the value in the EmployeeName column has an "a".
- [ ] It returns records in the Employees table where the value in the EmployeeName column ends with "a".

#### Q12. If you need to order a table of movies by name, which query will work?

- [ ] SELECT \* FROM movies GROUP BY name
- [x] SELECT \* FROM movies ORDER BY name
- [ ] SELECT \* FROM movies ORDER TABLE by name
- [ ] SELECT \* FROM movies FILTER BY name

#### Q13. You are working with very large tables in your database. Which SQL clause do you use to prevent exceedingly large query results?

- [ ] UNIQUE
- [x] LIMIT
- [ ] DISTINCT
- [ ] CONSTRAINT

#### Q14. How can you filter duplicate data while retrieving records from a table?

- [x] DISTINCT
- [ ] WHERE
- [ ] LIMIT
- [ ] AS

#### Q15. What is the difference between DROP and TRUNCATE?

- [ ] They both refer to the same operation of deleting the table completely.
- [ ] They both refer to the same operation of clearing the table, but keeping its definition intact.
- [ ] TRUNCATE deletes table completely, removing its definition as well. DROP clears the table but does not delete the definition.
- [x] DROP deletes table completely, removing its definition as well. TRUNCATE clears the table but does not delete the definition.