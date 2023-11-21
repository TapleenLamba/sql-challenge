# sql-challenge

This repository contains a data engineering project focused on researching employees at Pewlett Hackard during the 1980s and 1990s. The project involves data modeling, data engineering, and data analysis using six CSV files.

**Data Modeling:**
ER Diagram:
Inspect the CSV files and utilize tools like QuickDBD to sketch an Entity-Relationship (ER) diagram for the tables.

**Data Engineering:**

1.Table Schemas:
-Create a table schema for each CSV file, specifying data types, primary keys, foreign keys, and other constraints.


-Verify the uniqueness of primary keys or create composite keys if necessary.
Establish tables in the correct order to accommodate foreign keys.

2.Data Import:
Import each CSV file into its corresponding SQL table using appropriate scripts.

**Data Analysis:**

Queries:


Execute the following queries for data analysis:


List the employee number, last name, first name, sex, and salary of each employee.


List the first name, last name, and hire date for employees hired in 1986.


List the manager of each department along with their department number, department name, employee number, last name, and first name.


List the department number for each employee along with their employee number, last name, first name, and department name.


List first name, last name, and sex of each employee named Hercules with last names starting with the letter B.


List each employee in the Sales department, including employee number, last name, and first name.


List each employee in the Sales and Development departments, including employee number, last name, first name, and department name.


List the frequency counts, in descending order, of all employee last names.
