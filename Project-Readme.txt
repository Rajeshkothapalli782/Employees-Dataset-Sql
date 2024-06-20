Project : Employee Dataset

Introduction :

Welcome to the Employee Dataset SQL Project. This project involves an analysis of an employee dataset using SQL. The purpose of this project is to demonstrate SQL querying skills, data manipulation, and insights extraction from a structured dataset.

Dataset Description :

The dataset used in this project contains information about employees, including details such as employee IDs, names, job titles, departments, salaries, start and end dates, and more. The dataset is designed to simulate a real-world organizational structure and employee information system.

Key Features:

Employee personal information
Job details and roles
Department assignments
Salary data
Employment dates

Database Schema:

The database schema consists of the following tables:

Employees: Contains personal and job-related information of employees.
Departments: Lists all the departments within the organization.
Loaction: Address of the employees.
Job_history: History of the employees.
Jobs: Job and salary details of the employees.
Region : The Field where the employees working.
 
Schema Diagram:

+-------------------+       +-------------------+       +-------------------+
|    Employees      |       |   Departments     |       |    Locations      |
+-------------------+       +-------------------+       +-------------------+
| employee_id (PK)  |       | department_id (PK)|       | location_id (PK)  |
| first_name        |       | department_name   |       | street_address    |
| last_name         |       | manager_id        |       | postal_code       |
| email             |       | location_id (FK)  |       | city              |
| phone_number      |       +-------------------+       | state_province    |
| hire_date         |                                   | country_id (FK)   |
| job_id (FK)       |                                   +-------------------+
| salary            |                                   +-------------------+
| commission_pct    |                                   |    Countries      |
| manager_id (FK)   |                                   +-------------------+
| department_id (FK)|                                   | country_id (PK)   |
+-------------------+                                   | country_name      |
                                                        | region_id (FK)    |
+-------------------+                                   +-------------------+
|    Job_History    |                                   +-------------------+
+-------------------+                                   |     Regions       |
| employee_id (FK)  |                                   +-------------------+
| start_date (PK)   |                                   | region_id (PK)    |
| end_date          |                                   | region_name       |
| job_id (FK)       |                                   +-------------------+
| department_id (FK)|                                                   
+-------------------+
                                                                            
+-------------------+
|       Jobs        |
+-------------------+
| job_id (PK)       |
| job_title         |
| min_salary        |
| max_salary        |
+-------------------+

Setup and Installation:

Prerequisites : 

> SQL Database Management System (e.g., MySQL)


SQL Queries and Analysis :

#The project includes various SQL queries and analyses, such as:

#Retrieving employee details.

#Calculating average salaries by department.

#Identifying the longest-serving employees.

#Analyzing salary trends over time.

Usage :

To use this project, you can execute the provided SQL scripts in your SQL client. Adjust queries as needed to suit your specific requirements or to perform different analyses.
