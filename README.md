<div align="center">

# 🏛️ The Museum of Builds

### *A Curated Collection of Code — Built, Broken & Rebuilt*

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Bootstrap](https://img.shields.io/badge/Bootstrap_5-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)](https://getbootstrap.com/)
[![Google Gemini](https://img.shields.io/badge/Gemini_AI-4285F4?style=for-the-badge&logo=google&logoColor=white)](https://aistudio.google.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

> **"Every exhibit here began as an idea, then became a working piece of software — built line by line, tested, broken, and rebuilt."**

[🌐 Live Demo](#live-demo) • [📸 Screenshots](#screenshots) • [🚀 Features](#features) • [🛠️ Installation](#installation)

</div>

---

## 📖 Project Overview

**The Museum of Builds** is a personal portfolio gallery created by **Kirtan Patel**, a Full-Stack Developer and B.Tech Computer Engineering with AI (CEAI) student at UVPCE, Ganpat University.

This project is a **fully static, single-page HTML portfolio** that acts as a curated museum, showcasing six fully-functional web applications — each built end-to-end without any backend server, external database, or build pipeline. Every exhibit is a self-contained HTML file that can be opened directly in a browser.

The portfolio demonstrates hands-on proficiency across AI integrations, real-time multiplayer games, interactive tools, and classic front-end engineering.

---

## ✨ Features

| # | Exhibit | Category | Description |
|---|---------|----------|-------------|
| 🧩 01 | **Code Solver** | AI Tool | AI-powered code checker that reviews, explains, fixes, and simulates execution for 9 programming languages using the Gemini API |
| 💬 02 | **Message Repeater** | Utility | Lightweight tool for repeating and automating message flows |
| 🎨 03 | **DoodleGuess (Scribble Game)** | Multiplayer Game | Real-time draw-and-guess party game with AI-generated words, room-based multiplayer, live canvas sync, and scoring |
| 🤖 04 | **Multi-AI ChatBot** | AI Tool | Conversational chatbot supporting Gemini, OpenAI (GPT-4o), and Anthropic Claude — with file upload, voice input, image generation, and multi-provider switching |
| 🖼️ 05 | **Static WebPage** | Front-End | Elegant static landing page demonstrating solid front-end fundamentals |
| 🏃 06 | **Metro Dash** | Game | Neon endless-runner game with 3-lane dodging, jumping, sliding, coin collection, high-score tracking, and a fully synthesized procedural audio engine (zero external audio files) |
| 📜 — | **Museum Portfolio** | Portfolio | The gallery hub page linking all exhibits with a museum-themed aesthetic |
| 🎬 — | **Scroll Video Preview** | UI Demo | Scroll-driven video preview demonstration |

### 🔑 Core Capabilities

- ✅ **Zero Backend** — All apps run entirely in the browser
- ✅ **Multi-Provider AI** — Supports Gemini, OpenAI, Claude, and Groq in a single interface
- ✅ **Multiplayer** — Room-based real-time multiplayer using shared storage (DoodleGuess)
- ✅ **Procedural Audio** — Synthesized game music and SFX using the Web Audio API (Metro Dash)
- ✅ **Voice Input** — Speech-to-text in the ChatBot using the Web Speech API
- ✅ **File Analysis** — Upload and analyze documents in the Multi-AI ChatBot
- ✅ **Multi-Language Code Review** — Supports C, C++, Python, Java, C#, Rust, R, PHP, SQL
- ✅ **Secrets-Safe** — No API keys hardcoded; users supply keys through in-app settings panels
- ✅ **Fully Responsive** — Mobile-first, works on all screen sizes

---

## 🛠️ Technologies Used

### Languages
- **HTML5** — Semantic structure for all exhibits
- **CSS3** — Custom properties (variables), Flexbox, Grid, animations, glassmorphism
- **JavaScript (ES2022+)** — Async/await, Canvas API, Web Audio API, Web Speech API, Fetch API

### Frameworks & Libraries
- **Bootstrap 5.3.3** — Responsive grid and UI components (CDN)
- **Google Fonts** — Inter, JetBrains Mono, Playfair Display, Baloo 2, Merriweather, Source Code Pro

### AI & APIs
- **Google Gemini API** — `gemini-2.5-flash`, `gemini-2.5-pro`, `gemini-2.0-flash`
- **OpenAI API** — `gpt-4o`, `gpt-4o-mini`, `gpt-3.5-turbo`
- **Anthropic Claude API** — `claude-sonnet-5`, `claude-opus-4-8`, `claude-haiku-4-5`
- **Groq API** *(settings-based, no hardcoded keys)*

### Browser APIs
- **Canvas 2D API** — Drawing engine (Scribble Game, Metro Dash)
- **Web Audio API** — Synthesized game audio engine (Metro Dash)
- **Web Speech API** — Voice recognition (ChatBot)
- **Fetch API** — All AI provider calls
- **FileReader API** — File upload and analysis (ChatBot)

### DevOps & Version Control
- **Git** — Version control with history rewrite for secret removal
- **GitHub** — Source hosting with Push Protection enabled
- **`.gitignore`** — Secrets protection
- **`.env.example`** — API key documentation pattern

---

## 📁 Folder Structure

```
museum-of-builds/
│
├── 📄 museum-portfolio.html        # Main gallery hub (start here)
├── 📄 Simple-ChatBot.html          # Multi-AI ChatBot (Gemini/OpenAI/Claude)
├── 📄 code-solver.html             # AI Code Checker & Generator
├── 📄 scribble-game.html           # DoodleGuess Multiplayer Drawing Game
├── 📄 metro-dash.html              # Neon Endless Runner Game
├── 📄 message-repeater.html        # Message Automation Utility
├── 📄 Statik-WebPage.html          # Static Front-End Demo
├── 📄 scroll-video-preview.html    # Scroll-Driven Video Demo
│
├── 📁 video/                       # Local video assets for scroll preview
│
├── 📄 .env.example                 # API key template (safe to commit)
├── 📄 .gitignore                   # Prevents secrets from being tracked
└── 📄 README.md                    # This file
```

---

## ⚙️ Installation

> No build tools, no Node.js, no npm — just clone and open.

### 1. Clone the Repository

```bash
git clone https://github.com/kirtan1911/museum-of-builds.git
```

### 2. Navigate to the Project

```bash
cd museum-of-builds
```

### 3. Open in Browser

**Option A — Direct open (simplest):**
```bash
# Windows
start museum-portfolio.html

# macOS
open museum-portfolio.html

# Linux
xdg-open museum-portfolio.html
```

**Option B — Live Server (recommended for development):**

If you have VS Code, install the [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension, then right-click `museum-portfolio.html` → **"Open with Live Server"**.

**Option C — Python quick server:**
```bash
python -m http.server 8000
# Then open: http://localhost:8000/museum-portfolio.html
```

---

## ▶️ Run Project

Since every exhibit is a **self-contained HTML file**, no compilation or server startup is required.

### Start from the Gallery
Open `museum-portfolio.html` — this is the main hub. Click any exhibit card to navigate to that project.

### Open Individual Exhibits Directly

| Exhibit | File |
|---------|------|
| AI ChatBot | `Simple-ChatBot.html` |
| Code Solver | `code-solver.html` |
| Drawing Game | `scribble-game.html` |
| Metro Dash Game | `metro-dash.html` |
| Message Repeater | `message-repeater.html` |
| Static Page | `Statik-WebPage.html` |

### API Keys (for AI exhibits)

> ⚠️ **Never hardcode API keys.** All AI-powered exhibits ask for your key through an in-app settings panel. Keys are only stored in-memory for that browser session and are never saved to a file or sent to any server.

To use the AI features, you'll need one or more of:

| Provider | Get Key |
|----------|---------|
| Google Gemini | [aistudio.google.com/apikey](https://aistudio.google.com/apikey) |
| OpenAI | [platform.openai.com/api-keys](https://platform.openai.com/api-keys) |
| Anthropic Claude | [console.anthropic.com](https://console.anthropic.com) |

---

## 📸 Screenshots

> *Screenshots coming soon — visit the [live demo](#live-demo) to see every exhibit in action.*

| Museum Hub | AI ChatBot | Code Solver |
|:---:|:---:|:---:|
| `[Screenshot]` | `[Screenshot]` | `[Screenshot]` |

| DoodleGuess | Metro Dash | Static Page |
|:---:|:---:|:---:|
| `[Screenshot]` | `[Screenshot]` | `[Screenshot]` |

---

## 🌐 Live Demo

> 🔗 **[View Live on GitHub Pages](https://kirtan1911.github.io/museum-of-builds/museum-portfolio.html)** *(placeholder — update after enabling GitHub Pages)*

To enable GitHub Pages:
1. Go to your repository → **Settings** → **Pages**
2. Set source to **Deploy from a branch** → `main` → `/ (root)`
3. Save and wait ~1 minute for deployment

---

## 🔮 Future Improvements

- [ ] **Backend API Proxy** — Move API calls server-side to avoid exposing keys to browser network tab
- [ ] **WebSocket Multiplayer** — Replace polling-based multiplayer in DoodleGuess with real WebSocket connections for instant sync
- [ ] **Leaderboard Persistence** — Add persistent high-score storage for Metro Dash using localStorage or a lightweight backend
- [ ] **Additional AI Providers** — Add Mistral, Cohere, and Llama-based models to the ChatBot
- [ ] **More Exhibits** — ASP.NET Core project gallery, SQL database tools, REST API demos
- [ ] **Theme Toggle** — Light/dark mode switch for all exhibits
- [ ] **Progressive Web App (PWA)** — Service workers for offline support
- [ ] **CI/CD Pipeline** — GitHub Actions to auto-deploy to GitHub Pages on push
- [ ] **Code Solver Improvements** — Add support for TypeScript, Go, Kotlin, and Swift
- [ ] **Voice Output (TTS)** — Text-to-speech responses in the ChatBot
- [ ] **Accessibility (A11y)** — ARIA labels, keyboard navigation improvements across all exhibits

---

## 👤 Author

<div align="center">

### Kirtan Patel

**Full-Stack Developer · B.Tech CEAI Student**
*UVPCE, Ganpat University*

[![GitHub](https://img.shields.io/badge/GitHub-kirtan1911-181717?style=for-the-badge&logo=github)](https://github.com/kirtan1911)
[![Email](https://img.shields.io/badge/Email-kirtanbarot1911%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kirtanbarot1911@gmail.com)

**Skills:** ASP.NET Core · Entity Framework · SQL Server · JavaScript · Bootstrap · REST APIs · Gemini AI · Full-Stack Development

</div>

---

## 📜 License

```
MIT License

Copyright (c) 2026 Kirtan Patel

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
```

---

## 🤝 Contribution Guide

Contributions are welcome! Here's how to get involved:

### Step-by-Step

1. **Fork** the repository on GitHub
   ```
   Click the "Fork" button at the top right of this page
   ```

2. **Clone** your fork locally
   ```bash
   git clone https://github.com/YOUR-USERNAME/museum-of-builds.git
   cd museum-of-builds
   ```

3. **Create** a feature branch
   ```bash
   git checkout -b feature/your-feature-name
   ```

4. **Make your changes** — follow the existing code style and patterns

5. **Test** your changes in at least Chrome and Firefox

6. **Commit** with a clear message
   ```bash
   git add .
   git commit -m "feat: add dark mode toggle to ChatBot"
   ```

7. **Push** to your fork
   ```bash
   git push origin feature/your-feature-name
   ```

8. **Open a Pull Request** on GitHub — describe what you changed and why

### Contribution Rules

- ✅ Keep each exhibit self-contained (one `.html` file per exhibit)
- ✅ Never hardcode API keys — always use runtime input from the user
- ✅ Test on mobile before submitting
- ✅ Follow existing naming conventions
- ❌ Do not commit `.env` files or files containing real API keys
- ❌ Do not add npm/node dependencies — this is a zero-dependency project

---

## 🔀 Git Workflow

This project uses a simple **GitHub Flow**:

```
main  ──────●────────────────────●──────────────●──── (production)
             \                  /                \
feature/x     ●──●──●──────────●                 \
                               \                  ●──●── feature/y
                                hotfix/x           \
                                                    ●──●──●
```

| Branch | Purpose |
|--------|---------|
| `main` | Always deployable — only clean, reviewed code |
| `feature/*` | New features or exhibits |
| `fix/*` | Bug fixes |
| `hotfix/*` | Critical production fixes |

---

## 💻 Common Git Commands

```bash
# Clone the repository
git clone https://github.com/kirtan1911/museum-of-builds.git

# Check current status
git status

# Pull latest changes from GitHub
git pull origin main

# Create a new branch
git checkout -b feature/new-exhibit

# Stage all changes
git add .

# Stage a specific file
git add museum-portfolio.html

# Commit with a message
git commit -m "feat: add new exhibit to gallery"

# Push your branch to GitHub
git push origin feature/new-exhibit

# Merge feature branch into main (after PR review)
git checkout main
git merge feature/new-exhibit

# Delete the feature branch after merging
git branch -d feature/new-exhibit
git push origin --delete feature/new-exhibit

# View commit history
git log --oneline --graph

# Undo last commit (keep changes staged)
git reset --soft HEAD~1

# View differences
git diff
```

---

<div align="center">

**Built with ❤️ by Kirtan Barot — The Museum of Builds**

*"Every line of code is an artifact waiting to be exhibited."*

⭐ If you found this useful, please **star the repository!**

</div>