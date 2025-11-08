# Prepwise — AI Mock Interview Platform

Prepwise is an AI-powered mock interview platform that uses **Vapi Voice Agents**, **Google Gemini**, and **Firebase**. Users can practice interviews, get instant feedback, and track sessions through a clean dashboard.

---

## 🚀 Features
- AI-powered mock interviews using Vapi Voice Agents
- Real-time feedback with Google Gemini
- Firebase authentication (email + password)
- Dashboard to track all sessions
- Responsive UI built with Tailwind + shadcn/ui
- Detailed transcripts and structured AI feedback

---

## 🛠️ Tech Stack
- Next.js  
- Firebase  
- Vapi AI  
- Google Gemini  
- Tailwind CSS  
- shadcn/ui  
- TypeScript  
- Zod  

---

## 📦 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/prasidhichoudhary/ai-mock-interview.git
cd ai-mock-interview
```

### 2. Install dependencies
```bash
npm install
```

### 3. Set environment variables
Create a `.env.local` file and add:

```env
NEXT_PUBLIC_VAPI_WEB_TOKEN=
NEXT_PUBLIC_VAPI_WORKFLOW_ID=

GOOGLE_GENERATIVE_AI_API_KEY=

NEXT_PUBLIC_BASE_URL=

NEXT_PUBLIC_FIREBASE_API_KEY=
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=
NEXT_PUBLIC_FIREBASE_PROJECT_ID=
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=
NEXT_PUBLIC_FIREBASE_APP_ID=

FIREBASE_PROJECT_ID=
FIREBASE_CLIENT_EMAIL=
FIREBASE_PRIVATE_KEY=
```

### 4. Start development server
```bash
npm run dev
```

Visit:  
http://localhost:3000

---
