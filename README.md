
````markdown
<div align="center">

# InterviewOS

### Figma to Next.js UI Implementation and Frontend Debugging

<p>
  <img src="https://img.shields.io/badge/Next.js-15-black?style=for-the-badge&logo=next.js" />
  <img src="https://img.shields.io/badge/React-TypeScript-3178C6?style=for-the-badge&logo=typescript" />
  <img src="https://img.shields.io/badge/CSS-Responsive-1572B6?style=for-the-badge&logo=css3" />
  <img src="https://img.shields.io/badge/Git-GitHub-F05032?style=for-the-badge&logo=git" />
</p>

<p>
  <img src="https://img.shields.io/badge/Status-Completed-2ea44f?style=for-the-badge" />
  <img src="https://img.shields.io/badge/UI-Figma%20Matching-6f42c1?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Build-Passing-2ea44f?style=for-the-badge" />
</p>

<p>
  <a href="https://github.com/Ramrampal/interviewos-figma-matching">
    View Repository
  </a>
</p>

</div>

---

## Overview

InterviewOS is a frontend implementation of an interview and candidate assessment platform based on the provided Figma design references.

The project focuses on translating visual designs into a functional Next.js application while maintaining consistent layouts, reusable components, responsive behavior, and a clean frontend structure.

The work involved reviewing the existing implementation, identifying UI mismatches, updating components and styles, and validating the resulting application across multiple routes.

---

## Project Objective

The primary objective was to implement and refine the InterviewOS interface according to the provided design references.

The development process followed this workflow:

```text
Figma Design
     |
     v
Existing Implementation
     |
     v
UI Comparison
     |
     v
Identify Mismatches
     |
     v
Component and CSS Updates
     |
     v
Responsive Validation
     |
     v
Production Build
````

---

## Key Features

### Authentication

* Sign In
* Create Account
* Forgot Password
* Reset Password
* Check Email

### Candidate Assessment

* Assessment Welcome Screen
* Questions Interface
* Coding Challenge
* Coding Workspace
* Assessment Progress
* Timer-Based Assessment Interface

### Background Verification

* Candidate Information
* Candidate Status
* Document Information
* Verification Workflow
* Reports and Settings Sections
* Dashboard Navigation

### Frontend UI

* Figma-based UI implementation
* Responsive layouts
* Reusable React components
* Consistent typography
* Structured spacing and layouts
* Interactive navigation
* Maintainable component architecture

---

## Technical Highlights

| Area            | Implementation           |
| --------------- | ------------------------ |
| Framework       | Next.js                  |
| UI Library      | React                    |
| Language        | TypeScript               |
| Styling         | CSS                      |
| Package Manager | npm                      |
| Version Control | Git                      |
| Repository      | GitHub                   |
| Routing         | Next.js App Router       |
| Build           | Next.js Production Build |

---

## Application Architecture

```text
InterviewOS
|
+-- scripts
|   +-- build-docs.py
|
+-- src
|   |
|   +-- app
|   |   |
|   |   +-- auth
|   |   |   +-- check-email
|   |   |   +-- create-account
|   |   |   +-- forgot-password
|   |   |   +-- reset-password
|   |   |   +-- sign-in
|   |   |
|   |   +-- background-check
|   |   +-- challenge
|   |   +-- questions
|   |   +-- welcome
|   |   +-- workspace
|   |   |
|   |   +-- layout.tsx
|   |   +-- page.tsx
|   |   +-- styles.css
|   |
|   +-- components
|       +-- AuthShell.tsx
|       +-- Button.tsx
|       +-- Header.tsx
|
+-- .gitignore
+-- next.config.mjs
+-- next-env.d.ts
+-- package.json
+-- package-lock.json
+-- tsconfig.json
```

---

## Reusable Components

### AuthShell

Provides the common structure and visual layout for authentication screens.

### Button

Provides a reusable button implementation for consistent actions across the application.

### Header

Provides the common navigation and header structure used throughout the application.

---

## Application Routes

| Route                   | Description          |
| ----------------------- | -------------------- |
| `/`                     | Main Application     |
| `/welcome`              | Assessment Welcome   |
| `/questions`            | Assessment Questions |
| `/challenge`            | Coding Challenge     |
| `/workspace`            | Coding Workspace     |
| `/background-check`     | Background Check     |
| `/auth/sign-in`         | Sign In              |
| `/auth/create-account`  | Create Account       |
| `/auth/forgot-password` | Forgot Password      |
| `/auth/reset-password`  | Reset Password       |
| `/auth/check-email`     | Check Email          |

---

## Figma to Code Process

The implementation focused on converting design specifications into functional frontend components.

```text
Design Reference
       |
       v
