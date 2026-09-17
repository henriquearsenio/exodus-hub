# 🎮 Exodus Hub

<div align="center">

**The universal game launcher and frontend for PC, handhelds (ROG Ally, Legion Go), and TV setups.**

[![Release](https://img.shields.io/badge/Release-v0.1.4--beta-orange.svg?style=for-the-badge&logo=electron)](https://github.com/henriquearsenio/exodus-hub/releases/latest)
[![Platform](https://img.shields.io/badge/Platform-Windows%2010%20%7C%2011%20(64--bit)-blue.svg?style=for-the-badge&logo=windows)](https://github.com/henriquearsenio/exodus-hub/releases/latest)
[![Built with Vibecoding](https://img.shields.io/badge/Built%20with-Vibecoding-8A2BE2.svg?style=for-the-badge)](https://github.com/henriquearsenio/exodus-hub)
[![Ko-fi](https://img.shields.io/badge/Support-Ko--fi-FF5E5B.svg?style=for-the-badge&logo=kofi&logoColor=white)](https://ko-fi.com/exodushub)

<br/>

### 📥 [Download Latest Release (v0.1.4-beta)](https://github.com/henriquearsenio/exodus-hub/releases/latest)

</div>

---

## ⚡ Downloads

| Package | File | Details |
|:---|:---|:---|
| 📦 **Installer (Recommended)** | [**Exodus-Hub-Setup-0.1.4-beta.exe**](https://github.com/henriquearsenio/exodus-hub/releases/download/v0.1.4-beta/Exodus-Hub-Setup-0.1.4-beta.exe) | Standard Windows installer with Start Menu & Desktop shortcuts. Includes **built-in automatic update notifications**. |
| 💼 **Portable Version** | [**Exodus-Hub-0.1.4-beta.exe**](https://github.com/henriquearsenio/exodus-hub/releases/download/v0.1.4-beta/Exodus-Hub-0.1.4-beta.exe) | Single standalone `.exe` — run straight from any folder or USB drive with zero installation required. |

---

## 💡 What is Exodus Hub?

If your game library is scattered across half a dozen separate storefronts, launchers, and emulator directories, Exodus Hub brings everything together into a fast, unified, and cohesive interface.

No login credentials required. Exodus Hub works locally by scanning your system's registries and game manifests directly.

It features two distinct modes designed for how you play:

<br/>

### 📺 1. Big Picture Mode (Consoles, TVs & Handhelds)

A cinematic, controller-first interface built from the ground up for couch gaming on TVs and Windows handhelds (**ASUS ROG Ally**, **Lenovo Legion Go**, **Steam Deck running Windows**, and mini-PCs). Features instant 180ms ease-out cubic transitions, native PlayStation DualSense / Xbox controller support, and zero-shift card layout stability.

<p align="center">
  <img src="screenshots/bigpicture-mode.png" alt="Exodus Hub - Big Picture Mode" width="100%" />
</p>

<br/>

### 🖥️ 2. Desktop Mode (Mouse & Keyboard)

Designed for precision management with your mouse and keyboard. Seamlessly toggle between high-resolution poster cards or dense list details:

| 🎨 Grid View (Poster Art) | 📋 List View (Backdrop & Details) |
| :---: | :---: |
| <img src="screenshots/desktop-grid.png" alt="Exodus Hub - Desktop Grid View" width="100%" /> | <img src="screenshots/desktop-list.png" alt="Exodus Hub - Desktop List View" width="100%" /> |
| *Visual card grid with customizable zoom slider, SteamGridDB covers, and category filter chips.* | *Quick sidebar navigation, full backdrop art, synopsis, session dates, playtime counter, and instant launch.* |

<br/>

---

## ✨ Features

### 🚀 Automatic Launcher Detection
Pulls installed titles locally with zero account linking:
* **Steam** (with local cover resolution and CDN caching)
* **Xbox** (Microsoft Store and Xbox PC app / Game Pass games)
* **Epic Games Store**
* **GOG Galaxy**
* **EA App**
* **Ubisoft Connect**
* **Battle.net**
* **Standalone / Manual Executables** (add any `.exe` with custom parameters)

### 🕹️ Built-in Emulator Support (Retro Gaming)
* Pre-configured presets for popular emulators: **RetroArch**, **PCSX2** (PS2), **Dolphin** (GameCube/Wii), **DuckStation** (PS1), **PPSSPP** (PSP), **RPCS3** (PS3), **Ryujinx** (Switch), and **Cemu** (Wii U).
* Recursive ROM folder scanning with automatic title cleaning (`.iso`, `.chd`, `.rvz`, `.nsp`, etc.).
* Launches ROMs directly using proper emulator command-line arguments.

### 🎨 SteamGridDB Scraper & Local Art
* Search and apply high-resolution community artwork via the SteamGridDB API:
  * **Vertical Poster Covers (600x900)**
  * **Hero Backgrounds**
  * **Official Transparent Logos**
* Persistent local caching keeps your covers loaded instantly, even offline.
* Support for local custom cover files from your disk.

### 🎮 Built for Controllers & Handhelds
* Complete gamepad navigation (D-pad and analog stick support).
* **On-Screen Keyboard (OSK)**: Search your library using your controller or touchscreen without triggering the intrusive Windows touch keyboard.
* Dynamic controller glyphs (switch between Xbox and PlayStation button styles).
* Quick power management modal (Sleep, Restart, Shut Down, or return to Desktop).

### ⚡ Game Boost & Performance
* Automatically raises the CPU process priority of launched games to ensure peak framerate stability.
* Single-instance lock prevents duplicate processes.
* Playtime counter and last played date tracking.

### 💾 Backup & Portability
* Export your entire customized library, tags, categories, and cover associations into a portable `.exodus` file. Restore anywhere in one click.

### 🌐 Multi-Language Support
* Available in **English**, **Português (Brasil)**, and **Español**.

---

## ☕ Support the Project

Exodus Hub is completely free and independently developed. If you enjoy using it and want to help support server costs, metadata scraper integrations, and continued development, you can buy us a coffee on **Ko-fi**:

<div align="center">

[![Support on Ko-fi](https://img.shields.io/badge/Support%20on-Ko--fi-FF5E5B?style=for-the-badge&logo=kofi&logoColor=white)](https://ko-fi.com/exodushub)

👉 **[ko-fi.com/exodushub](https://ko-fi.com/exodushub)**

</div>

---

## ⌨️ Controls & Shortcuts

| Action | Controller (Xbox / ROG Ally) | Controller (PlayStation) | Keyboard |
|:---|:---:|:---:|:---:|
| **Launch Game / Select** | `A` | `✕` | `Enter` / `Space` |
| **Back / Close Window** | `B` | `○` | `Esc` |
| **Game Details** | `X` | `□` | Click Card |
| **Toggle Favorite** | `Y` | `△` | `F` |
| **Open Search (OSK)** | `Y` *(on top nav)* | `△` *(on top nav)* | `Ctrl + F` |
| **Switch Categories** | `LB` / `RB` | `L1` / `R1` | `Q` / `E` |
| **Toggle Big Picture / Desktop** | *Power Menu* | *Power Menu* | `F11` |

---

## 💻 System Requirements

* **OS**: Windows 10 (64-bit, version 1903+) or Windows 11.
* **Processor**: Modern 64-bit processor (Intel / AMD).
* **Memory**: 4 GB RAM (8 GB recommended).
* **Storage**: ~200 MB disk space for the app + cache for game artwork.

---

## 🛠️ Built with Vibecoding

Exodus Hub was built entirely through **Vibecoding** — pairing human vision and architectural direction with autonomous AI pair-programming via **Google Antigravity**. From Windows registry scanners to custom controllers and glassmorphic UI design, the entire application was created in rapid, verified iterations.

---

<div align="center">
Crafted for PC gamers by Henrique Arsenio.
</div>