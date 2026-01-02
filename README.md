# 📊 Mood Tracker PWA

A beautiful, minimal mood tracking app inspired by [K Manuel's viral mood tracker](https://x.com/theklmanuel). Track your daily mood throughout the year with a clean design.

![Mood Tracker Preview](https://img.shields.io/badge/PWA-Ready-brightgreen) ![License](https://img.shields.io/badge/license-MIT-blue)

## ✨ Features

- **📅 Month & Year Views** - Toggle between detailed monthly calendar and yearly overview
- **🎨 6 Mood Levels** - From A+ (core memory) to F (very negative)
- **📝 Daily Notes** - Add notes to remember what made each day special
- **📤 Share Your Year** - Generate beautiful Instagram Story images (1080x1920)
- **🌓 Auto Dark/Light Mode** - Switches based on time of day (7am-7pm)
- **📱 PWA Support** - Install on your iPhone home screen
- **💾 Offline First** - Works without internet
- **🔒 Privacy** - All data stored locally on YOUR device only
- **� Export/Import** - Backup your data as JSON

## 🚀 Quick Start

### Use the Hosted Version
1. Visit **[https://lennartP-sch.github.io/Mini-IphoneApp/](https://lennartP-sch.github.io/Mini-IphoneApp/)**
2. On iPhone: Tap Share → "Add to Home Screen"
3. Start tracking your mood!

### Self-Host
```bash
git clone https://github.com/LennartP-sch/Mini-IphoneApp.git
cd Mini-IphoneApp
# Serve with any static server
npx serve .
```

## 🎯 Mood Legend

| Grade | Color | Meaning |
|-------|-------|---------|
| **A+** | 🟢 Dark Green | Positive core memory |
| **A** | 🟢 Green | Very positive |
| **B** | 🟡 Light Green | Positive |
| **C** | 🟡 Yellow | Neutral (or positive offset negative) |
| **D** | 🟠 Orange | Negative |
| **F** | 🔴 Pink/Red | Very negative |

## 🔒 Privacy

Your mood data **never leaves your device**. Everything is stored in your browser's localStorage. Even if you share the link, others will see an empty tracker - they can't access YOUR data.

## 📦 Tech Stack

- Vanilla HTML, CSS, JavaScript
- PWA with Service Worker
- localStorage for persistence
- No frameworks, no backend, no tracking

## 📄 License

MIT - Feel free to fork and make it your own!

---

*Inspired by [@theklmanuel](https://x.com/theklmanuel)'s mood tracker tweets* 🙏
