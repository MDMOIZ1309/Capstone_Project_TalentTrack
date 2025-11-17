📌 TalentTrack – Job Search & Recruitment Platform

TalentTrack is a student-centric job search and recruitment platform designed to simplify the career journey of fresh graduates and early-career professionals.
Developed as a full-stack web application using ReactJS (frontend) and Django REST Framework (backend), TalentTrack focuses on skill-based job filtering, resume management, secure authentication, and interview preparation.

TalentTrack solves the limitations of traditional recruiter-oriented portals by providing a clean, personalized, transparent, and user-friendly platform exclusively for students.

🚀 Features
🎯 User & Account

Email-based OTP authentication

JWT-secured login sessions

User profile management

Settings & notifications

📄 Resume Management

Upload/download PDF/DOCX resumes

Secure file storage & handling

Easy update/delete functionality

🧠 Skill Management

Add / edit / delete skills

Skill certificate upload (PDF/JPG)

Verified skill tracking

Skill-based job filtering

💼 Job Search Module

Skill-based curated job recommendations

Job listing with search & apply

Clean job card UI

Apply through redirects or saved jobs

📘 Interview Preparation

Topic-wise preparation materials like:

Java

Python

DSA

DBMS

Cloud

Aptitude

Downloadable PDF notes and guides

🧪 Assessment Module

Direct links to HackerRank certifications

Skill tracking via external assessments

📞 Help & Support

Simple support section

Email-based help

FAQs

🛠️ Tech Stack
Frontend

ReactJS

JavaScript (ES6+)

Tailwind CSS

Axios

React Router

Backend

Django

Django REST Framework

JWT Authentication

Django ORM

Database

SQLite3 (development)

PostgreSQL (future upgrade)

Tools

VS Code

Git & GitHub

🏗️ System Architecture

Modular, scalable layered architecture

React frontend ↔ Django REST API

Clear separation of concerns

Media storage for resumes & certificates

JWT-based secure communication
🔐 API Endpoints (Key Endpoints)
Feature	Endpoint	Method	Description
Send OTP	/send-otp-registration/	POST	For new registration
Login OTP	/send-otp-login/	POST	OTP login
Verify OTP	/verify-otp/	POST	Verify user
Register	/register/	POST	Create user
Skills	/skills/	GET	Get user skills
Add Skill	/skills/add/	POST	Add new skill
Delete Skill	/skills/delete/<id>/	DELETE	Delete skill
Upload Resume	/resume/upload/	POST	Upload file
Download Resume	/resume/download/	GET	Get resume
Jobs	/jobs/skillbased/	GET	Skill-based job listings
🧩 Core Modules Implemented

Authentication (OTP + JWT)

Resume Management

Skills with certificate verification

Interview Prep Module

Assessments (HackerRank)

Skill-Based Job Filtering

Notifications & Settings

🧪 Result Highlights

Complete working full-stack web app

Clean UI with fast loading

Resume upload/download fully functional

Skill-based filtering working as expected

OTP + JWT authentication verified

Interview prep resources accessible

Modular and extendable backend

📈 Learning Outcomes

Full-stack development expertise

Django REST API design

State management in React

File handling & media storage

JWT authentication architecture

External platform integration (HackerRank)

Secure user data practices

Problem-solving & debugging skills

Professional documentation & planning

🚧 Challenges Faced

OTP timing & expiry handling

Authentication session issues before JWT

Resume upload failures due to file settings

CORS issues between React & Django

Efficient job filtering logic
All challenges were resolved with stable solutions during development.

🔮 Future Scope

TalentTrack can be extended to support:

AI-powered job recommendations

Course suggestions based on skill gap

Internship portal

Recruiter dashboards

Virtual career fairs

Mobile App (React Native)

Industry job API integrations

Explainable AI-based job matching

Student–recruiter communication system

TalentTrack aims to grow into a complete employability ecosystem.
