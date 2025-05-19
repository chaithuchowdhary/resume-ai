# 🚀 Resume Job Matching Application

A smart web application that helps users **manage resumes** and discover **matching job opportunities**. Packed with AI features like resume parsing, job matching, cover letter generation, and skill gap analysis.

---

## ✨ Features

### 📄 Resume Management

* 📤 Upload and store CVs
* 🧠 Parse resume data
* 🔗 Generate QR codes for easy sharing

### 💼 Job Matching

* 🤖 Automated job suggestions based on skills & experience
* 🔍 Real-time job listings
* 📊 View detailed match percentage for each job

### 🧠 AI-Powered Tools

* ✍️ AI-generated cover letters
* 📉 Skill gap analysis
* 🛠️ Resume improvement suggestions

---

## 🛠️ Tech Stack

### 🌐 Frontend

* ⚛️ React with TypeScript
* ⚡ Vite for lightning-fast builds
* 🎨 Tailwind CSS for modern styling
* 🧱 shadcn/ui for UI components
* 🔄 Tanstack Query for seamless data fetching

### 🔙 Backend (Supabase)

* 🐘 PostgreSQL Database
* ⚙️ Edge Functions for serverless logic
* 🗂️ Storage for file management
* 🔐 Row Level Security (RLS)

---

## 🚧 Getting Started

### 📋 Prerequisites

* Node.js (v18 or higher)
* npm or yarn
* Supabase account

### 🛠️ Installation

```bash
# Clone the repository
git clone <your-repo-url>

# Install dependencies
npm install

# Start the development server
npm run dev
```

### 🔧 Environment Setup

Create a Supabase project and configure the following environment variables:

* `SUPABASE_URL`
* `SUPABASE_ANON_KEY`
* `OPENAI_API_KEY`

---

## 🗃️ Database Setup

Main tables used:

* `user_cvs` – stores user resumes and extracted data
* `profiles` – stores user profile details

---

## 📁 Project Structure

```
/src
  /components       # Reusable and resume-specific UI components
    /resume
    /ui
  /integrations     # API & external service integrations
  /pages            # Main application routes
  /utils            # Utility functions and helpers
/supabase
  /functions        # Supabase Edge Functions
```

---

## 🚀 Deployment

### 🌍 Frontend

* Deploy to platforms like Vercel, Netlify, or GitHub Pages
* Configure production env variables

### 🔙 Backend

* Managed by Supabase
* Edge Functions are deployed through the Supabase dashboard

---

## 🔌 API Documentation

### 🧩 Edge Functions

* `fetch-jobs` – Pulls and matches job listings with user resumes
* `analyze-resume` – Extracts skills from uploaded resumes
* `generate-cover-letter` – Crafts personalized cover letters

---

## 🔐 Security

* ✅ Row Level Security ensures user data is protected
* 🔑 API keys and secrets are securely stored in Supabase
* 🧼 File uploads are validated to prevent malicious input

---

## 🤝 Contributing

1. 🍴 Fork the repository
2. 🌿 Create a new feature branch
3. 📩 Submit a Pull Request

---

## 📄 License

Licensed under the [MIT License](LICENSE).
