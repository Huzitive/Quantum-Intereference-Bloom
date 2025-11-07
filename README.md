# Quantum Interference Bloom — physics × art

A generative visualization blending **quantum interference** with **aesthetic design**.  
Two coherent light sources create an evolving interference pattern, rendered per pixel on an HTML5 canvas.  
By translating intensity fringes into vivid color palettes, it turns a fundamental wave-physics phenomenon into a living artwork.

---

## 🌀 Description

**Quantum Interference Bloom** simulates a **double-slit experiment** where two point sources emit coherent waves that interfere on a virtual screen.  
Each pixel’s brightness represents the local time-averaged intensity derived from the superposition of two oscillating fields:

\[
I(\mathbf r)\propto 1+\gamma\cos[k(r_1-r_2)+\phi]
\]

Here:
- \( \lambda \) controls wavelength,
- \( d \) sets slit separation,
- \( \phi \) defines phase difference,
- \( \gamma \) adjusts coherence between slits.

By mapping this intensity to RGB gradients, the interference fringes become colorful “blooms” that oscillate over time.  
Adjusting parameters reveals how coherence and phase sculpt the interference pattern, merging **physics, computation, and art**.

---

## ✦ Features

- Real-time double-slit interference with partial coherence  
- Adjustable physical parameters: λ, d, φ, γ, exposure, frequency  
- Palette options: **Spectral RGB**, **Neon Bloom**, **Duotone**, **Monochrome**  
- Interactive canvas: drag to move sources, double-click to recenter  
- PNG export of any generated frame  
- Fully client-side, no dependencies beyond MathJax  

---

## ⚙️ Tech Stack

- **HTML5 Canvas** — pixel-based rendering  
- **Vanilla JavaScript** — simulation logic and interactivity  
- **MathJax** — LaTeX-style equations  
- **CSS Grid / Glassmorphism** — Swiss-style UI design  

---

## 🧠 Concept

A visualization of **superposition** and **coherence**, two pillars of quantum and wave physics.  
The work bridges technical simulation and generative art, emphasizing how mathematical beauty can manifest visually when the parameters of nature become creative variables.

---

## 🧩 Author

**Huzaifa Ahmed Khan**  
> “Physics and design share one truth — everything is pattern.”
