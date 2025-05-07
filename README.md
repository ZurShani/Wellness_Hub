# Wellness Hub 🌿

A full-stack wellness web application that helps users explore health insights through AI recommendations, connect with the community, and manage their personal wellness journey.

---

## 📌 Features

- 🔐 **Authentication**
  - JWT-based login/register
  - Google Sign-In

- 👤 **User Profiles**
  - Edit username and profile photo
  - View user's personal posts

- 🗨️ **Community Forum**
  - Create, like, edit, and delete posts
  - Comment on posts and view replies

- 🤖 **AI Recommendation**
  - Enter symptoms and receive supplement suggestions via Gemini API

---

## 🛠️ Tech Stack

### Frontend
- React
- TypeScript
- Material-UI (MUI)
- Axios
- React Router

### Backend
- Node.js
- Express
- MongoDB & Mongoose
- TypeScript
- Passport.js (Google OAuth)
- Multer (File uploads)
- Swagger (API Docs)
- Jest + Supertest (Tests)

---

## 🚀 Getting Started

### Prerequisites
- Node.js
- MongoDB
- npm

---
## Create a .env file In The Backend Folder:

- PORT=4000
- MONGO_URI=mongodb://localhost:27017/Wellness_Hub
- JWT_SECRET=your_jwt_secret_here
- GOOGLE_CLIENT_ID=your_google_client_id_here
- GOOGLE_CLIENT_SECRET=your_google_client_secret_here
- GEMINI_API_KEY=your_gemini_api_key_here
- GOOGLE_SEARCH_API_KEY=your_google_search_api_key_here
- GOOGLE_SEARCH_ENGINE_ID=your_custom_search_engine_id_here


---

### 🔧 Backend Setup

```bash
cd backend
npm install
npx ts-node src/server.ts
```

### 🔧 Frontend Setup

```bash
cd frontend
npm install
npm start
```
