# 🧠 DSA-Mini-Projects

A curated collection of C++ mini-projects that demonstrate practical, hands-on applications of core **Data Structures and Algorithms (DSA)**. These projects aim to help students and developers strengthen their foundational DSA concepts while building functional, real-life systems.

## 📁 Project Structure

```
DSA-Mini-Projects/
├── FLIGHT_MANAGEMENT_SYSTEM/
│   ├── Flight_Route_Management_System.c++
│   ├── Flight_Route_Management_System.exe
│   ├── flights.txt
│   └── readme.md
│
├── MAZE_SOLVER/
│   ├── Maze-solver.c++
│   ├── Maze-solver.exe
│   └── readme.md
│
├── SUDOKU_SOLVER/
│   ├── Sudoku-solver.c++
│   ├── Sudoku-solver.exe
│   └── readme.md
│
└── README.md
```


## ✈️ Flight Management System

An efficient **Flight Route Planner** in C++. It finds the shortest and fastest flight paths between airports using classic graph algorithms—**Dijkstra** or **A\***[^1][^3][^5].

- Uses adjacency lists and priority queues for fast graph operations
- Handles large networks with thousands of routes
- Reads from `flights.txt`
- Excellent real-world example of graph algorithms

**Folder:** `FLIGHT_MANAGEMENT_SYSTEM`
**[Read More](./FLIGHT_MANAGEMENT_SYSTEM/readme.md)**

## 🚀 Maze Solver

A C++ program that finds the shortest path through a **10x10 maze** using **BFS/DFS or A\*** searching techniques.

- Avoids obstacles and returns valid path
- Easily adaptable to larger mazes
- Intuitive for visualizing search algorithms

**Folder:** `MAZE_SOLVER`
**[Read More](./MAZE_SOLVER/readme.md)**

## 🎯 Sudoku Solver

A clean, functional **9x9 Sudoku Solver** in C++ using an efficient **Backtracking Algorithm**.

- Checks all placements recursively
- Validates digits and solves quickly
- Handles any standard Sudoku puzzle
- `.exe` included for Windows

**Folder:** `SUDOKU_SOLVER`
**[Read More](./SUDOKU_SOLVER/readme.md)**

## 🛠️ Tech Stack

- **Language**: C++
- **Core DSA Concepts**: Graphs, Recursion, Backtracking, BFS, DFS, Dijkstra
- **Tools**: MinGW, GitHub, VS Code


## ▶️ How to Run

**1. Clone the repository:**

```bash
git clone https://github.com/deeplukhi/DSA-Mini-Projects.git
cd DSA-Mini-Projects
```

**2. Compile and run your chosen project:**

```bash
cd SUDOKU_SOLVER
g++ Sudoku-solver.c++ -o sudoku
./sudoku
```

**3. Or, execute the provided `.exe` files on Windows directly.**

## 🙌 Author

**Deep Lukhi**
🎓 B.Tech IT | 💻 DSA Lover | 📈 Building FAANG-level systems
🌐 GitHub: [deeplukhi](https://github.com/deeplukhi)

⭐ **Star this repository if you found it helpful!**
