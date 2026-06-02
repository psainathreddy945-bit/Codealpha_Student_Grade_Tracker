Student Grade Tracker
A Java application that tracks student grades and generates a comprehensive report with statistics and letter grades.

Features
Student Management: Add multiple students with their names and marks
Input Validation: Ensures marks are between 0 and 100
Grading System: Automatically assigns letter grades based on marks:
A: 90-100
B: 75-89
C: 50-74
F: Below 50
Statistics: Calculates and displays:
Average marks across all students
Highest marks
Lowest marks
Comprehensive Report: Displays a detailed report for each student
Requirements
Java 8 or higher
A terminal/command prompt to run the program
How to Run
Compile the program:

javac StudentGradeTracker.java
Run the program:

java StudentGradeTracker
Follow the prompts:

Enter the number of students
For each student, enter their name and marks (0-100)
The program will display a comprehensive grade report with statistics
Example Output
Enter number of students: 3

Student 1
Enter student name: Alice
Enter marks: 85

Student 2
Enter student name: Bob
Enter marks: 92

Student 3
Enter student name: Charlie
Enter marks: 78

===== STUDENT REPORT =====
----------------------
Student Name : Alice
Marks        : 85
Grade: B
----------------------
Student Name : Bob
Marks        : 92
Grade: A
----------------------
Student Name : Charlie
Marks        : 78
Grade: B

Average Marks: 85.0
Highest Marks: 92
Lowest Marks: 78
Code Structure
Student Class: Simple model class that stores student name and marks
StudentGradeTracker Class: Main application class that handles:
User input
Grade calculation
Statistics computation
Report generation
Input Validation
The program validates that marks are within the range of 0-100. Invalid entries will be rejected, and the user will be prompted to re-enter the data for that student.