Layout Analysis
       |
       v
Component Identification
       |
       v
React Implementation
       |
       v
CSS Refinement
       |
       v
Browser Validation
       |
       v
Responsive Validation
       |
       v
Production Build
```

---

## Getting Started

### Prerequisites

Make sure the following are installed:

* Node.js
* npm
* Git

### Clone the Repository

```bash
git clone https://github.com/Ramrampal/interviewos-figma-matching.git
```

### Navigate to the Project

```bash
cd interviewos-figma-matching
```

### Install Dependencies

```bash
npm install
```

### Start Development Server

```bash
npm run dev
```

The application will be available at:

```text
http://localhost:3020
```

---

## Production Build

To create a production build:

```bash
npm run build
```

The project was successfully validated using the production build process.

```text
Compiled successfully
Checking validity of types
Collecting page data
Generating static pages
Collecting build traces
Finalizing page optimization
```

---

## Build Validation

The application was validated for:

```text
Application Compilation       PASS
Type Checking                 PASS
Static Page Generation        PASS
Route Generation              PASS
Production Build              PASS
```

---

## Screenshots

Add screenshots from the implemented application inside a `screenshots` directory.

Recommended structure:

```text
screenshots/
|
+-- sign-in.png
+-- create-account.png
+-- welcome.png
+-- questions.png
+-- challenge.png
+-- workspace.png
+-- background-check.png
```

Then display them in this section:

### Authentication

![Sign In](screenshots/sign-in.png)

### Assessment Welcome

![Welcome](screenshots/welcome.png)

### Questions

![Questions](screenshots/questions.png)

### Coding Challenge

![Coding Challenge](screenshots/challenge.png)

### Coding Workspace

![Coding Workspace](screenshots/workspace.png)

### Background Check

![Background Check](screenshots/background-check.png)

GitHub supports images in README files, and repository images are best referenced using relative paths. ([GitHub Docs][1])

---

## Development Workflow

```text
Analyze
   |
Implement
   |
Run
   |
Compare
   |
Debug
   |
Validate
   |
Build
   |
Commit
   |
Push
```

---

## What I Learned

This project provided practical experience in:

* Figma-to-code implementation
* Frontend UI debugging
* React component architecture
* Next.js App Router
* TypeScript development
* CSS layout implementation
* Responsive design
* Reusable component development
* Visual UI validation
* Production build validation
* Git version control
* GitHub repository management

---

## Project Status

| Category                | Status    |
| ----------------------- | --------- |
| Figma UI Implementation | Completed |
| Authentication Screens  | Completed |
| Assessment Flow         | Completed |
| Questions Interface     | Completed |
| Coding Challenge        | Completed |
| Coding Workspace        | Completed |
| Background Check        | Completed |
| Reusable Components     | Completed |
| Production Build        | Passed    |
| GitHub Repository       | Published |

---

## Repository

[View InterviewOS on GitHub](https://github.com/Ramrampal/interviewos-figma-matching)

---

## Author

### Rampal

Computer Science Engineering
Frontend and Software Development

[GitHub](https://github.com/Ramrampal)

[LinkedIn](https://www.linkedin.com/in/rampal-lodhi-83775130a/)

---

<div align="center">

### InterviewOS

Figma-driven frontend implementation built with Next.js, React and TypeScript.

</div>
```
[1]: https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax?ref=goldsguide.com&utm_source=chatgpt.com "Basic writing and formatting syntax - GitHub Docs"
[2]: https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-readmes?ref=miguelarios.com&utm_source=chatgpt.com "About the repository README file - GitHub Docs"
