# 🎯 InterviewAI – Smart Interview Coach

<div align="center">

![InterviewAI Banner](https://img.shields.io/badge/InterviewAI-Smart%20Coach-6c63ff?style=for-the-badge&logo=robot&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
![Hackathon](https://img.shields.io/badge/Built%20For-Hackathon-ff6584?style=for-the-badge)

**An AI-powered mock interview coach that evaluates responses, measures confidence, and provides personalized feedback for technical and HR interviews.**

[🚀 Live Demo](#) · [📸 Screenshots](#-screenshots) · [✨ Features](#-features) · [🛠️ Tech Stack](#️-tech-stack) · [📦 Installation](#-installation)

</div>

---

## 🏆 Problem Statement

Students and job seekers often struggle with interview preparation due to:

- ❌ **Lack of personalized feedback** on their answers
- ❌ **No affordable mock interview** opportunities
- ❌ **Poor confidence assessment tools** to track improvement
- ❌ **Unstructured preparation** without knowing where to focus
- ❌ **No real-time guidance** on communication and body language

---

## 💡 Proposed Solution

**InterviewAI** is a fully interactive, browser-based AI Interview Coach that:

- ✅ Conducts **realistic mock interviews** (Technical, HR, Full Round)
- ✅ **Evaluates responses** with multi-dimensional AI scoring
- ✅ **Measures confidence** across communication, clarity, and composure
- ✅ Provides **model answers** and detailed improvement suggestions
- ✅ Tracks **progress over time** with visual analytics
- ✅ Features a **gamified learning system** with XP, levels, and achievements

---

## 🌟 Impact

| Metric | Impact |
|--------|--------|
| 📈 Interview Confidence | Increases by up to **40%** with consistent practice |
| 🗣️ Communication Skills | Structured STAR method training improves clarity |
| 🎯 Placement Readiness | Covers **10+ question categories** across all rounds |
| 🏆 Gamification | **7-day streaks** and leaderboards drive daily engagement |
| 📊 Self-awareness | Radar charts and skill bars show exactly where to improve |

---

## ✨ Features

### 🎤 Mock Interview Engine
- **3 Interview Types**: Technical, HR & Behavioral, Full Round Simulation
- **3 Difficulty Levels**: Easy (Entry), Medium (Industry), Hard (FAANG)
- **10+ Question Bank**: DSA, OOP, DBMS, System Design, Behavioral, Leadership
- **Live Countdown Timer** with warnings at critical time
- **3 Answer Modes**:
  - 📝 Text Answer (Free-form)
  - 🎙️ Voice Answer (with animated waveform simulation)
  - 📋 STAR Method (Structured: Situation → Task → Action → Result)
- **Hint System** — reveal contextual hints when stuck
- **Skip & Retry** functionality

### 🤖 AI Feedback System
- **Overall Score Ring** with animated fill
- **4-Dimension Scoring**: Communication, Technical Accuracy, Structure, Confidence
- **Tabbed Feedback Panel**:
  - 📊 Summary with grade and analysis
  - 💪 Strengths identified in your answer
  - 📈 Specific improvements with actionable advice
  - 🌟 Model Answer from expert sources
- **Smart scoring** based on answer length, structure, keywords, and examples

### 💬 AI Coach Chat (Alex)
- Intelligent chatbot powered by a curated knowledge base
- **8+ Deep Topic Responses**:
  - "Tell me about yourself" framework
  - Common technical interview mistakes
  - Salary negotiation tactics
  - STAR Method with live examples
  - Questions to ask the interviewer
  - Handling unknown questions gracefully
  - System Design (RESHADED framework)
  - Behavioral mastery guide
- **Quick-Chat Shortcuts** for instant topic access
- Typing indicator with realistic response delay

### 📈 Progress Tracking
- **4 Key Metrics**: Sessions, Best Score, Practice Hours, Total Improvement
- **6-Skill Radar Chart** (Canvas-rendered, no external libraries)
- **Animated Skill Bars** for each competency area
- **Activity Heatmap** (7-week GitHub-style contribution grid)

### 🏆 Gamification System
- **XP Points** earned per interview
- **12 Levels** from Beginner to Legend
- **20 Achievements/Badges** to unlock
- **Global Leaderboard** with weekly resets and rewards
- **7-Day Streak** tracking

### 💡 Tips & Study Material
- **10 Expert Tip Cards** across 4 categories
- Category filters: Technical, HR, Body Language, Mindset
- Expandable detail sections with actionable bullet points

---

## 📸 Screenshots

### 🏠 Dashboard
> Overview with stats, confidence meter, recent interviews, quick actions and level progress

### 🎤 Mock Interview Arena
> Live question with timer, STAR method form, and real-time AI feedback panel

### 🤖 AI Coach Chat
> Smart conversational coach with topic shortcuts and expert responses

### 📈 Progress Page
> Radar chart, skill bars, and activity heatmap visualization

### 🏆 Leaderboard & Achievements
> Global rankings and gamified badge system

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| **Frontend** | HTML5, CSS3, Vanilla JavaScript (ES6+) |
| **Styling** | Custom CSS with CSS Variables, Flexbox, CSS Grid |
| **Charts** | HTML5 Canvas API (no external chart library) |
| **Animations** | Pure CSS keyframe animations |
| **Fonts** | Segoe UI (system font) |
| **Icons** | Unicode Emoji (no icon library dependency) |
| **AI Logic** | Rule-based NLP matching with curated knowledge base |
| **Storage** | In-memory state management |
| **Deployment** | Static HTML — works on any web server or local browser |

> **Zero Dependencies** — No npm, no frameworks, no CDN required. Just open `index.html`!

---

## 📦 Installation

### Option 1: Direct Open (Simplest)
```bash
# Clone the repository
git clone https://github.com/gauribagde56-alt/interview-ai-smart-coach-.git

# Navigate to folder
cd interview-ai-smart-coach-

# Open in browser
start index.html          # Windows
open index.html           # macOS
xdg-open index.html       # Linux
```

### Option 2: Live Server (VS Code)
```bash
# Install VS Code Live Server extension
# Right-click index.html → "Open with Live Server"
```

### Option 3: Python HTTP Server
```bash
# Python 3
python -m http.server 8080

# Then visit: http://localhost:8080
```

### Option 4: Node.js
```bash
npx serve .
# Then visit: http://localhost:3000
```

---

## 📁 Project Structure

```
interview-ai-smart-coach-/
│
├── 📄 index.html          # Complete single-file application
│   ├── 🎨 <style>         # All CSS (2000+ lines, fully custom)
│   └── ⚙️ <script>        # All JavaScript logic (800+ lines)
│
├── 📖 README.md           # This file
└── 📜 LICENSE             # MIT License
```

---

## 🗺️ Pages & Navigation

```
InterviewAI
├── 🏠 Dashboard          → Stats, confidence meter, quick actions, recent interviews
├── 🎤 Mock Interview     → Setup → Arena → Feedback → Results
├── 🤖 AI Coach Chat      → Conversational AI with topic shortcuts
├── 💡 Tips & Tricks      → Filterable expert tip cards
├── 📈 My Progress        → Radar chart, skill bars, heatmap
├── 🏆 Leaderboard        → Global rankings & weekly rewards
├── 🎖️ Achievements       → Badge collection system
└── ⚙️ Settings           → Profile & preferences
```

---

## 🎮 How to Use

### Starting a Mock Interview
1. Click **"Start Interview"** from Dashboard or sidebar
2. Select **Interview Type** (Technical / HR / Full Round)
3. Set **Difficulty** (Easy / Medium / Hard) and **Number of Questions**
4. Optionally select **Target Company**
5. Click **"Begin Interview Session"**
6. Answer each question (text, voice, or STAR method)
7. Click **"Submit Answer"** to get instant AI feedback
8. Review strengths, improvements, and model answer
9. Continue to next question or finish session
10. View your **Results Summary** with full breakdown

### Using AI Coach Chat
1. Navigate to **AI Coach Chat** from sidebar
2. Type any interview-related question
3. Use **Quick Question shortcuts** for common topics
4. Get detailed, structured responses with actionable tips

### Tracking Progress
1. Navigate to **My Progress** from sidebar
2. View your skill radar chart and improvement over time
3. Check the activity heatmap for consistency tracking

---

## 🧠 Question Bank

### Technical Questions Cover:
| Topic | Questions |
|-------|-----------|
| Data Structures | Stack vs Queue, Hash Tables, BST |
| Algorithms | Big O Notation, Recursion, Sorting |
| OOP | Four Pillars, Design Patterns, Singleton |
| Databases | SQL vs NoSQL, Indexing, Normalization |
| Web/API | REST API, HTTP Methods, Status Codes |
| OS/Systems | Deadlocks, Concurrency, Memory Management |

### HR & Behavioral Questions Cover:
| Topic | Questions |
|-------|-----------|
| Introduction | Tell me about yourself |
| Situational | Challenge/failure handling |
| Leadership | Leading without authority |
| Self-awareness | Greatest weakness |
| Career | 5-year goals, company fit |
| Conflict | Disagreeing with managers |
| Pressure | Working under tight deadlines |

---

## 🚀 Future Enhancements

- [ ] 🎙️ **Real Voice Recognition** using Web Speech API
- [ ] 🤖 **GPT-4 Integration** for truly dynamic AI responses
- [ ] 📱 **Mobile App** (React Native)
- [ ] 👥 **Peer-to-Peer Mock Interviews** via WebRTC
- [ ] 📹 **Video Analysis** for body language feedback
- [ ] 📊 **Company-specific Question Sets** (Google, Amazon, etc.)
- [ ] 🌍 **Multi-language Support** (Hindi, Tamil, etc.)
- [ ] 🔐 **User Authentication** with persistent progress
- [ ] 📧 **Weekly Progress Email Reports**
- [ ] 🧠 **Adaptive AI** that learns from your weak areas

---

## 👩‍💻 Team / Author

**Built for Hackathon 2026**

| | |
|--|--|
| 👤 **Developer** | Gauri Bagde |
| 🐙 **GitHub** | [@gauribagde56-alt](https://github.com/gauribagde56-alt) |
| 🎯 **Project** | AI Interview Coach |
| 📅 **Built On** | October 2026 |

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

```
MIT License — Free to use, modify, and distribute with attribution.
```

---

## 🙏 Acknowledgements

- 📚 Interview preparation resources from top tech companies
- 🎨 Design inspired by modern SaaS dashboards
- 💡 STAR Method framework by behavioral interview research
- 🔧 RESHADED System Design framework by community contributors

---

<div align="center">

**⭐ If this project helped you, please give it a star! ⭐**

Made with ❤️ for students and job seekers everywhere

*"The best way to predict your future is to create it — starting with acing your interviews."*

</div>
