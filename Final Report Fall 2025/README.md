## Team Name: JQK

## Table of Contents
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

## Team & Abstract

Team Members:
- Quoc Huynh
- Jay (Tung) Dao
- Khai Nguyen

Advisor: Lee Seokki

Project Abstract:

JQK is an AI-assisted Learning Management System (LMS) designed to streamline classroom administration and enhance student learning. It features secure role-based authentication, modular course management, and teacher productivity tools like communication templates. Built with Next.js and Django, it leverages modern web technologies to provide a scalable, user-friendly educational platform.

## Project Description (Based on Assignment #2)

### Overview

JQK is a private, TypeScript-based project designed for educational environments. The repository supports features such as course management, module creation, authentication (including social logins), and productivity tools, with both frontend and backend components.

### Purpose

The main goal is to provide a platform for teachers to manage classes, assignments, and track student progress, while giving students access to resources. It aims to streamline classroom processes and enhance engagement through structured management of educational content.

### Key Features

- Course and Module Management: Backend services handle creating, updating, and fetching modules tailored to different languages and levels.
- Authentication: Supports standard and Google social login with role-based access (Teacher/Student).
- Productivity Tools: Frontend templates for emails, announcements, and weekly planning.

### Technology Stack

- Frontend: React, Next.js, Radix UI (TypeScript)
- Backend: Python, Django, REST APIs

## User Stories and Design Diagrams (Based on Assignment #4)

### User Stories

- As a Teacher, I want to create a new course module so that I can organize learning materials for my students.
- As a Student, I want to log in via Google so that I don't have to remember a new password.
- As a Teacher, I want to use an email template so that I can quickly communicate with parents.
- As an Administrator, I want to assign roles to users so that they have the correct permissions.

### Design Diagrams

#### Level 0: Context Diagram

![Level 0 Diagram]([ACTION REQUIRED: PASTE LINK TO YOUR LEVEL 0 IMAGE HERE])

Description: This diagram illustrates the interaction between the User (Teacher/Student), the JQK System, and external systems like Google Auth and Email Services.

#### Level 1: Container Diagram

![Level 1 Diagram]([ACTION REQUIRED: PASTE LINK TO YOUR LEVEL 1 IMAGE HERE])

Description: This highlights the high-level technical choices. It shows the Web Application (Next.js) communicating with the API Application (Django) which reads/writes to the Database.

#### Level 2: Component Diagram

![Level 2 Diagram]([ACTION REQUIRED: PASTE LINK TO YOUR LEVEL 2 IMAGE HERE])

Description: This details the internal components of the API Application, such as the AuthController, CourseController, and ProductivityService.

## Project Tasks and Timeline (Based on Assignment #5-6)

### Task List & Timeline (Fall 2025)

- Week 1-3: Requirements gathering, DB Schema V1 design, Skeleton UI setup.
- Week 4-6: Authentication implementation (Social Login & JWT), CI/CD pipeline setup.
- Week 7-10: Course and Module CRUD operations (Backend) and UI integration (Frontend).
- Week 11-13: Productivity Tools implementation (Email templates).
- Week 14-15: Testing, Bug fixes, and Final Presentation prep.

### Effort Matrix

Feature / Task | Jay (Frontend/UX) | Quoc (Backend/API) | Khai (DevOps/Integration)
---|---|---|---
Authentication | UI Login Forms | JWT & Social Auth Logic | Security & Env Config
Course Mgmt | Dashboard UI | Database Models & API | Database Migrations
DevOps | Vercel Deployment | Docker Setup | CI/CD Pipelines
Productivity | Template UI Components | N/A | Testing Automation

## ABET Concerns Essay (Based on Assignment #7)

[ACTION REQUIRED: PASTE YOUR ABET ESSAY HERE]

(Note: This essay typically discusses Economic, Environmental, Social, Political, Ethical, Health & Safety, and Manufacturability constraints.)

## PPT Slideshow (Based on Assignment #8)

[Click here to view our Final Presentation Slides]([ACTION REQUIRED: PASTE LINK TO GOOGLE SLIDES OR PDF])

## Self-Assessment Essays (Based on Assignment #3)

### Quoc Huynh

#### The Foundation of an AI-Assisted Learning Platform

My senior design project is an exciting culmination of my academic journey and professional experiences. We are building an AI-assisted Learning Management System (LMS) designed to streamline classroom administration for teachers and enhance the learning experience for students. From my perspective, this project is a unique opportunity to apply the full spectrum of my computer science education to a real-world problem. It's not just about writing code; it's about solving complex, multi-faceted challenges in software architecture, user experience design, and data management.

#### Applying Academic Knowledge & Co-op Experiences

Our collective college curriculum has provided a strong technical foundation. Courses like CS 3050: Software Engineering taught us systematic approaches to project management, while CS 4051: Database Systems gave us the skills to design our schema. As an Application and Data Analyst Co-op at AtriCure, I validated Azure ETL pipelines and maintained extensive project documentation. This taught me the importance of writing clean, well-documented code, a practice we've committed to in our team norms.

#### Motivation and Evaluation

My motivation is rooted in the desire to build technology that genuinely helps educators. My preliminary approach involves starting with a Minimum Viable Product (MVP) containing core functionalities before adding AI tools. I will measure success by the deployment of a functional web application and will self-evaluate through code reviews and tracking my contributions against our sprint goals.

### Jay (Tung) Dao

[ACTION REQUIRED: PASTE JAY'S ESSAY HERE]

### Khai Nguyen

[ACTION REQUIRED: PASTE KHAI'S ESSAY HERE]

## Professional Biographies (Based on Assignment #1)

### Quoc Huynh

Location: Cincinnati, OH 45225
Email: huynhqk@mail.uc.edu
LinkedIn: linkedin.com/in/quoc-huynh-uc

Quoc is a Computer Science student with a strong background in data engineering and web development. He completed a seasonal co-op as an Application and Data Analyst at AtriCure, Inc. (Jan 2024 – Dec 2024), where he validated 13+ Azure ETL pipelines and designed PowerApps flows to eliminate manual monitoring. Previously, he worked as a UI/UX Designer & Front-End Developer at INCOM in Vietnam, creating wireframes and resolving bugs in a fast-paced Agile environment. He is seeking a capstone project that combines Data Engineering, Cloud solutions, and Web Development.

### Jay (Tung) Dao

[ACTION REQUIRED: PASTE JAY'S BIO HERE]

### Khai Nguyen

[ACTION REQUIRED: PASTE KHAI'S BIO HERE]

## Budget

Expenses to Date: $0.00

### Donated Items:
- GitHub Student Developer Pack (Hosting, CI/CD minutes) - Value: ~$100/month (Donated by GitHub)
- Personal Laptops/Hardware - Provided by students.

## Appendix

Code Repository: https://github.com/kiq2908/Senior-Design

Meeting Notes: [ACTION REQUIRED: LINK TO MEETING NOTES]

### Effort Justification:
- Quoc: 45+ hours (Backend API development, Database Schema, Authentication logic).
- Jay: 45+ hours (Frontend UX/UI, Component library, Responsive design).
- Khai: 45+ hours (CI/CD setup, Dockerization, Integration testing).
