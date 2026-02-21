<div align="center">

<!-- Header Banner -->
<img src="https://img.shields.io/badge/🎲_Pig_Dice_Game-Roll_&_Win!-c7365f?style=for-the-badge&labelColor=753682" alt="Pig Dice Game" width="450"/>

<br/>
<br/>

# 🎲 Pig Dice Game

<p align="center">
  <em>A classic two-player Pig dice game built with vanilla HTML, CSS & JavaScript — featuring glassmorphism UI, smooth animations, and full responsive design</em>
</p>

<br/>

<!-- Badges -->
<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Players-2_Player-c7365f?style=flat-square" alt="Players"/>
  <img src="https://img.shields.io/badge/Target_Score-100_Points-753682?style=flat-square" alt="Score"/>
  <img src="https://img.shields.io/badge/Status-Active-brightgreen?style=flat-square" alt="Status"/>
  <img src="https://img.shields.io/badge/License-MIT-blue?style=flat-square" alt="License"/>
  <img src="https://img.shields.io/badge/Responsive-All_Devices-orange?style=flat-square" alt="Responsive"/>
</p>

<br/>

<!-- Separator -->
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%"/>

</div>

<br/>

## 📋 Table of Contents

<details open>
<summary><b>Click to expand / collapse</b></summary>

<br/>

