# SQL Homework - Employee Database: A Mystery in Two Parts :computer:

<p align='center'>
<a><img height="400" src="https://github.com/JavierSada/sql-challenge/blob/main/Images/postgresql-icon-12.jpg"></a>
</p>

## Background

It is a beautiful spring day, and it is two weeks since you have been hired as a new data engineer at Pewlett Hackard. Your first major task is a research project on employees of the corporation from the 1980s and 1990s. All that remain of the database of employees from that period are six CSV files.

In this assignment, you will design the tables to hold data in the CSVs, import the CSVs into a SQL database, and answer questions about the data. In other words, you will perform:

1. Data Engineering
2. Data Modeling
3. Data Analysis

#### Data Modeling

Inspect the CSVs and sketch out an ERD of the tables; 

<p align='center'>
<a><img height="600" src="https://github.com/JavierSada/sql-challenge/blob/main/Images/QuickDBD.PNG"></a>
</p>

#### Data Engineering

* Use the information you have to create a table schema for each of the six CSV files. Remember to specify data types, primary keys, foreign keys, and other constraints.

  * For the primary keys check to see if the column is unique, otherwise create a [composite key](https://en.wikipedia.org/wiki/Compound_key). Which takes to primary keys in order to uniquely identify a row.
  * Be sure to create tables in the correct order to handle foreign keys.

* Import each CSV file into the corresponding SQL table. **Note** be sure to import the data in the same order that the tables were created and account for the headers when importing to avoid errors.

