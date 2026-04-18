# 🧩 Sudoku Game

A simple browser-based Sudoku game built with vanilla JavaScript. Solve the puzzle by filling in the grid correctly while racing against the timer and keeping errors low.

---

## 🎮 Features
- Interactive 9x9 Sudoku board
- Number selection system (1–9)
- Real-time error tracking
- Countdown-style timer
- Win detection with success message
- Game reset on completion, time limit, or too many errors
- Pre-filled starting board with fixed puzzle

---

## 🧠 How to Play
1. Select a number from 1–9
2. Click an empty tile on the board
3. If correct → number fills in
4. If wrong → error count increases
5. Fill the entire board correctly to win

---

## ⏱️ Game Rules
- Max **10 errors allowed**
- Max **10 minutes per game**
- Game ends when:
  - Board is completed correctly 🎉
  - Time runs out ⏳
  - Too many errors ❌

---

## 🛠️ Tech Stack
- HTML
- CSS
- JavaScript (Vanilla DOM manipulation)

## 🧩 Key Concepts Used
- DOM manipulation
- Event handling
- Game state management
- Timer using `setInterval`
- Grid-based logic
- Basic algorithm validation (Sudoku solution checking)

## 📌 Future Improvements
- Difficulty levels
- Puzzle generator
- Hint system
- Mobile responsiveness improvements
- Save & resume game state

## 🎯 Purpose
This project was built to strengthen JavaScript fundamentals, DOM manipulation skills, and game logic design.
