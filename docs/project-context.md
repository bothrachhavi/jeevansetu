# JeevanSetu - Project Context

## Project Overview

JeevanSetu is an Emergency Blood Response System designed to connect blood donors, recipients, hospitals, and administrators through a verified platform.

The system helps recipients find blood quickly, enables donors to respond to emergency requests, and provides administrators with tools for verification, moderation, and analytics.

---

# Tech Stack

## Frontend

* React
* TypeScript
* Vite
* Tailwind CSS
* React Router
* React Query
* Axios

## Backend

* Node.js
* Express.js
* TypeScript
* MongoDB Atlas
* Mongoose
* JWT Authentication
* Socket.IO

## Deployment

Frontend:

* Vercel

Backend:

* Render

Database:

* MongoDB Atlas

---

# Architecture Rules

Claude must follow these rules:

1. Follow SDD.md strictly.
2. Do not invent new architecture.
3. Do not add technologies not listed in SDD.
4. Use TypeScript everywhere.
5. Use clean architecture.
6. Use feature-based frontend architecture.
7. Use service-based backend architecture.
8. Maintain scalability and modularity.

---

# User Roles

## Donor

Can:

* Maintain profile
* Toggle availability
* Respond to requests
* Chat with recipients

## Recipient

Can:

* Create blood requests
* Search donors
* Track requests
* Chat with donors

## Admin

Can:

* Verify requests
* Manage users
* View analytics
* Moderate platform activity

---

# Coding Standards

## General

* Use TypeScript
* Use ESLint
* Use Prettier
* Use async/await
* Avoid duplicated logic

## Backend

Structure:

routes
controllers
services
repositories
models
middlewares
validators

## Frontend

Structure:

pages
features
components
hooks
services
routes

---

# UI Rules

All UI must follow Stitch designs.

Claude should never redesign screens.

Claude should implement the provided designs faithfully.

---

# Workflow Rules

Before generating code:

1. Explain implementation plan.
2. List files to create.
3. Explain why each file is required.
4. Wait for approval.

Only after approval generate code.

---

# Development Priority

1. Project Setup
2. Authentication
3. Database Models
4. Blood Requests
5. Verification
6. Donor Search
7. Messaging
8. Notifications
9. Admin Module
10. Analytics

---

# Important

Claude is acting as a Senior Full Stack Engineer.

The goal is production-quality code, not demo code.
