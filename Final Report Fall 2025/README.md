## Team Name: JQK

## Team Members:
- Quoc Huynh  
- Jay (Tung) Dao  
- Khai Nguyen  

## Project Advisor: Professor Seokki Lee

## Project Abstract:

JQK is an AI-assisted Learning Management System (LMS) designed to streamline classroom administration and enhance student learning. It features secure role-based authentication, modular course management, and teacher productivity tools like communication templates. Built with Next.js and Django, it leverages modern web technologies to provide a scalable, user-friendly educational platform.

---

### Table of Contents
- Team & Abstract  
- Project Description  
- User Stories and Design Diagrams  
- Project Tasks and Timeline  
- ABET Concerns Essay  
- PPT Slideshow  
- Self-Assessment Essays  
- Professional Biographies  
- Budget  
- Appendix  

---

## Project Description

### Overview

JQK is a private, TypeScript-based project designed for educational environments. The repository supports features such as course management, module creation, authentication (including social logins), and productivity tools, with both frontend and backend components.

### Purpose

The main goal is to provide a platform for teachers to manage classes, assignments, and track student progress, while giving students access to resources. It aims to streamline classroom processes and enhance engagement through structured management of educational content.

### Key Features

- **Course and Module Management:** Backend services handle creating, updating, and fetching modules tailored to different languages and levels.  
- **Authentication:** Supports standard and Google social login with role-based access (Teacher/Student).  
- **Productivity Tools:** Frontend templates for emails, announcements, and weekly planning.  
- **Technology Stack:** Frontend (React, Next.js, Radix UI), Backend (Python, Django, REST APIs).  

---

## User Stories and Design Diagrams (Based on Assignment #4)

### User Stories

- As a Teacher, I want to create a new course module so that I can organize learning materials for my students.  
- As a Student, I want to log in via Google so that I don't have to remember a new password.  
- As a Teacher, I want to use an email template so that I can quickly communicate with parents.  
- As an Administrator, I want to assign roles to users so that they have the correct permissions.  

### Design Diagrams

#### Level 0: Context Diagram

![Level 0 Diagram]([Design_Diagrams/d0.png])

Description: This diagram illustrates the interaction between the User (Teacher/Student), the JQK System, and external systems like Google Auth and Email Services.

#### Level 1: Container Diagram

![Level 1 Diagram]([Design_Diagrams/d1.png])

Description: This highlights the high-level technical choices. It shows the Web Application (Next.js) communicating with the API Application (Django) which reads/writes to the Database.

#### Level 2: Component Diagram

![Level 2 Diagram]([Design_Diagrams/d2.png])

Description: This details the internal components of the API Application, such as the AuthController, CourseController, and ProductivityService.

---

## Project Tasks and Timeline (Based on Assignment #5–6)

### Task List & Timeline (Fall 2025)

- **Week 1–3:** 
- **Week 4–6:** 
- **Week 7–10:**  
- **Week 11–13:**  
- **Week 14–15:**  

### Effort Matrix
<!--
| Feature / Task   | Jay (Frontend/UX)        | Quoc (Backend/API)         | Khai (DevOps/Integration) |
|------------------|---------------------------|------------------------------|----------------------------|
| Authentication   | UI Login Forms           | JWT & Social Auth Logic     | Security & Env Config      |
| Course Mgmt      | Dashboard UI             | Database Models & API       | Database Migrations        |
| DevOps           | Vercel Deployment        | Docker Setup                | CI/CD Pipelines            |
| Productivity     | Template UI Components   | N/A                          | Testing Automation         |
-->
---

## ABET Concerns Essay (Based on Assignment #7)

