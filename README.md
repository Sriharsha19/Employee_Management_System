# Employee_Management_System
The main purpose of Employee management System is to efficiently manage employees within an organization . This Project is developed using java , JDBC , MySQL 


Employee Management Systems (EMS)
- Purpose: To efficiently manage employees within an organization
- Features: Record management, leave applications, etc.
 

 Key Components :
1. Entities:
   - Employee
   - Department
   - Leave Application
   
2. Technologies Used:
   - Java
   - JDBC (Java Database Connectivity)
   - MySQL
   - XAMPP (for local server setup)
   
 
Entity Details*
1. Employee:
   - Attributes: ID, Name, Email, Salary, Age, Department ID, Department Name
   - Operations: Add, Retrieve, Update, Delete
   
2. Department:
   - Attributes: ID, Name
   - Operations: Add, Retrieve
   
3. Leave Application:
   - Attributes: ID, Employee ID, Start Date, End Date, Leave Type, Reason, Status
   - Operations: Apply for Leave, View Leave History
 
  **Technologies Used**
1. Java:
   - Used for developing the application logic and user interface.
   
2. JDBC (Java Database Connectivity):
   - Enables Java applications to interact with databases.
   
3. MySQL:
   - Relational database management system used for storing employee and related data.
   
4. XAMPP:
   - Local server solution providing Apache, MySQL, PHP, and Perl.
 

 
 Application Flow
1. Main Class:
   - Central point of entry for the application.
   - Provides a menu-driven interface for performing various operations.
   
2. EmployeeDaoImpl Class:
   - Implements CRUD operations for employee data using JDBC.
   
3. DepartmentDaoImpl Class:
   - Implements CRUD operations for department data.
   
4. LeaveDaoImpl Class:
   - Implements operations related to leave applications.

 Advantages
1. Efficiency:
   - Streamlines employee record management.
   - Simplifies leave application process.
   
2. Accuracy:
   - Ensures accurate and up-to-date employee data.
   
3. Accessibility:
   - Provides easy access to employee information.
   
 
