# 🌍 Yoruba ↔ English AI Translator

> A beautiful, AI-powered web app for translating between Yoruba and English — built as a portfolio project to demonstrate practical AI integration skills.

![Yoruba Translator Screenshot](https://img.shields.io/badge/Status-Live-brightgreen?style=flat-square) ![Anthropic Claude](https://img.shields.io/badge/Powered%20by-Claude%20AI-orange?style=flat-square) ![HTML](https://img.shields.io/badge/Built%20with-HTML%2FJS-blue?style=flat-square)

---

## ✨ Features

- **Bidirectional translation** — Yoruba → English and English → Yoruba
- **Tonal accuracy** — understands Yoruba diacritics and tone marks (à, á, â, ẹ, ọ, ṣ, etc.)
- **Culturally aware AI** — preserves idiom, nuance, and meaning
- **Instant copy** — one-click clipboard copy on either panel
- **Zero backend** — pure client-side; your API key stays in memory only
- **Responsive design** — works on desktop and mobile

---

## 🚀 Quick Start

### Option 1 — Run locally
```bash
git clone https://github.com/YOUR_USERNAME/yoruba-translator.git
cd yoruba-translator
# open index.html in your browser (no server needed)
open index.html
```

### Option 2 — GitHub Pages (recommended)
1. Fork or clone this repo
2. Go to **Settings → Pages**
3. Set source to `main` branch, root `/`
4. Your app will be live at `https://YOUR_USERNAME.github.io/yoruba-translator`

---

## 🔑 API Key Setup

This app calls the [Anthropic Claude API](https://console.anthropic.com/). You need a free account:

1. Sign up at [console.anthropic.com](https://console.anthropic.com/)
2. Create an API key under **API Keys**
3. Paste it into the key bar at the top of the app

> **Privacy:** Your key is held in browser memory only. It is never stored in localStorage, cookies, or sent anywhere except Anthropic's official API endpoint.

---

## 🛠️ Tech Stack

| Layer | Choice | Reason |
|-------|--------|--------|
| Frontend | Plain HTML / CSS / JS | Zero-dependency, deployable anywhere |
| AI Model | Claude (Anthropic) | Best-in-class multilingual + cultural nuance |
| Fonts | Playfair Display + DM Sans | Editorial feel with cultural warmth |
| Design | Adire-inspired indigo palette | Homage to Yoruba textile tradition |

---

## 📖 About Yoruba

Yoruba is a tonal language spoken by over **45 million people** across Nigeria, Benin, Togo, and the diaspora. It uses three tones (high, mid, low) marked with diacritics — accurate AI translation must handle these correctly.

This project was built to:
- Demonstrate real-world API integration skills
- Contribute a tool that serves the Yoruba-speaking community
- Showcase clean, accessible frontend development

---

## 🤝 Contributing

PRs welcome! Ideas for improvement:
- [ ] Add text-to-speech (Web Speech API)
- [ ] Offline fallback with a smaller local model
- [ ] History / saved translations
- [ ] Browser extension version

---

## 📄 License

MIT — use freely, credit appreciated.

---

*Built with ❤️ and Claude AI*
