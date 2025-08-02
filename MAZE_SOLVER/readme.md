# Maze Solver 🚀

## 📌 Overview
The **Maze Solver** is a C++ program that finds the shortest path through a **10x10 maze** using efficient pathfinding algorithms. It takes a maze grid as input and determines a valid path from the **starting point** to the **destination**, avoiding walls.

## 🔧 Features
- **Pathfinding Algorithm**: Implements an optimized search algorithm to find the shortest route.
- **User Input**: Allows users to input a maze matrix, a start point, and an end point.
- **Visual Representation**: Displays the solved path in an intuitive format.
- **Efficient Execution**: Optimized for quick maze-solving.

---

## 📥 Input Format
- A **10x10 grid** where:
  - `0` represents an open path.
  - `1` represents a wall.
- The **starting position** `(x, y)`.
- The **destination position** `(x, y)`.

### 🖥 Example Input:
```
Enter the maze (10x10 grid, 0 for path, 1 for wall):
0 1 0 0 0 0 0 1 0 0
0 1 0 1 1 1 0 1 0 0
0 0 0 0 0 0 0 1 0 0
0 1 1 1 1 1 0 1 0 0
0 0 0 0 0 0 0 0 0 0
0 1 1 1 1 1 1 1 1 0
0 0 0 0 0 0 0 0 0 0
0 1 1 1 1 1 1 1 1 0
0 0 0 0 0 0 0 0 0 0
0 1 1 1 1 1 1 1 1 0

Enter the starting point (x y): 0 0
Enter the destination point (x y): 9 9
```

---

## 📤 Output Format
- A **solved maze** where `1` marks the shortest path.

### 🖥 Example Output:
```
1 0 0 0 0 0 0 0 0 0
1 0 0 0 0 0 0 0 0 0
1 1 1 1 1 1 1 0 0 0
0 0 0 0 0 0 1 0 0 0
0 0 0 0 0 0 1 1 1 1
0 0 0 0 0 0 0 0 0 1
0 0 0 0 0 0 0 0 0 1
0 0 0 0 0 0 0 0 0 1
0 0 0 0 0 0 0 0 0 1
0 0 0 0 0 0 0 0 0 1
```

---

## 🛠 How to Run
1. **Clone the Repository**:
   ```sh
   git clone https://github.com/deeplukhi/Maze_Solver.git
   cd Maze_Solver
   ```
2. **Compile the C++ Program**:
   ```sh
   g++ Maze_Solver.cpp -o maze_solver
   ```
3. **Run the Program**:
   ```sh
   ./maze_solver
   ```
4. **Enter the maze and start/end points** to see the solution.

---

## 📚 Future Enhancements
✅ Implementing more advanced pathfinding algorithms (A* or Dijkstra).  
✅ Adding support for larger, user-defined mazes.  
✅ Introducing a graphical visualization of the path.  

---

## 🏆 Contributions
Feel free to fork this repository and enhance the maze solver. Pull requests are welcome! 😊

---

## 📜 License
This project is open-source and available under the **MIT License**.


