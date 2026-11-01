# BATLIFE
BatLife is a lightweight, single-file web application designed to protect your device's lithium-ion battery health by alerting you when to unplug your charger (at 80%) and when to plug it back in (at 20%).

## ✨ Features

* **Real-Time Battery Monitoring:** Uses the native browser Web Battery Status API (`navigator.getBattery`) to track charge levels and charging states.
* **Interactive Simulation Mode:** Fully testable on browsers and operating systems that restrict hardware battery APIs.
* **Smart Thresholds:** Enforces the optimal 20%–80% battery longevity rule with customizable high/low sliders.
* **Multi-Layered Alert System:** 
  * Custom synthesized audio alerts using the Web Audio API (no external audio files required).
  * HTML5 Desktop push notifications.
  * Visual banner alerts and dynamic battery gauge.
* **Activity Session Log:** Tracks alert events with exact timestamps.

* ## 🚀 Getting Started Locally

1. Clone or download this repository.
2. Open the folder in your code editor (e.g., [VS Code](https://code.visualstudio.com/)).
3. Run it locally using **VS Code Live Server** or open `index.html` directly in your web browser.

---

## 🌐 Live Demo

You can view the live hosted application via GitHub Pages:  
👉 https://lakshmikrishna-hue.github.io/BATLIFE/

---
## 🙏 Acknowledgments
Built with the assistance of Gemini as an AI collaborator.
