# 🌈 Chromatic Echo

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Tech: Vanilla JS](https://img.shields.io/badge/Tech-Vanilla%20JS-f7df1e)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Tech: Tailwind](https://img.shields.io/badge/Tailwind-CSS-06b6d4)](https://tailwindcss.com/)
[![Forged with Game Forge](https://img.shields.io/badge/Forged%20with-Game%20Forge-blueviolet?style=flat-square)](https://github.com/your-repo-link)

**Chromatic Echo** is an experimental bullet hell survival game where color is your only sanctuary and movement is your only weapon. Navigate a minimalist void where your speed dictates your existence.

---

## 🌌 The Concept

In the void of *Chromatic Echo*, you leave a persistent trail that cycles through the RGB spectrum. Unlike traditional bullet hells where every collision is fatal, here, the danger is conditional. Projectiles are only lethal if their color matches the current hue of your trail. 

To survive, you must master the **Tactical Color Dance**: strategically accelerating to shift your hue or slowing down to linger in a safe spectrum, phasing through dense patterns of light that would otherwise be your end.

---

## 🎮 How to Play

1.  **Navigate:** Use `WASD` or `Arrow Keys` to move your character through the void.
2.  **Shift Hue:** Your movement speed directly controls the color of your trail.
    *   **Stand Still/Move Slowly:** Your trail lingers on a specific color.
    *   **Sprint:** Your trail cycles rapidly through the RGB spectrum.
3.  **Phase:** Watch the incoming projectiles. If a red bullet is approaching, ensure your trail is *not* red to pass through safely.
4.  **Survive:** The longer you last, the more complex the chromatic patterns become.

---

## ✨ Key Features

*   **Velocity-Based Chromatics:** A unique core mechanic where movement speed dictates your "color phase."
*   **Minimalist Aesthetics:** Clean, high-contrast visuals designed to keep the focus on color and movement.
*   **Dynamic RGB Trails:** A beautiful, persistent trail system that paints the void as you play.
*   **Procedural Bullet Patterns:** Experience escalating difficulty with patterns designed to test your rhythmic timing.
*   **Zero Loading Times:** Built with lightweight web technologies for instant action.

---

## 🛠️ Tech Stack

*   **Engine:** [HTML5 Canvas API](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API) for high-performance 2D rendering.
*   **Logic:** Vanilla JavaScript (ES6+).
*   **Styling:** [Tailwind CSS](https://tailwindcss.com/) for the minimalist UI overlay.
*   **Architecture:** Functional reactive programming patterns for projectile management.

---

## 🚀 How to Run

No installation or build process is required. Since this project is built with vanilla web technologies, you can run it directly in any modern browser.

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/chromatic-echo.git
    ```
2.  **Open the game:**
    Navigate to the project folder and open `index.html` in your favorite browser.

---

## 🛠️ Development

If you'd like to tweak the game physics or color cycle speeds:
*   Open `js/game.js` (or the respective logic file).
*   Adjust the `COLOR_SHIFT_FACTOR` or `BULLET_SPEED` constants.

---

## 💜 Credits

*   **Concept & Design:** Experimental Bullet Hell exploration.
*   **Tools:** Forged with **Game Forge**.

---

*“In the echo of color, speed is your only shield.”*