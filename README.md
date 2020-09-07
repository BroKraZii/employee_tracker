#employee tracker

View all employees with the option by role, department, or manager
Add an employee, role, or department
Update an employee role or manager
Delete employee, role, or department
View department salary budgets

#installation
Run npm install to install all dependencies
Run schema.sql in MySQLWorkbench
Edit MySQL connection properties in the connectionProperties object in employee-tracker.js

#usage
Run node employee-tracker.js to start the application

#tool & resources
Node.js - JavaScript runtime environment
MySQLWorkbench - Visual database design tool

#dependencies
inquirer - For the CLI user interface. This will prompt user within the CLI for employee information.
console.table - Used to print MySQL into tables to the console.
mysql - Used to connect to the MySQL database and perform queries
promise-mysql - Used to create promises from MySQL queries
