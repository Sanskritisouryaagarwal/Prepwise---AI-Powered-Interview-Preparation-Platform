# 🧠 Prepwise - AI-Powered Interview Preparation Platform

**Prepwise** is a powerful and interactive job interview preparation platform designed to simulate real-life interview scenarios using AI voice agents. Built using **Next.js**, **Firebase**, **Tailwind CSS**, and powered by **Vapi AI** and **Google Gemini**, Prepwise provides a seamless, smart, and personalized user experience for job seekers looking to improve their interview skills.

Whether you're preparing for technical, behavioral, or HR interviews, Prepwise offers real-time feedback, voice interaction, and performance analytics to help you grow confidently and efficiently.

![Untitled design](https://github.com/user-attachments/assets/cc356436-c541-41ee-95a9-1c4a46f6fb65)

---

## 📌 Table of Contents
- [Overview](#overview)
- [Tech Stack](#tech-stack)
- [Features](#features)
- [Getting Started](#getting-started)
- [Environment Variables](#environment-variables)
- [Run the App](#run-the-app)
- [Code Snippets](#code-snippets)
- [Assets](#assets)
- [Credits](#credits)
- [Contact](#contact)

---

## 🤖 Overview
Prepwise simulates realistic AI-driven interviews using voice and NLP technologies. It leverages Vapi’s voice agents and Google Gemini’s powerful generative AI to conduct mock interviews, generate dynamic questions, and provide immediate, insightful feedback. Users can:

- Practice interviews in real-time
- Get feedback on answers and speaking style
- Analyze transcripts and improvement suggestions
- Track interview history in a clean dashboard interface

Whether you're just starting your career or preparing for senior-level roles, Prepwise adapts to your level and helps you build confidence through practice.
![Untitled design (2)](https://github.com/user-attachments/assets/b6b67068-fb05-4626-89a5-5ee0217455d0)

---

## ⚙️ Tech Stack
- [Next.js](https://nextjs.org/) – Full-stack framework for building the UI and backend
- [Firebase](https://firebase.google.com/) – Authentication, Firestore database, and hosting
- [Tailwind CSS](https://tailwindcss.com/) – For modern, utility-first responsive styling
- [Vapi AI](https://www.vapi.ai/) – Voice agents to simulate interviews and analyze user inputs
- [Google Gemini API](https://deepmind.google/technologies/gemini/) – For dynamic question generation and feedback
- [shadcn/ui](https://ui.shadcn.dev/) – Reusable and accessible UI components
- [Zod](https://zod.dev/) – TypeScript-first schema validation

---

## 🔋 Features
- 🔐 **Authentication**: Secure login/signup with Firebase Email/Password authentication
- 🧑‍💼 **AI-Powered Interviews**: Engage in mock interviews with voice-based AI agents
- 💬 **Instant Feedback**: Receive AI-generated performance feedback post-interview
- 📄 **Transcripts**: Review a detailed transcript of your responses
- 📊 **Dashboard**: Track and manage previous interviews easily
- 💡 **Question Generation**: Dynamic, AI-driven question sets for various roles and domains
- 📱 **Mobile Friendly**: Fully responsive design for both desktop and mobile use
- 🧩 **Modular Architecture**: Clean, scalable, and reusable codebase for easy maintenance
![Untitled design (1)](https://github.com/user-attachments/assets/eb79e3e7-f73e-48dd-bf73-ad449d6972a5)

---

## ⚡ Getting Started

### Prerequisites
Ensure the following are installed on your system:
- Git
- Node.js (v16 or above recommended)
- npm (Node Package Manager)

### Clone the Repository
```bash
git clone https://github.com/adrianhajdin/ai_mock_interviews.git
cd ai_mock_interviews
```

### Install Dependencies
```bash
npm install
```

---

## 🔐 Environment Variables
Create a `.env.local` file in the root directory and fill in the following:

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
> ⚠️ Replace placeholder values with your actual credentials from Firebase and Vapi.

---

## 🧪 Run the App
Start the development server:
```bash
npm run dev
```
Visit `http://localhost:3000` in your browser to interact with the application.

---

## 🧩 Code Snippets
Key logic and utility files include:
- `globals.css` – Global styles and resets
- `lib/utils.ts` – Common utility functions
- `app/api/vapi/generate/route.tsx` – Interview question prompt generation logic
- `lib/actions/general.action.ts` – AI feedback prompt logic
- `app/(root)/interview/[id]/feedback/page.tsx` – Feedback display UI

Dummy interviews and test data available in seed files.

---

## 🔗 Assets
Public assets (images, logos, and static files) are stored in the `/public` directory.

---

## 📣 Credits
This project is inspired by and built following the [JavaScript Mastery](https://www.youtube.com/@javascriptmastery) tutorial. Special thanks to Adrian Hajdin and the JSM community.

---

## 📬 Contact
Built with 💙 by **Sanskriti Sourya**  
📧 Email: sanskritisourya8448@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/sanskriti-sourya)  

Feel free to fork, star ⭐, and contribute to the project!