Economic:
Our capstone has a near-zero cash budget, so we will prioritize open-source frameworks, free
academic tiers, and university resources; this constrains cloud choices (e.g., modest compute/storage),
pushes us toward serverless or credits-eligible services, and requires a lean MVP that can run on a single
database and one API. These limits shape scope by forcing simple, automatable operations—seed data,
scripted deployments, and observability we can maintain without paid tools. Legal: Because the system
stores student data and learning records, we must align with education-privacy expectations (FERPA-style
principles) and avoid ingesting any copyrighted materials without permission; that narrows content
sources, requires consent flows, and obligates data-retention and export features. Additionally, we will
license third-party assets carefully and segregate any model prompts/outputs that include copyrighted text
to prevent improper redistribution. Security & Privacy: We will implement role-based access control
(student/teacher/admin), encrypt data at rest and in transit, and minimize personally identifiable
information; this constrains schema design (clear data boundaries), logging (no sensitive payloads), and
feature choices (opt-in analytics, privacy-preserving defaults). AI features must include audit logs and
citation trails so that teachers can review model suggestions and students can contest automated feedback.
We will also harden uploads (MIME/type checks, virus scanning) and follow the principle of least
privilege in API/service accounts. Diversity & Cultural Impact: Our users span English/ Vietnamese/
Chinese contexts and mixed bandwidth environments; this constrains UX (simple language, multilingual
UI, offline-tolerant caching) and content (examples that respect local classroom norms). Pronunciation
and feedback must be inclusive of accents and tone errors without stigmatizing learners, and accessibility
will follow WCAG practices for color contrast, captions, and keyboard navigation. Together, these
constraints steer us toward a small, reliable core: transparent AI assistance with human oversight,
privacy-first data flows, and an interface that degrades gracefully on low-end devices. By embracing these
boundaries early, we reduce risk, protect learners and instructors, and deliver a credible pilot we can scale
only after evidence of value.


---

## PPT Slideshow (Based on Assignment #8)

