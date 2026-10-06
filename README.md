# 🎮 Dual Arcade: 2-Player Shared Keyboard Games

A premier suite of **12 handcrafted, 2-player local multiplayer and cooperative arcade games** playable together on **one shared keyboard in the browser**.

Built entirely with **Vanilla HTML5 Canvas, CSS, and the Web Audio API** — zero external frameworks, zero CDNs, and zero dependencies. Simply open `index.html` in any modern web browser to play!

---

## 🕹️ Master Arcade Portal
Open [`index.html`](index.html) to browse, filter, and launch all 12 games in an integrated fullscreen arcade modal or standalone browser tabs.

---

## 🎲 The Games Directory

| # | Game | Category | Description | Folder |
|---|---|---|---|---|
| 1 | **🌀 Dual Maze: Co-Op Escape** | Co-Op Maze | Both players steer ONE single shared character! Player 1 moves horizontally (A/D), Player 2 moves vertically (Up/Down). Dodge traps, find keys, and escape together. | [`maze_escape/`](maze_escape/index.html) |
| 2 | **📖 Our Storybook: Co-Op Tale** | Co-Op Story | Take turns picking cards to weave an illustrated 10-chapter tale together with soothing harp music. | [`story_builder/`](story_builder/index.html) |
| 3 | **🚢 Battleship: Naval Clash** | Strategy | Classic naval warfare. Secretly deploy ships, pass the device, and fire torpedoes with radar sonar and explosive hits. | [`battleship/`](battleship/index.html) |
| 4 | **🎈 Balloon Pop Party** | Action | Pop rising balloons in a 60-second frenzy! Collect Stars (2X score), Lightning (hyper speed), and Bombs. | [`balloon_pop/`](balloon_pop/index.html) |
| 5 | **🏗️ Tower Clash: Block Stacking** | Timing / Puzzle | Take turns dropping sliding blocks. Overhangs are sliced off as the tower narrows. 3 lives each. | [`block_stack/`](block_stack/index.html) |
| 6 | **🐥 Farm Pen: Block & Save** | Puzzle | Cozy Sokoban block-pusher puzzle. Push crates to build pens and guide wandering yellow chicks to safety. | [`farm_pen/`](farm_pen/index.html) |
| 7 | **🐑 The Great Fence Duel** | Strategy | Quoridor-inspired turn-based board game. Advance your sheep or place fence walls to block your opponent. | [`fence_duel/`](fence_duel/index.html) |
| 8 | **🐶 Pet Shield: Bee Defense** | Physics Defense | Control a floating wooden shield to deflect bouncing physics bees away from your puppy toward the enemy. | [`pet_shield/`](pet_shield/index.html) |
| 9 | **⚡ Laser Mirror Duel** | Strategy | Run across the shared grid to rotate 45° diagonal mirrors and direct the pulsing laser beam into enemy crystals. | [`laser/`](laser/index.html) |
| 10 | **🐼 Sumo Bouncy Battle** | Physics Sumo | Sumo wrestling on a slippery ice ring surrounded by water. Dash, tackle, and push each other off the edge. | [`sumo/`](sumo/index.html) |
| 11 | **🎨 Color Frenzy Arena** | Sports / Arcade | Fast-paced pinball soccer battle. Kick colored balls off bumpers, mix primary into secondary colors, and score! | [`color_frenzy/`](color_frenzy/index.html) |
| 12 | **🥣 Color Bowl Match** | Arcade Race | Vibrant competitive ball race. Dash across the arena to gather target colored spheres and dunk them into your goal. | [`color_bowl/`](color_bowl/index.html) |

---

## ⌨️ Universal Controls Layout

All games are designed for two players sitting side-by-side on the same keyboard:

* **Player 1 (Left Side — Blue):**
  * Movement: <kbd>W</kbd> <kbd>A</kbd> <kbd>S</kbd> <kbd>D</kbd>
  * Action: <kbd>Space</kbd> / <kbd>Q</kbd> (or <kbd>A</kbd>/<kbd>D</kbd> for horizontal-only games)
* **Player 2 (Right Side — Red):**
  * Movement: <kbd>▲</kbd> <kbd>◀</kbd> <kbd>▼</kbd> <kbd>▶</kbd> (Arrow Keys)
  * Action: <kbd>Enter</kbd> / <kbd>L</kbd> (or <kbd>▲</kbd>/<kbd>▼</kbd> for vertical-only games)

---

## 🛠️ Technology Stack
* **HTML5 Canvas 2D:** Butter-smooth 60 FPS graphics, custom particle systems, lighting effects, and animations.
* **Web Audio API:** Procedurally synthesized arcade sound effects, chimes, explosions, and ambient music without any audio asset downloads.
* **Modern CSS:** Glassmorphism UI, glowing neon accents, and responsive layout.
* **Zero Dependencies:** Pure vanilla JavaScript; no NPM packages, bundlers, or CDNs required.
