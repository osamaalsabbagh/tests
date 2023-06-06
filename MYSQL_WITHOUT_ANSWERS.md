## MySQL

#### Q1. When you have a subquery inside of the main query, which query is executed first?

**A)** The subquery is never executed. Only the main query is executed.  
**B)** They are executed at the same time  
**C)** the main query  
**D)** the subquery  

<br>

#### Q2. You need to export the entire database, including the database objects, in addition to the data. Which command-line tool do you use?

**A)** mysqlexport  
**B)** mysqladmin  
**C)** mysqldump  
**D)** mysqld  

<br>

#### Q3. You must ensure the accuracy and reliability of the data in your database. You assign some constraints to limit the type of data that can go into a table. What type of constraints are you assigning?

**A)** row level  
**B)** database level  
**C)** column level  
**D)** function level  

<br>

#### Q4. If you were building a table schema to store student grades as a letter (A, B, C, D, or F) which column type would be the best choice?

**A)** ENUM  
**B)** OTEXT  
**C)** VARCHAR  
**D)** LONGTEXT  

<br>

#### Q5. Which MySQL command shows the structure of a table?

**A)** INFO table;  
**B)** SHOW table;  
**C)** STRUCTURE table;  
**D)** DESCRIBE table;  


<br>

#### Q6. Which MySQL command modifies data records in a table?

**A)** UPDATE  
**B)** MODIFY  
**C)** CHANGE  
**D)** ALTER  

<br>

#### Q7. What is the best type of query for validating the format of an email address in a MySQL table?

**A)** a SQL query using partitions  
**B)** a SQL query using IS NULL  
**C)** a SQL query using a regular expression  
**D)** a SQL query using LTRIM Or RTRIM  

<br>

#### Q8. In MySQL, queries are always followed by what character?

**A)** line break  
**B)** colon  
**C)** semicolon  
**D)** period  

<br>

#### Q9. How can you remove a record using MySQL?

**A)** ALTER  
**B)** DELETE FROM  
**C)** REMOVE  
**D)** REMOVE FROM  

<br>

#### Q10. Which choice is NOT a statement you would use to filter data?

**A)** GROUP BY  
**B)** WHERE  
**C)** LIMIT  
**D)** LIKE  

<br>

#### Q11. What does the following SQL statement return?

`SELECT * FROM Employees WHERE EmployeeName LIKE 'a%'`

**A)** It returns records in the Employees table where the value in the EmployeeName column doesn't have an "a".  
**B)** It returns records in the Employees table where the value in the EmployeeName column starts with "a".  
**C)** It returns records in the Employees table where the value in the EmployeeName column has an "a".  
**D)** It returns records in the Employees table where the value in the EmployeeName column ends with "a".  

<br>

#### Q12. If you need to order a table of movies by name, which query will work?

**A)** SELECT \* FROM movies GROUP BY name  
**B)** SELECT \* FROM movies ORDER BY name  
**C)** SELECT \* FROM movies ORDER TABLE by name  
**D)** SELECT \* FROM movies FILTER BY name  

<br>

#### Q13. You are working with very large tables in your database. Which SQL clause do you use to prevent exceedingly large query results?

**A)** UNIQUE  
**B)** LIMIT  
**C)** DISTINCT  
**D)** CONSTRAINT  

<br>

#### Q14. How can you filter duplicate data while retrieving records from a table?

**A)** DISTINCT  
**B)** WHERE  
**C)** LIMIT  
**D)** AS  

<br>

#### Q15. What is the difference between DROP and TRUNCATE?

**A)** They both refer to the same operation of deleting the table completely.  
**B)** They both refer to the same operation of clearing the table, but keeping its definition intact.  
**C)** TRUNCATE deletes table completely, removing its definition as well. DROP clears the table but does not delete the definition.  
**D)** DROP deletes table completely, removing its definition as well. TRUNCATE clears the table but does not delete the definition.  