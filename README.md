# Employee_Management_System_SQL
A simple Employee Management System project using SQL and MySQL.
# Employee Management System (SQL Project)

## Project Description
This project is a simple **Employee Management System** built using **SQL and MySQL**.  
It demonstrates **database design, querying, and reporting skills**, combining HR knowledge with technical abilities.

## Objective
The objective of this project is to manage employee details, departments, attendance, and performance using a **relational database**, and generate useful reports for HR and management purposes.

## Database Structure

### Departments Table
- **DepartmentID** (Primary Key)
- **DepartmentName**
- **ManagerName**

### Employees Table
- **EmployeeID** (Primary Key)
- **Name**
- **DepartmentID** (Foreign Key)
- **DateOfJoining**
- **Salary**

### Attendance Table
- **AttendanceID** (Primary Key)
- **EmployeeID** (Foreign Key)
- **Date**
- **Status** (Present/Absent/Leave)

### Performance Table
- **PerformanceID** (Primary Key)
- **EmployeeID** (Foreign Key)
- **Month**
- **PerformanceScore**

## Sample SQL Queries
- List all employees with their department names and managers  
- Calculate average salary by department  
- Find employees with perfect attendance  
- Find top performer for a given month  

## Technologies Used
- SQL / MySQL  
- MySQL Workbench  
- Data Analysis  

## How to Run
1. Clone the repository.  
2. Open **MySQL Workbench**.  
3. Copy and run the SQL script files to create database, tables, and insert sample data.  
4. Run the sample queries to test the project.  

## Author
**Bandi Niharika Varma**  
- Email: niharikavarma724@gmail.com  
- LinkedIn: [linkedin.com/in/niharikavarma](https://linkedin.com/in/niharikavarma)  
- GitHub: [github.com/niharikavarma](https://githu)