| #   | Section                                            |
| --- | -------------------------------------------------- |
| 🎯  | [Overview](#-overview)                             |
| 🕹️  | [How to Play](#️-how-to-play)                       |
| ✨  | [Features](#-features)                             |
| 🎨  | [Design](#-design)                                 |
| 🛠️  | [Tech Stack](#️-tech-stack)                         |
| 📁  | [Project Structure](#-project-structure)           |
| ⚙️  | [Game Logic](#️-game-logic)                         |
| 🚀  | [Getting Started](#-getting-started)               |
| 📱  | [Responsive Breakpoints](#-responsive-breakpoints) |
| 🤝  | [Contributing](#-contributing)                     |
| 📄  | [License](#-license)                               |

</details>

<br/>

---

<br/>

## 🎯 Overview

<table>
<tr>
<td>

**Pig Dice Game** is a classic turn-based dice game for two players. Each player takes turns rolling a single die — accumulating points in their current round. But beware! Roll a **1** and you lose all your current round points, passing the turn to your opponent. Play it safe by pressing **Hold** to bank your points. The first player to reach **100 points** wins! 🏆

Built with **pure HTML, CSS & JavaScript** — no frameworks, no dependencies — featuring a stunning **glassmorphism UI** with a vibrant purple-to-red gradient background, smooth CSS transitions, and fully responsive design that works on everything from a Samsung phone to a 4K monitor.

> 🎲 _A perfect project for learning DOM manipulation, event handling, game state management, and responsive CSS design._

</td>
</tr>
</table>

<br/>

## 🕹️ How to Play

<div align="center">

```
                    🎲 PIG DICE GAME RULES 🎲
   ─────────────────────────────────────────────────

   👥 Players:     2 (taking turns)
   🏆 Goal:        Be the first to reach 100 points
   🎲 Equipment:   1 six-sided die

   ─────────────────────────────────────────────────

   TURN FLOW:

   ┌─── 🎲 Roll Dice ──────────────────────────────┐
   │                                                 │
   │   Rolled 2–6?                                   │
   │   ├── ✅ Points added to CURRENT score          │
   │   └── 🔄 Roll again or Hold                    │
   │                                                 │
   │   Rolled 1? 💀                                  │
   │   ├── ❌ CURRENT score resets to 0              │
   │   └── 🔄 Turn passes to other player            │
   │                                                 │
   ├─── 📥 Hold ────────────────────────────────────┤
   │   ├── ✅ CURRENT score added to TOTAL score     │
   │   ├── 🔄 Turn passes to other player            │
   │   └── 🏆 If TOTAL ≥ 100 → YOU WIN!             │
   │                                                 │
   ├─── 🔄 New Game ────────────────────────────────┤
   │   └── 🔁 Reset everything, start fresh          │
   └─────────────────────────────────────────────────┘
```

</div>

<table>
<tr>
<td align="center" width="33%">

### 🎲 Roll Dice

Roll the die. If it's **2–6**, it's added to your current score. If it's **1**, you lose everything and it's the next player's turn!

</td>
<td align="center" width="33%">

### 📥 Hold

Bank your current points to your total score. Your turn ends and the other player goes. Play smart!

</td>
<td align="center" width="33%">

### 🔄 New Game

Reset everything — scores, current points, active player. Start a completely fresh game!

</td>
</tr>
</table>

<br/>

## ✨ Features

<div align="center">

| Feature                    | Description                                                          | Status |
| :------------------------- | :------------------------------------------------------------------- | :----: |
| 🎲 **Dice Rolling**        | Random 1–6 dice generation with matching dice face images            |   ✅   |
| 👥 **Two Players**         | Turn-based gameplay with visual active player highlighting           |   ✅   |
| 📊 **Score Tracking**      | Real-time total score and current round score display                |   ✅   |
| 💀 **Roll-1 Penalty**      | Rolling a 1 resets current score and switches player                 |   ✅   |
| 📥 **Hold Mechanic**       | Bank current points safely to total score                            |   ✅   |
| 🏆 **Win Detection**       | Automatic winner detection at 100 points with dark theme celebration |   ✅   |
| 🔄 **New Game**            | Full game reset with single button click                             |   ✅   |
| 🎨 **Glassmorphism UI**    | Frosted glass effect with `backdrop-filter: blur(200px)`             |   ✅   |
| 🌈 **Gradient Background** | Vibrant purple `#753682` → red `#bf2e34` linear gradient             |   ✅   |
| ✨ **Smooth Transitions**  | 0.75s CSS transitions on player switching and state changes          |   ✅   |
| 🖼️ **6 Dice Images**       | Custom PNG dice faces for all 6 sides                                |   ✅   |
| 📱 **Fully Responsive**    | 5 breakpoints from mobile (480px) to desktop (1200px+)               |   ✅   |
| 🅰️ **Custom Typography**   | Google Fonts — Nunito typeface                                       |   ✅   |
| ⌨️ **Strict Mode**         | JavaScript `'use strict'` for safer, cleaner code                    |   ✅   |

</div>

<br/>

## 🎨 Design

<div align="center">

### 🌈 Color Palette

<table>
<tr>
<td align="center" width="140">
<img src="https://via.placeholder.com/60x60/753682/FFFFFF?text=+" alt="Purple"/>
<br/><b>#753682</b>
<br/><sub>Gradient Start</sub>
</td>
<td align="center" width="140">
<img src="https://via.placeholder.com/60x60/bf2e34/FFFFFF?text=+" alt="Red"/>
<br/><b>#bf2e34</b>
<br/><sub>Gradient End</sub>
</td>
<td align="center" width="140">
<img src="https://via.placeholder.com/60x60/c7365f/FFFFFF?text=+" alt="Pink"/>
<br/><b>#c7365f</b>
<br/><sub>Score & Accent</sub>
</td>
<td align="center" width="140">
<img src="https://via.placeholder.com/60x60/2f2f2f/FFFFFF?text=+" alt="Dark"/>
<br/><b>#2f2f2f</b>
<br/><sub>Winner BG</sub>
</td>
<td align="center" width="140">
<img src="https://via.placeholder.com/60x60/FFFFFF/333333?text=+" alt="White"/>
<br/><b>#FFFFFF</b>
<br/><sub>Glass Overlay</sub>
</td>
</tr>
</table>

### 🪟 Visual Effects

| Effect               | Implementation                                                           |
| :------------------- | :----------------------------------------------------------------------- |
| 🪟 **Glassmorphism** | `background: rgba(255, 255, 255, 0.35)` + `backdrop-filter: blur(200px)` |
| 🔲 **Box Shadow**    | `0 3rem 5rem rgba(0, 0, 0, 0.25)` for depth                              |
| 🔘 **Button Glass**  | `rgba(255, 255, 255, 0.6)` + `blur(10px)` + pill shape                   |
| ✨ **Active Player** | Brighter background `rgba(255, 255, 255, 0.4)` + bold name               |
| 🏆 **Winner State**  | Dark background `#2f2f2f` + bold crimson name                            |
| 🎲 **Dice Shadow**   | `0 2rem 5rem rgba(0, 0, 0, 0.2)` floating effect                         |
| 🔄 **Transitions**   | `all 0.75s` smooth state changes                                         |
| 👆 **Button Press**  | `translateY(3px)` + reduced shadow on `:active`                          |

### 🅰️ Typography

| Font                      | Weight | Usage                      |
| :------------------------ | :----- | :------------------------- |
| **Nunito** (Google Fonts) | 300    | Player names, scores       |
| **Nunito** (Google Fonts) | 400    | Body text, buttons         |
| **Nunito** (Google Fonts) | 700    | Active player name, winner |

</div>

<br/>

## 🛠️ Tech Stack

<div align="center">

<table>
<tr>
<td align="center" width="160">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" width="48" height="48" alt="HTML5" />
<br /><b>HTML5</b>
<br /><sub>Semantic Structure</sub>
</td>
<td align="center" width="160">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" width="48" height="48" alt="CSS3" />
<br /><b>CSS3</b>
<br /><sub>Glassmorphism + Responsive</sub>
</td>
<td align="center" width="160">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="48" height="48" alt="JavaScript" />
<br /><b>JavaScript (ES6+)</b>
<br /><sub>Game Logic & DOM</sub>
</td>
</tr>
</table>

### 📦 Zero Dependencies

> 🚀 This project uses **no frameworks, no libraries, no build tools** — just pure vanilla HTML, CSS, and JavaScript. Open `index.html` and play!

</div>

<br/>

## 📁 Project Structure

```
Dice_Game/
│
├── 📄 index.html         # Game UI structure (2 players, dice, 3 buttons)
├── 📄 style.css           # Glassmorphism styling, gradients & responsive design
├── 📄 script.js           # Game logic (roll, hold, switch, win, reset)
├── 📄 .prettierrc          # Prettier code formatter config
├── 🖼️ images.jpg          # Favicon image
│
└── 📁 image/              # Dice face images
    ├── 🎲 dice-1.png      # ⚀ One
    ├── 🎲 dice-2.png      # ⚁ Two
    ├── 🎲 dice-3.png      # ⚂ Three
    ├── 🎲 dice-4.png      # ⚃ Four
    ├── 🎲 dice-5.png      # ⚄ Five
    └── 🎲 dice-6.png      # ⚅ Six
```

<br/>

## ⚙️ Game Logic

<div align="center">

### State Variables

```javascript
let scores; // [Player 1 Total, Player 2 Total]
let currentScore; // Current round accumulator
let activePlayer; // 0 (Player 1) or 1 (Player 2)
let playing; // true = game active, false = game over
```

### Core Functions

| Function          | Description                                                                  |
| :---------------- | :--------------------------------------------------------------------------- |
| `init()`          | 🔄 Reset all scores to 0, set Player 1 active, hide dice, clear winner state |
| `switchPlayer()`  | 🔀 Reset current score, toggle `activePlayer` (0↔1), swap CSS classes        |
| `btnRoll` handler | 🎲 Generate random 1–6, display dice image, add to current or switch on 1    |
| `btnHold` handler | 📥 Bank current to total, check if ≥100 (win) or switch player               |
| `btnNew` handler  | 🆕 Call `init()` for fresh game                                              |

### Game Flow Diagram

```
  ┌──────────────────────────────────────────┐
  │              🔄 init()                   │
  │   scores = [0, 0]                        │
  │   currentScore = 0                       │
  │   activePlayer = 0                       │
  │   playing = true                         │
  └──────────────┬───────────────────────────┘
                 │
                 ▼
  ┌──────────────────────────────────────────┐
  │         🎲 Player Rolls Dice             │
  │   dice = Math.trunc(Math.random()*6)+1   │
  └──────────────┬───────────────────────────┘
                 │
          ┌──────┴──────┐
          │             │
     dice === 1    dice !== 1
          │             │
          ▼             ▼
  ┌──────────────┐  ┌──────────────────────┐
  │  💀 BUST!    │  │  ✅ currentScore +=  │
  │  current = 0 │  │     dice             │
  │  switchPlayer│  │  Display on screen   │
  └──────────────┘  └──────────┬───────────┘
                               │
                      Player clicks 📥 Hold
                               │
                               ▼
                    ┌─────────────────────┐
                    │  scores[active] +=  │
                    │    currentScore     │
                    └──────────┬──────────┘
                               │
                     ┌─────────┴─────────┐
                     │                   │
               score >= 100        score < 100
                     │                   │
                     ▼                   ▼
              ┌────────────┐     ┌──────────────┐
              │ 🏆 WINNER! │     │ switchPlayer  │
              │ playing =  │     │ Continue game │
              │   false    │     └──────────────┘
              └────────────┘
```

</div>

<br/>

## 🚀 Getting Started

### 📋 Prerequisites

<table>
<tr>
<td>

| Requirement     | Version                                            |
| :-------------- | :------------------------------------------------- |
| **Web Browser** | Any modern browser (Chrome, Firefox, Safari, Edge) |
| **Text Editor** | Optional — for viewing/editing code                |

> 💡 **No installation needed!** Just open the HTML file directly.

</td>
</tr>
</table>

### ▶️ Quick Start

<details open>
<summary><b>Step-by-step guide</b></summary>

<br/>

**1️⃣ Clone the repository**

```bash
git clone https://github.com/AmarAhmedMohammed/Dice_Game.git
cd Dice_Game
```

**2️⃣ Open the game**

```bash
# Simply open index.html in your browser
# On Windows:
start index.html

# On macOS:
open index.html

# On Linux:
xdg-open index.html
```

**3️⃣ Play! 🎲**

- Click **🎲 Roll dice** to roll
- Click **📥 Hold** to bank your points
- Click **🔄 New game** to restart

</details>

<br/>

## 📱 Responsive Breakpoints

<div align="center">

The game adapts to **5 screen sizes** using CSS `zoom` for pixel-perfect scaling:

| Breakpoint       | Width Range      |  Zoom  | Device Target                        |
| :--------------- | :--------------- | :----: | :----------------------------------- |
| 📱 **Mobile S**  | `≤ 480px`        | `0.40` | Samsung A13, iPhone SE, small phones |
| 📱 **Mobile L**  | `481px – 767px`  | `0.65` | Medium smartphones, large phones     |
| 📟 **Tablet**    | `768px – 991px`  | `0.80` | iPad, Samsung Tab, tablets           |
| 💻 **Desktop S** | `992px – 1199px` | `0.90` | Small laptops, compact screens       |
| 🖥️ **Desktop L** | `≥ 1200px`       | `1.00` | Full-size desktops, large monitors   |

</div>

<br/>

## 🤝 Contributing

<table>
<tr>
<td>

Contributions are always welcome! Here's how you can help:

1. 🍴 **Fork** the repository
2. 🌿 **Create** a feature branch (`git checkout -b feature/amazing-feature`)
3. 💾 **Commit** your changes (`git commit -m 'Add amazing feature'`)
4. 📤 **Push** to the branch (`git push origin feature/amazing-feature`)
5. 🔃 **Open** a Pull Request

### 💡 Contribution Ideas

- 🔊 Add sound effects for dice rolls and winning
- 🏆 Add customizable winning score (50, 100, 150)
- 🤖 Add single-player mode with AI opponent
- 🎨 Add theme switcher (dark mode, light mode)
- 📊 Add game statistics & history tracking
- ✨ Add dice roll animation (CSS or JS)

</td>
</tr>
</table>

<br/>

## 📄 License

<div align="center">

This project is licensed under the **MIT License**.

<br/>

```
MIT License — feel free to use this project for learning and development.
```

<br/>

---

<br/>

<p align="center">
  <b>⭐ If you found this project helpful, please give it a star!</b>
</p>

<p align="center">
  Made with ❤️ and 🎲
</p>

<br/>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%"/>

<br/>

<p align="center">
  <img src="https://img.shields.io/badge/Roll_the_dice_&_have_fun!-🎲-c7365f?style=for-the-badge" alt="Roll the dice!"/>
</p>

</div>
