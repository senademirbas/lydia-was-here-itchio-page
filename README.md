# itch.io Custom Page Design – Lydia Was Here

This repository contains the **custom HTML & CSS page design** created for  
**Studio Rainy Day’s game _Lydia Was Here_** on **itch.io**.

The design is built **fully within itch.io’s custom CSS limitations**, without external JavaScript or unsupported layout systems.

---

## 🎮 Project Overview

- **Game:** Lydia Was Here  
- **Team:** Studio Rainy Day  
- **Platform:** itch.io  
- **Purpose:** Custom game page layout using HTML & CSS  
- **Constraints:** itch.io Custom CSS rules  

This project focuses on creating a **visually narrative-driven game page** that reflects the psychological horror tone of the game while maintaining responsiveness and platform compatibility.

---

## 📂 File Structure
*├── index.html*  Page structure used for local testing & layout development

*├── style.css*  Custom CSS adapted for itch.io


> **Note:**  
> On itch.io, the HTML structure is partially injected by the platform.  
> The `index.html` file is included **for local testing, documentation, and version control purposes only**.

---

## 🧩 Design Principles

- Absolute positioning aligned to a fixed background image
- Scalable layout using `vw`-based typography
- Mobile compatibility via controlled zoom and centering
- No JavaScript (itch.io limitation)
- No external layout frameworks
- Optimized specifically for itch.io’s `.inner_column` structure

---

## 🎨 Features

- Fully hand-drawn visual presentation
- Trailer and screenshot showcase
- Story-driven text placement
- Thematic typography using Google Fonts (**Outfit**)
- Responsive scaling for both desktop and mobile

---

## 📱 Responsiveness Strategy

- **Desktop:**  
  Scaled layout using `transform: scale()` combined with `vw`-based font sizing

- **Mobile:**  
  Fixed minimum width with horizontal centering to preserve composition integrity

- Media queries are used to ensure layout stability and readability across devices

---

## 🚀 How It Works on itch.io

1. HTML elements are placed inside the itch.io page description area  
2. CSS is applied through itch.io’s **Custom CSS** settings  
3. Layout adapts to itch.io’s container rules (`.inner_column`)  
4. No scripts or unsupported assets are used  

---

## 🧠 Technical Notes

- Uses absolute positioning for pixel-accurate storytelling layout
- All images are hosted via the itch.io CDN
- Designed to remain stable against minor itch.io layout updates
- Global CSS overrides are avoided except where strictly necessary

---

## © Copyright & Asset Usage Notice

All visual assets, illustrations, and images used in this project are **original works created by the artists of Studio Rainy Day**.

**all rights to the visual materials belong to their respective creators (the illustrators and artists involved)**.

🚫 **Unauthorized use, reproduction, redistribution, or modification of any visual assets is strictly prohibited** without explicit permission from the creators.

Any use of the visual assets outside this repository, including both **commercial and non-commercial use**, requires **prior written permission** from the creators.

This repository is shared **for portfolio, educational, and documentation purposes only**.

---


