# ♟️ Francis Chess

An interactive, web-based chess platform built with modern HTML5, CSS3, and JavaScript. **Francis Chess** features interactive tactical puzzles, an embedded Stockfish engine for single-player games, real-time online multiplayer via Firebase, an opening library with automated board demonstrations, a custom sandbox builder, and a comprehensive learning guide.

🌐 **Live Demo:** [https://luna-crow.github.io/francis-chess/](https://luna-crow.github.io/francis-chess/)

---

## 🚀 Features

* **🧩 Puzzles Mode:** Practice key tactical patterns (Back-Rank Mate, Queen Skewer, Smothered Mate, Discovered Check, and more) with interactive hints and move validation.
* **🤖 Play vs. Computer:** Play against an integrated Stockfish AI engine with customizable difficulty levels (*Novice*, *Intermediate*, *Master*, and *Grandmaster*). Includes real-time opening detection and live PGN logging.
* **🕹️ Play Online:** Create or join public/private rooms to play live against friends. Real-time board state synchronization and in-game chat are powered by Firebase.
* **📖 Openings Library:** Interactive board demonstrations for 20 essential chess openings (10 for White and 10 for Black), including key moves and strategy descriptions.
* **♟️ Movement Demo:** Visual legal move generator for individual piece types on an open board.
* **🛠️ Sandbox Builder:** Position builder tool to place custom piece arrangements onto the board or start from a standard setup.
* **📖 Learn Chess:** Beginner-friendly reference guide detailing piece movements and essential rules like check, checkmate, *en passant*, and pawn promotion.

---

## 🛠️ Tech Stack & Dependencies

* **Frontend:** HTML5, CSS3 (Modern Glassmorphism & Custom Properties), Vanilla JavaScript (ES6+)
* **Engine & Logic:** [chess.js](https://github.com/jhlywa/chess.js) (v0.10.3) & [Stockfish.js](https://github.com/nmrugg/stockfish.js) (v10.0.2)
* **Backend / Database:** [Firebase Realtime Database](https://firebase.google.com/) (v8.10.1)

---

## ⚡ Quick Start & Deployment

### Play Online Directly
Visit the live hosted version: **[https://luna-crow.github.io/francis-chess/](https://luna-crow.github.io/francis-chess/)**

### Local Setup
1. Clone this repository:
   ```bash
   git clone [https://github.com/luna-crow/francis-chess.git](https://github.com/luna-crow/francis-chess.git)
