# SQL Notes - Basics

## Basic concepts

DBMS: Database Management System

C.R.U.D stands for Create, Read, Update and Delete. 

Two types of databases: 
1. Relational Databases (SQL)
2. Non-Relational (noSQL)

SQL: Structured query language for interacting with Relational DBMS. 

SQL is basically 4 types of languages in one: 
- DQL: Data Query Language
- DDL: Data Definition Lanugage
  - Used for defining database schemas
- DCL: Data Control Language
  - Used to control access to data in the database
- DML: Data Manipulation Language
  - Used to insert, delete or update data in the database

Query: Requests made to the DBMS for specific information. 

Primary key: A special relational database table column (or combination of columns) designated to uniquely identify each table record. 

Foreign key: A column or group of columns in a relational database table that provides a link between data in two tables. A table can have multiple foreign keys that refer to different tables respectively. 

Composite key: A candidate key that consists of two or more columns that together uniquely identify a row.

ER: Entity relationship. 

## Common datatypes in MySQL

| Datatype | Description |
| ---------------- | ----------- |
| VARCHAR(size) | The size parameter specifies the maximum length in characters - 0 to 65535 |
| INT(size) | The size parameter specifies the maximum display width |
| DECIMAL(size, d) | The total number of digits is specified in size. The number of digits after the decimal point is specified in d. Default: size = 10, d = 0 |
| BLOB(size) | Binary Large Objects |
| DATE | Format: YYYY-MM-DD |
| TIMESTAMP | Format: YYYY-MM-DD hh:mm:ss |



















































