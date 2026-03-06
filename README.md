<!-- BANNER -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=4,12,30&height=220&section=header&text=AskMyDocs&fontSize=72&fontColor=fff&animation=fadeIn&fontAlignY=38&desc=Chat%20with%20Any%20Document%20Using%20AI&descAlignY=60&descColor=ffffff88&descSize=18" width="100%"/>

<br/>

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://github.com/DragAditya/AskMyDocs)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://github.com/DragAditya/AskMyDocs)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://github.com/DragAditya/AskMyDocs)
[![Gemini API](https://img.shields.io/badge/Gemini%20API-4285F4?style=for-the-badge&logo=google&logoColor=white)](https://aistudio.google.com)
[![PWA](https://img.shields.io/badge/PWA-Ready-5A0FC8?style=for-the-badge&logo=pwa&logoColor=white)](https://github.com/DragAditya/AskMyDocs)
[![License: MIT](https://img.shields.io/badge/License-MIT-22c55e?style=for-the-badge)](LICENSE)

<br/>

[![Stars](https://img.shields.io/github/stars/DragAditya/AskMyDocs?style=social)](https://github.com/DragAditya/AskMyDocs/stargazers)
[![Forks](https://img.shields.io/github/forks/DragAditya/AskMyDocs?style=social)](https://github.com/DragAditya/AskMyDocs/network/members)
[![Issues](https://img.shields.io/github/issues/DragAditya/AskMyDocs?color=red)](https://github.com/DragAditya/AskMyDocs/issues)
[![Last Commit](https://img.shields.io/github/last-commit/DragAditya/AskMyDocs)](https://github.com/DragAditya/AskMyDocs/commits/main)
[![Repo Size](https://img.shields.io/github/repo-size/DragAditya/AskMyDocs)](https://github.com/DragAditya/AskMyDocs)

<br/>

> **AskMyDocs** is a zero-backend, fully client-side AI document chat application. Upload any PDF, TXT, Markdown, CSV, or Word document and instantly have a conversation with it — powered entirely by **Google's Gemini API**, running in your browser with no server required. Your documents never leave your device. Your API key never touches any third-party server. Just pure, private, AI-powered document intelligence.

<br/>

**[🚀 Live Demo]([https://host-askmydocs.netlify.app/) · [📱 Install as App](#-install-as-android-app) · [🐛 Report Bug](https://github.com/DragAditya/AskMyDocs/issues) · [✨ Request Feature](https://github.com/DragAditya/AskMyDocs/issues)**

<br/>

</div>

---

## 📸 Preview

<div align="center">

| Dark Theme — Document Chat | File Upload & Document Manager |
|:---:|:---:|
| ![Chat UI](https://ibb.co/hFdYBLg0) | ![Upload UI]([https://via.placeholder.com/480x320/080b14/7b6ff0?text=Upload+%26+Manage](https://image2url.com/r2/default/images/1772768468771-7d118a94-3c0a-4b2f-9f9f-7aa77fafd4cd.jpg)) |

</div>

---

## 📋 Table of Contents

<details>
<summary>Click to expand</summary>

- [✨ Features](#-features)
- [🛠 Tech Stack](#-tech-stack)
- [⚙️ How It Works](#️-how-it-works)
- [📦 Project Structure](#-project-structure)
- [🚀 Quick Start](#-quick-start)
- [🔑 Getting Your API Key](#-getting-your-api-key)
- [📁 Supported Formats](#-supported-formats)
- [📱 Install as Android App](#-install-as-android-app)
- [☁️ Deployment](#️-deployment)
- [🔒 Privacy & Security](#-privacy--security)
- [🗺 Roadmap](#-roadmap)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)

</details>

---

## ✨ Features

<table>
<tr>
<td width="50%">

### 🧠 AI-Powered Chat
- Conversational Q&A over your documents
- Multi-turn memory — follow-up questions work naturally
- Understands context across long documents
- Answers only from your document — no hallucinations outside source
- Cites the document name as the source

</td>
<td width="50%">

### 📂 Document Management
- Upload multiple documents simultaneously
- Switch between documents without losing chat history
- Drag and drop anywhere on the page
- PDF, TXT, Markdown, CSV, DOCX support
- 10MB per file limit with real-time progress

</td>
</tr>
<tr>
<td>

### ⚙️ Flexible Configuration
- Choose between Gemini 1.5 Flash, 1.5 Pro, 2.0 Flash
- Adjustable response style (Precise → Creative)
- Custom system prompt support
- Settings persisted locally via `localStorage`
- API key stored only in your browser

</td>
<td>

### 🎨 Premium UI / UX
- Dark glassmorphism design with grain texture
- Animated floating welcome screen
- Typing indicator with pulse animation
- Toast notification system
- Responsive — works on mobile, tablet, desktop
- Installable as a PWA on Android & iOS

</td>
</tr>
<tr>
<td>

### 📊 Session Stats
- Live query counter
- Estimated pages processed
- Token usage tracker
- Document word count display

</td>
<td>

### 💾 Export & Utilities
- Export full chat as Markdown file
- Clear chat without losing document
- Quick suggestion prompts to get started
- Keyboard shortcuts (Enter to send, Shift+Enter for newline)

</td>
</tr>
</table>

---

## 🛠 Tech Stack

<div align="center">

| Layer | Technology | Why |
|---|---|---|
| **UI** | HTML5 + CSS3 + Vanilla JS | Zero dependencies, instant load |
| **AI** | Google Gemini API | Best free tier, long context window |
| **Fonts** | Syne + DM Sans (Google Fonts) | Premium typography |
| **Storage** | Browser `localStorage` | Settings persist across sessions |
| **File Reading** | FileReader API | Reads documents client-side, no upload |
| **Install** | Web App Manifest (PWA) | Installable on Android & iOS |
| **Hosting** | Any static host | No server needed |

</div>

> **Zero backend. Zero database. Zero cost to run.** The only thing that costs money is your Gemini API calls — and the free tier gives you 15 requests/minute and 1 million tokens/day.

---

## ⚙️ How It Works

```
┌─────────────────────────────────────────────────────────────┐
│                      YOUR BROWSER                           │
│                                                             │
│  1. User uploads file                                       │
│         │                                                   │
│         ▼                                                   │
│  2. FileReader API reads it locally (no upload to server)   │
│         │                                                   │
│         ▼                                                   │
│  3. Text extracted and stored in memory                     │
│         │                                                   │
│         ▼                                                   │
│  4. User asks a question                                    │
│         │                                                   │
│         ▼                                                   │
│  5. Document content + question → sent to Gemini API        │
│         │                                                   │
│         ▼                                                   │
│  6. Gemini reads the document and answers                   │
│         │                                                   │
│         ▼                                                   │
│  7. Answer displayed in chat UI                             │
└─────────────────────────────────────────────────────────────┘
```

### What Gets Sent to Gemini

```
System Prompt  →  "You are AskMyDocs, answer only from the document..."
Document Text  →  [full content, up to 80,000 characters]
Chat History   →  [last 4 conversation turns for context]
User Question  →  "What are the main topics covered?"
```

**Your document text is sent to Google's Gemini API to generate answers. No other third party receives your data.**

---

## 📦 Project Structure

```
AskMyDocs/
│
├── 📄 index.html          # The entire app — HTML + CSS + JS in one file
├── 📋 manifest.json       # PWA manifest for home screen installation
├── ⚙️  sw.js               # Service worker for offline support
├── 🖼  icon-192.png        # App icon (192×192)
├── 🖼  icon-512.png        # App icon (512×512)
└── 📖 README.md           # You are here
```

> **Single-file architecture.** The entire application — 1,000+ lines of UI, logic, and AI integration — lives in `index.html`. No build step. No npm. No webpack. Open the file and it works.

---

## 🚀 Quick Start

### Option A — Just Open It (Fastest)

```bash
# Clone the repo
git clone https://github.com/DragAditya/AskMyDocs.git
cd AskMyDocs

# Open directly in browser
open index.html          # macOS
start index.html         # Windows
xdg-open index.html      # Linux
```

> Note: Some browser features (like service workers) require a local server. For full functionality, use Option B.

---

### Option B — Local Server (Recommended)

```bash
# Clone
git clone https://github.com/DragAditya/AskMyDocs.git
cd AskMyDocs

# Using Node.js
npx serve .
# → http://localhost:3000

# OR using Python
python3 -m http.server 8080
# → http://localhost:8080

# OR using VS Code
# Install "Live Server" extension → right-click index.html → Open with Live Server
```

Then **add your API key** in the Settings panel (⚙ button, top right).

---

## 🔑 Getting Your API Key

AskMyDocs runs on Google's **Gemini API**, which has a generous free tier.

```
Step 1 → Go to: https://aistudio.google.com/apikey
Step 2 → Sign in with your Google account
Step 3 → Click "Create API Key"
Step 4 → Copy the key (starts with "AIzaSy...")
Step 5 → Open AskMyDocs → click ⚙ Settings → paste your key → Save
```

### Free Tier Limits (as of 2025)

| Model | Requests/min | Tokens/day | Context Window |
|---|---|---|---|
| Gemini 1.5 Flash | 15 RPM | 1,000,000 | 1M tokens |
| Gemini 1.5 Pro | 2 RPM | 50,000 | 1M tokens |
| Gemini 2.0 Flash | 15 RPM | 1,500,000 | 1M tokens |

> **Gemini 1.5 Flash is recommended** — it's fast, accurate, free, and has a 1M token context window that can handle even very large documents.

---

## 📁 Supported Formats

| Format | Extension | Notes |
|---|---|---|
| **PDF** | `.pdf` | Text extraction via browser (best for text-based PDFs) |
| **Plain Text** | `.txt` | Full support |
| **Markdown** | `.md` | Full support, formatting preserved |
| **CSV** | `.csv` | Great for asking questions about data |
| **Word Document** | `.docx`, `.doc` | Text content extracted |

> **Tip:** For scanned PDFs (images of text), convert to `.txt` first using an OCR tool for best results. Browser-based PDF text extraction works on text-layer PDFs only.

---

## 💡 Example Queries

Once you upload a document, try asking:

```
📋 "Summarize this document in 5 bullet points"
🔍 "What are the main arguments made in section 2?"
📅 "List all dates, deadlines, and schedules mentioned"
✅ "What action items or tasks are assigned?"
❓ "What does the author conclude about X?"
📊 "What data or statistics are cited?"
🌐 "What topics does this document NOT cover?"
💬 "Explain [technical term] as mentioned in this document"
📝 "Write a short executive summary of this document"
🔎 "Find all mentions of [person/company/keyword]"
```

---

## 📱 Install as Android App

AskMyDocs is a **Progressive Web App (PWA)** — you can install it on your Android phone and it will appear and behave like a native app.

### Android (Chrome)
```
1. Host the app (see Deployment below) or use the live demo
2. Open the URL in Chrome on your Android phone
3. Tap the ⋮ menu → "Add to Home Screen"
4. Tap "Install"
5. AskMyDocs appears on your home screen with its icon
6. Opens full-screen, no browser address bar
```

### iPhone (Safari)
```
1. Open the URL in Safari
2. Tap the Share button (□↑)
3. Tap "Add to Home Screen"
4. Tap "Add"
```

> Once installed: works offline (UI loads), full-screen mode, home screen icon, feels like a native app.

---

## ☁️ Deployment

Since AskMyDocs is a static app (no backend), deployment is effortless.

### ▲ Netlify (Recommended — 2 minutes, free forever)

```bash
# Option 1: Drag & Drop
# Go to app.netlify.com → drag the AskMyDocs folder → done

# Option 2: CLI
npm install -g netlify-cli
netlify login
cd AskMyDocs
netlify deploy --prod --dir .
```

**Your app gets a live URL like:** `https://askmydocs.netlify.app`

---

### 🐙 GitHub Pages (Free)

```bash
# Push your repo to GitHub, then:
# Settings → Pages → Source: main branch / root folder
# Live at: https://yourusername.github.io/AskMyDocs
```

---

### ⚡ Vercel (Free)

```bash
npm install -g vercel
cd AskMyDocs
vercel --prod
```

---

### 🔥 Firebase Hosting (Free)

```bash
npm install -g firebase-tools
firebase login
firebase init hosting   # select public directory: .
firebase deploy
```

---

## 🔒 Privacy & Security

AskMyDocs is designed with **privacy-first** principles:

| What | How |
|---|---|
| **Your documents** | Read locally by your browser. Never uploaded to any server except Gemini. |
| **Your API key** | Stored in `localStorage` on your device only. Never sent anywhere except directly to Google's Gemini API. |
| **Chat history** | Stored in memory only. Cleared when you close the tab. Not persisted anywhere. |
| **Analytics** | None. Zero tracking. No cookies. No third-party scripts. |
| **Data sent to Google** | Document text + your question → Gemini API. Subject to Google's API Terms of Service. |

> **Recommendation:** Do not upload documents containing sensitive personal, financial, or confidential information — the text is sent to Google's Gemini API for processing.

---

## 🗺 Roadmap

```
v1.0  ✅  Core chat + document upload + Gemini integration
v1.1  🔲  PDF.js integration for better PDF text extraction
v1.2  🔲  Highlight mode — see which paragraph the answer came from
v1.3  🔲  Multiple document comparison ("Compare doc A and doc B")
v1.4  🔲  Chat history persistence (localStorage)
v1.5  🔲  Voice input (Web Speech API)
v1.6  🔲  Text-to-speech for AI responses
v1.7  🔲  Dark / Light theme toggle
v2.0  🔲  Local AI mode (WebLLM / Gemma in browser — fully offline)
v2.1  🔲  OpenAI + Anthropic API support alongside Gemini
v2.2  🔲  Document annotation and notes
v2.3  🔲  Share conversation as public link
v2.4  🔲  Google Drive / Dropbox import
```

Want a feature? [Open an issue →](https://github.com/DragAditya/AskMyDocs/issues/new?template=feature_request.md)

---

## 🤝 Contributing

Contributions are welcome! AskMyDocs is intentionally **zero-dependency** — please keep it that way. No npm, no frameworks, no build steps.

```bash
# 1. Fork the repo on GitHub

# 2. Clone your fork
git clone https://github.com/YOUR_USERNAME/AskMyDocs.git
cd AskMyDocs

# 3. Create a feature branch
git checkout -b feat/your-feature-name

# 4. Make changes to index.html (the whole app lives here)

# 5. Test locally
npx serve .
# Open http://localhost:3000, add your API key, test thoroughly

# 6. Commit with conventional commits
git commit -m "feat: add PDF.js for better extraction"

# 7. Push and open a Pull Request
git push origin feat/your-feature-name
```

### Commit Convention

| Prefix | Use for |
|---|---|
| `feat:` | New feature |
| `fix:` | Bug fix |
| `ui:` | Visual / design changes |
| `perf:` | Performance improvement |
| `docs:` | Documentation only |
| `chore:` | Maintenance |

### Good First Issues

- 🟢 Add a light theme toggle
- 🟢 Improve PDF text extraction using PDF.js
- 🟡 Add chat history persistence in localStorage
- 🟡 Add a "copy answer" button on each AI message
- 🔴 Add support for multiple documents in one chat

---

## 📚 Resources

| Resource | Link |
|---|---|
| Gemini API Docs | [ai.google.dev/docs](https://ai.google.dev/docs) |
| Google AI Studio | [aistudio.google.com](https://aistudio.google.com) |
| Gemini Free Tier Limits | [ai.google.dev/pricing](https://ai.google.dev/pricing) |
| FileReader API Docs | [MDN FileReader](https://developer.mozilla.org/en-US/docs/Web/API/FileReader) |
| PWA Guide | [web.dev/progressive-web-apps](https://web.dev/progressive-web-apps/) |
| PDF.js (for future PDF support) | [mozilla.github.io/pdf.js](https://mozilla.github.io/pdf.js/) |

---

## 📄 License

```
MIT License — Copyright (c) 2025 DragAditya

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
```

See [LICENSE](LICENSE) for full text.

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=4,12,30&height=120&section=footer" width="100%"/>

**Built with ❤️ by [DragAditya](https://github.com/DragAditya)**

*Stop reading documents. Start talking to them.*

[![GitHub stars](https://img.shields.io/github/stars/DragAditya/AskMyDocs?style=social)](https://github.com/DragAditya/AskMyDocs)

</div>
