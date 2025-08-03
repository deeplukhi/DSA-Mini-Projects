
---

# 🎯 Sudoku Solver – C++ Implementation

Solve **9x9 Sudoku puzzles** using an efficient **Backtracking Algorithm** written in C++. This project demonstrates a clean and functional Sudoku solver with a ready-to-run `.exe` file for quick execution.

---

## 📁 Files Included

* `Sudoku-solver.c++` – The main source code file (rename to `.cpp` if needed).
* `Sudoku-solver.exe` – Compiled executable for Windows users.

---

## ✅ Features

* **Backtracking Algorithm** – Explores possible values with recursive depth-first search.
* **Zero-Based Input** – Accepts `0` as a placeholder for empty cells.
* **Readable Output** – Solved Sudoku is printed in a clean 9x9 format.
* **Executable Available** – No need to compile if you're on Windows.

---

## 🚀 How to Use

### 🔹 Clone the Repository

```bash
git clone https://github.com/deeplukhi/DSA-Mini-Projects.git
cd DSA-Mini-Projects/SUDOKU_SOLVER
```

### 🔹 If Using Source Code (`.c++` file)

> 💡 Rename to `.cpp` if your compiler doesn’t recognize `.c++`.

#### Compile (Linux/macOS/Windows with g++):

```bash
g++ Sudoku-solver.c++ -o sudoku_solver
./sudoku_solver
```

#### Or (Windows CMD):

```bash
g++ Sudoku-solver.c++ -o sudoku_solver.exe
sudoku_solver.exe
```

### 🔹 If Using Executable Directly

> 🪟 Just double-click `Sudoku-solver.exe` or run it from terminal:

```bash
Sudoku-solver.exe
```

Then input your puzzle (0 for blanks) as prompted.

---

## 📥 Sample Input

```
5 3 0 0 7 0 0 0 0
6 0 0 1 9 5 0 0 0
0 9 8 0 0 0 0 6 0
8 0 0 0 6 0 0 0 3
4 0 0 8 0 3 0 0 1
7 0 0 0 2 0 0 0 6
0 6 0 0 0 0 2 8 0
0 0 0 4 1 9 0 0 5
0 0 0 0 8 0 0 7 9
```

---

## ✅ Sample Output

```
5 3 4 6 7 8 9 1 2
6 7 2 1 9 5 3 4 8
1 9 8 3 4 2 5 6 7
8 5 9 7 6 1 4 2 3
4 2 6 8 5 3 7 9 1
7 1 3 9 2 4 8 5 6
9 6 1 5 3 7 2 8 4
2 8 7 4 1 9 6 3 5
3 4 5 2 8 6 1 7 9
```

---

## 🧠 Algorithm Used

* **Backtracking**: Try placing digits `1-9` in empty cells and validate rows, columns, and 3×3 subgrids.
* **Recursion**: Automatically backtrack when an invalid placement is found.

---

## 🤝 Contributing

Want to improve this solver or add a GUI? Contributions are welcome!

```bash
# Fork the repo and contribute!
git checkout -b your-feature
git commit -m "Improved UI or logic"
git push origin your-feature
```

Then create a **Pull Request** 🔁.

---

## 📄 License

This project is licensed under the **MIT License**.

---

📌 If you found this useful, **star** ⭐ the repo to show support!