[Click here to view our Final Presentation Slides]([https://docs.google.com/presentation/d/1YTXQrST3H3Vr2R5uZ8zvJjgYitngvk0xuAOVsgVG3io/edit?usp=sharing])

---

## Self-Assessment Essays 

### Quoc Huynh  
**The Foundation of an AI-Assisted Learning Platform**

My senior design project is an exciting culmination of my academic journey and professional experiences. We are building an AI-assisted Learning Management System (LMS) designed to streamline classroom administration for teachers and enhance the learning experience for students. From my perspective, this project is a unique opportunity to apply the full spectrum of my computer science education to a real-world problem. It's not just about writing code; it's about solving complex, multi-faceted challenges in software architecture, user experience design, and data management.

#### Applying Academic Knowledge & Co-op Experiences

Our collective college curriculum has provided a strong technical foundation. Courses like CS 3050: Software Engineering taught us systematic approaches to project management, while CS 4051: Database Systems gave us the skills to design our schema. As an Application and Data Analyst Co-op at AtriCure, I validated Azure ETL pipelines and maintained extensive project documentation. This taught me the importance of writing clean, well-documented code, a practice we've committed to in our team norms.

#### Motivation and Evaluation

My motivation is rooted in the desire to build technology that genuinely helps educators. My preliminary approach involves starting with a Minimum Viable Product (MVP) containing core functionalities before adding AI tools. I will measure success by the deployment of a functional web application and will self-evaluate through code reviews and tracking my contributions against our sprint goals.

---

### Jay (Tung) Dao  
[ACTION REQUIRED: PASTE JAY'S ESSAY HERE]

### Khai Nguyen  
[ACTION REQUIRED: PASTE KHAI'S ESSAY HERE]

---

## Professional Biographies
### Quoc Huynh



#### Contact Information
**Name:** Quoc Huynh  
**Location:** Cincinnati, OH 45225  
**Email:** huynhqk@mail.uc.edu  
**LinkedIn:** [linkedin.com/in/quoc-huynh-uc](https://linkedin.com/in/quoc-huynh-uc)

---

#### Co-op Work Experience

##### Application and Data Analyst (Seasonal)  
**AtriCure, Inc | Mason, OH**  
*January 2024 – December 2024*  
- Validated 13+ Azure ETL pipelines for data ingestion from GP, MS Access, and Azure Lake Storage into SQL MI, improving data flow efficiency and reducing costs.  
- Designed PowerApps email-triggered flows for Power BI dataset refresh and pipeline status, eliminating 90% of manual monitoring work.  
- Maintained 150+ pages of project documentation, ensuring accuracy and accessibility for 4 cross-functional team members.  

**Skills:** Azure Data Factory, SQL MI, PowerApps, Power BI, Data Documentation  

---

##### UI/UX Designer & Front-End Developer  
**INCOM | Ho Chi Minh City, Vietnam**  
*September 2023 – November 2023*  
- Conducted user research and transformed 10+ key functionalities into interactive features for “BKASim” and “OKR Tool” dashboards.  
- Created 50+ wireframes and mockups using Balsamiq and Figma; implemented designs into functional web interfaces with HTML and CSS.  
- Resolved 200+ bugs during 15+ weekly code reviews, ensuring stakeholder satisfaction and timely delivery.  

**Skills:** Figma, Balsamiq, HTML, CSS, Front-End Development, Agile Collaboration  

---

##### IT Technician  
**TTS Technology Corporation | Ho Chi Minh City, Vietnam**  
*September 2023 – December 2023*  
- Assembled and optimized 100+ server PCs, ensuring 100% client satisfaction.  
- Deployed CCTV systems in 2 client warehouses, improving security and reducing inefficiencies by 15%.  
- Performed 30+ on-site inspections, diagnosing system issues and reducing downtime by 60%.  

**Skills:** Server Maintenance, Hardware Assembly, CCTV Deployment, Troubleshooting  

---

##### Coding Workshop Coordinator  
**CEAS Library | Cincinnati, OH**  
*January 2023 – May 2023*  
- Coordinated 40+ coding workshops, handling logistics, scheduling, and promotions.  
- Delivered 5-part Python workshops, teaching 50+ students fundamental programming and data manipulation.  
- Increased student and faculty engagement by 30% through structured improvements to content delivery.  

**Skills:** Python, Teaching, Workshop Coordination, Event Management  

---

##### IT Helpdesk Analyst  
**College of Nursing, CATER | Cincinnati, OH**  
*February 2022 – December 2022*  
- Resolved 500+ technical support requests, achieving 90% satisfaction.  
- Installed and maintained equipment in 100+ lecture halls and labs, ensuring 95% uptime.  

**Skills:** Technical Support, Hardware/Software Maintenance, Customer Service  

---

#### Project Sought
I am seeking a **Capstone Project** that combines my interests in **data engineering, web development, and cloud-based solutions**. Ideally, I would like to contribute to a project that involves:  

- **Data Engineering & Cloud:** Designing or optimizing data pipelines, working with Azure/AWS services, and developing dashboards for insights.  
- **Web Development & UI/UX:** Building responsive and user-friendly interfaces that integrate with backend systems.  
- **Applied Innovation:** Projects that provide tangible impact, such as process automation, workflow optimization, or community engagement platforms.  

My goal is to leverage both my **technical expertise** (Python, SQL, Azure, ReactJS) and **collaborative experience** (documentation, cross-team coordination, teaching) to contribute meaningful results to a capstone project team.


### Jay (Tung) Dao  
[ACTION REQUIRED: PASTE JAY'S BIO HERE]

### Khai Nguyen  
[ACTION REQUIRED: PASTE KHAI'S BIO HERE]

---

## Budget

**Expenses to Date:** $0.00

**Donated Items:**  
- GitHub Student Developer Pack (Hosting, CI/CD minutes) – Value: ~$100/month (Donated by GitHub)  
- Personal Laptops/Hardware – Provided by students.  

---

## Appendix

- Code Repository: https://github.com/kiq2908/Senior-Design  
- Meeting Notes: [ACTION REQUIRED: LINK TO MEETING NOTES]  

---

## Effort Justification

- **Quoc:** 45+ hours (AI Research, UI Design, Frontend Development).  
- **Jay:** 45+ hours  
- **Khai:** 45+ hours
