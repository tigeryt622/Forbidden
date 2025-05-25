University Management System
A Java Swing-based desktop application designed to manage various aspects of a university's administrative system. This project includes modules for handling student information, staff details, courses, attendance, and more.

Features
Graphical User Interface (GUI) built with Java Swing

Modular structure following object-oriented principles

Custom windows for:

Adding/Viewing/Updating student and teacher details

Managing courses and departments

Recording and viewing attendance

Fee management

Timetable and examinations

About section with credits

Technologies Used
Java (JDK 8+)

Swing for GUI

AWT for basic UI components

JDBC (optional, for future database connectivity)

Getting Started
Prerequisites
Java Development Kit (JDK) installed

IDE such as IntelliJ IDEA, Eclipse, or NetBeans

Setup Instructions
Clone or download this repository.

Open in your preferred IDE.

Compile and run any of the main classes, such as:

Login.java

About.java

(Optional) Add icons/ folder with required images (e.g., about.jpg) in your resources or src path.

Running the App
bash
Copy
Edit
javac university/management/system/About.java
java university.management.system.About
Project Structure
bash
Copy
Edit
university.management.system/
│
├── About.java                # About/credits window
├── AddStudent.java          # Add student form
├── AddTeacher.java          # Add teacher form
├── Dashboard.java           # Main menu/dashboard
├── Login.java               # Login window
├── StudentDetails.java      # View/edit student data
├── TeacherDetails.java      # View/edit teacher data
├── ...                      # Other functional classes
Author
Developed by Code for Interview
Contact: codeforinterview03@gmail.com
Roll Number: 1533146

License
This project is for educational purposes and may be used freely with attribution.
