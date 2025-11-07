# online-exam-system
An Online Exam MCQ System is a web-based platform that allows students to take multiple-choice exams online and teachers/admins to create, manage, and evaluate tests efficiently.  
The system automates the entire examination process — from question creation to result generation — and can be used in schools, colleges, and corporate training centers.

# System Architecture (Frontend + Backend)
1. Frontend (Client-Side):

Technology: Angular 

Responsibilities:

User authentication (login/register)

Display exams, questions, and timers

Capture and submit answers

Show scores and analytics

Responsive UI for desktop

2. Backend (Server-Side):

Technology: Java Spring Boot 

Responsibilities:

Manage users, roles (student, admin)

Handle question banks and exam scheduling

Process exam submissions and scoring

Generate reports and statistics

Store data securely in a database

3. Database:

MySQL 

Stores users, questions, exams, results, and logs

- Core Modules and Features
1. Admin / Teacher Module

Add, update, delete MCQ questions

Create exams (title, subject, duration, total marks)

Assign exams to students or groups

View results and performance reports

 2. Student Module

Register and log in to the system

View available exams

Take MCQ test (with countdown timer)

Submit answers

View instant results and correct answers (optional)

 3. Exam Module

Randomized questions per attempt

Support for single-correct or multiple-correct questions

Time tracking and automatic submission when time expires

Anti-cheating (disable back navigation, tab switching alerts)

 4. Results and Analytics

Automatic scoring

Summary of right/wrong answers

Leaderboard (optional)

Export result reports (PDF, Excel, etc.)

 5. Authentication and Security

JWT-based login system

Role-based access control (admin/student separation)

Password hashing and validation

Session timeout and secure APIs
