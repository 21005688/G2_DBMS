# EXP NO 1: DATA DEFINITION LANGUGE COMMANDS IN RDBMS

## AIM:
To create a student database and execute DDL queries using SQL.


## DDL (Data Definition Language)
<div align="justify">
DDL or Data Definition Language actually consists of the SQL commands that can be used to define the database schema. It simply deals with descriptions of the database schema and is used to create and modify the structure of database objects in the database. DDL is a set of SQL commands used to create, modify, and delete database structures but not data. These commands are normally not used by a general user, who should be accessing the database via an application.
</div>
 
## List of DDL commands: 
<div align="justify">
CREATE: This command is used to create the database or its objects (like table, index, function, views, store procedure, and triggers).
DROP: This command is used to delete objects from the database.
ALTER: This is used to alter the structure of the database.
TRUNCATE: This is used to remove all records from a table, including all spaces allocated for the records are removed.
RENAME: This is used to rename an object existing in the database.
</div>

## Query:
### 1) Create a table student with the following fieds rollno,name,age,address,phoneno.

### SQL QUERY: 





### OUTPUT:

### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
![d1](https://github.com/21005688/G2_DBMS/assets/94747031/84c0eaff-ec84-4650-81c2-9cadadcd9495)

### OUTPUT:
![d2](https://github.com/21005688/G2_DBMS/assets/94747031/50e84924-40e2-47f7-9c6e-1f98a4288777)


### 3) Drop the student table

### SQL QUERY: 
DROP TABLE student;


### OUTPUT:

![d3](https://github.com/21005688/G2_DBMS/assets/94747031/9ac19bf2-2b6e-498a-8b95-44c11b7d0af8)


### 4) Delete the student table using truncate keyword

### SQL QUERY: 
TRUNCATE TABLE student;


### OUTPUT:

![d4](https://github.com/21005688/G2_DBMS/assets/94747031/bdf35f6e-751b-46dc-b789-c45f1ea914ae)



### 5) Rename the student table to mystudent

### SQL QUERY: 
ALTER TABLE student RENAME TO mystudent;


### OUTPUT:
![d5](https://github.com/21005688/G2_DBMS/assets/94747031/1a1ec98a-48d0-4505-b21c-bb6cdcf1cddd)


### RESULT:
Thus a student database has been created and DDL queries are executed successfully.
