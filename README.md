
# NewsFlash / InsightEngine

AI-powered web app that lets you search the latest news or summarize any article instantly using LLMs.

---

## Features

- Search latest news by keywords  
- AI-powered article summarization  
- Instant TL;DR, key points & takeaways  
- Copy sections (hover UX)  
- Download full summary as a file  
- Clean, modern UI (Next.js + Tailwind)

---

## How it works

### 1. News Search
- Enter keywords (e.g. AI, Finance, Startups)  
- App fetches latest articles via News API  
- Results are sorted by newest first  

### 2. URL Summarization
- Paste any article URL  
- System:
  1. Fetches webpage content  
  2. Extracts readable text  
  3. Sends it to an LLM (Gemini / OpenAI)  
  4. Returns structured summary:
     - Title  
     - TL;DR  
     - Key Points  
     - Takeaways  

---

## Tech Stack

- Frontend: Next.js (App Router)  
- Styling: Tailwind CSS + Framer Motion  
- Backend: Next.js API routes  
- AI: Gemini / OpenAI  
- News Source: NewsAPI  
- Deployment: Vercel  

---

## Installation

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPO.git
cd YOUR-REPO
npm install
npm run dev
