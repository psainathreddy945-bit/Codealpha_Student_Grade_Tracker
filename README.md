# Student Grade Tracker

## Overview

Student Grade Tracker is a Java-based console application that helps manage student records and analyze academic performance. The program allows users to add student details, calculate grades, search for students, generate reports, rank students based on marks, and store data permanently using file handling.

## Features

* Add student records
* Validate marks input (0–100)
* Calculate grades automatically
* Search students by name
* Generate detailed student reports
* Calculate:

  * Average Marks
  * Highest Marks
  * Lowest Marks
* Display student rankings
* Save student data to a file
* Load existing student data automatically on startup
* Menu-driven interface
* Uses Object-Oriented Programming concepts

## Technologies Used

* Java
* ArrayList Collection Framework
* File Handling (FileWriter, FileReader, BufferedReader)
* Object-Oriented Programming (OOP)

## OOP Concepts Implemented

* Classes and Objects
* Encapsulation
* Methods
* Collections (ArrayList)

## Project Structure

StudentGradeTracker.java
students.txt

## How to Run

### Compile the Program

```bash
javac StudentGradeTracker.java
```

### Run the Program

```bash
java StudentGradeTracker
```

## Sample Output

```text
===== STUDENT GRADE TRACKER =====

===== MENU =====
1. Add Student
2. View Report
3. Search Student
4. Exit

Enter your choice: 1

Enter student name: Arun
Enter marks (0-100): 85

Student added successfully!
```

## Student Report Example

```text
===== STUDENT REPORT =====

Student Name : Arun
Marks        : 85
Grade: B

Average Marks: 85.00
Highest Marks: 85
Lowest Marks: 85

===== STUDENT RANKING =====
Rank 1: Arun - 85
```

## Future Enhancements

* Java Swing GUI
* Edit and delete student records
* Export reports to PDF
* Database integration using MySQL
* Graphical performance analysis

## Author

Sainath Reddy

## License

This project is created for educational and internship purposes.
