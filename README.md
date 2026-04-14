# Data-Structures---Strings-Tuples
# 📌 Project Overview
This project demonstrates the creation and management of a simple Employee Database System using MySQL. It covers essential database operations such as table creation, modification, relationships, and deletion.
The system includes tables for employees, departments, and locations, ensuring proper organization and relational integrity.

# 🎯 Project Objectives
Design a structured relational database
Implement Primary Keys and Foreign Keys
Perform DDL operations (CREATE, ALTER, DROP, RENAME)
Maintain data consistency and integrity
Practice real-world database management concepts

# 🛠️ Tools & Technologies
MySQL Database
SQL (Structured Query Language)

# 🗂️ Database Structure
1. Departments Table
department_id (Primary Key)
department_name (Unique, Not Null)
2. Location Table
location_id (Primary Key, Auto Increment)
location_name (Unique, Not Null)
3. Employees Table
employee_id (Primary Key)
employee_name
gender (M/F constraint)
designation
hire_date (default: current date)
department_id (Foreign Key)
location_id (Foreign Key)
salary
# 🔄 Database Operations Performed
# Table Creation
Created Departments, Location, and Employees tables
Defined relationships using foreign keys
# Table Modification
Added new column: email
Modified column: designation length increased
Dropped column: age
Renamed column: hire_date → date_of_joining
# Table Renaming
Departments → Departments_Info
Location → Locations
# Data Management
Used TRUNCATE to remove all employee records
# Cleanup Operations
Dropped Employees table
Dropped entire employee database

# 🔑 Key Features
Ensures data integrity with constraints
Demonstrates real-time database modifications
Implements relational database design
Covers full lifecycle: creation → modification → deletion

# 📊 Learning Outcomes
Understanding of SQL DDL commands
Hands-on experience with database schema design
Knowledge of constraints and relationships
Ability to manage and modify databases efficiently

# 🚀 How to Use
Open MySQL Workbench or any SQL editor
Copy and execute the SQL script step by step
Observe changes after each operation
Practice modifying and querying the database

# 📌 Conclusion
This project provides a foundational understanding of database management using MySQL. It helps in building strong SQL skills required for real-world applications like HR systems, enterprise software, and data-driven solutions.
