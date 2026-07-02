# CIS530: Creating Relational Table Schema and Populating with Data

> **Complete Solution & Source Code Available Here:** [[INSERT_PRODUCT_LINK]]([INSERT_PRODUCT_LINK])

This CIS530 Lab Assignment 1 guides students through creating a relational database schema and populating it with data using SQL DDL and DML statements in MS SQL Server. A complete, tested solution is provided, demonstrating database and table creation for Employee and Department entities with specific data.

## Assignment Instructions

CIS530 Lab Assignment 1
Creating Relational Table Schema and Populating with Data
1. Creating a database COMPANY and tables for 2 Entities in the COMPANY database schema using SQL (Data Definition Language) statements in a MS SQL Server.
The COMPANY database schema and data record values are depicted in the Figure at the end of this lab. The Core data for this database is shown at the end of this lab.
In this lab, create a database named Company and create two tables Employee and Department with schema as shown at the end of this Lab specification.
Note that you are asked to create the scheme (Meta data) of two tables in the Company database and populate the tables with the given data states (values of each record).
In SQL Management Studio you installed with SQL Server, Create two tables Employee, Department (without any relationship or constraints) as shown in the tables at the end of this Lab specification with writing Data Manipulation Language (DDL) commands.
The typical SQL commands (DDL) to create a table and Select from the created table for this task are like the following example.
Create Database...;
Drop Database ...;
Use database_name;
Create table Employee (....);
Delete table...;
Drop table Employee;
Select * From Employee;
Create table Department (....);
Select * From Department;
2. Populate the two tables Employee and Department with data shown in the Figure at the end of this lab by writing a DML (Data Manipulating Language) - Insert Statement.
INSERT INTO EMPLOYEE VALUES('John','B','Smith','123456789','9-Jan-55','731Fondren, Houston, TX','M',30000,'987654321',5);
Insert Into Department Values ('Headquarters','1','888665555','19-Jun-71');
3. Copy and paste of all your SQL DDL and DML Statements into a Word document. Add your SQL Management Studio Screenshots (Ctrl-Alt-PrintScr) showing your each DDL and DML statement execution and the results of each "Create table” followed by “Select” statements, and "Insert" followed by “Select”.
4. Document your work. Add comments explaining the meaning of each component included in the report. Use the following header
CIS430- Lab Assignment 1
Name: your-name-goes-here
ID: Your-CSU-number
CIS530 Lab Assignment 1
Object: Creating a Relational Database Schema Using SQL and SQL Server
The rest of your report goes here...
CIS530 Lab Assignment 1
SQL Statements you need to look up for use for this assignment:
CREATE Database Company...;
Go
Use Company;
CREATE TABLE EMPLOYEE (...);
CREATE TABLE DEPARTMENT (...);
DELETE FROM EMPLOYEE...;
DROP TABLE EMPLOYEE;
DROP TABLE DEPARTMENT;
SELECT * FROM DEPARTMENT;
SELECT * FROM EMPLOYEE;
INSERT INTO EMPLOYEE VALUES...;
SELECT * FROM EMPLOYEE;
Insert Into Department Values...;
SELECT * FROM DEPARTMENT;
r:
For Data Types in MS SQL Server :
http://msdn.microsoft.com/en-us/library/ms187752.aspx
For Data Types in Oracle Database Server :
http://docs.oracle.com/cd/B28359 01/server.111/b28318/datatype.htm#i2093
COMPANY DATABASE
EMPLOYEE
CIS530 Lab Assignment 1
FNAME MINIT LNAME SSN BDATE ADDRESS SEX SALARY SUPERSSN DNO
John B Smith 123456789 9-Jan-55 731 Fondren, Houston, TX M 30000 987654321 5
Franklin T Wong 333445555 8-Dec-45 638 Voss, Houston, TX M 40000 888665555 5
Joyce A English 453453453 31-Jul-62 5631 Rice, Houston, TX F 25000 333445555 5
Ramesh K Narayan 666884444 15-Sep-52 975 Fire Oak, Humble, TX M 38000 333445555 5
James E Borg 888665555 10-Nov-27 450 Stone, Houston, TX M 55000 1
Jennifer S Wallace 987654321 20-Jun-31 291 Berry, Bellaire, TX F 43000 888665555 4
Ahmad V Jabbar 987987987 29-Mar-59 980 Dallas, Houston, TX M 25000 987654321 4
Alicia J Zelaya 999887777 19-Jul-58 3321 Castle, SPring, TX F 25000 987654321 4
DEPARTMENT
DNAME DNUMBER MGRSSN MGRSTARTDATE
Headquarters 1 888665555 19-Jun-71
Administration 4 987654321 1-Jan-85
Research 5 333445555 22-May-78
Automation 7 123456789 6-Oct-05

## Keywords & Metadata

`SQL`, `MS SQL Server`, `Data Definition Language`, `DDL`, `Data Manipulation Language`, `DML`, `CREATE DATABASE`, `CREATE TABLE`, `INSERT INTO`, `SELECT FROM`, `Employee table`, `Department table`, `Relational database`, `Database population`

<!--
Metadata for search discovery and indexing optimization:
Course: CIS530
Topic: Creating Relational Table Schema and Populating with Data
Summary: This CIS530 Lab Assignment 1 guides students through creating a relational database schema and populating it with data using SQL DDL and DML statements in MS SQL Server. A complete, tested solution is provided, demonstrating database and table creation for Employee and Department entities with specific data.
Keywords: SQL, MS SQL Server, Data Definition Language, DDL, Data Manipulation Language, DML, CREATE DATABASE, CREATE TABLE, INSERT INTO, SELECT FROM, Employee table, Department table, Relational database, Database population
-->

## Contact & Support

Stuck on this assignment or need help with a similar project? 
Reach out to xujuncoding for tutoring, code explanations, and custom coding assistance at: xujuncoding@gmail.com
