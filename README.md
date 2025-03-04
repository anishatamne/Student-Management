Student Management System

Project Overview

This Java program is a menu-driven application that demonstrates the concepts of classes, array of objects, instance members, and constructors. It provides operations to manage student records using an ArrayList. The program follows modular programming with different Java files for better maintainability.

Features

Add Student: Allows the user to add a new student record.

Display Students: Displays all stored student records.

Search Student: Search for a student by PRN, Name, or Position.

Update Student: Modify existing student details.

Delete Student: Remove a student record.

Exit: Terminates the program.

Project Structure:
StudentManagementSystem/
│-- src/
│   ├── Student.java           # Defines the Student class with attributes and methods
│   ├── StudentOperations.java # Implements all CRUD operations
│   ├── Main.java              # Contains the main method and menu-driven logic
│
│-- README.md                  # Documentation of the project
│-- .gitignore                  # Git ignore file

Class Descriptions

1. Student.java

This class defines the Student attributes and constructors:

prn (Primary Registration Number)

name

dob (Date of Birth)

marks

Methods:

Constructor for initialization.

Getter and Setter methods.

2. StudentOperations.java

This class contains methods for handling student operations:

addStudent(Student student): Adds a new student to the list.

displayStudents(): Displays all students in the list.

searchByPRN(int prn): Finds a student by PRN.

searchByName(String name): Finds students by name.

searchByPosition(int index): Finds a student by position in the list.

updateStudent(int prn, Student newDetails): Updates a student's details.

deleteStudent(int prn): Removes a student from the list.

3. Main.java

This file contains the main method that runs the menu-driven interface.

Uses a Scanner to interact with the user.

Calls relevant methods from StudentOperations based on user input.

Coding Guidelines

Follows Java naming conventions (CamelCase, meaningful variable names).

Uses comments for better readability.

Implements modular programming by separating logic into different files.
