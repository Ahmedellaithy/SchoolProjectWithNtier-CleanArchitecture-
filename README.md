# Title

A Student Management System Built with Clean Architecture

## Table of Contents
* [Description](#description)
* [Installation](#installation)
* [Usage](#usage)
* [Features](#features)
* [Database](#database)
* [Description](#description)
* [Questions](#questions)
## Description 
The Student Management System is a web-based application designed to manage and track student information in an educational institution. Built using Clean Architecture, this system promotes maintainability, testability, and scalability by separating concerns into well-defined layers.
## Installation
  
``` 
 git clone https://github.com/Ahmedellaithy/SchoolProjectWithNtier-CleanArchitecture-
```
## Usage 

  Login to the System
When the application opens, you'll be prompted to log in.
Username: Enter your username.
Password: Enter your password.
The system supports the following user roles:
Admin: Full access to manage students, courses, grades, and generate reports.
Teacher: Can manage grades and enroll students in courses.
Student: Can view personal grades and enrolled courses.

## Features
- CQRS Design Pattern
- Generic(Repository) Design Pattern
- Database Operations(Views,Procedures,Functions) Endpoint
- Service Like Send (Email,Upload Image)
- JWT Authentication and Refresh tokens: Secure the API endpoints using JWT tokens and Refresh tokens
- Localizations Of Data And Responses
- Student(Get,Update,Delete) Enpoint
- Teacher crud operations Endpoint
## Database

![image](https://github.com/user-attachments/assets/ac6e5c2a-83ba-4a59-8d97-9a8c62c6705c)

   
## Description
  Key features of the system include:

- Student Registration: Admins can easily register new students with essential information like name, age, and grade.
- Grade Management: Teachers can assign and update grades for students based on their course performance.
- Report Generation: Admins can generate reports detailing student performance, course completion, and more.
- User Authentication: Role-based access control is implemented to ensure that each user (Admin, Teacher, Student) has access to appropriate system functionalities.
- Localization and Email server provider

## Questions

If you have any questions about your repo, open an issue or contact me directly at a.ayman123400@gmail.com. 
