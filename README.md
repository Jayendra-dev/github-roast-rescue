# 🔥 GitHub Roast & Rescue - LIVE

> **Real-time GitHub profile analyzer powered by Gemini AI + GitHub API**
> Get savagely roasted by AI based on your LIVE GitHub data, then get rescued with actionable fixes.

![Live Badge](https://img.shields.io/badge/LIVE-API-green?style=for-the-badge)
![Gemini AI](https://img.shields.io/badge/Gemini-1.5%20Flash-purple?style=for-the-badge)
![GitHub API](https://img.shields.io/badge/GitHub-API-black?style=for-the-badge)
![No Backend](https://img.shields.io/badge/100%25-Client%20Side-blue?style=for-the-badge)

**🚀 Live Demo:** https://your-link.netlify.app _(replace after deploy)_

---

### 📸 Preview
- Real-time fetch from `api.github.com/users/{username}`
- Gemini AI generates personalized roast with repo names
- Recruiter score, new bio, resume pitch, checklist

---

### ✨ Features

**LIVE Data (Not Mocked)**
- ✅ Fetches real-time profile + 50 repos + README check
- ✅ Shows `LIVE FETCHED 11:32 AM` timestamp - judge can verify
- ✅ 5-layer proxy fallback - works even on college WiFi
- ✅ Offline cache after 1st success

**GitHub Token Integration**
- 🔑 Without token: 60 req/hr
- 🔑 With token: 5000 req/hr - No more `Failed to fetch`
- Stored only in `localStorage`, never sent to server

**Gemini AI Integration**
- 🤖 Without Gemini: Rule-based roast (fork %, desc %, activity)
- 🤖 With Gemini: `gemini-1.5-flash` reads your actual repos and roasts with names like `portfolio`, `chat-app`
- Prompt engineering for JSON output: score, roasts, new bio, recruiter thought

**Roast & Rescue**
- 💀 Savage roast with highlights `<span>` - mentions specific repos
- 🛠️ Personalized rescue: New bio, resume pitch, pin checklist
- 👀 Recruiter POV - what hiring manager thinks in 30 sec

---

### 🛠️ Tech Stack

- **Frontend:** Single `index.html` - TailwindCSS + Vanilla JS
- **APIs:** GitHub REST API v3, Google Gemini 2.0 Flash
- **No Backend, No Build** - 100% client-side, deploy anywhere
- **Storage:** localStorage for API keys + last roast cache

---

### 🧠 How It Works
