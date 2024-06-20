# Course Management System

## Overview
The Course Management System is a Java-based application designed to manage courses, students, teachers, and modules within an educational institution. It utilizes MySQL as the database backend and integrates with Swing for the user interface.

#### Login Page
<img width="1420" alt="Screenshot 2024-06-19 at 10 50 59 PM" src="https://github.com/nismail1/Course-Management-System/assets/41389592/2053fb25-ff12-4413-877c-056ba00e259a">


#### Welcome Page
<img width="1420" alt="Screenshot 2024-06-19 at 3 05 30 PM" src="https://github.com/nismail1/Course-Management-System/assets/41389592/1bdd19b2-fdf6-4659-8e71-2e737612635f">


## Features
- **User Authentication**: Secure login and authentication system for administrators.
- **Course Management**: Create, update, and delete courses.
- **Module Management**: Manage modules within each course, including core and optional modules.
- **Student and Teacher Management**: Track students and teachers associated with courses.
- **Results and Enrollment**: Record student enrollment in courses and maintain module-wise results.

## Technologies Used
- **Java**: Core programming language for backend logic.
- **MySQL**: Database management system for storing application data.
- **Swing**: Java's GUI toolkit used for building the user interface.
- **MySQL Connector/J**: JDBC driver for MySQL connectivity in Java applications.

## Prerequisites
Before running the application, ensure you have the following installed:
- Java Development Kit (JDK) 8 or higher
- MySQL Server
- MySQL Connector/J (JDBC driver for MySQL)

## Setup Instructions

### Database Setup:
1. Install MySQL Server.
2. Create a database named `course_management_system`.
3. Execute the SQL scripts in the `database-scripts` folder to create tables and populate initial data.

### Java Setup:
1. Install JDK 8 or higher.
2. Ensure MySQL Connector/J JAR file (`mysql-connector-java-8.x.x.jar`) is downloaded and available in the project's classpath.

### Running the Application:
1. Compile the Java source files.
2. Run the `App` class, which serves as the entry point.

Example command:
```sh
java -cp "/path/to/mysql-connector-java-8.x.x.jar:src" App

