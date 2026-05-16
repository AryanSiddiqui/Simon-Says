# Simon-Says
# Simon Memory Game (Python Turtle Version)

A graphical Simon-style memory game built in Python using the `turtle` graphics library.

The game generates an increasingly long sequence of colored flashes that the player must memorize and repeat by clicking the correct colored buttons in order.

---

# 📌 Overview

This project recreates the classic **Simon memory game** using:

- Python
- Turtle graphics
- Mouse click interaction
- Dynamic speed scaling
- Randomized button layouts

The player watches a sequence of flashing colors and must repeat the sequence correctly. Each successful round increases the difficulty by extending the sequence and eventually increasing the game speed.

---

# 🎮 Features

## 🔹 Randomized Button Positions
Each level randomizes the position of the color buttons to increase difficulty and prevent memorization based on location.

---

## 🔹 Dynamic Sequence Generation
The game continuously appends new random colors to the sequence as levels progress.

---

## 🔹 Speed Scaling
Every 5 levels:
- the game speed doubles
- flash timing becomes faster
- reaction difficulty increases

---

## 🔹 Interactive Mouse Input
Players interact with the game by clicking colored squares directly on the screen.

---

## 🔹 Score Tracking
The current score is displayed in real-time in the top-right corner of the screen.

---

## 🔹 Status Messaging
The game displays:
- current game state
- level transitions
- game-over messages

---

# 🧠 How the Game Works

## Step 1 — Generate Sequence
The program randomly selects a color and appends it to the existing sequence.

---

## Step 2 — Display Sequence
The buttons flash in order for the player to memorize.

---

## Step 3 — User Input
The player clicks the buttons attempting to repeat the sequence exactly.

---

## Step 4 — Validation
The program checks:
- whether the player input matches the sequence
- whether the player made a mistake

If correct:
- advance to the next level

If incorrect:
- game over

---

# 🖥️ Technologies Used

- Python 3
- Turtle Graphics
- Random Module
- Time Module

---

# 📂 Project Structure

```text
simon_game.py
README.md
```

---

# ▶️ How to Run

## 1. Install Python
Make sure Python 3 is installed on your computer.

---

## 2. Save the File

Save the code as:

```text
simon_game.py
```

---

## 3. Run the Program

Open a terminal or command prompt and run:

```bash
python simon_game.py
```

---

# 🧪 Gameplay Rules

- Watch the flashing sequence carefully
- Repeat the sequence by clicking the colors
- Each level adds one more color
- Every 5 levels the game speeds up
- One mistake ends the game

---

# 🎨 Color Mapping

| Key | Color |
|---|---|
| R | Red |
| G | Green |
| B | Blue |
| Y | Yellow |

---

# 🚀 Possible Future Improvements

Potential upgrades include:

- Sound effects
- High-score saving
- Difficulty modes
- Keyboard controls
- Multiplayer support
- Animated transitions
- Custom themes

---

# 📚 Concepts Demonstrated

This project demonstrates practical use of:

- Event-driven programming
- GUI interaction
- State management
- Randomization
- Memory-game logic
- User input validation
- Real-time graphics

---

# 🏁 Final Notes

This project is a Python implementation of the classic Simon memory game designed to practice:

- graphical programming
- game logic
- interactive event handling
- algorithmic thinking

while creating a fun and progressively challenging gameplay experience.
