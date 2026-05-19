# Student Habit Tracker 📋

A simple C++ console application that helps students track their daily habits.

--- 

## 📌 Project Description 

This program allows students to manage their habits by adding new habits,
updating progress, searching for a specific habit, and viewing all habits
with their completion percentage.

---

## ✨ Features

- Add a new habit with a name and target days
- Update completed days for any habit
- View all habits with progress percentage
- Search for a habit by ID
- Input validation (duplicate ID, full list, empty list)
- Progress cap so completed days never exceed target days

---

## 🧠 Concepts Used

| Concept | Where I Used It |
|---|---|
| `struct` | To store each habit (id, name, tardays, comdays) |
| Arrays | `ha h[100]` to store up to 100 habits |
| Functions | `addHabit()`, `updateHabit()`, `showHabits()`, `searchHabit()` |
| `while(true)` loop | To keep the menu running |
| `switch` statement | To handle menu choices |
| `for` loop | To search and display habits |
| `if / else` | For input validation |
| `cin.ignore()` + `getline()` | To read names that have spaces |

---

## 🔄 Version History

| Version | What changed |
|---|---|
| v0.1 | Menu inside wrong loop - never showed |
| v0.3 | Added functions + `while(true)` |
| v0.5 | Fixed bugs in variables and showHabits |
| v0.7 | Renamed `count` → `habitCount` |
| v0.8 | Fixed name input with `cin.ignore()` + `getline()` |
| v1.0 | Added validation, progress %, formatting |

---

## 🛠️ How to Run

1. Open the project in any C++ compiler
   (Code::Blocks, Visual Studio, Dev-C++)
2. Compile `main.cpp`
3. Run the program
4. Use the menu to interact with the tracker

---

## 📷 Sample Output

<img width="300" height="477" alt="sample output" src="https://github.com/user-attachments/assets/52157267-44ad-45e1-a298-1b3ab58907a8" />

---

## 👨‍💻 Author

- **Name:** Ayman
- **Course:** Structural Programming with C++
- **University:** University of Fallujah
- **Year:** 2025–2026
