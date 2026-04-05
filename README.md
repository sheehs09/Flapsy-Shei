# 🐦 FLAPSY-SHEI

> A stylish, offline-ready Flappy Bird game built with pure HTML, CSS & JavaScript.

![Game](https://img.shields.io/badge/Game-Flappy%20Bird-f97316?style=for-the-badge&logo=javascript)
![HTML](https://img.shields.io/badge/Built%20With-HTML%2FCSS%2FJS-f5d020?style=for-the-badge)
![PWA](https://img.shields.io/badge/PWA-Offline%20Ready-4ade80?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)
![Free](https://img.shields.io/badge/Hosting-100%25%20Free-22c55e?style=for-the-badge)

---

## 🎮 Play Now

👉 **[flapsy-shei.netlify.app](https://flapsy-shei.netlify.app)** *(replace with your live URL)*

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
```

---

## 🚀 Deploy to Netlify

This project is deployed via **GitHub + Netlify** — both are completely free.

### Step 1 — Push to GitHub
```bash
git clone https://github.com/YOUR_USERNAME/flapsy-shei.git
cd flapsy-shei
# Add your files, then:
git add .
git commit -m "🐦 Initial commit - FLAPSY-SHEI"
git push origin main
```

### Step 2 — Connect to Netlify
1. Go to [netlify.com](https://netlify.com)
2. Click **"Add new site"** → **"Import an existing project"**
3. Choose **GitHub** and select the `flapsy-shei` repo
4. Leave build settings **blank** (no build command needed)
5. Click **"Deploy site"** 🎉

### Auto-Deploy
Every `git push` to `main` automatically redeploys your game on Netlify. No manual steps needed!

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

## 💰 Cost Breakdown

| Service | Cost |
|---|---|
| GitHub (code hosting) | **FREE** |
| Netlify (web hosting) | **FREE** |
| `.netlify.app` domain | **FREE** |
| Custom domain *(optional)* | ~$10–15/year |

**Total to go live: $0** 🎉

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

<div align="center">
  Made with ❤️ · Built with pure HTML/CSS/JS · No frameworks, no dependencies
</div>
