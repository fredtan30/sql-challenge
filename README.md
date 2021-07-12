###### SQL-CHALLENGE


# **SQL Homework - Employee Database: A Mystery in Two Parts**

# **BACKGROUND**

We are hired to conduct a research on employees of the organisation from 1980s and 1990s.

We have been given 6 data sets from that period as csv files.

In order to answer all the research question provided. We have to perform these following steps

1. ERD Data Modelling 
2. Data Engineering
3. Data Analysis


## **1st Phase - ERD DATA Modelling**

Inspect the CSV and draw out the ERD Diagram using QuickDBD

![A Mystery ERD](https://user-images.githubusercontent.com/83207549/125291304-94589480-e364-11eb-8a09-5aa06b276e19.png)


## **2nd Phase - Data Engineering**

From the ERD Diagram, we create the table schema of each data sets and we set the data types, primary key, foreign keys and other constraints, we commit this by importing the  ERD diagram into our Postgres SQL

Once we created the tables, we import each of the data sets into the corresponding SQL table and display the table

https://github.com/fredtan30/sql-challenge/blob/main/EmployeeSQL/Schema.sql

Challenges encountered when importing files from csv into the respective table especially on DATE type


## **3rd Phase - Data Analysis**

Once the all database have been created, we have to perform these analysis below

1. List the following details of each employee: employee number, last name, first name, sex, and salary.

2. List first name, last name, and hire date for employees who were hired in 1986.

3. List the manager of each department with the following information: department number, department name, the manager's employee number, last name, first name.

4. List the department of each employee with the following information: employee number, last name, first name, and department name.

5. List first name, last name, and sex for employees whose first name is "Hercules" and last names begin with "B."

6. List all employees in the Sales department, including their employee number, last name, first name, and department name.

7. List all employees in the Sales and Development departments, including their employee number, last name, first name, and department name.

8. In descending order, list the frequency count of employee last names, i.e., how many employees share each last name.

The Analysis can be found under this link below or EmployeeSQL in this repository

https://github.com/fredtan30/sql-challenge/blob/main/EmployeeSQL/data_analysis.sql

Challenges were on converting date from string to date using the to_date function





