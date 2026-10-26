# Studymate AI

<div align="center">

  <img src="https://img.shields.io/badge/MERN-Stack-61DAFB?style=for-the-badge&logo=react" alt="MERN Stack" />
  <img src="https://img.shields.io/badge/AI-Gemini-8A2BE2?style=for-the-badge" alt="AI Gemini" />
  <img src="https://img.shields.io/badge/Docs-PDF%20Learning-00C853?style=for-the-badge" alt="PDF Learning" />

  <h3>Your AI study stay, designed for focused learning.</h3>

  <p>
    Studymate AI is a full-stack learning platform that helps students study smarter, not harder.
    It combines AI-powered tutoring, document understanding, personalized revision tools, and progress tracking to create a seamless study experience.
  </p>

  <p>
    <a href="#features">Explore features</a>
    ·
    <a href="#quick-start">Quick start</a>
    ·
    <a href="#tech-stack">Tech stack</a>
  </p>

</div>

---

## Stay smart. Learn better.

Think of Studymate AI as a digital study hotel for your brain:

- Check in with your notes and course material
- Stay in a focused, personalized learning space
- Ask questions like a smart tutor
- Receive flashcards, quizzes, and progress insights
- Leave with stronger understanding and better retention

---

## Why students book a stay

<div align="center">

| Experience | What it does |
| --- | --- |
| Smart AI Chat | Answers questions grounded in your uploaded documents and chat history |
| Document Intelligence | Reads PDFs, extracts key ideas, and helps you understand content faster |
| Revision Rooms | Generates flashcards and quizzes based on your material |
| Progress Tracking | Monitors learning sessions and highlights what needs attention |
| Personal Workspace | Keeps your study flow organized in a clean, secure dashboard |

</div>

---

## Features

### 1. AI study concierge
- Chat with an AI assistant trained on your uploaded documents
- Ask follow-up questions and get explanations in plain language
- Keep conversation context to build a personalized learning thread

### 2. PDF learning engine
- Upload lecture notes, PDFs, and study material
- Split and process document chunks for smarter retrieval
- Summarize long content into useful, digestible insights

### 3. Smart revision tools
- Generate flashcards for important topics
- Create quiz flows with scoring and self-check mechanisms
- Review difficult concepts before tests or exams

### 4. Learning progress dashboard
- Track study activity by session and topic
- Stay consistent with structured progress visibility
- Keep your academic momentum going with guided improvements

### 5. Secure learning workspace
- User authentication and protected routes
- Clean interface for focused academic work
- Built for a smooth study experience on the web

---

## How it works

### Check in
Create an account and enter your study workspace.

### Upload your material
Add notes, lectures, PDFs, and other resources you want the AI to understand.

### Learn with AI
Ask questions, request summaries, create flashcards, and revise with contextual help.

### Track your progress
Monitor what you've covered and keep improving with consistent, intelligent feedback.

---

## Tech stack

### Frontend
- React
- Vite
- Tailwind CSS
- React Router
- React Markdown

### Backend
- Node.js
- Express
- JWT authentication
- Multer for uploads
- MongoDB Atlas

### AI & data layer
- Google Gemini API
- PDF parsing and content processing
- MongoDB-backed user and study data

---

## Project structure

```bash
studymate-ai/
├── src/                  # Frontend app
├── backend/             # Express API and data layer
├── public/              # Static frontend assets
├── package.json         # Frontend dependencies and scripts
├── vite.config.js       # Vite configuration
├── index.html           # App entry point
├── README.md            # Project documentation
└── .gitignore
```

---

## Quick start

### 1. Install dependencies

```bash
npm install
cd backend && npm install
```

### 2. Configure environment variables

Create a `backend/.env` file:

```bash
MONGO_URI=your_mongodb_atlas_uri
GEMINI_API_KEY=your_google_generative_ai_key
JWT_SECRET=your_jwt_secret
JWT_EXPIRES_IN=7d
MAX_FILE_SIZE=10485760
PORT=8000
NODE_ENV=development
```

### 3. Run the app

Start the backend:

```bash
cd backend && npm run dev
```

Start the frontend from the project root:

```bash
npm run dev
```

Then open the local Vite URL in your browser.

---

## Deployment

For production deployment:

1. Provision a MongoDB Atlas cluster
2. Set the backend environment variables on your hosting platform
3. Build the frontend with:

```bash
npm run build
```

4. Serve the frontend via a static host or reverse proxy
5. Point the app to your deployed backend API

Compatible hosting options include Render, Railway, Vercel, or a VM.

---

## Built for better learning

Studymate AI is designed for students who want a more personalized, focused, and effective study experience.

It turns raw study material into a learning journey — one that feels organized, intelligent, and motivating.

---

## License

This project is currently in active development for educational and personal productivity use.

---

<p align="center">
  <strong>Studymate AI</strong><br>
  Smart study. Better retention. Stronger outcomes.
</p>
