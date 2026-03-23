# YT GenAI - Simple & Smart Interview Prep 🎯

**AI-powered interview practice.** Upload resume → Get questions, answers & PDF resume.

Easy to use. Fast results.

## 📱 How it Works (Simple Flow)

```
1️⃣ Login/Register
     ↓
2️⃣ Home → See your reports
     ↓ New
3️⃣ Upload Resume + Job Info
     ↓ AI ✨
4️⃣ Get Interview Report + PDF
```

## 🛠️ Tech Stack

- Frontend: **React** + Vite
- Backend: **Node.js** + Express + MongoDB
- AI: **Google GenAI**

## 🚀 Start in 2 Minutes

**Backend:**

```bash
cd Backend
npm i
# Edit .env (DB, API keys)
npm run dev
```

_Port: 3000_

**Frontend:**

```bash
cd Frontend
npm i
npm run dev
```

_Port: 5173_

## 🔑 Key APIs

| Action  | Endpoint                             |
| ------- | ------------------------------------ |
| Login   | POST /api/auth/login                 |
| Reports | GET /api/interview/                  |
| Create  | POST /api/interview/ (resume upload) |

## .env (Backend)

```
DB_URI=your-mongo-url
JWT_SECRET=secret
GOOGLE_AI_API_KEY=your-key
```

**That's it!** Run → Login → Practice interviews.

⭐ Enjoy your prep! 🚀
