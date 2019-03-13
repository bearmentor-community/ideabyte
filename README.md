# Idea Byte Discussion + Design

This repo is to manage all discussion and design assets of Idea Byte.

<!-- vscode-markdown-toc -->

- 1. [Introduction](#Introduction)
- 2. [Links](#Links)
- 3. [Designs on Figma](#DesignsonFigma)
     _ 3.1. [Logo Design](#LogoDesign)
     _ 3.2. [UI Design](#UIDesign)
- 4. [Project Setup](#ProjectSetup)
- 5. [Technology & Design Stack](#TechnologyDesignStack)
- 6. [Features](#Features)
- 7. [License](#License)

<!-- vscode-markdown-toc-config
	numbering=true
	autoSave=true
	/vscode-markdown-toc-config -->
<!-- /vscode-markdown-toc -->

## 1. <a name='Introduction'></a>Introduction

Let's build a full stack project in 5 days

- Monday: Design UI & UX in Figma, implement frontend components in React
- Tuesday: Give interactivity with Redux
- Wednesday: Implement backend REST API
- Thursday: Integrate frontend and backend
- Friday: Present full stack project with slide

## 2. <a name='Links'></a>Links

- Organization:
  - https://github.com/ideabyte
- Repositories:
  - https://github.com/ideabyte/ideabyte-discussion
  - https://github.com/ideabyte/ideabyte-design
  - https://github.com/ideabyte/ideabyte-frontend
  - https://github.com/ideabyte/ideabyte-backend

## 3. <a name='DesignsonFigma'></a>Designs on Figma

### 3.1. <a name='LogoDesign'></a>Logo Design

Figma: https://www.figma.com/file/Ulv3rNFBEvLpAYVQKyrQUf7R/Logo

![Logo](assets/logo/ideabyte-logo.png)

### 3.2. <a name='UIDesign'></a>UI Design

Figma: https://www.figma.com/file/fnUhskd1moNIQIefbwC0eknE/Web-App–

![Desktop](assets/desktop/desktop.png)

![Idea](assets/desktop/desktop-idea.png)

![Register](assets/desktop/desktop-register.png)

## 4. <a name='ProjectSetup'></a>Project Setup

- Determine a team/app name
  - Example: Idea Byte
- Create a Gmail account
  - Example: impactbyte.ideabyte@gmail.com
- Create GitHub account
  - Example: https://github.com/ideabyte-admin (free personal account)
- Create GitHub organization
  - Example: https://github.com/ideabyte (organization)
- Update organization profile in settings
  - https://github.com/organizations/ideabyte/settings/profile
- Add team members on GitHub
  - https://github.com/orgs/ideabyte/people
- Setup repositories
  - `discussion`: https://github.com/ideabyte-discussion
  - `design`: https://github.com/ideabyte-design
  - `frontend`: https://github.com/ideabyte-frontend
  - `backend`: https://github.com/ideabyte-backend
- Protect `master` branches
  - https://github.com/impactbyte-ideabyte/ideabyte-frontend/settings/branches
- Setup project with linked repositories
  - Example: https://github.com/orgs/impactbyte-ideabyte/projects/1
- List features we NEED, not just WANT
- Protect `master` branches
  - https://github.com/ideabyte/ideabyte-frontend/settings/branches
- Setup project with linked repositories
  - Example: https://github.com/orgs/ideabyte/projects/1
- List features that we NEED, not just WANT

## 5. <a name='TechnologyDesignStack'></a>Technology & Design Stack

- Management
  - Gmail
  - Git
  - GitHub
- Editor
  - VS Code
  - Postman
- Images
  - Figma
  - Unsplash
  - The Noun Project
- Frontend
  - HTML
  - CSS
  - JavaScript (ESNext)
  - React + React Dev Tools
  - React Router
  - React Helmet
  - Styled Components
  - Redux + Redux Dev Tools
- Backend
  - Node.js
  - Express
  - bcrypt + JWT
  - NoSQL
    - MongoDB + Robo 3T
    - Mongoose
  - SQL
    - MySQL + MySQL Workbench
    - Knex.js + Objection.js
- Server
  - Uniregistry
  - CloudFlare
  - Netlify
  - Google Cloud Platform
    - Compute Engine

## 6. <a name='Features'></a>Features

- Display introduction in homepage (`/`)
- Display all ideas in homepage (`/ideas`)
- Display about in about page (`/about`)
- Register new user (`/register`)
  - Put full name
  - Put username
  - Put email
  - Put password
  - Register button
- Login with registered user (`/login`)
  - Put username
  - Put password
  - Login button
- Check our own profile
  - Full Name
  - Username
  - Email
  - Password should not be displayed
  - Remove user button
    - Remove our own user/profile
- Create a new idea in the idea editor
  - Put the title
  - Put an image or multiple images
  - Put some description
  - Submit idea
- Update idea in the idea editor
  - Update the title and description
  - Resubmit the idea
- Remove our own idea

## 7. <a name='License'></a>License

- MIT License
- Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License

Thanks to [Unsplash](https://unsplash.com) and [The Noun Project](https://thenounproject.com).
