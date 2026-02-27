⚠️ Important Notice

This repository is for issue tracking and documentation purposes only.
The source code for this project is maintained in a private repository due to security and confidentiality requirements. The platform handles sensitive student data, examination content, and institutional processes that must remain secure.

📋 Project Overview

The CDC SVNIT Student Evaluation Platform is a comprehensive web-based system developed for the Career Development Cell (CDC) of Sardar Vallabhbhai National Institute of Technology (SVNIT). It provides a secure and efficient environment for conducting recruitment tests and evaluations across multiple departments.

🎯 Purpose

Conduct secure online examinations for placement and recruitment processes

Manage student evaluations across various branches and programs

Provide real-time performance tracking and analytics

Facilitate communication between administrators and students

✨ Key Features
🔐 Secure Exam Environment

SEB Integration: Seamless integration with Safe Exam Browser (SEB) to restrict students' access to unauthorized resources during examinations

Cryptographic Verification: Full cryptographic config key verification (Config Key Hash) ensures the examination environment is exactly as configured

Email-Based OTP Authentication: Secure registration and login using email verification through Postmark service

👨‍💼 Advanced Admin Dashboard

Test Management: Create, edit, and manage tests with category-based questions and cutoff percentages

Targeted Announcements: Send announcements to specific programs, branches, and admission years

Real-time Leaderboard: Live tracking of student performance with filtering by program, branch, year, and test type

Performance Analysis: Comprehensive statistics and visualizations for qualification rates

Bulk Operations: Upload question banks via Excel and download detailed results

📝 Examination Features

Timed Tests: Configurable tests with specific start times, end times, and buffer periods

Live Notifications: Real-time alerts using Socket.io when tests go live

Category-Based Scoring: Multiple categories per test with individual cutoff percentages

Question Marking: Students can mark questions for review during the test

Auto-Submission: Automatic submission when time expires

📊 Student Features

Test History: Complete record of all attempted tests with detailed breakdowns

Submission Review: View answers, scores, and qualification status for each category

Announcements: Receive targeted announcements based on program, branch, and year

Profile Management: View and update personal information

🛠️ Tech Stack
Backend

Runtime: Node.js

Framework: Express.js

Database: MongoDB with Mongoose ODM

Authentication: Passport.js with Local Strategy

Real-time: Socket.io for live updates

Scheduling: Node-schedule for automated test management

Frontend

Template Engine: EJS (Embedded JavaScript)

Styling: Bootstrap 5 for responsive design

Rich Text Editor: Quill.js for announcements

Charts: Chart.js for performance visualizations

Services & Tools

Email: Postmark API for OTP delivery

File Processing: Multer and XLSX for Excel handling

Session Management: Express-session with MongoDB store

Security: Safe Exam Browser (SEB) integration

📱 Key Workflows
👨‍🎓 For Students

Register with institute email → Receive OTP → Verify and login

View available tests based on program, branch, and year

Take tests in Safe Exam Browser during scheduled time

View results and performance breakdown

Receive targeted announcements

👨‍💼 For Administrators

Login to admin dashboard

Upload question banks or create tests manually

Configure test parameters (timing, categories, cutoffs)

Create targeted announcements

Monitor leaderboards and performance analytics

Download detailed results in Excel format

🚫 Why Code is Not Public

Security: The platform handles sensitive examination content and student data

Integrity: Preventing unauthorized access to test questions and answers

Confidentiality: Protecting institutional processes and evaluation methods

Compliance: Meeting data protection and privacy requirements

Competitive Advantage: Maintaining the uniqueness of the evaluation system

🐛 Issue Tracking

This repository is used for:

Reporting bugs and issues

Requesting new features

Discussing improvements

Documenting known issues

📝 How to Report an Issue

Go to the Issues tab

Click "New Issue"

Provide a clear title and detailed description

Include steps to reproduce (if applicable)

Add relevant labels (bug, enhancement, question, etc.)

❌ Please DO NOT

Share sensitive information (passwords, API keys, etc.)

Post screenshots containing student data

Request access to the private repository

📚 Documentation Available

System architecture and workflows

User guides for students and administrators

API documentation (internal use)

Deployment and configuration guides
For detailed documentation, please contact the development team.

🤝 Contributing

While the source code is private, we welcome:

Bug reports and issue submissions

Feature suggestions and enhancement ideas

Documentation improvements

User experience feedback
All contributions will be reviewed by the development team and implemented in the private repository.

👨‍💻 Developers

This platform was developed and maintained by:

Jenil Prajapati
🔗 LinkedIn: linkedin.com/in/jenil-prajapati-svnit
🎓 SVNIT Student

Vineet Gupta
🔗 LinkedIn: linkedin.com/in/vineet-gupta-431396272
🎓 SVNIT Student

🖼️ Screenshots
<img width="1918" height="867" alt="REGISTER" src="https://github.com/user-attachments/assets/36d2bc1c-bde5-4b2c-92ff-d6473793d109" /> <img width="1917" height="866" alt="admin_3" src="https://github.com/user-attachments/assets/c79d7481-aa6a-4286-bd4c-4de4b34bd30b" /> <img width="1918" height="865" alt="admin_2" src="https://github.com/user-attachments/assets/0bcfc155-3f05-425b-856f-08110f463942" /> <img width="1918" height="868" alt="admin_1" src="https://github.com/user-attachments/assets/beb68fe6-39bf-4f4b-8f64-1d534f9360ca" /> <img width="1918" height="867" alt="a" src="https://github.com/user-attachments/assets/41c1adc5-375b-435a-9733-1dc468bffbbf" />
