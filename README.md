# 🎵 SimonPlays – Scratch Game

## 📌 Description

**SimonPlays** is a memory-based musical game inspired by *Simon Says*. The player must listen to a sequence of musical notes and then reproduce the exact same sequence by clicking the corresponding keys. Each level increases the difficulty by extending the note sequence.

This project was developed using **Scratch** as part of **CS50 Problem Set 0**, demonstrating the use of events, conditionals, loops, lists, and custom blocks.

---

## 🎮 How to Play

1. Click **Play** to start the game.
2. Listen carefully to the sequence of notes played.
3. Click the piano keys to reproduce the same sequence.
4. If the sequence is correct, you advance to the next level.
5. If the sequence is incorrect, the game ends and you can restart.

---

## 🧠 Game Mechanics

* The game uses **lists** to store:

  * The correct sequence for each level
  * The notes played by the user
* Each note button:

  * Plays a sound
  * Changes costume for visual feedback
  * Adds the note to the current input list
* After each input, the game compares the user sequence with the expected sequence.
* Difficulty increases progressively:

  * Easy
  * Medium
  * Hard

---

## 🧩 Features Used (CS50 Requirements)

* **Events** (`when green flag clicked`, `broadcast`)
* **Conditionals** (`if / else`)
* **Loops** (`repeat until`)
* **Lists** (note sequences)
* **Custom Blocks** (e.g., `playKey`, `checkLevel`)
* **Sounds and visual feedback**
* **Variables** to control level progression

---

## 🏆 Win & Lose Conditions

* **Win:** The player successfully reproduces the full sequence of the current level.
* **Lose:** The player plays a wrong note or an incorrect sequence order.

---

<img width="801" height="934" alt="image" src="https://github.com/user-attachments/assets/db1446ef-d029-4c7b-bdf4-a351443bc57c" />

## 🚀 Author

Developed by **Liandra Monteiro** for **CS50 – Problem Set 0**.
