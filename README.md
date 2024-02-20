# Sql_Code
A collection of my sql files
SELECT * FROM table_name 

SELECT column1, column2 FROM table_name; 

SELECT DISTINCT column_name FROM table_name; SELECT * FROM table_name WHERE condition; 

SELECT * FROM table_name ORDER BY column_name ASC; 
SELECT * FROM table_name ORDER BY column_name DESC; 
SELECT * FROM table_name LIMIT 10;
SELECT * FROM table_name WHERE condition1 AND condition2 
SELECT * FROM table_name WHERE condition1 OR condition2; 

SELECT COUNT(*) FROM table_name; Group rows based on a column: sql Copy code 
SELECT column_name, COUNT(*) FROM table_name GROUP BY column_name; 

SELECT column_name, COUNT(*) FROM table_name GROUP BY column_name HAVING COUNT(*) > 5; 

SELECT * FROM table1 JOIN table2 ON table1.column_name = table2.column_name;  

SELECT * FROM table1 LEFT JOIN table2 ON table1.column_name = table2.column_name;

SELECT * FROM table1 RIGHT JOIN table2 ON table1.column_name = table2.column_name; 

SELECT * FROM table1 INNER JOIN table2 ON table1.column1 = table2.column1 AND table1.column2 = table2.column2; 

SELECT * FROM table1 LEFT JOIN table2 ON table1.column1 = table2.column1 AND table1.column2 = table2.column2; 

UPDATE table_name SET column_name = new_value WHERE condition; 

DELETE FROM table_name WHERE condition; 

INSERT INTO table_name (column1, column2) VALUES (value1, value2); 

 SELECT AVG(column_name) FROM table_name; 

SELECT SUM(column_name) FROM table_name; 

SELECT MIN(column_name) FROM table_name; 

SELECT MAX(column_name) FROM table_name; ALTER TABLE table_name RENAME COLUMN old_name TO new_name; 

ALTER TABLE table_name ADD new_column datatype; 
 
ALTER TABLE table_name DROP COLUMN column_name; CREATE TABLE new_table (     column1 datatype,     column2 datatype,     ... ); 

DROP TABLE table_name; 
![image](https://github.com/PanchputreKomal/Sql_Code/assets/94497134/664a4b4a-cfec-421d-b9bb-42dfa875d971)
