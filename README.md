A Python-based School Management System with SQLite3 database connectivity that allows efficient management of teacher and student data. This project provides a command-line interface to handle CRUD (Create, Read, Update, Delete) operations for both teachers and students, and also includes functionality for managing courses and grades.

# Features

1. Teacher Management:
-> Add Teacher: Allows entry of a new teacher's data.
-> Update Teacher: Allows updating of existing teacher information.
-> Delete Teacher: Removes teacher data from the database.
-> Show Teacher: Displays the details of a specific teacher.

2. Student Management:
-> Add Student: Allows entry of a new student's data.
-> Update Student: Allows updating of existing student information.
-> Delete Student: Removes student data from the database.
-> Show Student: Displays the details of a specific student.

3. Course and Grades Management:
-> Course Details: Displays available courses and their associated teachers.
-> Student Course:
-> -> -> Add Course: Adds a course for a specific student.
-> -> -> Update Grades: Updates the grades for a student's course.
-> -> -> Show Grades: Displays the grades for a specific student.


# Technologies Used
-> Python: The main programming language used.
-> SQLite3: The database system used to store and manage data.
-> Numpy: Used for generating random IDs.
-> Getpass: Used for secure password entry.

# Requirements
-> Python 3.x
-> SQLite3
-> Numpy
-> Getpass


# Install Required Packages:
Make sure you have numpy , Sqlite3 and getpass installed.

#Usage
1) School Login:
-> Enter the School ID and Password to access the system.
-> Default School ID: 123
-> Default School Password: 123


2) Main Menu Options:
-> Press 1 to manage teacher or student data.
-> Press 2 to manage student course details.
-> Press 3 to exit the system.

3)Teacher and Student Data Management:
-> Follow the prompts to add, update, delete, or display data for teachers or students.

4) Course Management:
-> Add or update courses for students and manage their grades.


# Database Structure

-> Teacher Table:
                  name (text)
                  age (int)
                  mobile (int)
                  salary (int)
                  subject (text)
                  id (int)
                  email (text)
                  password (int)
-> Student Table:
                  name (text)
                  age (int)
                  class (text)
                  mobile (int)
                  father (text)
                  mother (text)
                  id (int)
                  email (text)
                  password (int)
-> Course Table:
                  id (int)
                  course (text)
                  grades (text)

# Future Improvements
-> Implement a graphical user interface (GUI) for easier use.
-> Add more detailed error handling and input validation.
-> Extend the functionality to include attendance management and scheduling.

# Contributing
-> Contributions are welcome! Please open an issue or submit a pull request for any enhancements or bug fixes.
