# Personal AI Assistant for Study

Personal AI Assistant is a full-stack intelligent tutoring system built as a final year project. It combines a React frontend with a Node.js + Express backend and MongoDB for persistence.

## 📌 Overview

- Frontend: React + Vite
- Backend: Node.js + Express
- Database: MongoDB
- Features: AI chat, YouTube search, Wikipedia lookup, user authentication, and support contact.

## 🚀 Quick Start

### 1. Clone the repository

```bash
git clone git@github.com:Sufiyan123-max/Personal-Ai-Assistant-for-study.git
cd "personnel training assistent - Copy"
```

### 2. Install dependencies

```bash
cd server
npm install
cd ../client
npm install
```

### 3. Configure environment variables

Create a `.env` file inside `server/` with these values:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
EMAIL_USER=your_email@example.com
EMAIL_PASS=your_email_password
GROQ_API_KEY=your_groq_api_key
AI_API_URL=https://api.groq.com/GIVEN_URL
YOUTUBE_API_KEY=your_youtube_api_key
```

### 4. Run the app

```bash
cd server
npm run dev
```

In another terminal:

```bash
cd client
npm run dev
```

Open the frontend at the URL shown by Vite (default `http://localhost:5173`).

## 📁 Project Structure

- `client/` — React frontend
- `server/` — Express backend
- `README.md` — project documentation

## 🔒 Ignore Rules

The repository ignores:

- `.env`
- `node_modules/`

## ℹ️ Notes

- Do not commit `.env` files or `node_modules`.
- Change the Git remote if needed:

```bash
git remote set-url origin git@github.com:Sufiyan123-max/Personal-Ai-Assistant-for-study.git
```

## 👥 Contributors

- **Aaditya Jha**
- **Abhay Kumar Yadav**
- **Palli Harshavardhan**
- **Suraj Kumar**
