# Ticketing Tool Web Application

A full-stack MERN application for managing organizational tickets.

## Features
- **Roles**: Employee, Support, Admin.
- **Auth**: JWT Authentication, Role-based protection.
- **Tickets**: Create, Assign, Comment, Track Status.
- **Tech**: React (Vite+Tailwind), Node/Express, MongoDB.

## Quick Start

### 1. Backend
```bash
cd server
npm install
# Setup .env (PORT=5000, MONGO_URI=..., JWT_SECRET=...)
node seeder.js # Load initial data
npm run dev
```

### 2. Frontend
```bash
cd client
npm install
npm run dev
```

### Default Credentials
| Role | Email | Password |
|------|-------|----------|
Employee: EMP001 / password123
Support Agent: support1@example.com / password123
Admin: admin@example.com / password123

## Folder Structure
- `/server`: API and Database logic.
- `/client`: React Frontend.
