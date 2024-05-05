# College Fest Debate Event Registration System

This project is aimed at helping students manage registrations for a debate event during the college fest. It allows users to perform CRUD operations on a table storing student details based on their course. The project uses Spring MVC and Hibernate ORM for implementation.

## Features

- Insert new student records into the table.
- Update existing student records in the table.
- Delete existing student records from the table.
- Print all student records from the table.
- Security layer with two roles: USER and ADMIN.
- ADMIN role has privileges to perform all operations.
- USER role can view and save student details.

## Technologies Used

- Java
- Spring MVC
- Hibernate ORM
- MySQL

## Setup Instructions

1. Clone the repository to your local machine.
2. Import the project into your IDE as a Maven project.
3. Configure your MySQL database settings.
4. Run the project on your local server.

## Usage

1. Navigate to the homepage.
2. Log in with your credentials.
3. Depending on your role, you can perform the necessary operations:
   - ADMIN: Add, update, delete, and view all student records.
   - USER: View and save student details.
