# Conjugation Drill

A single-file web app for drilling Spanish verb conjugations at
conversational speed, based on the "random conjugation switching"
practice method. No dependencies, no backend, no account — all data
stays on your device.

## The drill

You're shown an English prompt like **"They gave it to us"** and race
a live timer to produce the Spanish (*nos lo dieron*). Reveal the
answer, self-mark it, repeat. Under a second is the goal — hesitation
means the form isn't automatic yet.

## Features

- **Live response timer** — amber at 2s, red at 5s
- **Object pronoun stacking** — direct, indirect, and se-lo
  transformations (le/les + lo → se lo)
- **Spaced re-queuing** — missed cards return 2–3 cards later, then
  again ~8 cards later
- **10-verb bank** — core 5 (decir, dar, pedir, necesitar, ver) plus
  traer, llevar, mandar, llamar, ayudar; minimum 2 selected
- **Preterite toggle** — mixes past tense 50/50 when enabled
- **Progress tracking** — day streak, accuracy and response-time
  charts, difficulty-change markers, per-verb weak-spot table
- **Fixed benchmark cohort** — the core 5 verbs in present tense are
  charted separately, so the trend line stays comparable even as you
  add verbs and tenses

## Usage

Open `index.html` in any browser. On Android, open the
hosted page in Chrome and use **⋮ → Add to Home screen** for an
app-like install that works offline.

Desktop keys: **Space** = reveal · **1** = got it · **2** = missed.

## Data

History is stored in `localStorage`, aggregated per verb/tense/day.
Clearing site data resets progress. Nothing is transmitted anywhere.
Speed drill for Spanish verb conjugations with object pronouns — single-file web app with response timer, spaced re-queuing of misses, and on-device progress tracking.
