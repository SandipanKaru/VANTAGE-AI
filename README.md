# 🎙️ VANTAGE.AI

AI-Powered Autonomous Mock Interview Platform

VANTAGE.AI helps students and job seekers prepare for real-world interviews through AI-generated questions, voice-based interaction, intelligent evaluation, and detailed performance analytics.

Built as a Capstone Project at IIT Patna.

---

## 🎁 Features

### ♦ AI Interview Generation

* Resume-based question generation
* Personalized interview flow
* Technical and HR interview support

### 🎤 Voice-Based Interviews

* AI interviewer voice interaction
* Multiple voice options
* Real-time conversation experience

### 🧠 AI Evaluation

* Automated answer assessment
* Performance scoring
* Personalized feedback generation

### 📄 Smart Reports

* Downloadable PDF reports
* Interview summaries
* Performance analytics

### 📊 Dashboard & Analytics

* Interview history
* Attempts tracking
* Progress monitoring
* Statistics dashboard

### 🏆 Leaderboard System

* User rankings
* Score aggregation
* Competitive learning experience

### 💳 Premium Features

* Razorpay payment integration
* Premium interview access
* Enhanced report generation

### 🔐 Authentication & Security

* User registration and login
* Password hashing using bcrypt
* Session management using MongoDB

---

## 🏗️ Architecture

```text
User
 ↓
React Frontend (Vite)
 ↓
Node.js + Express Backend
 ↓
MongoDB Atlas
 ↓
Groq AI + ElevenLabs APIs
 ↓
PDF Reports & Analytics
```

---

## 🛠️ Tech Stack

### Frontend

* React
* Vite
* JavaScript
* CSS

### Backend

* Node.js
* Express.js

### Database

* MongoDB Atlas
* Mongoose

### AI Services

* Groq API
* ElevenLabs API

### Authentication

* Express Session
* Connect-Mongo
* bcryptjs

### Payments

* Razorpay

### Additional Libraries

* Multer
* Nodemailer
* PDF-Parse

---

## 📂 Project Structure

```text
Ai-interview-1-main
│
├── middleware/
├── models/
├── server.js
│
└── voice-frontend/
    ├── src/
    │   ├── Auth.jsx
    │   ├── Interview.jsx
    │   ├── Leaderboard.jsx
    │   ├── DashboardStats.jsx
    │   ├── Attempts.jsx
    │   ├── Payment.jsx
    │   └── VoicePicker.jsx
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/SandipanKaru/VANTAGE-AI.git
```

### Install Backend Dependencies

```bash
npm install
```

### Install Frontend Dependencies

```bash
cd voice-frontend
npm install
```

### Configure Environment Variables

Create a `.env` file:

```env
MONGO_URI=your_mongodb_uri
SESSION_SECRET=your_session_secret

GROQ_API_KEY=your_groq_api_key
ELEVENLABS_API_KEY=your_elevenlabs_api_key

EMAIL_USER=your_email
EMAIL_PASS=your_password

RAZORPAY_KEY_ID=your_key
RAZORPAY_KEY_SECRET=your_secret
```

### Run Backend

```bash
npm start
```

### Run Frontend

```bash
cd voice-frontend
npm run dev
```

---

## 🧪 Challenges Solved

* Session persistence issues
* Duplicate interview records
* Incorrect score retrieval
* Leaderboard aggregation problems
* Render deployment failures
* Environment variable configuration
* PDF report generation issues
* Missing dependency management
* Payment workflow handling

---

## 📸 Screenshots

### Login Page
![Login Page](https://raw.githubusercontent.com/SandipanKaru/VANTAGE-AI/main/vintage.ai-main/assets/login.png)

### Dashboard
![Dashboard](https://raw.githubusercontent.com/SandipanKaru/VANTAGE-AI/main/vintage.ai-main/assets/dashboard.png)

### Leaderboard
![Leaderboard](https://raw.githubusercontent.com/SandipanKaru/VANTAGE-AI/main/vintage.ai-main/assets/leaderboard.png)

* Login Page
* Dashboard
* Interview Interface
* Voice Selection
* PDF Report
* Leaderboard
* Premium Features

### Live Link
https://vintage-ai-1jmk.onrender.com/

---

## 🌟 Future Scope

* Mobile Application
* Emotion Detection
* Multi-Language Interviews
* Recruiter Dashboard
* AI Career Recommendations
* Advanced Analytics

---

## 📜 License

This project was developed for educational purposes as part of the IIT Patna Capstone Program.
