# Employee Database-SQL

![image](https://github.com/AnaTipps/SQL-challenge/assets/131827518/7740da13-220d-4704-885e-b30bcb0d8c77)


## Background

This project researches people whom the company (ewlett Hackard, a fictional company) employed during the 1980s and 1990s. All that remains of the employee database from that period are six CSV files.

For this project, tables to hold the data from the CSV files were created, by importing the CSV files for each table into a SQL database, and then answer questions about the data. 

For this project data modeling, data engineering, and data analysis, respectively was performed.

## 1. Data Modeling

For this secction CSV files were inspected, and then an Entity Relationship Diagram of the tables were sketched. By using this technique six employee database entities or tables are identified, these entities are `employees`, `departments`, `titles`, `department managers`, `department employees` and , `salaries`. The the data type of the entities also presented. 

The diagram looks as follows: 

![image](https://github.com/AnaTipps/SQL-challenge/assets/131827518/d3f9ed57-7bbb-4bb1-a4ac-7e0319af80d2)

## 2. Data Engineering

To be able to interact with information found in the imported CVS files a table schema for each of the six CSV files was created, and the data types, primary keys, foreign keys, and constraints also developed.  The order of the table is based on the primary, and foreign arrangements. 
 

A full table query can be found in the file **EmployeeSchema**.

**Note** to import each  CSV file into the corresponding SQL table the order of creation should be followed, this to avoid errors. 


## 3. Data Analysis

After completing the importing process a Postgresql analysiss was perfomed and full query can be found in the file **EmployeeQueries**



