# Edima Bassey — Software Engineer

**Full-stack engineer working across AI systems, backend architecture, and security. Based in Nigeria.**

I build end-to-end systems that can run offline, stay private, and ship. Creator of SALLY — Science Artificial Learning Logic and You.

<p>
<a href="https://github.com/Techma2004/SALLY"><img src="https://img.shields.io/badge/SALLY-v0.35%20Voice-8A2BE2?style=for-the-badge" /></a>
<img src="https://img.shields.io/badge/Offline-100%25-00D26A?style=for-the-badge" />
<img src="https://img.shields.io/badge/Debian-13_Trixie-A81D33?style=for-the-badge&logo=debian" />
<img src="https://img.shields.io/badge/Focus-AI%20Systems%20%26%20Security-c39b62?style=for-the-badge" />
</p>

- **Portfolio:** https://techma2004.github.io/Edima-Bassey-/
- **Main Project:** [Techma2004/SALLY](https://github.com/Techma2004/SALLY)
- **Email:** belovedbassey4@gmail.com | **GitHub:** [@Techma2004](https://github.com/Techma2004)

>  I build tech that respects privacy.

---

### About

I'm a software engineer who enjoys owning products end-to-end — from backend architecture to the last UI detail. My work spans **AI systems, backend, and security**.

I'm currently heads-down on **Sally Station** — a local, offline-capable AI assistant designed as a full "Station OS" for desktop, paired with a companion Android app. Built around one idea: a personal assistant shouldn't require a constant connection to someone else's server.

Alongside that, I'm working through a structured **cybersecurity and ethical hacking curriculum**, because I want to build systems I can also defend. I'm open to full-stack, AI/ML, or systems-focused roles where I can bring that same ownership.

---

### Tech Stack

**AI / Voice:** `llama.cpp` `Qwen2.5` `Piper TTS` `faster-whisper` `whisper.cpp` `openWakeWord`  
**Backend:** `Python` `Django + Channels` `FastAPI` `Flask` `PocketBase` `Node.js`  
**Frontend / Desktop:** `PyQt6 / OpenGL` `Rust` `Dioxus` `Tailwind`  
**Systems:** `Debian` `Linux` `Git` `Electronics / Robotics`

---

### Selected Work — What I've Built End to End

#### 1. SALLY — Science Artificial Learning Logic and You
`2025 — present | v0.35 Voice Shipped | In development`  
**Offline-first, private, voice-enabled personal assistant.**

SALLY is not a chatbot demo. She runs 100% locally on your machine. No cloud. The core that powers Sally Station.

**What it does today (v0.35):**
- **Offline Chat:** `llama.cpp` + `Qwen2.5-Coder-1.5B-Instruct-Q3_K_L.gguf` locally
- **Tools:** `get_weather` (OpenWeatherMap) + `get_news` (NewsAPI) — auto intent detection
- **Memory:** `memory.json` with last 10 turns for context
- **Voice:** Piper TTS `en_US-lessac-medium` (natural, offline) + faster-whisper `tiny` (39MB, offline STT)
- **API:** FastAPI server for companion apps
- **Portable & Identity Locked:** `PROJECT_ROOT` paths, anti-JARVIS filter

**Setup:**
```bash
git clone https://github.com/Techma2004/SALLY.git
cd SALLY && python3 -m venv venv && source venv/bin/activate
pip install -r requirements.txt
# download models (see repo README)
cp .env.example .env # add OPENWEATHER_API_KEY, NEWS_API_KEY
python3 main.py # Press Enter = voice, Type = text
```

**Repo:** [github.com/Techma2004/SALLY](https://github.com/Techma2004/SALLY)

#### 2. Sally Station — The Full Station OS
`In development`  
The full vision of SALLY — desktop OS + Android companion. Currently designing the macro/protocol system and mood state machine that voice tone and avatar behavior will be built on.  
`Django + Channels` `llama.cpp` `whisper.cpp` `PyQt6 / OpenGL`

#### 3. School Website Portal
`2024 — 2025 | Deployed`  
School management portal for a secondary institution, handling result processing across five user roles and six houses, with WAEC-standard grading. Now in active use and handed off to staff.  
`PocketBase` `Role-based access` `Grading systems`

#### 4. WENET
`2023 — 2024 | Prototype`  
Private messaging platform built solo from a single Flask app — real-time chat, contact discovery via phone matching and QR codes, consent-based message request flow. Later version explored P2P payments and admin panel with AI-assisted moderation.  
`Flask` `Real-time messaging`

#### 5. Cross-platform Browser Shell
`2024 | Active`  
Lightweight browser built in Rust with Dioxus, using system webview to run from single codebase on desktop and Android. Includes tab management, URL normalization, DuckDuckGo fallback.  
`Rust` `Dioxus`

#### 6. Tegy Mobile
`Prototype | Concept`  
Remote controlled surveillance vehicle — wireless camera, night vision, electric drive in hardware design phase. Planned upgrades: autonomous navigation, GPS, obstacle avoidance.  
`Robotics` `Electronics`

---

### Right Now

**Main focus:** SALLY v0.35 is stable. Building v0.4 wake word "Hey SALLY" with openWakeWord + v0.5 Tauri desktop GUI + RAG over docs.

**Learning:** Cybersecurity and ethical hacking — building systems I can defend.

**Open to:** Full-stack, backend, or AI-systems roles and collaborations.

---

### Contact

- **Email:** belovedbassey4@gmail.com
- **Phone:** +234 707 828 7176
- **GitHub:** github.com/Techma2004
- **Portfolio:** https://techma2004.github.io/Edima-Bassey-/ — replace with `https://techma2004.github.io/Edima-Bassey-/` when Pages is live

---

<p align="center">Edima Bassey · Nigeria · 2026 · Built offline</p>
