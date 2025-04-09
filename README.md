# Sudoku-Solver-GUI-Game
# 🧩 Sudoku Solver

This is a **Sudoku Solver** project built in **Java**, developed using **NetBeans IDE**. The application provides a visual and interactive way to solve Sudoku puzzles, complete with solution reveal, move checking, and reset functionality.

---

## 📘 Description

Sudoku is a popular logic-based, combinatorial number-placement puzzle. The goal is to fill a 9×9 grid so that every row, column, and each 3×3 subgrid contains the numbers **1 to 9** exactly once.

This project allows users to interactively solve Sudoku puzzles, with additional tools to assist, validate, and auto-solve the puzzle.

---

## 🧠 Introduction

The solver uses a **backtracking algorithm** to fill numbers into empty cells. Before placing a number, it checks whether the number already exists in:

- The current **row**
- The current **column**
- The current **3×3 subgrid**

Only if it passes all three checks is the number placed. If a dead-end is reached, it backtracks and tries a different number.

---

## 🕹️ Features & Usage

- **Number Buttons (1 to 9)**  
  - Located at the bottom of the interface.
  - Initially displayed in light blue.
  - Clicking a number highlights it in royal blue.
  - All other numbers turn black upon selection.

- **Reset Button**  
  - Resets the game to its initial state.
  - Prompts a confirmation dialog (`YES/NO`) before proceeding.

- **Exit Button**  
  - Exits the application.
  - Displays a confirmation dialog asking whether you want to exit.

- **Solution / Hide Solution Button**  
  - Displays the complete solution to the current puzzle.
  - Once clicked, the button label changes to **"Hide Solution"** to allow toggling.

- **Check Moves Button**  
  - Highlights mistakes:
    - **Incorrect numbers** turn **red**
    - **Correct numbers** remain unchanged

---

## 📸 Screenshots

### ▶️ Initial Game View
![Initial Game View](https://github.com/user-attachments/assets/a1d8bcbe-8a81-43d7-8559-8102068b5074)

### ✅ After Clicking on Solution Button
![Solution View](https://github.com/user-attachments/assets/fc944805-51ed-4712-a8ee-5409cf33296c)

### 🔍 After Clicking on Check Moves
![Check Moves](https://github.com/user-attachments/assets/18f8ba37-0a45-4e39-aa54-87442eb3e745)

### 🔄 After Clicking on Reset & Exit Buttons
![Reset and Exit](https://github.com/user-attachments/assets/cc5c7d60-4805-4ff7-ba5c-cee2308eb454)

---

## 🙏 Acknowledgements

I would like to express my heartfelt gratitude to:

- Everyone who contributed to this project directly or indirectly.
- The open-source community for their wealth of resources and shared knowledge.
- Developers and designers who share their code and ideas online.
- Friends, family, and mentors for their unwavering support and encouragement throughout the development process.

---

## ✅ Conclusion

This project not only solves Sudoku puzzles using a logical algorithm but also gives users the ability to interactively test and validate their inputs. With a user-friendly GUI and smart features, solving Sudoku has never been more engaging.

> 🎯 *“Fill every row, every column, and every 3x3 subgrid with numbers 1–9, and enjoy the challenge!”*

---

## 🛠️ Technologies Used

- **Java**
- **NetBeans IDE**
- **Swing GUI**

---

