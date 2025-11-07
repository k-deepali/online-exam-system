# online-exam-system
An Online Exam MCQ System is a web-based platform that allows students to take multiple-choice exams online and teachers/admins to create, manage, and evaluate tests efficiently.  The system automates the entire examination process — from question creation to result generation — and can be used in schools, colleges, and corporate training centers.

# System Architecture (Frontend + Backend)
1. Frontend (Client-Side)
Technology: Angular
Responsibilities:
- User authentication (Login / Register)
- Display exams, questions, and timers
- Capture and submit answers
- Show scores and analytics
- Responsive UI for desktop

2. Backend (Server-Side)
Technology: Java Spring Boot
Responsibilities:
- Manage users and roles (Student / Admin)
- Handle question banks and exam scheduling
- Process exam submissions and scoring
- Generate reports and analytics
- Securely store data in database

3. Database
Technology: MySQL
Responsibilities:
- Store users, questions, exams, results, and logs

# Core Modules and Features

1. Admin / Teacher Module
- Add, update, and delete MCQ questions
- Create exams (title, subject, duration, total marks)
- Assign exams to students or groups
- View results and performance reports

2. Student Module
- Register and log in
- View available exams
- Take MCQ test with countdown timer
- Submit answers
- View instant results and correct answers (optional)

3. Exam Module
- Randomized questions per attempt
- Support single-correct / multiple-correct questions
- Time tracking and auto submission
- Anti-cheating (disable back navigation, tab switch alerts)

# Results and Analytics
1. Automatic scoring
2. Summary of right/wrong answers
3. Leaderboard (optional)
4. Export reports (PDF / Excel)

# Authentication and Security
1. JWT-based login system
2. Role-based access control (Admin / Student)
3. Password hashing and validation
4. Session timeout and secure REST APIs
