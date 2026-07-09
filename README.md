# Volumetric CSS Art Showcase

This repository contains an extraordinary, competition-level CSS Art showcase featuring five famous animated characters, built using **100% pure HTML5 and CSS3** (No SVGs, Canvas, JavaScript, external images, or icon libraries).

## 🚀 Deployed Demo
👉 **[View Live Demo / GitHub Pages Link](https://rishithareddychalla.github.io/CartoonArt/)**

---

## 🎨 Characters Showcase

### 1. Pikachu (Pokemon)
*   **Aesthetics:** Multi-layered radial/linear skin highlights, inset shadows for cheeks.
*   **Interactions:** Hover to trigger facial expression changes, ear twitches, cheek glows, and spark emissions. Click/hold to trigger an electrical discharge, causing the entire screen to shake and flash yellow.

### 2. GitHub Octocat
*   **Aesthetics:** 5 independently moving and rotated tentacles, volumetric head, whiskers.
*   **Interactions:** Hover to make her smile, scale her eyes, and wiggle her tentacles.

### 3. Super Mario
*   **Aesthetics:** Red cap with emblem, large volumetric nose, and a detailed 3D mustache.
*   **Interactions:** Hover to trigger a waving hand animation and cap twitch.

### 4. Baby Groot (Guardians of the Galaxy)
*   **Aesthetics:** Sprouted bark textures, wood grain markings, green leaves, and vine limbs.
*   **Interactions:** Hover to sway branches and animate wood grain depths.

### 5. Toothless (Night Fury)
*   **Aesthetics:** Sleek jet-black skin, glowing green cat eyes with vertical slit pupils, wings, and his iconic prosthetic red tail fin.
*   **Interactions:** Hover to narrow his pupils, flap his wings, and wiggle his tail fin.

---

## 🛠️ Tech Stack & Advanced CSS Techniques
*   **Volumetric 3D Rendering:** `radial-gradient` and `linear-gradient` layered overlaying to emulate light reflection, ambient occlusion, and fake depth.
*   **Zero JS State Switching:** Tab/character switching and cinematic background shifts are handled entirely via HTML `<input type="radio">` toggles and CSS sibling/ancestor selectors (`~`).
*   **Organic Vector Art:** Curves, borders, and joint segments are crafted using custom `border-radius` mapping and `clip-path` polygon cuts.
*   **Parallax Environment:** Twisted starry background structures, independent floating particle generators, and moving cloud animations.
*   **Accessibility:** Respects `@media (prefers-reduced-motion: reduce)` to automatically pause all animations for users with motion sensitivities.

---

## 📦 How to Run Locally

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/rishithareddychalla/CartoonArt.git
    cd CartoonArt
    ```
2.  **Open index.html directly:**
    Simply double-click `index.html` to open it in your browser.
3.  **Serve using a local server (Optional):**
    ```bash
    npx http-server -p 8080
    ```
    Go to `http://localhost:8080` in your web browser.

---

*100% Private, Lightweight, and Responsive. Built for Hackathon Excellence.*
