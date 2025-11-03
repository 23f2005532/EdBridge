# EdBridge — A Digital Companion for B.Ed. Students and Teachers

> _Bridging the gap between theory and practice in teacher education._

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Status](https://img.shields.io/badge/status-Development-orange.svg)
![Built with](https://img.shields.io/badge/Built%20with-Python%20%7C%20Vue.js%20%7C%20TailwindCSS-green)

---

## Introduction

The **Integrated B.Sc. B.Ed. program** prepares reflective, tech-competent teachers. Yet, most tasks—lesson plans, reflections, and feedback—remain offline, creating inefficiency and disorganization.

**EdBridge** is a web application that acts as a *digital companion* for both B.Ed. students and teacher educators. It centralizes **lesson planning, reflections, feedback, communication, and resources** into a single digital space.

---

## Objectives

- Build a **user-friendly digital platform** for managing practicum activities.  
- Digitize lesson plans, reflective journals, and internship records.  
- Enable smooth **student–mentor collaboration** and organized feedback.  
- Foster the integration of **educational technology** in teacher training.  
- Track personal progress and reflective growth over time.

---

## Scope

EdBridge focuses on **academic and professional development** (not administration).  
It serves:

- **Students:** Create lesson plans, submit assignments, maintain reflections, and track internships.  
- **Mentors:** Review submissions, provide structured feedback, and monitor progress.  

**Target Users:** Initially, 7th-semester B.Sc. B.Ed. students during internship and practicum.  
**Future Scope:** Expansion to all semesters and institutions.

---

## Problem Statement

Current teacher training suffers from:

- Manual, scattered records.  
- Limited feedback cycles.  
- Weak linkage between theory and classroom practice.  
- Lack of digital tools for collaboration.  

**EdBridge** addresses these by digitizing the workflow and creating an interactive feedback-driven environment.

---

## Key Features (Phase 1)

- 🎓 **Student Dashboard** — Overview of activities and mentor feedback.  
- 🧾 **Lesson Planning Module** — Create lesson plans using NCERT/NCTE templates.  
- ✍️ **Reflection Journal** — Record daily reflections and receive mentor comments.  
- 📚 **Assignment Tracker** — Submit assignments digitally and track progress.  
- 🏫 **Internship Logbook** — Maintain attendance and school activity records.  
- 💬 **Communication Tools** — Announcements, peer discussions, and private chat.  
- 📂 **Resource Library** — Shared teaching materials and lesson exemplars.

---

## Technology Stack

| Component | Technology |
|------------|-------------|
| **Frontend** | Vue.js / React + Tailwind CSS / Bootstrap |
| **Backend** | Flask / FastAPI / Django |
| **Database** | SQLite / PostgreSQL |
| **Authentication** | Flask-Login / JWT |
| **Deployment** | Railway / Render / Vercel |
| **Extras** | Celery (Async Tasks), Redis (Caching) |

---

## Implementation Plan

| Phase | Duration | Description |
|--------|-----------|-------------|
| **Phase 1** | 4–6 weeks | Authentication, dashboards, and basic resource sharing |
| **Phase 2** | 6–8 weeks | Lesson planning, reflection journal, internship logbook |
| **Phase 3** | 4 weeks | Feedback system, analytics, and mobile optimization |
| **Phase 4** | Continuous | Iterative improvement and new features |

---

## Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/23f2005532/edbridge.git
cd edbridge
```

### 2. Backend Setup (Flask Example)
```bash
pip install -r requirements.txt
python app.py
```

### 3. Frontend Setup (Vue Example)
```bash
cd frontend
npm install
npm run dev
```

### 4. Access Application
Visit **http://localhost:3000** (or configured port).

---

## Evaluation Metrics

| Criteria | Measurement |
|-----------|-------------|
| **Usability** | User feedback and ease of navigation |
| **Functionality** | Smooth operation of all main features |
| **Accessibility** | Responsive for mobile and desktop |
| **Performance** | Fast load times and reliable backend |
| **Adoption** | Number of active student and mentor users |

---

## Future Enhancements

- **AI-based feedback** for lesson plans and reflections.  
- **Micro-teaching uploads** and video feedback.  
- **Digital teaching portfolios** and peer review tools.  
- **Institutional dashboards** for marks, attendance, and analytics.  

---

## Conclusion

**EdBridge** transforms the B.Ed. practicum into an organized, reflective, and tech-driven experience. By uniting students and mentors in a single digital ecosystem, it simplifies record-keeping, deepens reflection, and fosters growth.

---

### Core Phase-1 Summary

- Student & Mentor Login  
- Dashboard Overview  
- Lesson Plan Creator (NCTE Template)  
- Reflection Journal  
- Assignment Upload & Feedback  
- Internship Logbook  
- Resource Library  
- Discussion & Announcement System  

---

**Developed by:** *Ehtesham (B.Sc. B.Ed. Student, Central University of Jharkhand)*  
**Mentor:** *Sumanta Halder*  
**License:** MIT  
**Project Type:** Personal + Supported Academic Project  
