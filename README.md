# AI Learning Assistant (MERN)

Full-stack AI-powered study assistant with chat, document understanding, flashcards, quizzes, and progress tracking for learners.

## Features
- AI chat grounded in user documents and chat history
- PDF ingestion with chunking, search, and summarization
- Flashcard and quiz generation with scoring and review flows
- Progress tracking per user session
- Authenticated workspace with protected routes and clean UI

## Tech Stack
- Frontend: React + Vite, Tailwind, React Router, React Markdown
- Backend: Node.js, Express, JWT auth, Multer uploads
- Data/AI: MongoDB Atlas, Gemini API for generation

## Environment
Create `backend/.env` with your keys:

```bash
MONGO_URI=your_mongodb_atlas_uri
GEMINI_API_KEY=your_google_generative_ai_key
JWT_SECRET=your_jwt_secret
JWT_EXPIRES_IN=7d
MAX_FILE_SIZE=10485760
PORT=8000
NODE_ENV=development
```

## Run Locally
- Install frontend dependencies from the project root: `npm install`
- Install backend dependencies: `cd backend && npm install`
- Start the backend API: `cd backend && npm run dev` (uses nodemon)
- Start the frontend: from the root run `npm run dev` and open the local Vite URL

## Deploy (high level)
- Provision a MongoDB Atlas cluster and keep its connection string ready
- Set the backend environment variables above on your host (Render, Railway, Vercel, or a VM)
- Build the frontend with `npm run build` and serve it via a static host or reverse proxy
- Point the frontend API base URL to your deployed backend service
