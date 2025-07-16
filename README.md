# 🧩 2048 Game – Python (Console Version)

A simple and fully playable version of the classic 2048 game built with **Python**, running in the terminal. This version uses basic console I/O and avoids external GUI libraries, making it lightweight and easy to understand.

---

## 🎯 Objective

Combine numbered tiles by sliding them (up/down/left/right) to reach the **2048** tile. Each move spawns a new tile (2 or 4). The game ends when no moves are possible.

---

## 🛠️ Features

* Fully text-based interface
* Responsive input handling (`w`, `a`, `s`, `d`)
* Dynamic tile merging
* Random tile generation
* Real-time score tracking (`max_value`)
* Game-over detection

---

## 📦 Requirements

* Python 3.6+
* `tabulate` (optional, unused in final version)

> On Windows, `os.system('cls')` is used to clear the screen. For Linux/Mac, replace with `'clear'` if needed.

---

## 🚀 How to Run

1. Clone the repo or copy the Python file:

   ```bash
   git clone https://github.com/EswaranS-06/2048-Python-
   cd 2048-Python-
   ```

2. Run the script:

   ```bash
   python 2048.py
   ```

---

## 🎮 Controls

| Key | Action     |
| --- | ---------- |
| `w` | Move Up    |
| `s` | Move Down  |
| `a` | Move Left  |
| `d` | Move Right |

---

## 📌 Code Structure

* `display()` – Prints the board
* `move_*()` – Handles movement logic for all directions
* `added_value()` – Merges adjacent equal tiles
* `add_new_tile()` – Adds a 2 or 4 tile in an empty cell
* `check_game_over()` – Ends game if no moves left
* `main()` – Game loop

---

## 🧠 Improvements You Can Try

* Add score display or high-score tracking
* Allow undoing the previous move
* Save game state to file
* Create a GUI version with Tkinter or Pygame

---

## 📄 License

This project is free to use and modify. Attribution appreciated!
