# 🚀 TaskFlow — Complete Deployed Application

**SWYNEX Internship — Task 4**

TaskFlow is a full-stack task management application developed as part of the SWYNEX internship program.

The application allows users to register, log in, create and manage tasks, update task status, search/filter tasks, and securely access their own data through a REST API.

---

## 📌 Project Overview

TaskFlow is built using a modern full-stack architecture:

- **Frontend:** React + Vite + Tailwind CSS
- **Backend:** Node.js + Express.js
- **Database:** MongoDB Atlas + Mongoose
- **Authentication:** JWT + bcrypt
- **API Communication:** Axios
- **Deployment:** Frontend and backend deployed separately

This repository is the final **Task 4 submission/documentation repository**. The complete frontend and backend source code are maintained in their respective repositories.

---

## ✨ Features

- User registration and login
- JWT-based authentication
- Secure password hashing with bcrypt
- Create tasks
- View tasks
- Update tasks
- Delete tasks
- Change task status
- Search tasks
- Filter tasks by status
- Loading states
- Error and success messages
- Responsive user interface
- MongoDB persistence
- Protected API routes
- User-specific task access

---

## 🏗️ Architecture

```text
                    ┌─────────────────────┐
                    │       User          │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │   React Frontend    │
                    │  Vite + Tailwind    │
                    └──────────┬──────────┘
                               │
                         REST API / Axios
                               │
                               ▼
                    ┌─────────────────────┐
                    │   Express Backend   │
                    │   Node.js + JWT     │
                    └──────────┬──────────┘
                               │
                           Mongoose
                               │
                               ▼
                    ┌─────────────────────┐
                    │    MongoDB Atlas    │
                    └─────────────────────┘
```

---

## 🔗 Project Links

### Frontend Repository

>  Task 3 GitHub repository URL here.

`https://github.com/RAFIKULMONDAL/SWYNEX-Frontend-Integration.git`

### Backend Repository

> Task 2 GitHub repository URL here.

`https://github.com/RAFIKULMONDAL/SWYNEX-Backend-API-and-Database.git`

### 🌐 Live Application

>  deployed frontend URL here after deployment.

`swynex-frontend-integration.vercel.app`

### Backend API

> deployed backend API URL here after deployment.

`https://swynex-backend-api-and-database.onrender.com`

---

## 📸 Screenshots

Add your screenshots inside the `screenshots` folder and update the image names below.

### Login

![TaskFlow Login](screenshots/login.png)

### Register

![TaskFlow Register](screenshots/register.png)

### Dashboard

![TaskFlow Dashboard](screenshots/dashboard.png)

### Create / Edit Task

![Task Management](screenshots/task-management.png)

### Task Status

![Task Status](screenshots/task-status.png)

---

## 🛠️ Local Setup

### 1. Clone the frontend repository

```bash
git clone YOUR_FRONTEND_REPOSITORY_URL
cd YOUR_FRONTEND_PROJECT
```

Install dependencies:

```bash
npm install
```

Create a `.env` file:

```env
VITE_API_URL=http://localhost:5000/api
```

Start the frontend:

```bash
npm run dev
```

---

### 2. Clone the backend repository

```bash
git clone YOUR_BACKEND_REPOSITORY_URL
cd YOUR_BACKEND_PROJECT/backend
```

Install dependencies:

```bash
npm install
```

Create a `.env` file:

```env
PORT=5000
MONGO_URI=YOUR_MONGODB_ATLAS_CONNECTION_STRING
JWT_SECRET=YOUR_SECRET_KEY
```

Start the backend:

```bash
npm run dev
```

The backend runs locally on:

```text
http://localhost:5000
```

---

## 🔐 Environment Variables

### Frontend

```env
VITE_API_URL=YOUR_BACKEND_API_URL/api
```

### Backend

```env
PORT=5000
MONGO_URI=YOUR_MONGODB_ATLAS_CONNECTION_STRING
JWT_SECRET=YOUR_SECRET_KEY
```

**Never commit real secrets, passwords, API keys, or `.env` files to GitHub.**

---

## 🔌 Main API Endpoints

| Method | Endpoint | Purpose |
|---|---|---|
| POST | `/api/auth/register` | Register user |
| POST | `/api/auth/login` | Login user |
| GET | `/api/auth/me` | Get authenticated user |
| GET | `/api/tasks` | Get user's tasks |
| POST | `/api/tasks` | Create task |
| PUT | `/api/tasks/:id` | Update task |
| DELETE | `/api/tasks/:id` | Delete task |
| GET | `/api/health` | API health check |

---

## 🚀 Deployment

The application is designed to be deployed as:

- **Frontend:** Vercel
- **Backend:** Render / similar Node.js hosting platform
- **Database:** MongoDB Atlas

### Deployment URLs

Replace the placeholders below after deployment:

```text
Frontend:
YOUR_LIVE_APPLICATION_URL

Backend:
YOUR_BACKEND_API_URL
```

---

## 🧪 Testing Checklist

Before submitting Task 4, verify:

- [ ] Registration works
- [ ] Login works
- [ ] Logout works
- [ ] Dashboard loads
- [ ] Create task works
- [ ] Edit task works
- [ ] Delete task works
- [ ] Status update works
- [ ] Search works
- [ ] Filter works
- [ ] Loading states work
- [ ] Error states work
- [ ] MongoDB data persists
- [ ] Live frontend can communicate with live backend
- [ ] GitHub repository is public
- [ ] Live URL works in incognito mode

---

## 📚 Task 4 Completion

### SWYNEX Internship

**Task:** Complete Deployed Application

The application was completed by integrating the frontend, backend, authentication, database, and deployment workflow.

### Key Learnings

- Full-stack application integration
- REST API development and consumption
- JWT authentication
- MongoDB Atlas database integration
- Frontend and backend environment configuration
- Deployment of full-stack applications
- GitHub project documentation
- Debugging production configuration issues

---

## 👨‍💻 Developer

**Rafikul Mondal**

Information Technology  
SPPU

---

## 🏷️ Internship

Completed as part of the **SWYNEX Internship Program**.

**Hashtags:** `#SWYNEX #Internship #FullStackDevelopment #React #NodeJS #MongoDB #WebDevelopment`
