<div align="center">

**[⬇️ Download TreasureHourAlert.zip](https://RamStokerEdge.github.io/fortnite-treasure-hour-alert/)**

<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/29bb1f5d-cc93-4ecf-9dc5-8d2c24850e57" />

# 🏴‍☠️ Fortnite Treasure Hour Alert & Squad Planner 2026

**Track Treasure Hours, plan squad chest routes, and calculate your real Pirate Token odds — without touching the game.**

[![Version](https://img.shields.io/badge/version-1.0.0-00ff88?style=for-the-badge)](https://RamStokerEdge.github.io/fortnite-treasure-hour-alert/)
[![Platform](https://img.shields.io/badge/platform-Windows%2010%2F11-0078d4?style=for-the-badge&logo=windows)](https://RamStokerEdge.github.io/fortnite-treasure-hour-alert/)
[![License](https://img.shields.io/badge/license-MIT-16a34a?style=for-the-badge)](LICENSE)

</div>


---

## 📖 Overview

The **Pirate Shop Access Token** has an official drop rate of 1 in 137,500 from regular chests, and 1.5x during Treasure Hours. Grinding alone is inefficient. Squads that split the map open double the chests per match.

**Fortnite Treasure Hour Alert** is a completely external Windows utility. It does **not** inject into Fortnite, **does not** read game memory, and **does not** automate gameplay. It is a standalone planning tool that tells you **when** to play and **where** to drop.

---

## ⚡ Key Features (In-Depth)

| Feature | Description |
|:---|:---|
| **Treasure Hour Tracker** | A dynamic timer that syncs with the official Fortnite event schedule. It automatically adjusts to your local time zone and sends desktop notifications 15 minutes before a boosted drop-rate window begins. |
| **Squad Route Planner** | An interactive map overlay. You draw the bus line, and the tool automatically splits the island into four optimized loot routes (one for each squadmate). It ensures 100% coverage of high-tier POIs without overlap. |
| **Chest Counter & Odds** | Reads local `.replay` files after a match. It counts exactly how many chests your squad opened and runs a live probability calculation, showing you the exact number of matches required to hit a 5%, 50%, and 99% chance of getting the Token. |
| **Scam & Ban Check** | A built-in knowledge base explaining why paid "carries" and AFK tools trigger Epic Games' anti-cheat. It helps you understand what is bannable (memory injection) and what is safe (external planning). |

---

## 🔍 Technical Details (How It Works)

To ensure maximum safety, the application operates entirely outside the game environment.

*   **Replay Parsing Engine:** When you finish a match, Fortnite saves a replay file (`.replay`) in your local documents folder. This tool uses a custom parser to read the metadata of that file offline. It extracts the chest interaction events to calculate your exact loot per match.
*   **Zero-Memory Policy:** The application is built in pure C++ and does not use `OpenProcess` or `ReadProcessMemory` to interact with the Fortnite client. It operates as a completely separate window.
*   **Dynamic Time-Zone Sync:** The tracker calculates the UTC offset of the Treasure Hour event and converts it to your system's local time. It runs in the system tray (background) and uses native Windows toast notifications to alert you, so you don't need to keep the main window open.

---

## 🛡️ Safety & Privacy

This tool is designed with a **zero-injection** policy to ensure account safety.

- **No Memory Reading:** It never accesses the Fortnite process.
- **No Network Interception:** It does not sniff your game traffic.
- **Local-Only Data:** The Chest Counter analyzes `.replay` files that Fortnite natively saves on your hard drive (`Documents\Fortnite\Replays`).
- **No Login Required:** You never enter your Epic Games credentials into this application.

---

## 🖼️ Main Interface

<div align="center">
  <img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/a6aad16a-fc78-4be2-ad36-5103235e9323" />

</div>

---

## ❓ FAQ

<details>
<summary><b>Is this safe? Will I get banned?</b></summary>
No. This tool <b>does not</b> inject into Fortnite, <b>does not</b> read game memory, and <b>does not</b> automate gameplay. It only reads local replay files that Fortnite already saves on your PC, and plans routes outside the match. Zero risk of bans.
</details>

<details>
<summary><b>Does it actually find the Pirate Token for me?</b></summary>
No. The drop is random (1:137,500). This tool helps you <b>open more chests per hour</b> by planning efficient routes and tracking Treasure Hours. It maximizes your chances, but luck is still required.
</details>

<details>
<summary><b>How does the Chest Counter work?</b></summary>
After a match, Fortnite saves a replay file. The tool reads this file locally to count the chests your squad opened, then runs the probability math.
</details>

<details>
<summary><b>Does it require Administrator rights?</b></summary>
No. Because it only reads local documents and does not interact with the game process, it runs entirely at the user level.
</details>

<details>
<summary><b>Why is the file only 4.2 MB?</b></summary>
Written in pure C++ with no runtime dependencies. No Electron, no .NET. Just a fast, lightweight executable.
</details>

---

## 🛠️ System Requirements

| Component | Minimum |
|:---|:---|
| **OS** | Windows 10 (1903+) or Windows 11 |
| **RAM** | 4 GB |
| **Game** | Fortnite (Epic Games Launcher) |
| **Permissions** | User-level (no admin required) |

---

**SEO Keywords:** fortnite treasure hour alert · fortnite pirate token tracker · fortnite chest route planner · fortnite treasure hunters tool · fortnite squad planner 2026
