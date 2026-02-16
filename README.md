<div align="center">

<img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExbmhtZm5qbXF5eW5qbXF5eW5qbXF5eW5qbXF5eW5qbXF5eW5qbXF5eSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/4lu5FuhtrbaOQgKN57/giphy.gif" width="100%" />

<br/><br/>

# Anime Reel Inspired

### WebGL × Gesture Interaction 

<br/>

<!-- Animated SVG Buttons -->

<a href="https://github.com/1sarthak7/Anime-Reel-ins" target="_blank">
  <img src="https://img.shields.io/badge/View%20Repository-000000?style=for-the-badge&logo=github&logoColor=white" />
</a>

<a href="https://github.com/1sarthak7?tab=repositories" target="_blank">
  <img src="https://img.shields.io/badge/More%20Projects-111111?style=for-the-badge&logo=github&logoColor=cyan" />
</a>

<br/><br/>

<!-- Custom Animated SVG Glow Button -->

<svg width="260" height="60" viewBox="0 0 260 60" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="grad1" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#ff00ff">
        <animate attributeName="stop-color" values="#ff00ff;#00ffff;#ff00ff" dur="4s" repeatCount="indefinite" />
      </stop>
      <stop offset="100%" stop-color="#00ffff">
        <animate attributeName="stop-color" values="#00ffff;#ff00ff;#00ffff" dur="4s" repeatCount="indefinite" />
      </stop>
    </linearGradient>
  </defs>
  <rect x="5" y="5" rx="15" ry="15" width="250" height="50" fill="none" stroke="url(#grad1)" stroke-width="3"/>
  <text x="50%" y="50%" dominant-baseline="middle" text-anchor="middle" fill="url(#grad1)" font-family="Arial" font-size="16" letter-spacing="2">
    INTERACTIVE WEBGL EXPERIENCE
  </text>
</svg>

</div>

---

# Project Overview

Anime Reel Ins is a cinematic browser-based visual engine that combines real-time gesture interaction, particle simulations, and post-processing effects to create an immersive anime-inspired digital experience.

The project blends:

* Three.js rendering pipeline
* WebGL particle systems
* MediaPipe gesture tracking
* Post-processing effects (Bloom, energy glow)
* Cinematic motion logic

This is not a static webpage.
It is a real-time visual system running entirely in the browser.

---

# Core Features

## Real-Time Interaction

* Hand gesture recognition via webcam
* Dynamic state transitions
* Live particle morphing

## Cinematic Rendering

* 20K+ particle field
* Additive blending energy effects
* Unreal Bloom post-processing
* Grain overlay for texture depth
* Camera shake under high-intensity states

## Modular Architecture

* ES Module based structure
* Clean separation of rendering, input, and animation logic
* Responsive viewport handling

---

# Technology Stack

* Three.js
* WebGL
* MediaPipe Hands
* JavaScript ES Modules
* UnrealBloomPass

---

# Running the Project

Because the project uses ES Modules and webcam permissions, it must run on a local server.

### Option 1 — VS Code

1. Open the folder in VS Code
2. Install Live Server
3. Right-click index.html
4. Open with Live Server

### Option 2 — Python

```
python -m http.server 8000
```

Then open:

```
http://localhost:8000
```

---

# Performance Considerations

* Optimized for modern GPUs
* Heavy bloom may impact low-end systems
* Best experienced in Chromium-based browsers

---

# Visual Direction

The system is designed around:

* Dark anime aesthetics
* Volatile energy motion
* High-contrast glow effects
* Subtle instability through motion distortion

Every animation state modifies:

* Particle target arrays
* Color gradients
* Bloom intensity
* Rotational axes
* Camera vibration amplitude

---

# Future Improvements

* Custom GLSL shader materials
* Depth-based volumetric lighting
* Audio-reactive energy pulses
* Multi-user shared domain system
* Gesture combination chaining

---

# Author

Designed and Developed by

Sarthak Bhopale

GitHub:
[https://github.com/1sarthak7](https://github.com/1sarthak7)

---

If this project inspired you, consider starring the repository and exploring more experimental WebGL systems.
