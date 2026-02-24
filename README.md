# 🎯 Meet Your Match — AI-Powered Course Discovery

<div align="center">

![React](https://img.shields.io/badge/React-18-61DAFB?style=for-the-badge&logo=react)
![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?style=for-the-badge&logo=typescript)
![Vite](https://img.shields.io/badge/Vite-5-646CFF?style=for-the-badge&logo=vite)
![Google Gemini](https://img.shields.io/badge/Google_Gemini-AI-4285F4?style=for-the-badge&logo=google)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3-06B6D4?style=for-the-badge&logo=tailwindcss)
![Vercel](https://img.shields.io/badge/Deployed-Vercel-000000?style=for-the-badge&logo=vercel)

**Tinder-style AI course matching that helps prospective students find their perfect degree**

[🚀 Live Demo](https://meet-your-match.vercel.app) • [🎓 About](#-about) • [🛠️ Tech Stack](#️-tech-stack) • [🚀 Getting Started](#-getting-started)

</div>

---

## 🎓 About

**Meet Your Match** was built for a **Lincoln Award Programme** employer brief at the **University of Lincoln** to address a real institutional challenge: reduced student enrollment caused by prospective students being unsure of what to study.

The solution is a gamified, AI-powered experience — students swipe through courses Tinder-style, answer a short interest quiz, and receive **Google Gemini-powered recommendations** matched to the degree programmes best suited to them.

### The Problem It Solves

Many prospective students don't apply to university because they're uncertain which course to choose. Traditional course finders are passive and uninspiring. This app makes discovery **interactive, fun, and personalised** — directly addressing the gap between student uncertainty and university applications.

---

## ✨ Features

- **Tinder-Style Swiping** — Swipe right to shortlist, left to skip with smooth spring animations
- **AI-Powered Matching** — Google Gemini API analyses student interests and recommends best-fit courses
- **Interest Quiz** — Short personality and preference questionnaire to sharpen match accuracy
- **Match Results** — Visual breakdown of recommended courses with AI reasoning
- **Shareable Results** — Students can share their course matches
- **Analytics Dashboard** — Track which courses attract the most interest (Recharts)
- **Fully Responsive** — Optimised for mobile and desktop

---

## 🛠️ Tech Stack

| Category | Technology |
|---|---|
| Framework | React 18 + Vite |
| Language | TypeScript 5 |
| Styling | Tailwind CSS + shadcn/ui (Radix UI) |
| AI | Google Gemini API (`@google/genai`) |
| Swiping | react-tinder-card |
| Animations | react-spring |
| Routing | React Router v6 |
| Data Fetching | TanStack React Query |
| Forms | React Hook Form + Zod |
| Charts | Recharts |
| Deployment | Vercel |

---

## 🚀 Getting Started

### Prerequisites

- Node.js 18+ and npm
- Google Gemini API key ([get one here](https://ai.google.dev/))

### Installation

```bash
# Clone the repository
git clone https://github.com/toptech5419/course-leap-match-copyy.git
cd course-leap-match-copyy

# Install dependencies
npm install

# Set up environment variables
# Create a .env file and add:
# VITE_GEMINI_API_KEY=your_gemini_api_key_here

# Start the development server
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser.

### Build for Production

```bash
npm run build
npm run preview
```

---

## 🌐 Live Demo

**[https://meet-your-match.vercel.app](https://meet-your-match.vercel.app)**

---

## 🏗️ Project Context

Built as part of the **Lincoln Award Programme** — a professional development initiative at the University of Lincoln where students work on real employer briefs. This was a team project (4 developers).

**My contributions:**
- Swiping card mechanics and interaction logic
- App flow and navigation architecture
- Results page
- Google Gemini AI integration
- UI components and design

---

## 👨‍💻 Developer

**Temitope Alabi** — Full-Stack Developer | MSc Computer Science, University of Lincoln

- 🌐 GitHub: [@toptech5419](https://github.com/toptech5419)
- 💼 LinkedIn: [toptech5419](https://linkedin.com/in/toptech5419)
- 📧 Email: alabitemitope51@gmail.com
