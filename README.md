# ⏱️ Kinetic Workout Timer

A minimal, high-performance interval workout timer built with the **Kinetic Glass** design system — dark OLED, state-driven colors, and zero-friction UX for athletes.

## Features

- 🔥 **Work / 💧 Rest interval cycling** with auto state switching
- 🎨 **Dynamic theming** — orange ring for work, cyan for rest
- 👆 **Double-tap the dial** to pause/resume (subtle, no visible button)
- 🔧 **Interval Builder** — configure warmup, work, rest, rounds, cooldown
- 📋 **Protocol presets** — Tabata, EMOM, HIIT Pyramid, Custom
- 📊 **Consistency dashboard** with weekly streak tracking
- ⚡ **+5S** and **+1 ROUND** live adjustments during workout

## Design System

**Kinetic Glass** — engineered for elite interval pacing.
- Fonts: Space Grotesk (timers) + Inter (body)
- Colors: `work-active: #FF5722` · `rest-active: #00E5FF` · `prep-state: #FFB300`
- True OLED black backgrounds · Frosted glass cards · Specular edge highlights

## Usage

Single `index.html` file — no build step needed. Open in browser or deploy to Vercel.

## Gestures

| Gesture | Action |
|---------|--------|
| Double-tap the timer dial | Pause / Resume |
| Tap +5S button | Add 5 seconds to current interval |
| Tap +1 ROUND | Add one more round |
| Tap STOP | End session (with confirmation) |
