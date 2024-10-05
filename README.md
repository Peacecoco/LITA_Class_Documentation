# LITA_Class_Documentation

### Project Outline
---
[Project Topic](#project-topic)

[Project Overview](#project-overview)

[Data Analysis](data-analysis)

[Data Sources](#data-sources)

[Tools Used](#tools-used)

[Data Cleaning and Perparations](#datacleaning&preparations)

[Microsoft Excel](#micrsoft-excel)


### Project Topic -  Data Analysis
---

### Project Overview
---
This project focuses on analyzing data to uncover patterns, trends and insights that helps to solve problems and support decision making. It also focuses on the tools used and how these tools can be used in analyzing data.

## Data Analysis
---
Data Analysis involves inspecting, cleaning, transforming and modelling data to discover useful information, draw conclusions and support decision making.

### Skills Required
---
- Technical Skills
- Data Visualization
- Critical Thinking
- Data Wrangling and Cleaning
- Communication Skills

### Data Sources
---
Data are gotten from different open sources online. Some are:
- [Kaggle](https://www.kaggle.com/datasets)
- [Google Dataset Search](https://datasetsearch.research.goggle.com/)
- [Data.gov](https://www.data.gov/)
- [Quandl](https://www.quandl.com/)

### Tools Used
---
- Microsoft Excel [Download Here](https://www.microsoft.com)
  1. For Data Cleaning
  2. For Data Analysis
  3. For Data Storage
  4. For Data Visualization
- SQL - Structured Query Language for Quering of Data [Download Here](https://www.microsoft.com/en-us/sql-server/sql-server-downloads)
- PowerBI - Power Business Intelligence for visualizing and sharing insights from data [Download Here](https://powerbi.microsoft.com/desktop/)
- GitHub for Portfolio Building [Download Here](https://github.com/apps/desktop)

### Microsoft Excel
---
This is a spreadsheet application used to store data and analyse data. In microsoft excel, there are:
- Data Entry
- Data Formatting
- Data Validation

### Excel Function
---
There are some basic excel function learnt in class which include:
- SUM
- AVERAGE
- MAX
- MIN
- COUNT / COUNTA
- LARGE
- SMALL
- LEFT, RIGHT & MID Function
- Random Function
- Trim Function
- Cases Function
- V-Lookup
- Conditional Function

### Data Summarization
---
Pivot table is a data summarizing tool used to manage a report in excel. It can be prepared from a table, range or from an internal data source.

### Structured Query Language (SQL)
---
SQL is a standard language for relational database system. It is used for storing, retrieving and managing data in Relaational Database Management System (RDBMS). It allows user to relate databases and tables. It also allows user to query the database in a number of ways, using English-like statements. Examples are:
- MYSQL
- Oracle
- Postgre SQL
- MS Acess

5 Types of SQL Commands were taught which are:
  - DDL: Data Manipulation Language
  - DML: Data Manipulation Language
  - DCL: Data Control Language
  - TCL: Transaction Control Language
  - DQL: Data Query Language
  
The RDBM used in class was SQL Server. Here are some queries used in SQL Server:
```SQL
create database LITA_DB

CREATE TABLE Employee (
staffid varchar (10) not null,
FirstName varchar (255) NOT NULL,
SecondName varchar (255),
Gender varchar (10),
Date_of_Birth date,
HireDate datetime,
primary key (staffid)
)
select * from Employee

insert into Employee (staffid, firstname, secondname, gender,Date_of_Birth, hiredate)
values ( 'AB401', 'ayan', 'olakun', 'female', '1992-08-22', '2018-02-09'),
( 'AB212', 'okorie', 'mercy', 'female','1988-10-09', '2018-10-09'),
( 'AB223', 'joshua', 'chukwuemeka', 'male','1980-10-09', '2022-02-09'),
( 'AB234', 'sanni', 'ibrahim', 'male','1958-10-09', '2019-09-23'),
( 'AB254', 'mercy', 'olanipekun', 'female','1982-10-09', '2020-02-09'),
( 'AB249', 'johnson', 'mercy', 'female','1982-10-09', '2019-12-09'),
( 'AB298', 'ayomide', 'halleluyah', 'female', '1982-10-09','2018-07-11'),
( 'AB260', 'deborah', 'justin', 'female','1982-10-09', '2018-02-09'),
( 'AB281', 'wale', 'olanipekun', 'male','1982-10-09', '2018-02-09')

-------to drop table --------

drop table employee

----delete sql command--

delete from employee
where staffid  = 'ab281'

-----truncate sql command

truncate table employee
```
The above queries have their specific function in the SQL Server database.

### Data Visualization
---
Data visualization is the process of representing data in a graphical or pictorial formats such as charts, graphs, maps and dashboards. It is important because it breaks down complex data and extracts meaningful insights in a more digestible way.
An example of a data visualization:





  
