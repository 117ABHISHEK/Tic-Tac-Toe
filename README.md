# Tic-Tac-ToeA# 🎮 Advanced Tic-Tac-Toe (C++ Console Game)

This is a C++ console-based **Tic-Tac-Toe** game where a human plays against a basic AI. It provides a fun, visually guided terminal interface with clear board mapping and automatic game rounds. The AI attempts to block your moves and respond logically, adding more challenge to the gameplay.

---

## 📝 Instructions

1. Play as `O` (Player 1) and try to beat the AI (`X`).
2. Use the **Key Map** shown alongside the game board to select your move (1-9).
3. If you win, the AI starts second in the next round. If you lose, you start first again.
4. The game automatically resets after each round.

---

## 🧠 AI Logic

- Detects player's winning positions and blocks them
- If no threats detected, it plays randomly
- Basic pattern recognition is implemented to avoid immediate loss

---

## 🎯 Features

- Turn-based gameplay with **YOU vs AI**
- Smart AI blocking and random fallback
- Clear screen refresh after every move (`system("CLS")`)
- Auto-reset with alternating start between player and AI
- Color-coded board using characters (`O` for player, `X` for AI)
- Instruction section shown before starting the game
- Informs when game ends in **Win**, **Lose**, or **Tie**

---

## 🖥️ How to Run

### Compile & Execute using `g++` (Windows recommended)

```bash
g++ tictactoe.cpp -o tictactoe
./tictactoe
```

💡 Requires `windows.h`, so works best on **Windows systems**.

---

## 📦 Dependencies

- C++11 or higher
- Windows OS
- g++, Code::Blocks, Visual Studio, or other C++ compilers

---

## 🚧 Potential Improvements

- Replace `goto` with loop-based control flow
- Implement smarter AI using Minimax algorithm
- Add sound effects or visuals using external libraries
- Track game statistics (win/lose ratio)
- GUI version using SFML or SDL

---

## 👨‍💻 Developer Notes

- **AI uses hard-coded defensive strategies** to block immediate threats
- **Screen refreshes** give a clean experience but are OS-specific
- **Basic structure and logic** makes this a great beginner project

---


## ✨ Author

Created by Abhishek
C++ Enthusiast | Game Logic Builder | Terminal UI Designer

---
