# Prapanch "Punch" Kokkalemada | Portfolio

Welcome to the source code for my professional portfolio. This repository houses my digital resume and interactive strategy case studies (including deep-dives into Supply Chain, M&A, and Corporate Strategy). 

**The Objective:** To build a dynamic, data-driven "Executive Dashboard" that doesn't just list skills, but actively models them. This repository solves the communication gap between technical teams and business stakeholders by providing programmatic visual models of Supply Chain trade-offs (EOQ, stochastic lead times) and Go-To-Market (GTM) strategies—all without the sluggish load times of traditional CMS platforms like WordPress or Squarespace.

🔗 **[View the Live Portfolio Here](https://punch-k.github.io/Prapanch_Punch_Kokkalemada/)**

https://github.com/user-attachments/assets/5a4f7e82-715a-424a-8a66-6cfa922ea0f2

## 🏗️ Architecture & Tech Stack
This project was built to ensure lightning-fast load times and complete control over the UI/UX.

* **Core:** HTML5, CSS3, Vanilla JavaScript
* **Data Visualization:** Chart.js
* **Methodology:** Modular file architecture (separated concerns for markup, styles, and logic).

## ✨ Key Technical Features
* **Interactive Data Visualization:** Programmatic rendering of complex case study data using Chart.js.
* **Custom CSS Physics:** 3D tilt-card hover states calculated via JavaScript mouse-tracking, and pure CSS ambient parallax backgrounds.
* **Performance Optimized:** Utilizes `IntersectionObserver` APIs to only trigger animations when elements scroll into the viewport, saving CPU/GPU load.
* **Fully Responsive:** Fluid typography and layout scaling using CSS `clamp()` and modern Flexbox/Grid architectures.

### 🚚 The Operations & Logistics Simulator (GTM Sim)
While static dashboards are great for historical data, supply chain operations are inherently dynamic. To demonstrate this, I built a custom, interactive logistics engine directly into the portfolio.

**The Business Application:**
The simulator gamifies last-mile delivery and route optimization. It forces the user to navigate trade-offs in real-time:
* **Route & Time Optimization:** Models the pressure of SLA (Service Level Agreement) fulfillment.
* **Yield Degradation:** The "Bonus" metric dynamically decays over time, representing the financial cost of delayed deliveries and holding costs.
* **Stochastic Variables:** Unpredictable obstacles model supply chain disruptions, requiring the user to adjust their execution strategy on the fly to avoid total route failure.

**Technical Implementation:**
* Built entirely in **Vanilla JavaScript** and **HTML5 `<canvas>`** (Zero external game engines used).
* Implements a custom 2D physics engine handling gravity, velocity, and precise hitbox collision detection.
* Uses `requestAnimationFrame` for a smooth, hardware-accelerated 60fps render loop without bottlenecking the main browser thread.

## 📬 Connect
I am always open to discussing supply chain strategy, operational execution, and data-driven market entry. Connect with me through the contact links on the live portfolio!


![Build Status](https://img.shields.io/github/actions/workflow/status/Punch-k/Portfolio/pages/pages-build-deployment?style=flat-square&label=Deploy%20Status&color=4ade80)
![Lighthouse Score](https://img.shields.io/badge/Lighthouse-100%2F100-success?style=flat-square)
![Dependencies](https://img.shields.io/badge/Dependencies-Zero-blue?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-gray?style=flat-square)
