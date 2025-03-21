# SQL

What is sql?

SQL is a standard database language used to create,maintain,destroy,update and retrive data from relational databases.

Day1:
------------
1.CREATING DATABASE:
SYNTAX:
--------
CREATE DATABASE database_name;

->it is used to create new database within your SQL ecosystem.
-> **NOTE** 
1. Spaces are not occupied in database name,but it will accept undrscore(_).
2. Data base name should be UNIQUE
3. database name is CASE-SENSITIVE
4. Maximum length of database name is 128 characters.
5. 


2.LIST databases in SQL:
----------------------
->To know the list of databases that exist in our system then we use the following Command 

syntax:
---------
"SHOW DATABASES"

3.USE database in SQL:
------------------------
Once database is created we can switch to that database to begin adding tables,inserting data and performing queries.

syntax:
--------
USE database_name

DELETE a database in SQL:
---------------------------
->To delete a database use the following command. this command will delete a database and all its contents.It permanently deletes the database and all of its data.

Syntax:
--------
DROP DATABASE database_name

CREATING TABLES and Adding data:
-----------------------------------
->To create a table use the following command

Syntax:
--------
CREATE TABLE table_name
(
Column1 datatype(size),    //names of the columns in the table
column2 datatype(size),
.
.
columnN datatype(size)
);

To Insert data into the created table:
--------------------------------------
->To insert data into table use the following Command

syntax:
--------
INSERT INTO table_name(column1,column2,....)VALUES(value1,value2,.....)
