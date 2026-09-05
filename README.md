# 🎂 Ultah Joice &mdash; 12 September 2026

A one-file birthday love-letter website built for a best friend's 15th birthday. Pink, sparkly, and full of inside jokes.

> **Live site:** https://wilsonmarbun231210-afk.github.io/ultah-joice/

## ✨ Features

- 🎉 Opening envelope + day picker cover
- 📜 Birthday wish with a typing animation (instant on mobile)
- 🎂 Animated 3-candle cake with drips, sprinkles, and smoke
- 🖼️ Photo slideshow with lightbox
- 💬 Chat buttons &mdash; WhatsApp &amp; Instagram (kept private on purpose)
- 📱 Fast on phones: lazy-loaded images, no heavy animations on mobile

## 🔧 Customize

All content lives in `index.html` (one file, no build step):

| What | Where |
|---|---|
| Birthday message | `const UCAPAN = "..."` |
| WhatsApp number | `const WA_NUMBER = "..."` |
| Instagram handle | `const IG_USERNAME = "..."` |
| Photos | `<img>` tags in slideshow / cover picker |
| Music | the `.mp3` referenced in the audio tag |

Open `index.html` directly in a browser, or serve it:

```bash
python -m http.server 8000
```