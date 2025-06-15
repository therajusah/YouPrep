# YouPrep 🤖🎯

**YouPrep** is an **AI-based interview preparation website** built using Google Gemini, designed to simulate real interview experiences and provide intelligent feedback. Whether you're preparing for technical roles, behavioural interviews, or domain-specific questions — YouPrep customizes the journey with generative AI and performance insights.

---

## 🚀 Features

- 🔮 **AI-Powered Question Generation** via Google Gemini
- 💬 **Realistic Mock Interviews** with voice and text-based interaction (powered by Vapi)
- 📚 **Topic-wise Practice** based on selected job roles
- 📈 **Performance Tracking** using real-time data and analytics
- 🔐 **User Authentication** via Firebase Auth
- 🧠 **Personalized Feedback & Suggestions** for continuous improvement
- 🌐 **Responsive Web Interface** built with Next.js and Tailwind CSS

---

## 🛠 Tech Stack

- **Frontend:** [Next.js](https://nextjs.org/), [Tailwind CSS](https://tailwindcss.com/)
- **Backend:** [Firebase Auth](https://firebase.google.com/products/auth), [PostgreSQL](https://www.postgresql.org/), [Prisma ORM](https://www.prisma.io/)
- **AI Engine:** [Google Gemini](https://deepmind.google/technologies/gemini/)
- **Voice Integration:** [Vapi AI](https://www.vapi.ai/)
- **Deployment:** Vercel / Firebase Hosting

---

## 🔧 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/therajusah/YouPrep.git
cd YouPrep
````

### 2. Install Dependencies

```bash
npm install
```

### 3. Setup Environment Variables

Create a `.env.local` file and add the following:

```env

# 🔥 Firebase Configuration
NEXT_PUBLIC_FIREBASE_API_KEY=your_firebase_api_key
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=your_project.firebaseapp.com
NEXT_PUBLIC_FIREBASE_PROJECT_ID=your_project_id
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=your_project.appspot.com
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=your_messaging_sender_id

# 🔐 Firebase Admin SDK (Used in server-side functions only)
FIREBASE_PROJECT_ID=your_project_id
FIREBASE_CLIENT_EMAIL=your_service_account_email@your_project.iam.gserviceaccount.com
FIREBASE_PRIVATE_KEY="-----BEGIN PRIVATE KEY-----\nYOUR_PRIVATE_KEY_CONTENT_HERE\n-----END PRIVATE KEY-----\n"

# 🤖 Google Gemini AI Key
GOOGLE_GENERATIVE_AI_API_KEY=your_gemini_api_key

# 🗣️ Vapi Integration
NEXT_PUBLIC_VAPI_WORKFLOW_ID=your_vapi_workflow_id
NEXT_PUBLIC_VAPI_WEB_TOKEN=your_vapi_web_token

# Google Gemini
GEMINI_API_KEY=your_gemini_api_key

# Vapi AI
VAPI_API_KEY=your_vapi_api_key

# PostgreSQL
DATABASE_URL=postgresql://USER:PASSWORD@HOST:PORT/DATABASE
```

### 4. Setup Prisma

```bash
npx prisma generate
npx prisma migrate dev --name init
```

### 5. Run the App

```bash
npm run dev
```

---

## 🧑‍🎓 Ideal For

* Freshers and experienced professionals preparing for:

  * Frontend / Backend / Full-Stack Interviews
  * Data Structures & Algorithms
  * Behavioral Rounds
  * Domain-specific roles

---
