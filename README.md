# G2_DBMS


EXP NO 1: DATA DEFINITION LANGUAGE COMMANDS IN RDBMS

AIM :
To create a student database and execute DDL queries using SQL.

DDL (Data Definition Language) :

DDL or Data Definition Language actually consists of the SQL commands that can be used to define the database schema. It simply deals with descriptions of the database schema and is used to create and modify the structure of database objects in the database. DDL is a set of SQL commands used to create, modify, and delete database structures but not data. These commands are normally not used by a general user, who should be accessing the database via an application.

List of DDL commands :
CREATE: This command is used to create the database or its objects (like table, index, function, views, store procedure, and triggers).



DROP: This command is used to delete objects from the database.



ALTER: This is used to alter the structure of the database.



TRUNCATE: This is used to remove all records from a table, including all spaces allocated for the records are removed.



RENAME: This is used to rename an object existing in the database.

Query :
Create a table student with the following fieds rollno,name,age,address,phoneno.



SQL QUERY :
create table student(rollno numeric(10),name char(10),age numeric(5),address varchar(25),phoneno numeric(15));


OUTPUT :

![image](https://github.com/SAKTHISWAR/G2_DBMS/blob/main/d1.png)


Query :
Change the above student table by adding another attribute department.

SQL QUERY :
alter table student add department varchar(15);


OUTPUT :

![image](https://github.com/SAKTHISWAR/G2_DBMS/blob/main/d2.png)

QUERY :
Drop the student table.


SQL QUERY :
drop table student;


OUTPUT :

![image](https://github.com/SAKTHISWAR/G2_DBMS/blob/main/d3.png)

QUERY :
Delete the student table using truncate keyword.


SQL QUERY :
truncate table student;


OUTPUT :

![image](https://github.com/SAKTHISWAR/G2_DBMS/blob/main/d4.png)

QUERY :
Rename the student table to mystudent.


SQL QUERY :
rename table student to mystudent;


OUTPUT :

![image](https://github.com/SAKTHISWAR/G2_DBMS/blob/main/d5.png)



RESULT :
The queries got the output and statifies the given question.
