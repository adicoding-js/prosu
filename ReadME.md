![Hackatime Badge](https://hackatime-badge.hackclub.com/U0A1XMKQU6S/prosu)
# Prosu! ❤️‍🔥🔥

A browser-based osu!-style rhythm game built in vanilla HTML/CSS/JS. No frameworks, no build tools, just download and play.

---

## How to Run

- Clone the repo:
```
git clone https://github.com/adicoding-js/prosu.git
```
- Double click `index.html` and just play it there!.

---

### Or you can just play it here → [prosuu.netlify.app](https://prosuu.netlify.app/) (updates every commit)

---

## How to Play

Click the circles when the approach ring lines up with the circle. That's literally it. 😭
*However*
For sliders — click and **hold** until the ball reaches the end. Let go early and you get a 50.
For spinners — spin your mouse in circles as fast as you can before the timer runs out.

---

## What's in it so far

- Custom crosshair cursor that follows your mouse
- Hit circles with approach ring animation and combo numbering
- Timing windows — 300 / 100 / 50 / Miss based on how close you are to the beat
- Sliders with hold detection, bounce/repeat logic, and ball progress animation
- Spinners with rotation tracking and bonus score for extra spins
- Score popups that float up and fade out
- Live accuracy percentage and combo counter
- Miss detection with red flash animation

## Maps

- **prosu pilot!** — 100 bpm, the starter map, circles + sliders + a spinner at the end
- **stream machine** — 160 bpm, dense streams and sliders
- **jump king** — 140 bpm, wide jumps and big movement
- **slider test** *(debug map)* — 100 bpm, sliders only, good for practice

## Features

- 4 hardcoded beatmaps
- 3 difficulty settings (Easy / Normal / Hard) — changes circle size and timing windows
- Main menu with animated orbit buttons and background video
- Song select screen with per-map object breakdown (circles / sliders / spinners)
- Results screen with grade, accuracy, max combo, and hit counts
- Local leaderboard (top 10 per map per difficulty, stored in localStorage)
- Profile page with lifetime stats and best grades per map
- 4 skins (Default, Pixel, Minimal, Warm) with localStorage persistence
- Pause menu (Esc) with resume, restart, song select, settings, and exit
- Custom audio upload (plays in background, not synced to map)
- Combo sounds and a win sound for good grades
- Volume control in settings

## Known Issues

- Beatmaps aren't synced to audio by default (map1 has no audio file)
- No online leaderboard — scores only saved locally per browser

## Plans

- Synced audio for all maps
- HP/drain bar
- More maps
- Maybe custom beatmap support

---

## Made with 💖 by [@adicoding-js](https://github.com/adicoding-js/)
### Forever a Hack-Clubber 💖
### Made for [Jackpot](https://jackpot.hackclub.com/) with sooooooooooooooooooooo much love and hard-work😭💖