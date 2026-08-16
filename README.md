<div align="center">
🚀 InterviewOS
Figma → Next.js Interview & Assessment Platform
<p> <img src="https://img.shields.io/badge/Next.js-15-000000?style=for-the-badge&logo=next.js&logoColor=white" /> <img src="https://img.shields.io/badge/React-TypeScript-3178C6?style=for-the-badge&logo=react&logoColor=white" /> <img src="https://img.shields.io/badge/CSS-Responsive-1572B6?style=for-the-badge&logo=css3&logoColor=white" /> <img src="https://img.shields.io/badge/Git-GitHub-F05032?style=for-the-badge&logo=git&logoColor=white" /> </p> <p> <img src="https://img.shields.io/badge/Status-Completed-2ea44f?style=for-the-badge" /> <img src="https://img.shields.io/badge/UI-Figma%20Matching-6f42c1?style=for-the-badge" /> <img src="https://img.shields.io/badge/Build-Passing-2ea44f?style=for-the-badge" /> </p> <p> <a href="https://github.com/Ramrampal/interviewos-figma-matching"> <img src="https://img.shields.io/badge/View%20on%20GitHub-181717?style=for-the-badge&logo=github&logoColor=white" /> </a> </p> </div>
📌 Overview

InterviewOS is a modern frontend implementation of an interview and candidate assessment platform built from Figma design references.

The project focuses on transforming visual designs into a functional, responsive, and maintainable Next.js application.

It includes authentication flows, candidate assessments, interview questions, coding challenges, an interactive coding workspace, background verification, and dashboard-related interfaces.

🎯 Main Goal: Convert Figma designs into a polished real-world frontend while maintaining reusable components, responsive layouts, consistent styling, and clean project architecture.

✨ Highlights
🎨 Figma-to-code implementation
⚛️ React component architecture
🚀 Next.js 15 App Router
🔷 TypeScript development
📱 Responsive UI
🧩 Reusable components
🔐 Authentication interfaces
📝 Candidate assessment workflow
💻 Coding challenge interface
🧑‍💻 Interactive coding workspace
⏱️ Assessment timer and progress
🔍 Background verification workflow
🎯 Production build validation
🛠️ Git & GitHub workflow
🖥️ Application Features
🔐 Authentication

InterviewOS includes a complete authentication UI flow:

Sign In
Create Account
Forgot Password
Reset Password
Check Email
📝 Candidate Assessment

The assessment experience includes:

Assessment Welcome Screen
Interview Questions
Assessment Progress
Timer-Based Assessment
Candidate Information
Interactive navigation
💻 Coding Challenge

The platform includes an interactive coding workflow:

Coding Challenge
Coding Workspace
Question Navigation
Assessment Timer
Progress Tracking
Developer-focused workspace
🔍 Background Verification

A dedicated background verification workflow includes:

Candidate Information
Candidate Status
Document Information
Verification Workflow
Reports & Settings
🎨 Figma → Code

One of the main objectives of this project was to accurately translate the provided Figma designs into a working frontend.

Development Process
        🎨 Figma Design
              │
              ▼
     🔎 Layout Analysis
              │
              ▼
    🧩 Component Planning
              │
              ▼
      ⚛️ React Implementation
              │
              ▼
        🎨 CSS Refinement
              │
              ▼
       🌐 Browser Testing
              │
              ▼
      📱 Responsive Testing
              │
              ▼
       🏗️ Production Build
              │
              ▼
        ✅ Final Validation

🛠️ Tech Stack
<div align="center">
Technology	Purpose
⚛️ React	UI Development
🚀 Next.js 15	Frontend Framework
🔷 TypeScript	Type-safe Development
🎨 CSS	Styling & Responsive Layout
📦 npm	Package Management
🌿 Git	Version Control
🐙 GitHub	Repository & Collaboration
🧭 App Router	Application Routing
</div>
🧩 Reusable Components

The project follows a reusable component-based structure.

AuthShell

Provides a common layout and visual structure for authentication pages.

Button

Reusable button component for consistent actions and styling.

Header

Provides shared navigation and header functionality across application screens.

📂 Project Structure
InterviewOS/
│
├── 📁 scripts/
│   └── build-docs.py
│
├── 📁 src/
│   │
│   ├── 📁 app/
│   │   │
│   │   ├── 📁 auth/
│   │   │   ├── check-email/
│   │   │   ├── create-account/
│   │   │   ├── forgot-password/
│   │   │   ├── reset-password/
│   │   │   └── sign-in/
│   │   │
│   │   ├── 📁 background-check/
│   │   ├── 📁 challenge/
│   │   ├── 📁 questions/
│   │   ├── 📁 welcome/
│   │   ├── 📁 workspace/
│   │   │
│   │   ├── layout.tsx
│   │   ├── page.tsx
│   │   └── styles.css
│   │
│   └── 📁 components/
│       ├── AuthShell.tsx
│       ├── Button.tsx
│       └── Header.tsx
│
├── .gitignore
├── next.config.mjs
├── next-env.d.ts
├── package.json
├── package-lock.json
└── tsconfig.json

