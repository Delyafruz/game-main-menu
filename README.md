# 🎮 Game Main Menu System - Technical Assignment

## 📋 Project Overview
Complete implementation of a game's main menu system according to technical specifications.

## ✅ Features Implemented

### **Navigation System**
- 4 Screen Flow: Main Menu → DLC → Settings → Credits
- Black Fade Transitions (0.2s duration)
- Back buttons on all sub-screens
- Centralized MainMenuManager controller

### **DLC Selection Screen**
- "Select Campaign" with 3 DLC options
- Interactive selection highlighting
- "Start Scenario" button activation logic
- Debug output: `Log: Starting Game with [Selected DLC]`

### **Settings Screen**
- 3 Volume Sliders (Master, Music, SFX)
- Fullscreen Toggle with auto-save
- PlayerPrefs persistence
- Real-time Debug.Log feedback

### **Credits Screen**
- Auto-scrolling text
- Scrollable view area
- Professional black fade transitions

## 🛠️ Technical Details
- **Engine:** Unity 2022.3+
- **Language:** C#
- **Architecture:** Event-driven, State-based
- **UI:** Canvas Groups, Fade animations
- **Persistence:** PlayerPrefs

## 🚀 How to Run
1. Clone repository: `git clone https://github.com/Delyafruz/game-main-menu.git`
2. Open in Unity 2022.3+
3. Load scene: `Assets/Scenes/MainMenuScene.unity`
4. Press Play
