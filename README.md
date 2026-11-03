# Authentication & Dashboard — Secure Blog Management System

Module 05 project featuring JWT authentication, protected routes, a user profile greeting, logout, and a private blog dashboard.

## Features
- User registration and login
- Password hashing with bcryptjs
- JWT access token with 2-hour expiry
- Protected profile and blog API routes
- Each user can access only their own blog posts
- User profile greeting and logout
- Create, read, update, delete, and search personal blogs
- Responsive mobile/desktop interface

## Tech stack
HTML, CSS, JavaScript, Node.js, Express, JSON Web Tokens, bcryptjs.

## Run locally
1. Install Node.js 18 or later.
2. Open this folder in a terminal.
3. Run `npm install`.
4. Copy `.env.example` to `.env` and set a long random `JWT_SECRET` value.
5. Run `npm start`.
6. Visit `http://localhost:3000` and register an account.

## GitHub upload
Create a repository named `authentication-dashboard-blog-app` and upload all project files. Do not upload `.env`, `node_modules`, or `data/db.json` containing real user data.

## Deployment
This is a Node.js/Express application. GitHub Pages cannot host the backend. Deploy to a Node-compatible host and configure `JWT_SECRET` as a private environment variable. Use persistent managed database storage for production.

## Security note
This is an educational project. The demo stores JWT in browser localStorage and uses a JSON file as its database. For production, use HTTPS, secure HttpOnly/SameSite cookies, CSRF protection where appropriate, rate limiting, stronger validation, and a managed database. JSON-file storage is not suitable for concurrent or production use.

## LinkedIn title
**Authentication & Dashboard | JWT-Based Secure Blog Management System**

## LinkedIn post
🚀 Excited to share my Module 05 project: **Authentication & Dashboard – Secure Blog Management System**!

I built a blog application with user registration, login, JWT-based authentication, protected dashboard routes, and user-specific blog management.

✨ **Key Features**
- User registration and login
- Password hashing
- JWT authentication
- Protected dashboard and API routes
- Private, user-specific blog posts
- User profile greeting and logout
- Create, read, update, and delete blog posts

🛠️ **Technologies:** HTML, CSS, JavaScript, Node.js, Express.js, JWT, and bcryptjs.

This project helped me understand authentication workflows, protected routes, backend APIs, and user-specific data access.

#Authentication #JWT #NodeJS #ExpressJS #WebDevelopment #Dashboard #CRUD #JavaScript #InternshipProject #GitHub
