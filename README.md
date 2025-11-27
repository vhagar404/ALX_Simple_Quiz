# ALX Simple Quiz

This project is a small interactive quiz application built using **HTML**, **CSS**, and **JavaScript**.  
The goal is to practice basic DOM manipulation, event handling, and conditional logic in JavaScript.

---

## 📌 Project Structure

ALX_Simple_Quiz/
│
├── index.html  
├── styles.css  
└── quiz.js  

---

## 🎯 Learning Objectives

By completing this project, learners will be able to:

- Use JavaScript to interact with the DOM
- Retrieve user input from radio buttons
- Compare user input with a correct answer
- Display interactive feedback messages
- Use event listeners to trigger functions on click

---

## 🧩 Quiz Functionality

The quiz asks the question:

**“What is 2 + 2?”**

The user selects one of three radio button answers:

- 4  
- 22  
- 3  

When the user clicks the **Submit Answer** button:

### ✔ If the answer is correct:

### ✘ If the answer is incorrect:

Feedback appears inside the `<p id="feedback"></p>` element.

---

## 🛠 JavaScript Requirements

Your JavaScript must include:

### 1️⃣ A function named `checkAnswer()`
This function:
- Defines the correct answer
- Finds the selected radio button using `querySelector`
- Compares the values
- Updates the feedback text

### 2️⃣ An Event Listener
The button with id `"submit-answer"` must trigger `checkAnswer` when clicked.

Correct usage:
```js
document.getElementById("submit-answer").addEventListener("click", checkAnswer);
