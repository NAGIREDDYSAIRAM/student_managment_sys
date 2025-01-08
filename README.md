# Student Management System 

A simple Student Management System built in Python, using a CSV file to store student data permanently. The system allows users to add, update, delete, view, and search student records.
*******************************************************************************************************************************************************************
## Features

- **Add Student**: Allows the user to add a new student with details like student ID, name, age, and course.
- **Update Student**: Allows the user to update the details of an existing student.
- **Delete Student**: Allows the user to delete a student's record by student ID.
- **View Students**: Displays a list of all students with their details.
- **Search Student**: Allows the user to search for a student by their ID.

The data is stored in a CSV file named `students.csv`, ensuring that student information is persisted between program runs.

## Requirements

- Python 3.x
- ***********************************************************************************************************************************************
**How It Works**
Data Persistence: The student data is saved in the students.csv file. Every time a student is added, updated, or deleted, the file is updated to reflect the changes.

CSV Format: The CSV file stores the following fields:

Student ID (unique identifier)
Name (student's name)
Age (student's age)
Course (the course the student is enrolled in)
Loading and Saving: When the program starts, it will automatically load the existing data from students.csv if the file exists. If the file doesn't exist, it will start with an empty list. After every operation (add, update, delete), the data is saved back into the CSV file.

