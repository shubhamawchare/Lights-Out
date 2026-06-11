# Lights Out 🔦

**Lights Out** is an intense horror game built with **Unity** and **C#**, designed to immerse players in a dark, suspenseful, and terrifying environment.  
Armed with only a flickering torch, players must explore gloomy areas, solve key-based puzzles, avoid enemies, and survive through increasingly difficult stages.

---

## 👻 About the Game

Lights Out focuses on atmosphere, tension, and exploration.  
Players move through shadow-filled rooms and corridors where visibility is limited, sounds amplify the fear, and danger can appear at any moment.

The game blends horror, puzzle-solving, and stealth-style survival elements.  
Keys are hidden throughout the levels, locked doors block the way forward, and enemies patrol the environment while the player attempts to escape.

---

## ✨ Features

- Dark, atmospheric horror gameplay
- Flickering torch light for suspenseful visuals
- Hidden keys and locked doors
- Card door mechanics with special objectives
- Enemy AI with patrol and chase behavior
- Level progression and unlock system
- Pause menu support
- Main menu and level selection screen
- Save system for unlocked levels
- Pathfinding-based enemy movement
- Horror-themed sound and tension-focused design

---

## 🔦 Gameplay Overview

The player must:

1. Explore dark environments using a weak torch
2. Find hidden keys to unlock doors
3. Solve progression-based room and level challenges
4. Avoid or escape enemies
5. Reach the exit to complete each stage

The torch light flickers randomly, creating unpredictable shadows and increasing the fear factor.

---

## 🎮 Controls

Controls can be customized in Unity’s Input settings, but the gameplay is built around movement and interaction in a top-down style horror experience.

Typical controls:

- **Move**: WASD / Arrow Keys
- **Pause**: Escape
- **Interact / Trigger mechanics**: Through collision-based gameplay

---

## 🧩 Core Mechanics

### Torch / Light System
The torch light flickers over time, sometimes becoming stronger and sometimes dimmer, creating a tense survival atmosphere.

### Keys and Doors
Players collect keys of different types to unlock matching doors.  
If the player reaches a locked door without the required key, the game displays a message telling them which key is needed.

### Card Door System
Some doors require a special card/objective to unlock.  
This adds another puzzle layer to the game.

### Enemy AI
Enemies patrol between points and switch to chasing the player when they come into range.

### Level Progression
The game tracks unlocked stages and saves progress so players can continue from later levels after completing earlier ones.

### Pause/Menu System
Players can pause the game, return to the menu, retry levels, or continue from the last scene.

---

## 🛠️ Built With

- **Unity**
- **C#**
- **Unity 2D**
- **Unity UI**
- **Pathfinding / A* style navigation**
- **Unity Scene Management**
- **JSON-based save system**

---

## 📁 Project Structure

```text
Lights-Out/
│
├── Assets/
│   ├── Scripts/
│   ├── Scenes/
│   ├── Prefabs/
│   ├── Sprites/
│   ├── Audio/
│   └── UI/
│
├── Packages/
├── ProjectSettings/
├── README.md
└── Save files / progress data
