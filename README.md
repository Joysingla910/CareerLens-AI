# 🚀 CareerLens AI

<div align="center">

![React](https://img.shields.io/badge/React-19-blue?style=for-the-badge&logo=react)
![NodeJS](https://img.shields.io/badge/Node.js-Express-green?style=for-the-badge&logo=node.js)
![MongoDB](https://img.shields.io/badge/MongoDB-Database-green?style=for-the-badge&logo=mongodb)
![Gemini](https://img.shields.io/badge/Google-Gemini-orange?style=for-the-badge&logo=google)
![JWT](https://img.shields.io/badge/JWT-Authentication-red?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)

### AI Powered Resume Analysis & Interview Preparation Platform

Analyze your resume, compare it with a Job Description, identify missing skills, generate interview questions, build a preparation roadmap, and create an ATS-friendly resume using Generative AI.

</div>

---

# 📖 Project Overview

CareerLens AI is a full-stack AI-powered web application designed to help job seekers prepare for technical interviews more effectively.

The platform combines Resume Analysis, Job Description Matching, Skill Gap Detection, Personalized Interview Question Generation, and ATS Resume Optimization into one seamless workflow.

Instead of manually comparing resumes with job descriptions, CareerLens AI automates the entire process using Google's Gemini Large Language Model.

The application generates:

- Resume Analysis
- Job Match Report
- Skill Gap Detection
- Technical Questions
- HR Questions
- Interview Preparation Roadmap
- ATS Friendly Resume PDF

The entire workflow is built using modern Full Stack technologies including React, Node.js, Express, MongoDB, JWT Authentication, Multer, Puppeteer and Google Gemini API.

---

# 🎯 Problem Statement

Most students face the following challenges before applying for jobs:

- They don't know whether their resume matches the job description.
- They don't know which skills are missing.
- They don't know what interview questions may be asked.
- They spend hours manually modifying resumes.
- They don't receive a personalized preparation roadmap.

As a result, interview preparation becomes time-consuming and inefficient.

CareerLens AI solves this problem by using Artificial Intelligence to automate the complete interview preparation process.

---

# 💡 Solution

CareerLens AI acts as an AI Career Assistant.

Users simply:

1. Upload Resume
2. Paste Job Description

The platform automatically:

✔ Extracts Resume Information

✔ Understands Job Requirements

✔ Detects Missing Skills

✔ Generates Personalized Interview Questions

✔ Suggests Learning Roadmap

✔ Creates ATS Friendly Resume

✔ Stores Reports for Future Access

This reduces manual effort while significantly improving interview readiness.

---

# ✨ Key Features

## 🤖 AI-Powered Resume Analysis
- Upload your resume in PDF format.
- Extracts relevant information from the resume.
- Analyzes technical skills, projects, education, and experience.
- Generates AI-powered insights using Google Gemini.

---

## 📄 Job Description Matching
- Compare your resume with any job description.
- Identify matching skills.
- Detect missing technologies and keywords.
- Calculate overall resume-job compatibility.

---

## 🎯 Skill Gap Detection
The platform identifies:

- Missing Technical Skills
- Missing Tools & Frameworks
- Missing Soft Skills
- Learning Priorities

This helps candidates understand exactly what they need to improve before interviews.

---

## 💬 Personalized Interview Questions

CareerLens AI generates:

- Technical Interview Questions
- Behavioral Questions
- HR Interview Questions
- Follow-up Questions

Questions are generated specifically according to the uploaded resume and job description.

---

## 📚 Preparation Roadmap

The AI creates a structured preparation plan including:

- Important Topics
- Recommended Technologies
- Practice Strategy
- Interview Tips
- Learning Priority

---

## 📄 ATS-Friendly Resume Generation

Generate a clean ATS-compatible resume in PDF format using Puppeteer.

---

## 🔐 Secure Authentication

- User Registration
- User Login
- JWT Authentication
- Protected Routes
- Token Blacklisting
- Secure API Access

---

## 📊 Report Management

Users can:

- View Previous Reports
- Revisit Analysis
- Download Resume PDF
- Generate Multiple Reports

---

# 🛠 Tech Stack

## Frontend

- React.js
- Vite
- SCSS
- Context API
- Axios
- React Router

---

## Backend

- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT
- Multer
- Puppeteer

---

## Artificial Intelligence

- Google Gemini API
- Prompt Engineering

---

## Development Tools

- VS Code
- Git
- GitHub
- Postman
- npm

---

# 📂 Project Structure

```
CareerLens-AI
│
├── Backend
│   │
│   ├── src
│   │   ├── config
│   │   ├── controllers
│   │   ├── middlewares
│   │   ├── models
│   │   ├── routes
│   │   ├── services
│   │   └── app.js
│   │
│   ├── server.js
│   └── package.json
│
├── Frontend
│   │
│   ├── src
│   │   ├── features
│   │   ├── hooks
│   │   ├── pages
│   │   ├── services
│   │   ├── styles
│   │   └── App.jsx
│   │
│   └── package.json
│
└── README.md
```

---

# 🏗 System Architecture

```
                  User
                    │
                    ▼
           React Frontend (Vite)
                    │
         Axios HTTP Requests
                    │
                    ▼
           Express.js Backend
                    │
      ┌─────────────┴─────────────┐
      │                           │
      ▼                           ▼
 Google Gemini API          MongoDB Database
      │                           │
      └─────────────┬─────────────┘
                    │
                    ▼
          Interview Report
                    │
                    ▼
             React Dashboard
```

---

# 🔄 Complete Workflow

```
User Login
      │
      ▼
Upload Resume
      │
      ▼
Paste Job Description
      │
      ▼
Backend Validation
      │
      ▼
Resume Parsing
      │
      ▼
Prompt Engineering
      │
      ▼
Google Gemini API
      │
      ▼
AI Response
      │
      ▼
Store Report in MongoDB
      │
      ▼
Display Report
      │
      ▼
Download ATS Resume PDF
```

---

# 🔐 Authentication Flow

CareerLens AI uses **JWT (JSON Web Token)** based authentication to securely manage user sessions.

### Authentication Process

```text
User Registration
        │
        ▼
Password Hashing
        │
        ▼
Store User in MongoDB
        │
        ▼
User Login
        │
        ▼
JWT Token Generation
        │
        ▼
Protected API Access
        │
        ▼
Logout
        │
        ▼
Token Blacklisting
```

### Security Features

- Password hashing before storage
- JWT-based authentication
- Protected Routes
- Token Blacklisting on Logout
- Environment Variables for Secrets

---

# 🤖 AI Processing Pipeline

Google Gemini powers the intelligence behind CareerLens AI.

The AI analyzes:

- Resume
- Job Description
- Skills
- Projects
- Experience
- Education

and generates a complete interview preparation report.

## AI Workflow

```text
Resume
      +
Job Description
      │
      ▼
Prompt Engineering
      │
      ▼
Google Gemini API
      │
      ▼
Structured JSON Response
      │
      ▼
Interview Report
```

The generated report contains:

- Resume Summary
- Match Analysis
- Skill Gap Analysis
- Technical Questions
- HR Questions
- Behavioral Questions
- Learning Roadmap

---

# 📄 Resume Upload Flow

The application supports resume upload using **Multer**.

```text
User Selects Resume
        │
        ▼
React File Input
        │
        ▼
FormData
        │
        ▼
Axios Request
        │
        ▼
Express Route
        │
        ▼
Multer Middleware
        │
        ▼
Controller
        │
        ▼
Gemini AI
```

Supported format:

- PDF

---

# 🗄 Database Design

## User Collection

```text
User
│
├── name
├── email
├── password
└── createdAt
```

---

## Interview Report Collection

```text
InterviewReport
│
├── userId
├── jobDescription
├── resumeAnalysis
├── skillGap
├── technicalQuestions
├── behavioralQuestions
├── preparationPlan
├── atsResume
└── createdAt
```

---

# 🌐 REST API

## Authentication APIs

| Method | Endpoint | Description |
|---------|----------|-------------|
| POST | `/auth/register` | Register User |
| POST | `/auth/login` | Login User |
| POST | `/auth/logout` | Logout User |

---

## Interview APIs

| Method | Endpoint | Description |
|---------|----------|-------------|
| POST | `/interview/generate` | Generate AI Interview Report |
| GET | `/interview/:id` | Get Interview Report |
| GET | `/interview` | Get All Reports |
| GET | `/interview/resume/pdf` | Download Resume PDF |

---

# ⚡ Request Lifecycle

```text
Browser
    │
    ▼
React Components
    │
    ▼
Axios API
    │
    ▼
Express Router
    │
    ▼
Authentication Middleware
    │
    ▼
Controller
    │
    ▼
Business Logic
    │
    ▼
Gemini API / MongoDB
    │
    ▼
JSON Response
    │
    ▼
React UI
```

---

# 🎨 Frontend Highlights

- Responsive UI
- React Context API
- Protected Routing
- SCSS Styling
- Axios API Integration
- File Upload Support
- Dynamic Report Rendering
- Resume Download

---

# ⚙️ Backend Highlights

- RESTful API Architecture
- JWT Authentication
- MongoDB Integration
- Multer File Upload
- AI Service Layer
- Error Handling
- Modular Folder Structure
- Secure Environment Variables

---

# 🚀 Getting Started

## Prerequisites

Before running the project, make sure you have:

- Node.js (v18 or above)
- npm
- MongoDB Atlas or Local MongoDB
- Google Gemini API Key
- Git

---

# ⚙️ Installation

## Clone Repository

```bash
git clone https://github.com/Joysingla910/CareerLens-AI.git
```

---

## Backend Setup

```bash
cd Backend
npm install
npm start
```

---

## Frontend Setup

```bash
cd Frontend
npm install
npm run dev
```

---

# 🔑 Environment Variables

Create a `.env` file inside the Backend directory.

```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
GOOGLE_GENAI_API_KEY=your_gemini_api_key
```

---

# 📸 Screenshots


## Login Page

<img width="100%" src="screenshots/login.png"/>

---

## Dashboard

<img width="100%" src="screenshots/dashboard.png"/>

---

## AI Interview Report

<img width="100%" src="screenshots/report.png"/>

---

## ATS Resume PDF

<img width="100%" src="screenshots/resume.png"/>

---

# 📈 Future Enhancements

- 🎙️ AI Mock Interview with Voice Support
- 🗣️ Real-time Speech Evaluation
- 📊 Resume ATS Score
- 📄 AI Cover Letter Generator
- 🌍 Multi-language Support
- 📅 Interview Progress Tracker
- 🧠 Company-specific Interview Preparation
- 📈 Resume Improvement Suggestions
- 🎥 Video Interview Analysis
- ☁️ Cloud Deployment

---

# 📚 Key Learnings

Building CareerLens AI helped in understanding:

- Full Stack Web Development
- REST API Design
- Authentication & Authorization
- React Context API
- MongoDB Data Modeling
- File Upload using Multer
- Prompt Engineering
- Google Gemini Integration
- PDF Generation using Puppeteer
- Git & GitHub Workflow
- Secure Backend Development

---

# 💼 Why I Built This Project

Preparing for interviews often requires switching between multiple platforms for resume analysis, interview questions, ATS optimization, and skill gap identification.

CareerLens AI brings all these functionalities together into one intelligent platform powered by Generative AI, making interview preparation faster, more personalized, and more effective.

---

# 🚀 Deployment

The application can be deployed using:

- Frontend → Vercel
- Backend → Render / Railway
- Database → MongoDB Atlas

---

# 🤝 Contributing

Contributions, suggestions, and improvements are always welcome.

1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Open a Pull Request

---

# 📬 Contact

**Joy Singla**

📧 Email: joysingla3121@gmail.com

💼 LinkedIn: linkedin.com/in/joy-singla-923005357

💻 GitHub: https://github.com/Joysingla910

---

# ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.

It helps others discover the project and motivates future improvements.

---

# 📄 License

This project is licensed under the MIT License.

---

<div align="center">

## ⭐ Thank You for Visiting ⭐

**CareerLens AI — Empowering Smarter Interview Preparation with Generative AI**

Made with ❤️ using React, Node.js, MongoDB & Google Gemini

</div>