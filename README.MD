# DnD WebAR Assistant 🎲✨

An open-source, web-based Augmented Reality (AR) assistant designed for Tabletop Role-Playing Games (TTRPG) like Dungeons & Dragons. This project bridges the gap between physical character sheets and digital stat management using native web technologies.

## 🚀 Overview

Traditionally, AR applications require heavy engine runtimes (like Unity) or dedicated mobile app installations. **DnD WebAR Assistant** disrupts this by utilizing **Native WebAR**. It runs directly in the mobile browser, allowing players to scan their physical character sheets to reveal and interact with digital overlays such as health points (HP), spell slots, and status effects.

## ✨ Key Features

- **No Installation Required:** Works instantly via any modern mobile browser (Chrome, Safari, Firefox).
- **Marker-Based Tracking:** Uses the physical character sheet as an AR marker to anchor digital UI elements.
- **Real-Time Interaction:** Interactive on-screen buttons to manage character stats (e.g., HP increment/decrement).
- **Lightweight & High Performance:** Built with native web standards to ensure low battery consumption and fast loading times on mobile devices.

## 🛠️ Tech Stack

- **[A-Frame](https://aframe.io/):** Web framework for building 3D/AR experiences.
- **[MindAR.js](https://github.com/hiukim/mind-ar-js):** Lightweight image tracking and AR engine.
- **HTML5 / CSS3 / JavaScript:** Core web technologies.
- **PyCharm:** Used as the primary development environment on Ubuntu.

## 📦 Project Structure

```text
.
├── index.html          # Main application and logic
├── targets.mind        # Compiled AR marker (Character Sheet fingerprints)
└── assets/             # 3D models, images, and visual assets