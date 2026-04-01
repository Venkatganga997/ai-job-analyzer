# 🎯 AI Job Application Analyzer

An AI-powered tool that analyzes your resume against a job description — highlights missing keywords, scores ATS compatibility, and rewrites weak bullet points to improve your chances.

**100% free · No backend · Runs in the browser**

---

## ✨ Features

- **Job Match Score** — how well your resume aligns with the JD
- **ATS Score** — likelihood of passing Applicant Tracking System filters
- **Keyword Analysis** — missing / partial / matched keywords highlighted
- **Bullet Point Rewrites** — AI rewrites weak lines with stronger action verbs and job-relevant keywords
- **Actionable Tips** — specific improvements to make
- **PDF Resume Upload** — drag & drop or browse (parsed in-browser, nothing uploaded to any server)

---

## 🚀 Getting Started

### 1. Get a Free Gemini API Key

1. Go to [Google AI Studio](https://aistudio.google.com/app/apikey)
2. Sign in with your Google account
3. Click **Create API Key**
4. Copy the key

### 2. Open the App

Just open `index.html` in any modern browser — no install, no server needed.

### 3. Use It

1. Paste your **Gemini API key** in the top-right and click Save
2. Paste the **Job Description** on the left
3. **Upload your resume** (PDF/TXT) or paste the text on the right
4. Click **Analyze My Resume**
5. Review your scores, keywords, and rewritten bullet points

---

## 🛠 Tech Stack

| Layer | Tool |
|-------|------|
| UI | Vanilla HTML + CSS (dark theme) |
| AI | Google Gemini 1.5 Flash (free tier) |
| PDF Parsing | PDF.js (in-browser, no upload) |
| Hosting | Any static host or just open locally |

---

## 📁 Project Structure

```
ai-job-analyzer/
├── index.html   # Complete app (HTML + CSS + JS in one file)
└── README.md
```

---

## 🔒 Privacy

- Your resume and JD are sent **only to the Gemini API** using your own key
- Nothing is stored on any server — no database, no backend
- API key is saved in your browser's `localStorage` only

---

## 💡 How to Host for Free

**GitHub Pages:**
1. Push this repo to GitHub
2. Go to repo **Settings → Pages → Source: main / root**
3. Your app is live at `https://yourusername.github.io/ai-job-analyzer`

**Netlify:**
1. Drag the project folder to [netlify.com/drop](https://app.netlify.com/drop)
2. Done — instant live URL

---

## 📄 License

MIT — free to use, modify, and share.
