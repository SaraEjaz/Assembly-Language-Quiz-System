# 🧠 Assembly Language Quiz System

A console-based, interactive **multiple-choice quiz system** developed in **Assembly Language**, designed to enhance learning and assessment in academic or training environments. The system provides instant feedback, tracks incorrect attempts, and ends the game after three wrong answers.

---

## 📄 Abstract

This project presents an **Assembly Language-based Quiz System** designed to streamline the process of administering and taking quizzes.
Players can answer multiple-choice questions with immediate feedback. A player is allowed **only two incorrect answers**; the third wrong attempt results in failure.
The system offers a simple yet effective platform for educational engagement using low-level programming concepts.

---

## 📌 Table of Contents

* [Abstract](#-abstract)
* [Introduction](#-introduction)
* [Problem Statement](#-problem-statement)
* [Requirement Analysis](#-requirement-analysis)
* [Design Planning](#-design-planning)
* [Technology Selection](#-technology-selection)
* [Project Scope](#-project-scope)
* [Features](#-features)
* [Tools & Technologies](#-tools--technologies)
* [How to Run](#-how-to-run)
* [Future Improvements](#-future-improvements)
* [Conclusion](#-conclusion)

---

## 📖 Introduction

This quiz game allows a user to choose a subject and answer a set of questions. The system evaluates each answer:

* Displays “Your answer is right” or “Your answer is wrong”.
* Ends the game on the **third wrong attempt**.
* If completed successfully, displays a congratulatory message.

This system promotes interactive learning and assessment with immediate feedback.

---

## ❓ Problem Statement

To design and implement a functional **Quiz System in Assembly Language** that:

* Administers multiple-choice quizzes
* Accepts and validates user input
* Provides real-time feedback
* Tracks performance and ends the session on repeated incorrect answers

---

## 🔍 Requirement Analysis

* **Understand Specifications**: Identify essential functionalities such as quiz creation, quiz participation, and feedback.
* **Core Features**:

  * Quiz creation (by admin)
  * Quiz taking (by user)
  * Feedback generation (real-time)
  * Error handling (maximum 2 wrong answers)

---

## 🧩 Design Planning

* **Architecture**:

  * Console-based, step-by-step flow for interaction
* **Data Structures**:

  * Arrays/tables to store questions and answer choices
* **Interface**:

  * Clear options and messages using keyboard input
* **Game Logic**:

  * Loops and conditions to control flow based on answers

---

## ⚙️ Technology Selection

* **Language**: Assembly Language (x86)
* **Reason**: Performance, learning depth, compatibility with educational tools like TASM or MASM
* **Platform**: DOS (via emulator such as DOSBox)

---

## 📦 Project Scope

The project scope includes:

1. Admin functionality to create quizzes with MCQs.
2. Sequential question presentation with multiple choices.
3. User input for answers with instant feedback.
4. Quiz termination logic after 3 wrong attempts.
5. Console-based interface with basic UI messages.

---

## ✅ Features

### Functional Features

* User login/quiz start
* Display of questions and options
* Answer selection via keyboard input
* Feedback message for each answer
* Game ends after 3 wrong answers
* Congratulatory message if quiz is completed

### Non-Functional Features

* Lightweight and fast performance
* Simple and interactive interface
* Easy to edit/extend questions in code

---

## 🛠️ Tools & Technologies

| Component   | Technology Used         |
| ----------- | ----------------------- |
| Programming | Assembly Language (x86) |
| IDE         | TASM / MASM             |
| Platform    | DOS (via DOSBox)        |

---

## ▶️ How to Run

1. Open the source file in **TASM** or **MASM**.
2. Compile the code:

   ```
   tasm quiz.asm
   tlink quiz.obj
   ```
3. Run the executable using DOSBox:

   ```
   quiz.exe
   ```
4. Follow the on-screen instructions to play the quiz.

---

## 🔮 Future Improvements

* Add subjects/categories for user selection
* Include question randomization
* Store and display score history
* Add sound effects or visual cues (ASCII UI)
* Port to a GUI version in a high-level language

---

## 📚 Conclusion

The Assembly Language Quiz System demonstrates how low-level programming can be used to create meaningful and interactive educational tools. It’s a great example of applying system-level programming to real-world use cases while reinforcing logic and control structures.

OUTPUT


![image](https://github.com/user-attachments/assets/d4062be0-aca4-4b7a-8228-6ded6aae9618)


![image](https://github.com/user-attachments/assets/63518d97-d9d4-429b-b601-9cc32045a63e)



