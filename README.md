Idea Title: Smart Hospital Management Team Members :1.Mayuri Patil 2.Pranjali Walke 
Problem Statement :creating a website of hospital management system which is useful for villages.


Solution Approach :Develop a Hospital Management Website that : Stores Admits patients and assigns rooms Allows multiple doctors to treat patients Manages lab tests and reports Centralizes hospital database


Tech Stack : Frontend HTML CSS JavaScript Backend* Node.js / PHP MySQL Installation Steps :

Install frontend tools -Install a browser (Chrome, Edge, etc.) -Install code editor like Visual Studio Code 2.Install backend software -Install Node.js -Check installation using command -node -v 3.Install database Install MySQL Create database for hospital system 4.Create project folder -Make a folder for hospital project -Open it in Visual Studio Code
Install project dependencies Run in terminal: npm init -y npm install express mysql cors body-parser
Configure database -Create tables (patient, doctor, appointment, billing) -Connect MySQL with backend
How to Run : tech stack is:

Frontend → HTML, CSS, JavaScript Backend → Node.js Database → MySQL

Here is the simple step-by-step process to run your Hospital Management System:

Step 1 — Start MySQL

Open MySQL Workbench / Services
Start MySQL server
Make sure your database (example: hospital_db) exists
Step 2 — Open project folder

Open folder in Visual Studio Code

Open terminal (Ctrl + `)

Step 3 — Install dependencies (first time only)

Run: -npm install express mysql cors body-parser

Step 4 — Check database connection

In server.js, verify: host → localhost user → root password → your password database → hospital_db

Step 5 — Run backend server

Run: node server.js If successful, terminal shows: Server running on port 3000

Step 6 — Run frontend

If frontend files are inside Node project Open browser:
http://localhost:3000

If frontend is separate Open index.html directly in browser
To run the system, start MySQL server, run backend using node server.js, and open frontend in browser using localhost.

If project not running (common errors)

MySQL not started Wrong DB password Port already used Missing npm packages

Features : Current Features

1️ Patient Management

-Add, update, delete patient details -Store medical history

2️ Doctor Management

-Manage doctor information -Assign doctors to patients

3️. Appointment Booking

-Schedule and manage appointments -Check availability

Database Storage
Store all records securely using MySQL

7️ Web-Based System

Built using HTML, CSS, JavaScript (Frontend)

Backend using Node.js

Future Scope :

1️ Online Consultation -Video call feature for remote patients

2️ Mobile Application -Android/iOS app version

3️ AI-Based Diagnosis -Suggest possible diseases based on symptoms

4️ Cloud Integration -Secure cloud storage -Access from anywhere

5️ E-Pharmacy Integration -Online medicine ordering

6️ Ambulance Tracking System -GPS-based emergency tracking

7️ Health Monitoring Devices (IoT) -Connect smart health devices

8️ Multi-Hospital Connectivity -Share patient records between hospitals