🧭 Application Routes
Route	Description
/	Main Application
/welcome	Assessment Welcome
/questions	Interview Questions
/challenge	Coding Challenge
/workspace	Coding Workspace
/background-check	Background Verification
/auth/sign-in	Sign In
/auth/create-account	Create Account
/auth/forgot-password	Forgot Password
/auth/reset-password	Reset Password
/auth/check-email	Check Email
📸 Screenshots

Add screenshots from the application inside the screenshots/ directory.

Recommended structure:

screenshots/
│
├── sign-in.png
├── create-account.png
├── welcome.png
├── questions.png
├── challenge.png
├── workspace.png
└── background-check.png

🔐 Authentication
<p align="center"> <img src="./screenshots/sign-in.png" width="80%" alt="InterviewOS Sign In"/> </p>
📝 Assessment Welcome
<p align="center"> <img src="./screenshots/welcome.png" width="80%" alt="InterviewOS Welcome"/> </p>
❓ Interview Questions
<p align="center"> <img src="./screenshots/questions.png" width="80%" alt="InterviewOS Questions"/> </p>
💻 Coding Challenge
<p align="center"> <img src="./screenshots/challenge.png" width="80%" alt="InterviewOS Coding Challenge"/> </p>
🧑‍💻 Coding Workspace
<p align="center"> <img src="./screenshots/workspace.png" width="80%" alt="InterviewOS Coding Workspace"/> </p>
🔍 Background Check
<p align="center"> <img src="./screenshots/background-check.png" width="80%" alt="InterviewOS Background Check"/> </p>
🔄 Development Workflow
       🔎 Analyze
           │
           ▼
       🧩 Implement
           │
           ▼
         ▶️ Run
           │
           ▼
       👀 Compare
           │
           ▼
        🐛 Debug
           │
           ▼
       📱 Validate
           │
           ▼
        🏗️ Build
           │
           ▼
        📦 Commit
           │
           ▼
        🚀 Push

🧠 What I Learned

Working on InterviewOS gave me practical experience in:

🎨 Converting Figma designs into real interfaces
⚛️ Building reusable React components
🚀 Working with Next.js App Router
🔷 Developing with TypeScript
🎨 Creating responsive layouts with CSS
🐛 Debugging frontend UI issues
📱 Validating interfaces across different screen sizes
🧩 Structuring maintainable frontend code
🏗️ Validating production builds
🌿 Managing projects with Git and GitHub
🧪 Build Validation

The application was validated using the Next.js production build process.

Validation	Status
Application Compilation	✅ PASS
Type Checking	✅ PASS
Static Page Generation	✅ PASS
Route Generation	✅ PASS
Production Build	✅ PASS
📊 Project Status
Feature	Status
Figma UI Implementation	✅ Completed
Authentication Screens	✅ Completed
Assessment Flow	✅ Completed
Questions Interface	✅ Completed
Coding Challenge	✅ Completed
Coding Workspace	✅ Completed
Background Check	✅ Completed
Reusable Components	✅ Completed
Responsive UI	✅ Completed
Production Build	✅ Passed
GitHub Repository	✅ Published
🚀 Getting Started
Prerequisites

Make sure you have the following installed:

Node.js
npm
Git
Clone the Repository
git clone https://github.com/Ramrampal/interviewos-figma-matching.git

Navigate to the Project
cd interviewos-figma-matching

Install Dependencies
npm install

Start Development Server
npm run dev


The application will be available at:

http://localhost:3020

🏗️ Production Build

Create a production build with:

npm run build


Run the production application with:

npm start

📌 Project Objective

The purpose of InterviewOS was not only to create a visually similar interface, but to understand how a real-world design can be transformed into a structured and maintainable frontend application.

The project focuses on:
Design
  ↓
Structure
  ↓
Components
  ↓
Styling
  ↓
Responsiveness
  ↓
Testing
  ↓
Validation

👨‍💻 About the Developer
<div align="center">
Rampal Lodhi

Computer Science Engineering Student | Frontend & Software Developer

Passionate about building real-world applications, learning modern technologies, solving programming problems, and continuously improving software development skills.

</div>
🤝 Connect With Me
<p align="center"> <a href="https://github.com/Ramrampal"> <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" /> </a> <a href="#"> <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /> </a> </p>
⭐ Support

If you find this project useful or interesting, consider giving it a ⭐ on GitHub.

<p align="center"> <a href="https://github.com/Ramrampal/interviewos-figma-matching"> <img src="https://img.shields.io/github/stars/Ramrampal/interviewos-figma-matching?style=for-the-badge&logo=github" /> </a> </p>
<div align="center">
🚀 Keep Learning. Keep Building. Keep Improving.

InterviewOS

Figma-driven frontend implementation built with Next.js, React & TypeScript.

<br>

⭐ Built with dedication by Rampal Lodhi

</div>
