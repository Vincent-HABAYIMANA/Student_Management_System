Student Record Management System (C++)

This is a console-based Student Record Management System written in C++. It allows users to manage student information, including subjects and grades, using a linked list data structure.

Features
Add new student records
Display all students
Search for a student by ID
Update student details
Delete student records
Sort student grades (ascending order)
Calculate average grade per student
Save student records to a file (students.txt)
How It Works
Run the program
Choose an option from the menu
Enter student details when prompted
Perform operations like search, update, delete, or grade sorting
Data is stored in memory and saved to a file
Menu Options
1 → Add Student
2 → Display Students
3 → Sort Student Grades
4 → Search Student
5 → Update Student
6 → Delete Student
7 → Calculate Average Grade
8 → Exit
File Storage
Student records are saved in students.txt
Data is appended each time a new student is added
Technologies Used
C++
File Handling (fstream)
Dynamic Memory Allocation
Linked List
Notes
Grades must be between 0 and 100
Each student can have multiple subjects
Data is not reloaded from file when the program restarts (only saved)
