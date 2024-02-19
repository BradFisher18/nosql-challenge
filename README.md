# sql-challenge
The purpose of this challenge is to practise using a new language called SQL. We are given six seperate datasets related to employee information at Pewlett Hackard and are to create tables within SQL to store these to then be able to complete a variety of analysis.

## Data
The data provided is the employee information of those employed by Pewlett Hackard in the 1980's and 1990's and comprise of six seperate CSV files. These files are described below and can be found in 'EmplopyeeSQL' -> 'data':
* departments (containing department number and department name)
* dept_emp (containing employee numbers and their corresponding department number)
* dept_manager (containing the employee number of each departments managers)
* employees (cointaining for each employee their; employee number, title id, date of birth, first and last name, gender, and hire date)
* salaries (containing the salary for each corresponding employee id)
* titles (containing each title id and the title ofd the role)

## Data Modelling
A sketch ERD of this dataset can be found as 'ERD-EmployeeSQL.png' within the 'EmployeeSQL' directory

## Data Engineering
The code for the creation and importation of the data tables is located within the 'EmployeeSQL' directory and named 'schema_EmployeeSQL_DataEngineering.sql'.

## Data Analysis
The analysis for this dataset is located in the 'EmployeeSQL' under the name 'schema_EmployeeSQL_DataAnalysis.sql'. There are also screenshots of an example of the output to each question within the 'Analysis_Outputs' directly and labelled according to which question number it is.

## Running
To run the engineering and analysis, a program to read in SQL is required. One example of a program is PostgreSQL, which can be downloaded with the link below and select the relevant operating system.
##
PostgreSQL download: https://www.enterprisedb.com/downloads/postgres-postgresql-downloads
