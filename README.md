# 🧠 AI-Powered Dynamic Personal Website

This is a smart personal website that updates itself — seriously.

Instead of manually updating your site every time you add a new skill, job, or project, this system does it for you. It uses AI agents to pull new activity from LinkedIn, categorize it (skills, experience, posts, etc.), and automatically update your website via a backend.

The project is divided into three parts:

## 🚀 Repositories

- **Frontend** – [ryan-pwp-front](https://github.com/ryanviana/ryan-pwp-front)  
  The dynamic personal website interface, connected to the backend.

- **AI Agents** – [ryan-pwp-ai](https://github.com/ryanviana/ryan-pwp-ai)  
  Intelligent agents that crawl LinkedIn, extract relevant updates, and format them accordingly.

- **Backend** – [ryan-pwp-back](https://github.com/ryanviana/ryan-pwp-back)  
  Stores structured data and serves it to the frontend.

---

## ✨ How It Works

1. AI agents scan your LinkedIn activity.
2. They detect new experiences, skills, blog posts, etc.
3. That info gets automatically formatted and posted to your backend.
4. Your personal website reflects the updates in real-time — no manual edits needed.

---

## 🔧 Tech Stack

- Frontend: Next.js / React
- Backend: Node.js / Express / MongoDB
- AI Layer: LangChain / OpenAI API / Puppeteer
