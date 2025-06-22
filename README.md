# Magezi AI

Magezi AI is an open-source, mobile-first website for generating AI-powered video shorts from text or templates.  
Key features include PWA support, voice input, dark mode, instant downloads, and integrations with OpenAI, Stability AI, and ElevenLabs. Free to use and installable as a mobile app!

---

## Table of Contents

1. [Features](#features)
2. [Live Demo](#live-demo)
3. [Screenshots](#screenshots)
4. [Tech Stack](#tech-stack)
5. [Project Structure](#project-structure)
6. [Getting Started](#getting-started)
7. [Usage](#usage)
8. [API Reference](#api-reference)
9. [Contributing](#contributing)
10. [Roadmap](#roadmap)
11. [License](#license)
12. [Contact](#contact)

---

## Features

- 🎬 Generate AI Shorts/Videos from text or templates
- 📱 Fully mobile-optimized UI (React + Tailwind)
- 🆓 Free basic access, no login needed
- ⬇️ Download/share video outputs easily
- 🧠 Smart templates and pretests
- 🟣 PWA: Install as a web/mobile app
- 🌙 Dark mode support
- 🎙️ Voice input (mic support)
- ⚡ Real-time feedback during generation
- 🕒 Output history & autosave
- 🔁 Regen/retry options
- 🔌 Public APIs for power users
- 🔗 Integrations: OpenAI, Stability AI, ElevenLabs

---

## Live Demo

[https://magezi-ai-github.io](https://magezi-ai-github.io)  
_Coming soon!_

---

## Screenshots

<!-- Add your screenshots or GIFs here -->
![Homepage - Mobile](docs/screenshots/mobile-home.png)
![Video Generation](docs/screenshots/generation.gif)

---

## Tech Stack

- **Frontend:** React, Tailwind CSS, PWA
- **Backend:** Node.js (Express) or Python (FastAPI/Flask)
- **AI APIs:** OpenAI, Stability AI, ElevenLabs
- **Hosting:** GitHub Pages (frontend), Render/Railway (backend)
- **Domain:** magezi-ai-github.io

---

## Project Structureai-video-generator/
├── frontend/    # React + Tailwind (PWA)
├── backend/     # Node.js or Python API
├── docs/        # Documentation
├── .github/     # GitHub workflows, templates
├── README.md
└── LICENSE# Clone repo
git clone https://github.com/quavo256/ai-video-generator.git
cd ai-video-generator

# Frontend setup
cd frontend
npm install
npm run dev  # or npm start

# Backend setup (choose one)
cd ../backend/node
npm install
npm run dev

# or for Python
cd ../python
pip install -r requirements.txt
python main.py# ai-video-generator