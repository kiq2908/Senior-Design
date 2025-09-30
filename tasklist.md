### Tasklist.md

### JQK - AI-assisted Learning Platform Task List (Assignment #5)

**Team Members:** Jay (Frontend/UX), Quoc (Backend/API), Khai (Integration/DevOps)

| Task # | Responsible | Task Statement |
| :---: | :---: | :--- |
| **I. Core Infrastructure & Data** | | |
| 1 | Khai | **Initialize** the monorepo structure and configure initial Git branches and GitHub Projects Kanban board. |
| 2 | Quoc | **Design** the PostgreSQL database schema for Users, Courses, and Modules, ensuring support for role-based access. |
| 3 | Khai | **Configure** the CI/CD pipeline using GitHub Actions to automate testing and deployment for both frontend and backend services. |
| 4 | Quoc | **Develop** the core Python/Django settings and environment for API development, including necessary package installations. |
| 5 | Khai | **Set up** the cloud hosting environment (e.g., AWS or Azure) for the Django Backend and PostgreSQL instance. |
| **II. Authentication & Frontend** | | |
| 6 | Quoc | **Develop** the Authentication API endpoints for user registration, standard login, and secure token generation. |
| 7 | Jay | **Design** and **Develop** the responsive login, registration, and user profile pages in React/Next.js. |
| 8 | Quoc | **Integrate** the Google Social Sign-On (SSO) service into the Authentication API for user convenience. |
| 9 | Jay | **Implement** role-based navigation and access control on the Frontend to ensure users only see content relevant to their role (Student/Teacher). |
| 10 | Jay | **Specify** the main UI/UX components (e.g., buttons, forms, navigation) using a component library for consistency across the application. |
| **III. Course, Content, & Materials** | | |
| 11 | Quoc | **Develop** the CRUD API endpoints for Teacher-driven Course and Module Management, including file/video upload handling. |
| 12 | Jay | **Create** the "Materials Creation" workflow on the Teacher UI, allowing teachers to upload and publish content. |
| 13 | Quoc | **Investigate** and **Select** a suitable Django library for handling large file uploads and secure storage (e.g., Cloud Storage integration). |
| 14 | Jay | **Develop** the Student Module Viewer interface to easily access and display course materials (files, videos) based on their enrolled courses. |
| **IV. Advanced Features & Analysis** | | |
| 15 | Quoc | **Develop** the **"Finalize & Grade"** API endpoint to process quiz submissions and save grades to the database. |
| 16 | Khai | **Integrate** the Backend API with the **AI/Speech Service** (e.g., via a message queue or async worker) to handle data analysis and feedback requests. |
| 17 | Jay | **Implement** the **"Start Quiz"** and **"Submit Answers"** flows on the Student UI, connecting to the relevant backend endpoints. |
| 18 | Khai | **Document** the API contract for the AI Service integration, detailing required inputs (e.g., text, audio) and expected output (e.g., feedback, quiz generation). |
| 19 | Quoc | **Refine** the database schema to store AI-generated content and performance feedback data. |
| 20 | Jay | **Design** the Teacher Dashboard to display **AI-assisted student performance analysis** and overall course grades. |