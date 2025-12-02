# 📚 Student Record Management System (Java)

A fully-featured Student Record Management System built in Java using OOP concepts, file handling, custom exceptions, interfaces, multithreading, and runtime polymorphism.

This project enables adding, deleting, updating, searching, sorting, and storing student records in a text file (students.txt), ensuring data persistence across program runs.

🚀 Features
🧑‍🎓 Student Management

Add new student records

Update existing student details

Delete student by roll number

Search student by roll number

View all stored student records

📊 Sorting Feature

Sort students by marks (Descending order)

🗂 File Handling

Reads student records from a file at program startup

Saves updated records back to students.txt on exit

Uses pipe-separated (|) storage format

🧵 Multithreading

Loading animation implemented using a dedicated thread (Loader class)

🧱 Object-Oriented Concepts Used

Abstraction → Person (abstract class)

Inheritance → Student extends Person

Interfaces → RecordActions

Custom Exceptions → StudentNotFoundException

Polymorphism & Encapsulation throughout design

🧩 Project Structure
StudentRecordSystem.java
├── Person (abstract class)
├── Student (child class)
├── RecordActions (interface)
├── StudentNotFoundException (custom exception)
├── Loader (thread for animation)
└── StudentManager (handles CRUD + file operations)

📁 File Format — students.txt

Each line in the file stores a student record in this format:

rollNo|name|email|course|marks


Example:

101|John Doe|john@gmail.com|BCA|89.5
102|Ananya Sharma|ananya@gmail.com|B.Tech|93.0

▶️ How to Run
1️⃣ Compile the program
javac StudentRecordSystem.java

2️⃣ Run it
java StudentRecordSystem


The students.txt file will be created automatically if it doesn’t exist.

📌 Menu Options
===== Menu =====
1. Add Student
2. View All
3. Search
4. Delete
5. Update
6. Sort by Marks
7. Save & Exit

✨ Highlights

Proper use of Java Collections (HashMap, ArrayList)

Robust error handling and clean input validation

Professional implementation of file I/O

Demonstrates multi-class OOP structure

Easy-to-extend and maintain codebase
