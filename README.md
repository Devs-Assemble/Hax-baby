# 💤 Pip's Nursery — Junior Dream Engineer

> *"Hi, I'm Pip. I build the lullabies, nightlights and bedtime routes that help the neighborhood's little creatures fall asleep, zzz."*

A cozy, one-page website about **Pip**, a sleepy skull baby who works the night shift at Midnight Nursery. Built for the **haX.baby "Baby's First Website"** hackathon (17–19 October 2026, 48 hours).

🔗 **Live site:** https://devs-assemble.github.io/Hax-baby/

![Pip, a sleepy skull baby in a star nightcap, sitting on a cloud](assets/pip_avatar_cloud.jpg)

---

## ✨ What's inside

| Section | What it does |
|---|---|
| **Hero** | Pip's eyes follow your mouse or finger. Press *Say goodnight* to put Pip to sleep. |
| **Meet the baby** | Pip's profile: look, outfit, personality, quirks and voice. |
| **The Lullaby Lab** | A wind-up music box that composes a new lullaby each time, using the Web Audio API on a pentatonic scale so nothing can sound wrong. |
| **Nightlight Collection** | Tap the Sleepy Moon lamp to switch it on and off. Pairs with night mode. |
| **Rattle & Block Toys** | Tap blocks to play notes. Pip remembers your last eight taps and plays your tune back. |
| **Dream Delivery Routes** | A scroll-driven route where you follow Pip's cloud across the rooftops. |
| **How I got here** | A short scrolling origin story told in four scenes. |
| **Sign my wall** | A guestbook. Notes are saved in your own browser (`localStorage`). |

Small touches: a bedtime marquee, a day/night theme toggle that respects your system preference, a sound toggle, a visit counter (per device), and a hidden Easter egg. *(Hint: try typing `zzz`.)*

## 🛠️ Tech

- Plain **HTML, CSS and JavaScript** in a single `index.html`. No frameworks, no build step, no dependencies.
- **Web Audio API** for all sound. No audio files.
- **localStorage** for the guestbook, theme and visit count, with safe fallbacks if storage is unavailable.
- **Google Fonts:** [Fraunces](https://fonts.google.com/specimen/Fraunces) and [Fredoka](https://fonts.google.com/specimen/Fredoka).
- Hosted on **GitHub Pages**.

## ♿ Accessibility

- Respects `prefers-reduced-motion` and turns animations down.
- Follows `prefers-color-scheme` for the initial day/night theme.
- Decorative elements are hidden from assistive tech with `aria-hidden`.

## 📁 Project structure

```
Hax-baby/
├── index.html        # The whole site (markup, styles, scripts)
├── assets/
│   ├── pip_avatar_cloud.jpg
│   ├── pip_portrait.jpg
│   ├── pip_lullaby_box.jpg
│   └── pip_dream_lantern.jpg
└── README.md
```

## 🚀 Run it locally

No install needed. Clone the repo and open the file:

```bash
git clone https://github.com/Devs-Assemble/Hax-baby.git
cd Hax-baby
# open index.html in your browser, or serve it:
python3 -m http.server 8000   # then visit http://localhost:8000
```

## 🎨 Credits

- **Pip the Skull Baby** artwork: official haX.baby Track 1 asset pack.
- Built by **Team Devs-Assemble** for the haX.baby hackathon.

---

<p align="center">Made with love · Best at bedtime · No scary stuff 🌙</p>
