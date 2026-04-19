# 🌙 3AM Thoughts — Enter The Void

> **VishwaNova 2026 · National Level Weboreel AI Hackathon**

Your brain at 3AM is something else. This weboreel is a deeply atmospheric, pitch-black experience that generates introspective, weird, and existential thoughts — the kind that only hit when you're staring at the ceiling at 3 in the morning.

## ✨ Features

- 🖤 **Cinematic Hook Sequence**: Opens with 2 full seconds of pure black silence. Then thoughts fade in and out one at a time with slow opacity transitions — "Do fish get thirsty?" — creating genuine tension before the CTA appears.
- 🌟 **Canvas Starfield**: 200 procedurally twinkling stars rendered on an HTML5 Canvas with individual oscillation speeds, creating a living night sky backdrop across all 4 pages.
- ⏰ **Live 3AM Clock**: A ticking digital clock (`Space Mono`) counts seconds from 3:00:00 AM. Each tick fires a subtle sine-wave audio pulse via the Web Audio API.
- ✨ **Per-Character Reveal**: Generated thoughts animate letter-by-letter using individual `opacity` + `filter: blur()` transitions, creating a dreamy materialization effect.
- 💫 **Sparkle Particle System**: Clicking a reaction pill spawns 12 directional sparkle particles that burst outward using the `Element.animate()` API with randomized angles and distances.
- 🎵 **Lo-Fi Ambient Engine**: Toggled via the moon icon — generates a warm sine-wave pad chord (C3, E3, G3, C4) layered with bandpass-filtered white noise to simulate vinyl hiss. Entirely procedural, zero external files.
- 🌊 **Drifting Community Wall**: Community thoughts float across the screen as translucent bubbles at varying speeds and vertical positions using CSS `translateX` keyframe animations. Filterable by category (Existential, Weird Facts, Life Realizations, Hypotheticals).
- 📓 **localStorage Journal**: Every thought you react to is automatically saved with its timestamp. The journal page renders them as entries in a CSS-drawn dark notebook with a margin line, downloadable as a `.txt` file.

## 🧠 Thought Database

32 hand-written thoughts across 4 categories:
- **Existential** — "One day someone thought about you for the last time and you had no idea."
- **Weird Facts** — "Pineapples take two years to grow. TWO YEARS. For one pineapple."
- **Life Realizations** — "Nobody is coming to save you, and that's actually the most freeing realization."
- **Hypotheticals** — "What if déjà vu is just a save point from a previous playthrough?"

## 🛠️ Tech Stack

- **HTML5** — Canvas, multi-page SPA
- **Vanilla CSS3** — Blur transitions, infinite drift keyframes, dark notebook drawing
- **Vanilla JavaScript** — Per-character animation timing, particle physics, category filtering, localStorage persistence
- **Web Audio API** — Lo-fi ambient pad synthesis, tick pulses, sparkle chimes

## 📸 Try It Out

Simply double-click the `index.html` file to open it in any modern browser. No servers, build steps, or dependencies required.

---

*Built with ❤️ for VishwaNova 2026*
