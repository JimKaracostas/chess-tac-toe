<h1 align="center">
  Chess-Tac-Toe
</h1>

<p align="center">
  <strong>A strategic web-based game combining Tic-Tac-Toe's objective with Chess's movement mechanics.</strong>
</p>

<p align="center">
  <img alt="HTML5" src="https://img.shields.io/badge/html5-%23E34F26.svg?style=flat&logo=html5&logoColor=white">
  <img alt="CSS3" src="https://img.shields.io/badge/css3-%231572B6.svg?style=flat&logo=css3&logoColor=white">
  <img alt="JavaScript" src="https://img.shields.io/badge/javascript-%23323330.svg?style=flat&logo=javascript&logoColor=%23F7DF1E">
</p>

<hr>

**Chess-Tac-Toe** is a strategic web-based game that combines the winning objective of Tic-Tac-Toe with the movement mechanics of Chess. It is built entirely in a single HTML file using vanilla JavaScript and CSS.

## 🎮 Game Concept

Two players (White and Black) compete on a 3x3 grid.
* **The Goal:** Align 3 of your pieces horizontally, vertically, or diagonally.
* **The Twist:** Unlike standard Tic-Tac-Toe, you don't just place pieces. You can move them around the board and capture opponent pieces based on standard Chess rules.

## ✨ Features

* **Hybrid Gameplay:** Place new pieces from your reserve or move existing pieces on the board.
* **Move Validation:** Visual indicators show valid moves (🟢) and valid captures (🔴).
* **Win Detection:** Automatic detection of winning lines with a celebration overlay.
* **Responsive Design:** Works smoothly on desktop and mobile devices.
* **Zero Dependencies:** Built with pure HTML5, CSS3, and JavaScript.

## 📜 How to Play

### 1. The Objective
Get **three** of your pieces in a row (horizontal, vertical, or diagonal).

### 2. Turn Mechanics
On your turn, you have two options:
1.  **Place:** Select a piece from your unused "hand" (top of screen) and place it on any empty square.
2.  **Move:** Select one of your pieces already on the board and move it to a new square (or capture an opponent).

### 3. Movement Rules
Pieces move similarly to standard Chess, but adapted for a 3x3 grid:

| Piece | Symbol | Movement Logic |
| :--- | :---: | :--- |
| **King** | ♔ / ♚ | Moves 1 square in any direction. |
| **Queen** | ♕ / ♛ | Moves any distance straight or diagonally. |
| **Rook** | ♖ / ♜ | Moves any distance horizontally or vertically. |
| **Bishop** | ♗ / ♝ | Moves any distance diagonally. |
| **Knight** | ♘ / ♞ | Moves in an "L" shape (jumps over pieces). |
| **Pawn** | ♙ / ♟ | Moves 1 square forward; captures 1 square diagonally. |

### 4. Capturing
If you move a piece onto a square occupied by an opponent, that piece is **captured** and removed from the board permanently.

## 🚀 Getting Started

Since this is a single-file application, running it is incredibly simple.

### Prerequisites
* A modern web browser (Chrome, Firefox, Safari, Edge).

### Installation
1.  Download the `index.html` file.
2.  Double-click `index.html` to open it in your browser.
3.  **That's it!** No server or build process required.

## 🔮 Future Improvements

Ideas for extending the game:
* [ ] Add a timer per turn.
* [ ] Implement a simple AI for single-player mode.
* [ ] Add sound effects for moves and captures.

## 📄 License

This project is open-source and free to use.
