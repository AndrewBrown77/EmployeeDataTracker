# EmployeeDataTracker

To create a SQL Employee Tracker, you can follow these general steps:

Set Up Your Environment:

Install Node.js if you haven't already.
Create a new project directory and initialize it with npm init.
Install Required Packages:

Install the necessary packages using npm, such as inquirer for user prompts and pg for PostgreSQL database interaction:
npm install inquirer pg
Set Up the PostgreSQL Database:

Create a PostgreSQL database for your employee tracker.
Define the necessary tables (e.g., employees, departments, roles) according to the schema outlined in your project instructions.
Create the Application Structure:

Set up your project files, including:
index.js for the main application logic.
Additional modules for handling database queries and user interactions if needed.
Implement Database Queries:

Write functions to handle CRUD operations (Create, Read, Update, Delete) for employees, departments, and roles. Use the pg package to interact with your PostgreSQL database.
Build the User Interface:

Use inquirer to create a command-line interface that allows users to navigate through different options (e.g., view employees, add new employees, update roles, etc.).
Implement Additional Features:

Add bonus features as outlined in the grading requirements, such as updating employee managers, viewing employees by manager or department, and calculating the total utilized budget of a department.
Test Your Application:

Run your application and test all functionalities to ensure everything works as expected.
Create a Walkthrough Video:

Record a video demonstrating the functionality of your employee tracker, ensuring all technical acceptance criteria are met.
Prepare Your README:

Write a README file that includes a description of your project, installation instructions, usage, and a link to your walkthrough video.