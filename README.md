Deathtrap Tile Puzzle 🎮🧩
Group 4 Project

📜 Overview
Deathtrap Tile Puzzle is a Java-based game inspired by the famous puzzle from the "Uncharted" game series. The game challenges players to solve a deadly tile puzzle, where choosing the wrong tile could lead to a trap!

The goal is to identify and select all the safe tiles while avoiding traps based on visual clues. The game is developed using Java Swing GUI in NetBeans.

🕹️ Game Description
The puzzle features two types of tiles:

✅ Safe Tiles — Step on these to proceed safely.
❌ Trap Tiles — Stepping on these will make you lose the game.
🧭 Gameplay Flow:
Interface Frame:

A welcome screen that greets the player.
A "Begin" button to proceed to the instructions.
Start Frame:

Displays an explanation of the puzzle mechanics.
Introduces three guiding shapes:
🚢 Ship
☀️ Sun
⚔️ Sword
Each shape helps the player deduce the locations of traps.
A "Start" button to enter the puzzle game board.
Deathtrap Frame (Game Board):

The interactive board where players select tiles.
Goal: Find all safe tiles to win.
If the player steps on a trap tile, they lose.
Escape Frame (Winning Screen):

Displayed when all safe tiles are successfully selected.
Includes "Replay" and "Exit" buttons.
Reset Frame (Losing Screen):

Displayed when a trap tile is selected.
Includes "Replay" and "Exit" buttons.
💻 How to Run the Game
Prerequisites:

Java JDK installed on your system.
NetBeans IDE (recommended for easy GUI handling).
Setup:

Clone the repository or download the source code.
Open the project in NetBeans.
Run the project by clicking the Run button or pressing Shift + F6.
📁 Project Structure
css
Copy
Edit
DeathtrapTilePuzzle/
│
├── src/
│   ├── InterfaceFrame.java
│   ├── StartFrame.java
│   ├── DeathtrapFrame.java
│   ├── EscapeFrame.java
│   └── ResetFrame.java
│
└── README.md

📷 Screenshots


![Frame Screenshot](src/photos/screenshots/Deathtrap-frame.png)

Or view it directly [here](src/photos/screenshots/your-screenshot.png).


✨ Features
Simple and intuitive Java Swing GUI.
Step-by-step game progression.
Replay and exit options for flexibility.
Puzzle logic inspired by Uncharted series.
🚀 Future Improvements
Add sound effects for traps and wins.
Improve GUI design and tile animations.
Include hints or difficulty levels.
🤝 Contributors
Group 4 Team Members
📜 License
This project is for educational purposes. No commercial use intended.

🔗 References
Inspired by the puzzle in "Uncharted" series (Naughty Dog ©).

