<p align="center">
  <img src="https://img.shields.io/badge/Internet%20Programming-I-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/Code%20Review-Assignment-green?style=for-the-badge">
  <img src="https://img.shields.io/badge/Tic--Tac--Toe-Project-orange?style=for-the-badge">
</p>

<h1 align="center">🎮 Tic Tac Toe (OX) – Code Review Project</h1>

<p align="center">
  A group-based code review assignment for <strong>SWEG3107 – Internet Programming I</strong><br>
  Department of Software Engineering | College of Engineering
</p>

---

## 📌 Course Information
- **Course:** Internet Programming – I (SWEG3107)  
- **Section:** D  
- **Assignment Type:** Group Assignment (Code Review)  
- **Submitted To:** *Ms. Aster Alemu*  
- **Submission Date:** *Dec 18, 2025 (G.C.)*

---

## 👥 Group Members

| No | Name | ID |
|----|------|----|
| 1 | Surafel Mesfin | ETS1322/16 |
| 2 | Surafel Sintayehu | ETS1324/16 |
| 3 | Tamru Masresha | ETS1333/16 |
| 4 | Tekleyesus Asteraw | ETS1336/16 |
| 5 | Temesgen Belay | ETS1337/16 |

---

## 📖 Introduction
Code review is a fundamental practice in software engineering that improves **code quality**, **correctness**, and **maintainability**.  
This project evaluates a **web-based Tic Tac Toe (OX) game**, focusing on structure, logic, efficiency, readability, and user experience.

Tic Tac Toe serves as an effective example for demonstrating:
- Conditional logic
- Event handling
- State management
- DOM manipulation

The original implementation was adapted from a tutorial by **Canan Korkut (2020)** and reviewed critically for improvement opportunities.

---

## 🧩 Project Overview
The Tic Tac Toe game is built using:

- **HTML** → Structure of the game board and controls  
- **CSS** → Layout, grid design, and visual clarity  
- **JavaScript** → Game logic, state management, and interactivity  

### Key Features
- Interactive 3×3 grid
- Two-player turn-based gameplay
- Win and tie detection
- Restart functionality without page reload
- Real-time feedback messages

---

## 🧠 Code Structure & Logic (JavaScript)

✔ Organized variable declarations  
✔ Modular functions (`checkWin`, `checkTie`, `restartButton`)  
✔ Predefined winning combinations  
✔ Controlled game state using flags  
✔ Efficient event handling with early returns  

The code is structured to ensure **clarity**, **maintainability**, and **correct logic flow**.

---

## 🎨 Game Design & Functionality
- Simple and intuitive user interface
- Clear visual separation of grid cells
- Hover effects for better usability
- Prevents invalid moves
- Displays turn status, win, or tie dynamically
- Allows multiple consecutive games

---

## ⚡ Efficiency & Performance
- Uses a predefined array for win conditions
- Avoids redundant checks
- Minimal DOM manipulation
- Lightweight and responsive gameplay
- Optimized for small-scale web applications

---

## 📝 Documentation & Readability
### Strengths
- Descriptive variable and function names
- Consistent indentation and formatting
- Modular logic design

### Areas for Improvement
- Add inline comments in critical functions
- Improve beginner-friendliness
- Enhance restart feedback visually or audibly

---

## 🚀 Identified Issues & Suggested Improvements

### 🎯 Visual Feedback for Winning Combination
- Highlight winning squares using CSS classes
- Remove highlight on restart to reset visuals

### 🧩 Global Variables
- Encapsulate `currentPlayer` and `gameOver` into a single game state object

### ⌨️ Keyboard Accessibility
- Enable arrow-key navigation
- Use Enter or Space to place moves
- Improve accessibility for all users

### 🗒️ Minimal Comments
- Add brief inline comments in:
  - `checkWin()`
  - `checkTie()`
  - Click event handlers

---

## ✅ Summary
This project demonstrates a **well-structured and functional** implementation of a Tic Tac Toe game using core web technologies.  
It follows good programming practices, manages game state effectively, and provides a solid foundation for further enhancements.

With minor improvements in **accessibility**, **visual feedback**, and **documentation**, the application can achieve a higher level of usability and maintainability.

---

## 📚 References
- Korkut, C. (2020). *How to create a tic-tac-toe with HTML, CSS, and JavaScript*. Medium  
- Atlassian – Code Review Best Practices  
- Built In – Code Review Best Practices  
- Code-Review.org – Improving Code Review Skills  

---

<p align="center">
  <img src="https://img.shields.io/badge/Made%20With-HTML%20%7C%20CSS%20%7C%20JavaScript-blue?style=flat-square">
  <img src="https://img.shields.io/badge/Status-Completed-success?style=flat-square">
</p>
