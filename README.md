# 2D SFML Chess Game

A classic 2D Chess Game written in **C++** using the **Simple and Fast Multimedia Library (SFML)**. This project features full interactive mouse controls for dragging and dropping pieces, a complete set of custom chess piece sprites, and structured game logic.

## 🚀 Features
* **Interactive Gameplay:** Smooth drag-and-drop mechanics to move chess pieces across the board.
* **Visual Interface:** Rendered using SFML graphics with dedicated textures for all black and white pieces.
* **Cross-Platform Compatibility:** Configured to compile cleanly on both Windows (Visual Studio) and Linux/WSL environments without altering source structure.

## 🛠️ Built With
* **Language:** C++
* **Framework:** SFML (Simple and Fast Multimedia Library)

## 📦 How to Run (Linux/WSL)
1. Make sure you have SFML 2.5/2.6 installed.
2. Compile using:
   ```bash
   g++ chess.cpp -o chess_game -lsfml-graphics -lsfml-window -lsfml-system
   ```
3. Run the executable:
   ```bash
   ./chess_game
   ```
