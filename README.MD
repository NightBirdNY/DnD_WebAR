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
```

## 🛠️ How to Run Locally

Since the application requires camera access and a secure context:

    Clone the repository.

    Open the project in PyCharm Professional or VS Code.

    Use a local server (e.g., PyCharm's built-in server or Live Server extension).

    Navigate to http://localhost:[PORT].

    Point your camera at the target character sheet.

## 📜 Academic Context

This project was developed as a Proof of Concept (PoC) for a graduate-level Augmented Reality course at Tokat Gaziosmanpaşa University. It explores the transition from heavyweight game engines to lightweight web standards in the context of tabletop gaming.
🗺️ Roadmap

    [ ] OCR Integration: Read handwritten values from the physical sheet using Tesseract.js.

    [ ] 3D Dice Roller: Integrated physics-based dice rolling on the sheet's surface.

    [ ] Multi-Target Support: Tracking multiple sheets for different party members.


Developer: Taha Sencer Şenel