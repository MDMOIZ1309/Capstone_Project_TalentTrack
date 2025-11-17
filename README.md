# 📌 TalentTrack – Job Search & Recruitment Platform

TalentTrack is a **student-centric job search and recruitment platform** designed to simplify the career journey of fresh graduates and early-career professionals.  
Built using **ReactJS (frontend)** and **Django REST Framework (backend)**, the platform provides:

- Skill-based job filtering  
- Resume upload & management  
- Secure OTP-based authentication  
- Interview preparation resources  
- Simple and clean UI  

TalentTrack solves the limitations of traditional recruiter-oriented portals by offering a **personalized, transparent, and easy-to-use platform exclusively for students**.

---

## 🚀 Features

### 🎯 User & Account
- Email-based OTP authentication  
- JWT-secured login sessions  
- User profile management  
- Settings & notifications  

### 📄 Resume Management
- Upload/download PDF/DOCX resumes  
- Secure file storage  
- Easy update/delete functionality  

### 🧠 Skill Management
- Add / edit / delete skills  
- Upload skill certificates (PDF/JPG)  
- Verified skill tracking  
- Skill-based job filtering  

### 💼 Job Search Module
- Curated job recommendations based on user skills  
- Job listing with search & apply  
- Clean job card UI  
- Apply via redirect or saved jobs  

### 📘 Interview Preparation
Topic-wise materials including:  
- Java  
- Python  
- DSA  
- DBMS  
- Cloud  
- Aptitude  
- Downloadable PDFs and notes  

### 🧪 Assessment Module
- Direct access to HackerRank certifications  
- Skill tracking via external assessments  

### 📞 Help & Support
- FAQs  
- Support email  
- Simple help section  

---

## 🛠️ Tech Stack

### **Frontend**
- ReactJS  
- JavaScript (ES6+)  
- Tailwind CSS  
- Axios  
- React Router  

### **Backend**
- Django  
- Django REST Framework  
- Django ORM  
- JWT Authentication  

### **Database**
- SQLite3 (development)  
- PostgreSQL (future upgrade)  

### **Tools**
- VS Code  
- Git & GitHub  

---

## 🏗️ System Architecture
- Modular, scalable layered architecture  
- React frontend ↔ Django REST API  
- Clear separation of concerns  
- Media storage for resumes & certificates  
- Secure JWT-based communication  

---

## 🔐 API Endpoints (Key Endpoints)

| Feature | Endpoint | Method | Description |
|--------|----------|--------|-------------|
| Send OTP | `/send-otp-registration/` | POST | OTP for registration |
| Login OTP | `/send-otp-login/` | POST | OTP login |
| Verify OTP | `/verify-otp/` | POST | Verify user |
| Register | `/register/` | POST | Create user |
| Get Skills | `/skills/` | GET | Fetch user skills |
| Add Skill | `/skills/add/` | POST | Add skill |
| Delete Skill | `/skills/delete/<id>/` | DELETE | Delete skill |
| Upload Resume | `/resume/upload/` | POST | Upload resume |
| Download Resume | `/resume/download/` | GET | Get resume |
| Job Listings | `/jobs/skillbased/` | GET | Skill-based job suggestions |

---

## 🧩 Core Modules Implemented
- OTP + JWT authentication  
- Resume management  
- Skill CRUD with certificate verification  
- Interview preparation module  
- Assessments (HackerRank)  
- Skill-based job filtering  
- Notifications & settings  

---

## 🧪 Result Highlights
- Fully functional full-stack web application  
- Clean, responsive UI  
- Resume upload/download working seamlessly  
- Skill-based filtering tested successfully  
- Secure OTP + JWT flow implemented  
- Backend modular & scalable  
- Interview preparation resources accessible  

---

## 📈 Learning Outcomes
- Full-stack development (React + Django)  
- Designing REST APIs using DRF  
- State management in React  
- Secure file handling (media storage)  
- JWT authentication architecture  
- Integration with external platforms  
- Debugging, testing & API handling  
- Writing clean documentation  

---

## 🚧 Challenges Faced
- OTP expiration & timing issues  
- Token handling before JWT  
- Resume upload configuration  
- CORS issues between React & Django  
- Efficient job filtering logic  

All issues were resolved with stable fixes.

---

## 🔮 Future Scope
TalentTrack can be expanded with:

- AI-powered job recommendations  
- Skill gap detection & course suggestions  
- Internship portal  
- Recruiter dashboard  
- Virtual career fairs  
- Mobile app (React Native)  
- External job API integrations  
- Explainable AI-based recommendations  
- Student–recruiter communication system  

TalentTrack aims to evolve into a complete **employability ecosystem**.

---

## 👨‍💻 Developed By — Team 57, SR University
- D. Srawik  
- **Md. Moiz Ur Rehman**  
- V. Sai Raj  
- R. Shrujan  
- A. Vaninath  

**Guide:**  
Dr. S. Jamalaiah, Assistant Professor, School of CS & AI  

---
