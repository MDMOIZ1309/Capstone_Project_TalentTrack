<!-- PROJECT LOGO -->
<p align="center">
  <img src="https://cdn-icons-png.flaticon.com/512/3135/3135692.png" alt="Logo" width="120">
</p>

<h1 align="center">🎯 TalentTrack – Job Search & Recruitment Platform</h1>

<p align="center">
  A student-centric job search platform built using <b>React + Django</b>, offering skill-based job filtering,<br/>
  resume management, secure OTP authentication, interview preparation & more.
</p>

---

## 🚀 **Badges**

<p align="center">
  <img src="https://img.shields.io/badge/React-18.0-blue?logo=react" />
  <img src="https://img.shields.io/badge/Django-REST%20API-green?logo=django" />
  <img src="https://img.shields.io/badge/SQLite-Database-blue?logo=sqlite" />
  <img src="https://img.shields.io/badge/Status-Active-success" />
  <img src="https://img.shields.io/badge/Full--Stack-Project-orange" />
  <img src="https://img.shields.io/badge/License-Open%20Source-purple" />
</p>

---

## 📌 **Overview**

TalentTrack is a full-stack web platform designed to simplify job searching for **students and fresh graduates**.  
Instead of recruiter-centric portals, TalentTrack provides:

✔ Skill-matched job recommendations  
✔ Resume upload & management  
✔ Interview preparation resources  
✔ Simple & transparent UI/UX  
✔ OTP + JWT secure authentication  

---

## 🖼️ **Project Preview (Screenshots)**

> You can upload real screenshots later — placeholders added.

| Home Page | Resume Upload | Job Listings |
|----------|---------------|--------------|
| ![Home](https://via.placeholder.com/300x160?text=Home+Screenshot) | ![Resume](https://via.placeholder.com/300x160?text=Resume+Upload) | ![Jobs](https://via.placeholder.com/300x160?text=Job+Listings) |

---

## 🌟 **Key Features**

### 🔐 **Authentication**
- Email-based OTP login
- JWT-secured sessions
- Protected user routes

### 🧠 **Skills & Certificates**
- Add / delete / update user skills  
- Upload certificates (PDF/JPG)  
- Verified skill tracking  
- Real-time job filtering based on skills  

### 📄 **Resume Module**
- Upload, update, download resumes  
- Secure media handling in Django  
- Validations on file format & size  

### 💼 **Job Search**
- Personalized job recommendations  
- Clean job card UI  
- "Apply Now" redirects  
- Search & filtering  

### 🎓 **Interview Preparation**
- Topic-wise structured content  
- PDFs for: Java, Python, DSA, DBMS, Cloud, Aptitude  

### 🧪 **Assessments**
- HackerRank certification redirect  
- Track assessment attempts  

### 💬 **Help & Support**
- FAQ  
- Support email  
- Simple contact workflow  

---

## 🛠️ **Tech Stack**

### **Frontend**
<p align="left">
  <img src="https://img.shields.io/badge/React-18.0-blue?logo=react" />
  <img src="https://img.shields.io/badge/TailwindCSS-3.0-teal?logo=tailwindcss" />
  <img src="https://img.shields.io/badge/JavaScript-ES6-yellow?logo=javascript" />
</p>

### **Backend**
<p align="left">
  <img src="https://img.shields.io/badge/Django-REST%20Framework-green?logo=django" />
  <img src="https://img.shields.io/badge/Python-3.x-blue?logo=python" />
  <img src="https://img.shields.io/badge/JWT-Authentication-orange" />
</p>

### **Database**
<p align="left">
  <img src="https://img.shields.io/badge/SQLite-Database-lightgrey?logo=sqlite" />
</p>

### **Tools**
<p align="left">
<img src="https://img.shields.io/badge/GitHub-Version%20Control-black?logo=github" />
<img src="https://img.shields.io/badge/Postman-API%20Testing-orange?logo=postman" />
<img src="https://img.shields.io/badge/VSCode-Editor-blue?logo=visualstudiocode" />
</p>

---
Frontend (React)
⇅ REST API
Backend (Django + DRF)
⇅
Database (SQLite)
⇅
Media Storage (Resumes / Certificates)

---

## 📡 **Core API Endpoints**

| Feature | Method | Endpoint |
|--------|--------|----------|
| Send OTP | POST | `/send-otp-registration/` |
| Login OTP | POST | `/send-otp-login/` |
| Verify OTP | POST | `/verify-otp/` |
| Register | POST | `/register/` |
| Skills | GET | `/skills/` |
| Add Skill | POST | `/skills/add/` |
| Delete Skill | DELETE | `/skills/delete/<id>/` |
| Upload Resume | POST | `/resume/upload/` |
| Get Resume | GET | `/resume/download/` |
| Job Listing | GET | `/jobs/skillbased/` |

---

## 📈 **Project Outcomes**
- End-to-end full-stack web app  
- Clean UI with skill-based job filtering  
- OTP + JWT secured system  
- Resume & skill certificates working flawlessly  
- Strong database design with ORM  

---

## 👨‍💻 **Developed By**

### **Team 57 – SR University**

- D. Srawik  
- **Md. Moiz Ur Rehman**  
- V. Sai Raj  
- R. Shrujan  
- A. Vaninath  

**Guided by:**  
🎓 *Dr. S. Jamalaiah, Assistant Professor, School of CS & AI*

---

## ⭐ **Show Your Support**

If you like this project, please:

⭐ **Star this repository**  
🍴 **Fork it**  
🐛 **Report issues**

---

<p align="center"><b>TalentTrack – Empowering students with smarter job discovery.</b></p>


## 🧩 **System Architecture**

