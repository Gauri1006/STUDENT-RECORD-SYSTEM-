
===========================================
           STUDENT RECORD SYSTEM
        Java Lab Assignment – OOP 
===========================================

Submitted by: Gauri Katiyar  
Course: B.Tech CSE  
Subject: Java Programming  
Instructor: Dr. Manish Kumar  
Assignment: Lab Assignment 1  
Topic: Student Class Design & Basic Operations

-------------------------------------------
1. Overview
-------------------------------------------
This project implements a Student Record Management System using 
Object-Oriented Programming (OOP) concepts in Java. The system allows 
users to:

✔ Add new student records  
✔ Display all student records  
✔ Calculate grades based on marks  
✔ Validate user input (marks between 0–100)  
✔ Use a menu-based console interface  

-------------------------------------------
2. Features Implemented
-------------------------------------------
1. Object-Oriented Design  
   - Student class inherits from Person class  
   - Encapsulation through fields and methods  

2. Constructors  
   - Default constructor  
   - Parameterized constructor  

3. Methods  
   - inputDetails(): Accepts user input  
   - calculateGrade(): Computes A/B/C/D based on marks  
   - displayDetails(): Prints student information  

4. Data Structures  
   - 1D array to store multiple students  
   - Supports multiple entries  

5. User Interaction  
   - Clear, menu-based navigation  
   - Loops until user selects Exit  

6. Data Validation  
   - Ensures marks are within 0 to 100  

-------------------------------------------
3. Technologies Used
-------------------------------------------
- Java (JDK 24 or above)  
- IntelliJ IDEA  
- Scanner for input  
- Arrays and conditional statements  

-------------------------------------------
4. How to Run the Program
-------------------------------------------
1. Open IntelliJ IDEA  
2. Create a new Java project  
3. Inside the 'src' folder, add the file:  
       StudentRecordSystem.java  
4. Copy the full source code into the file  
5. Right-click on the file → Run 'StudentRecordSystem'  

-------------------------------------------
5. Grade Calculation Logic
-------------------------------------------
A → Marks >= 90  
B → Marks >= 75  
C → Marks >= 60  
D → Marks < 60  

-------------------------------------------
6. File Structure
-------------------------------------------
src/
 └── StudentRecordSystem.java  
README.txt  

-------------------------------------------
7. Sample Program Output
-------------------------------------------
===== Student Record Menu =====
1. Add Student
2. Display All Students
3. Exit

Enter your choice: 1
Enter Roll No: 048
Enter Name: gauri
Enter Course: b.tech
Enter Marks (0-100): 8.7

===== Student Record Menu =====
Enter your choice: 2
Roll No: 48
Name: gauri
Course: b.tech
Marks: 8.7
Grade: D

-------------------------------------------
8. Conclusion
-------------------------------------------
This Student Record System demonstrates core OOP concepts such as 
inheritance, constructors, data encapsulation, and method implementation. 
The assignment fulfills the requirements of Java Lab Assignment 1 and 
provides a strong foundation in class-based program design.


