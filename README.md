# Questify: Quiz Platform With Leaderboard

Questify is a responsive MERN-stack web application designed for interactive test-taking, real-time scoring, analytics, and leaderboard competition.

## Project Details
* **Intern Name**: `Bhavesh Kumar`
* **Intern ID**: `CITS5188`
* **Project Name**: **Quiz Platform With Leaderboard**
* **Target Company**: CodTech IT Solutions
* **Domain**: Full Stack Web Development (MERN)

---

## Features
- **User Authentication**: Secure JWT-based session authorization for Admins and Challengers.
- **Interactive Quiz Engine**: Multi-choice quizzes with categories, difficulties, countdown timers, and cheat prevention.
- **Dashboards & Analytics**: Personalized Challenger dashboard with interactive SVG charts (accuracy, mastery breakdown).
- **Leaderboards**: Real-time global standings sorted by accuracy and response time.
- **Admin Control Panel**: Full CRUD operations to manage quiz questions and categories dynamically.

---

## Setup & Running Instructions

### 1. Prerequisites
- Node.js (v16+)
- MongoDB (running locally or Atlas cloud database)

### 2. Installation
Install dependencies from the root directory:
```bash
npm run install-all
```

### 3. Environment Setup
Create a `.env` file in the `backend/` directory:
```env
PORT=5000
MONGODB_URI=mongodb://127.0.0.1:27017/quiz-platform
JWT_SECRET=your_jwt_secret_key_here
NODE_ENV=development
```

### 4. Database Seeding
Populate the database with default categories, questions, and test users:
```bash
npm run seed
```

### 5. Running the Application
Start both frontend and backend development servers concurrently:
```bash
npm run dev
```
- **React Frontend**: `http://localhost:5173/`
- **Express API**: `http://localhost:5000/`

---

## Demo Credentials

### Challenger Access
- **Email**: `john@example.com`
- **Password**: `password123`

### Administrator Access
- **Email**: `admin@quiz.com`
- **Password**: `admin123`

