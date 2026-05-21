<h1 align="center">
  🎯 VocabMaster
</h1>

<h3 align="center">
  A gamified English vocabulary learning app powered by Spaced Repetition algorithm
</h3>

<p align="center">
  <em>Inspired by Duolingo & Anki — Built with React, Firebase, and Web Speech API</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/-React-61DAFB?style=for-the-badge&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/-Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" />
  <img src="https://img.shields.io/badge/-Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" />
  <img src="https://img.shields.io/badge/-Tailwind%20CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" />
  <img src="https://img.shields.io/badge/-Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" />
</p>

<p align="center">
  <a href="https://vocabmaster-luan.vercel.app">🌐 Live Demo</a>
  •
  <a href="#-features">✨ Features</a>
  •
  <a href="#-tech-stack">🛠️ Tech Stack</a>
  •
  <a href="#-installation">🚀 Installation</a>
  •
  <a href="#-architecture">🏗️ Architecture</a>
</p>

---

## 📸 Demo

<p align="center">
  <img src="./docs/screenshots/hero.png" alt="VocabMaster Hero" width="80%" />
</p>

<table>
  <tr>
    <td><img src="./docs/screenshots/flashcard.png" alt="Flashcard Mode" /></td>
    <td><img src="./docs/screenshots/quiz.png" alt="Quiz Mode" /></td>
  </tr>
  <tr>
    <td align="center"><b>Flashcard Mode</b></td>
    <td align="center"><b>Quiz Mode</b></td>
  </tr>
  <tr>
    <td><img src="./docs/screenshots/stats.png" alt="Statistics" /></td>
    <td><img src="./docs/screenshots/leaderboard.png" alt="Leaderboard" /></td>
  </tr>
  <tr>
    <td align="center"><b>Statistics Dashboard</b></td>
    <td align="center"><b>Weekly Leaderboard</b></td>
  </tr>
</table>

---

## 💡 The Problem

Learning English vocabulary is challenging for Vietnamese students. Existing apps like Duolingo are great but lack:
- 🇻🇳 **Vietnamese-focused content** (idioms, business terms relevant to VN market)
- 📚 **Custom vocabulary decks** (most apps lock content behind paywall)
- 🧠 **Transparent learning algorithm** (users don't know why a word appears today)

**VocabMaster** solves this by combining:
- ✅ Open-source Spaced Repetition (Leitner System)
- ✅ User-created decks
- ✅ Free, ad-free, with Vietnamese translation

---

## ✨ Features

### 🟢 Core Features
- 🔐 **Authentication** — Google OAuth & Email/Password via Firebase Auth
- 📚 **5 Pre-made Decks** — Business, Travel, Daily Life, IT, Food (100+ words)
- 🎴 **Flashcard Mode** — 3D flip animation with word, pronunciation, meaning, example
- 🔊 **Native Pronunciation** — Powered by Web Speech API (no API key needed)
- 📝 **Quiz Mode** — Multiple choice with timer and scoring system
- 💾 **Cloud Sync** — Progress saved to Firestore, accessible from any device

### 🟡 Gamification
- 🔥 **Daily Streak** — Track consecutive learning days
- ⭐ **XP System** — Earn 10 XP per correct answer
- 🎯 **Daily Goals** — Set custom word targets (default: 20/day)
- 🏆 **Weekly Leaderboard** — Compete with friends and global users
- 🏅 **Achievement Badges** — Unlock rewards for milestones

### 🔴 Advanced Features
- 🧠 **Spaced Repetition (Leitner System)** — 5-box algorithm for optimal review timing
- 📊 **Statistics Dashboard** — Visualize learning progress with interactive charts
- 🎨 **Dark Mode** — Eye-friendly for night studying
- 📱 **PWA Support** — Install as native app on mobile/desktop
- ✍️ **Custom Decks** — Create your own vocabulary sets
- 🎤 **Voice Recognition** — Practice pronunciation with speech-to-text

---

## 🛠️ Tech Stack

### Frontend
| Technology | Purpose |
|------------|---------|
| **React 18** | UI library |
| **Vite** | Build tool (fast HMR) |
| **React Router v6** | Client-side routing |
| **Tailwind CSS** | Utility-first styling |
| **Framer Motion** | Smooth animations |
| **Zustand** | Lightweight state management |
| **Recharts** | Data visualization |
| **Lucide React** | Modern icon library |

### Backend & Services
| Technology | Purpose |
|------------|---------|
| **Firebase Authentication** | User auth (Google + Email) |
| **Cloud Firestore** | NoSQL database |
| **Firebase Hosting** | Static hosting (optional) |
| **Web Speech API** | Text-to-speech & speech recognition |

### Deployment & Tools
| Technology | Purpose |
|------------|---------|
| **Vercel** | Production deployment |
| **GitHub Actions** | CI/CD pipeline |
| **ESLint + Prettier** | Code quality |

---

## 🏗️ Architecture
