# Prepwise — AI Mock Interview Platform

<div align="center">
  <img src="https://github.com/user-attachments/assets/1c0131c7-9f2d-4e3b-b47c-9679e76d8f9a" alt="Project Banner" />

  <div>
    <img src="https://img.shields.io/badge/-Next.JS-black?style=for-the-badge&logo=nextdotjs" />
    <img src="https://img.shields.io/badge/-Vapi-black?style=for-the-badge&color=5dfeca" />
    <img src="https://img.shields.io/badge/-Tailwind_CSS-black?style=for-the-badge&logo=tailwindcss&color=06B6D4" />
    <img src="https://img.shields.io/badge/-Firebase-black?style=for-the-badge&logo=firebase&color=DD2C00" />
  </div>
</div>

Prepwise is an AI-powered mock interview platform that uses **Vapi Voice Agents**, **Google Gemini**, and **Firebase**. Users can practice interviews, get instant feedback, and track sessions through a clean dashboard.

---

## 🚀 Features
- AI-powered mock interviews using **Vapi Voice Agents**
- Real-time feedback with **Google Gemini**
- Firebase authentication (email + password)
- Dashboard to track all sessions
- Responsive UI built with Tailwind + shadcn/ui
- Detailed transcripts and structured AI feedback

---

## 🛠️ Tech Stack
- Next.js 15  
- Firebase (Auth + Firestore)  
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
Create a `.env.local` file:

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

## 🕸️ Snippets

### Generate Interview Questions (API)
```javascript
`Prepare questions for a job interview.
The job role is ${role}.
The job experience level is ${level}.
The tech stack is: ${techstack}.
The focus between behavioural and technical questions is: ${type}.
Number of questions: ${amount}.
Return only the questions in JSON array format.`
```

### Feedback Prompt
```javascript
prompt: `
You are an AI interviewer analyzing the mock interview.

Transcript:
${formattedTranscript}

Score from 0 to 100 on:
- Communication Skills
- Technical Knowledge
- Problem-Solving
- Cultural & Role Fit
- Confidence & Clarity
`
```

---

## 🔗 Assets
Public assets for the project:  
https://drive.google.com/drive/folders/1DuQ9bHH3D3ZAN_CFKfBgsaB8DEhEdnog?usp=sharing

