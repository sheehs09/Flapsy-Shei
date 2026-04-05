# 🐦 FLAPSY-SHEI

> A stylish, offline-ready Flappy Bird game built with pure HTML, CSS & JavaScript.

![Game](https://img.shields.io/badge/Game-Flappy%20Bird-f97316?style=for-the-badge&logo=javascript)
![HTML](https://img.shields.io/badge/Built%20With-HTML%2FCSS%2FJS-f5d020?style=for-the-badge)
![PWA](https://img.shields.io/badge/PWA-Offline%20Ready-4ade80?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)
![Free](https://img.shields.io/badge/Hosting-100%25%20Free-22c55e?style=for-the-badge)

---

## 🎮 Play Now

👉 **[flapsy-shei.netlify.app](https://flapsy-shei.netlify.app)** 

---

## ✨ Features

- 🐦 **Smooth bird physics** — gravity, flap jump, and realistic angle rotation
- 🌙 **Night sky theme** — animated stars, moon, and glowing pipes
- 💥 **Particle explosion** on death
- 🏆 **Medal system** — earn 💀🥉🥈🥇🏆 based on your score
- 💾 **High score saved** locally via `localStorage`
- 📱 **Mobile friendly** — tap to flap on any touchscreen
- ⌨️ **Keyboard support** — `Space` or `Arrow Up` to flap
- 📶 **Offline ready** — works without internet after first visit (PWA)
- 📲 **Installable** — add to Home Screen on Android & iOS

---

## 🗂️ Project Structure

```
flapsy-shei/
├── index.html      # Game — all logic, canvas rendering & UI
├── sw.js           # Service Worker — offline caching
├── manifest.json   # Web App Manifest — installable as an app
└── README.md       # You are here

---

## 🎯 How to Play

| Control | Action |
|---|---|
| `Click` / `Tap` | Flap wings |
| `Space` | Flap wings |
| `Arrow Up` | Flap wings |

- Fly through the gaps between pipes
- Don't hit the pipes, ground, or ceiling
- Every pipe you pass = **+1 point**
- Beat your high score to earn a better medal!

---

## 🏅 Medal System

| Medal | Score |
|---|---|
| 💀 | 0–4 |
| 🥉 | 5–9 |
| 🥈 | 10–19 |
| 🥇 | 20–39 |
| 🏆 | 40+ |

---

## 📶 Offline / PWA Setup

FLAPSY-SHEI works offline thanks to a **Service Worker** (`sw.js`). Here's how it works:

1. **First visit** — the browser caches all game files automatically
2. **Next visits** — the game loads instantly from cache, even with no internet
3. **Install it** — on mobile, tap *"Add to Home Screen"* to install it like a native app

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 Canvas | Game rendering |
| Vanilla JavaScript | Game logic & physics |
| CSS3 | UI, animations, styling |
| Service Worker API | Offline caching (PWA) |
| Web App Manifest | Installable app support |
| Google Fonts | Press Start 2P pixel font |
| localStorage | Persistent high score |

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

<div align="center">
  Shei made with ❤️ · Built with pure HTML/CSS/JS · No frameworks, no dependencies
</div>
