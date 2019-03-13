# Idea Byte Discussion + Design

This repo is to manage all discussion and design assets of Idea Byte.

<!-- vscode-markdown-toc -->

- 1. [Introduction](#Introduction)
- 2. [Links](#Links)
- 3. [Development Setup](#DevelopmentSetup)
- 4. [Features](#Features)
- 5. [Management Accounts](#ManagementAccounts)
- 6. [Technology & Design Stack](#TechnologyDesignStack)
- 7. [Design](#Design)
     _ 7.1. [Logo Design](#LogoDesign)
     _ 7.2. [UI & UX Design](#UIUXDesign)
- 8. [License](#License)

<!-- vscode-markdown-toc-config
	numbering=true
	autoSave=true
	/vscode-markdown-toc-config -->
<!-- /vscode-markdown-toc -->

## 1. <a name='Introduction'></a>Introduction

Let's build a full stack project in just 5 days.

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

## 3. <a name='DevelopmentSetup'></a>Development Setup

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
  - `primary`: https://github.com/ideabyte
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

## 4. <a name='Features'></a>Features

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
- Check our own profile (`/profile`)
  - Full Name
  - Username
  - Email
  - Password should not be displayed
  - Remove user button
    - Remove our own user/profile
- Check other user's profile (`/users/:username`)
- Create a new idea in the idea editor (`/create`)
  - Put the title
  - Put an image or multiple images
    - This will be a cover image
  - Put some description
  - Date and time created automatically
  - Submit idea
- See the idea on its own (`/ideas/:id`)
  - Cover image
  - Title
  - Description
  - Date and time
  - Author
    - Link to user's profile
  - Details
- Update idea in the idea editor (`/ideas/:id/edit`)
  - Update the title and description
  - Remove our own idea
  - Resubmit the idea

## 5. <a name='ManagementAccounts'></a>Management Accounts

`yourteamname@gmail.com`

- Gmail
- Google Chrome Profile
- Uniregistry
- Cloudflare
- Figma
- Netlify
- Heroku
- GitHub Personal Admin
- GitHub Organization
- The Noun Project
- Unsplash
- Grammarly

## 6. <a name='TechnologyDesignStack'></a>Technology & Design Stack

- Management
  - Gmail: managing all emails
  - Google Keep: storing secrets
  - Google Drive & Slide: making the presentation
  - Git: managing versions
  - GitHub: managing admin and organization
- Editor
  - VS Code: developing the software
  - Postman: storing API collections
- Contents
  - Figma: designing the logo, UI, UX
  - Unsplash: getting sample photos
  - The Noun Project: getting icons
  - Grammarly: checking the writing and grammar
- Frontend
  - HTML: layouting the page
  - CSS: styling the page
  - JavaScript (ESNext): making the website interactive
  - React: component-based design
  - React Dev Tools: helping React development
  - React Router: routing the React app pages
  - React Helmet: managing metadata in React
  - Styled Components: CSS in JS
  - Emotion: CSS in JS
  - Redux: managing the state across the React app
  - Redux Thunk: managing asynchronous process in Redux
  - Redux Dev Tools: helping Redux development
- Backend
  - Node.js: JavaScript in the backend
  - Express: making the REST API
  - bcrypt: securing the password, also with salt
  - JWT (JSON Web Token): managing authorization with token after login
  - NoSQL: non-relational database
    - MongoDB: document-based database
    - Robo 3T: managing MongoDB data
    - Mongoose: ODM (Object Data Modeling) for MongoDB
  - SQL: relational database
    - MySQL: table-based database
    - MySQL Workbench: designing and managing MySQL data
    - Knex.js: SQL query builder
    - Objection.js: ORM (Object Relational Mapping) for MongoDB
- Server
  - Netlify: hosting the frontend web application
  - Heroku: hosting the backend REST API
  - Heroku mLab: hosting MongoDB in Heroku
  - Heroku Postgres: hosting PostgreSQL in Heroku
  - Google Cloud Platform
    - Compute Engine: hosting all applications
- Domain
  - Uniregistry: registering the domain
  - CloudFlare: managing the DNS (Domain Name Server) between domain and server
- Social Media
  - Twitter
  - Facebook
  - Instagram

## 7. <a name='Design'></a>Design

### 7.1. <a name='LogoDesign'></a>Logo Design

Figma: https://www.figma.com/file/Ulv3rNFBEvLpAYVQKyrQUf7R/Logo

![Logo](assets/logo/ideabyte-logo.png)

### 7.2. <a name='UIUXDesign'></a>UI & UX Design

Figma: https://www.figma.com/file/fnUhskd1moNIQIefbwC0eknE/Web-App–

![Desktop](assets/desktop/desktop.png)

![Idea](assets/desktop/desktop-idea.png)

![Register](assets/desktop/desktop-register.png)

## 8. <a name='License'></a>License

- MIT License
- Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License

Thanks to [Unsplash](https://unsplash.com) and [The Noun Project](https://thenounproject.com).
