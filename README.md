# Banking Operations 🏦

![Status](https://img.shields.io/badge/status-completed-green?style=for-the-badge)
![Java](https://img.shields.io/badge/Java-Beginner-orange?style=for-the-badge&logo=java)

A terminal-based Java application that simulates basic bank account operations — checking balance, transferring funds, and receiving payments through a menu-driven interface.

---

## Overview

This was one of my first Java projects. Nothing fancy — just a menu loop, a Scanner reading input, and some conditionals controlling what happens to a balance. But that's exactly the point. Before you can write OOP, you have to get comfortable with the basics: variables, types, loops, and input validation. This is where I got there.

---

## Features

- **Check Balance** — displays the current account balance
- **Transfer Funds** — deducts a value with insufficient funds validation
- **Receive Payment** — adds an incoming value to the balance
- **Menu Loop** — runs continuously until the user chooses to exit

---

## How to Run

**Prerequisites:** Java 8 or higher + any IDE

```bash
git clone https://github.com/victorhubarb/banking-operations.git
cd banking-operations

javac src/Challenge.java -d out
java -cp out Challenge
```

---

## What I Learned

- Java syntax and basic data types (`String`, `double`, `int`)
- `Scanner` for reading user input from the terminal
- `while` loops and `if/else` conditional chains
- Input validation — checking balance before allowing a transfer
- Text block strings for cleaner multiline output

---

## Author

**Victor Hugo Barbosa**
[GitHub](https://github.com/victorhubarb) · [LinkedIn](https://www.linkedin.com/in/victorhbarbosa/)
