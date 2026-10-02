# 🎸 Jason’s Guitar Basics

**Interactive left-handed-friendly guitar learning web app for absolute beginners.**

Learn open chords, strumming patterns, and classic rock / grunge songs with real-time feedback from your microphone — all in your browser. No install required (but you *can* install it as an app).

![App](icon-512.png)

---

## ✨ Features

- **Lefty Mode** — One-tap toggle that mirrors every chord diagram the way a left-handed player sees the neck
- **Visual chord diagrams** — Em, Am, G, C, D, E, A, Dm with finger numbers and tips
- **Real-time mic feedback** — Play a chord and the app tells you when it sounds right
- **Chord Coach** — Dedicated practice mode with live match %
- **Strumming patterns** — Down, Down-Up, Folk, Island, Rock 8ths, Slow Ballad
- **Beginner Rock Starter Set** — Carefully ordered songs that build on each other
- **Practice metronome** — Chord switcher with optional mic assist
- **Progress tracking** — Local streak counter and “practiced” checkmarks
- **PWA support** — Add to home screen and use it like a native app

---

## 🎵 Beginner Rock Starter Set

| Order | Chords              | Song                          | Why it’s good for beginners      |
|-------|---------------------|-------------------------------|----------------------------------|
| 1     | Em + D              | Horse with No Name            | Only 2 chords                    |
| 2     | A + D + E           | Wild Thing                    | Classic 3-chord garage rock      |
| 3     | D + C + G           | Sweet Home Alabama + Bad Moon Rising | Southern rock staples     |
| 4     | G + C + D + Em      | Good Riddance + Brown Eyed Girl | Green Day & Van Morrison     |
| 5     | Em + C + G + D      | Zombie                        | 90s alternative feel             |
| 6     | Em + G              | About a Girl (Nirvana)        | Simple grunge                    |
| 7     | G + D + Am + C      | Knockin’ on Heaven’s Door     | Dylan / Guns N’ Roses            |

---

## 🚀 How to Use

### Quick start (local)
1. Download or clone this repo
2. Keep **all files in the same folder**
3. Open `guitar-learner.html` in Chrome or Safari
4. Allow microphone access when asked (for the “Check Me” / Coach features)

### Install as an app (recommended)
- **Android (Chrome)**: Menu → “Install app” or “Add to Home screen”
- **iPhone (Safari)**: Share button → “Add to Home Screen”
- **Computer (Chrome / Edge)**: Look for the install icon in the address bar

Once installed it opens full-screen with its own icon.

### Live demo via GitHub Pages
If you enable **Settings → Pages** on this repo (Source: `main` / root), the app will be available at:

```
https://indymodz.github.io/jasons-guitar-basics/guitar-learner.html
```

---

## 📁 Files

| File                    | Purpose                          |
|-------------------------|----------------------------------|
| `guitar-learner.html`   | Main app (everything runs here)  |
| `manifest.json`         | PWA configuration                |
| `sw.js`                 | Service worker (offline cache)   |
| `icon-192.png`          | App icon (192×192)               |
| `icon-512.png`          | App icon (512×512)               |
| `apple-touch-icon.png`  | iOS home-screen icon             |

---

## 🎸 Tips for Left-Handed Players

1. Turn on **Lefty Mode** (top-right toggle) — diagrams flip so the low E string is on the right
2. Start with **Em** and **Am** (only two fingers each)
3. Practice changes slowly with the metronome before adding speed
4. Use the **Strumming** tab to learn patterns, then apply them in Practice or Songs

---

## 🛠 Technical Notes

- Pure HTML + CSS + JavaScript — no build step, no frameworks
- Microphone feedback uses the Web Audio API (pitch-class energy matching)
- Works best over **https** (or localhost) for full mic + install support
- Progress and Lefty preference are saved in `localStorage`

---

## 📄 License

Free to use and share for personal learning.  
Created for Jason — lefty acoustic beginner on a rock & grunge path.

---

**Practice a little every day. You’ve got this.** 🎸
