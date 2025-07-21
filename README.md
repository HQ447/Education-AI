# EduAI – AI-Powered E-Learning Marketplace 🎓🤖

EduAI is an AI-driven e-learning platform designed to provide affordable, personalized, and accessible education to students and professionals across Pakistan. The system supports competitive exam preparation (MDCAT, CSS, NTS, etc.), skill-building courses, and instructor-led content delivery using modern web technologies.

---

## 🚀 Features

- 🎯 AI-powered personalized learning paths
- 📚 Instructor-uploaded multimedia courses
- 🧠 Intelligent course recommendations
- 📊 Real-time performance analytics dashboards
- 🧾 Mock exams, quizzes, and progress tracking
- 🗣️ Live webinars, messaging, and discussion forums
- 🧩 Gamification (leaderboards, badges, certificates)
- 🌍 Urdu & English language support
- 📱 Mobile-friendly & low-bandwidth optimized
- 💳 Secure payments & instructor revenue sharing

---

## 🛠️ Tech Stack

### 🔹 Frontend

- [Next.js](https://nextjs.org/)
- TypeScript
- Tailwind CSS
- React.js
- Material UI

### 🔹 Backend

- Node.js
- Express.js
- MongoDB (via Mongoose)
- JWT for authentication
- Redis (optional for caching)

### 🔹 AI / ML (Optional for Expansion)

- TensorFlow / Scikit-Learn for recommendation engine (future)

---

## 🔐 Authentication & Authorization

- JWT-based user login & registration
- Role-based access for:
  - Students
  - Instructors
  - Admin (Create Admin Account using secret)

---

## 📦 Installation (For Development)

```bash
# Clone the repo
git clone https://github.com/yourusername/eduai.git
cd eduai

# Install backend dependencies
cd server
npm install

# Install frontend dependencies
cd ../frontend
npm install

# Create `.env` files
# Example environment variables:
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key

# Run backend
cd ../server
npm run dev

# Run frontend
cd ../frontend
npm run dev
```

---

## 🔐 DEMO Accounts

Learner Account - hq16877@gmail.com - regNo$
Admin Account route - /auth/admin-Login and /auth/inital-admin
hamadqur447@gmail.com - regNo$
