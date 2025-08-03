---

# ✈️ Flight Management System – C++ Project

An efficient **Flight Route Planner** built in **C++**, this system uses advanced graph algorithms to find the **shortest** and **fastest** routes between airports. Designed to be highly **scalable**, it can handle **thousands of flight routes** with ease.

---

## 🔍 Overview

The **Flight Management System** is a command-line application that processes real-world flight data and provides optimized routing using graph algorithms like **Dijkstra** and optionally **A\***. Built for performance, it ensures quick lookups and efficient memory handling.

---

## 🚀 Key Features

* ✅ **Graph-Based Optimization** – Utilizes **Dijkstra’s algorithm** for shortest path.
* ✅ **Fast Performance** – Efficient with thousands of routes and dynamic updates.
* ✅ **Modular Design** – Easy to scale and integrate with UI or databases later.
* ✅ **Real-Time Route Handling** – Add or modify routes during execution.
* ✅ **Command-Line Interface** – Easy interaction and minimal dependencies.

---

## 📁 File Structure

```
Flight-Management-System/
├── Flight_Route_Management_System.cpp   # Main C++ source code
├── Flight_Route_Management_System.exe   # Precompiled executable (Windows)
├── flights.txt                          # Input data for flight connections
├── README.md                            # Project documentation
```

---

## 🛠️ Getting Started

### 🔧 Prerequisites

* C++ Compiler (Recommended: `g++`)
* Code Editor (VS Code, Code::Blocks, etc.)
* Basic understanding of graphs and DSA (for extending features)

---

### 🔹 Clone the Repository

```bash
git clone https://github.com/deeplukhi/DSA-Mini-Projects.git
cd DSA-Mini-Projects/FLIGHT_MANAGEMANT_SYSTEM
```

---

### 🔹 Compile the Code

```bash
g++ Flight_Route_Management_System.cpp -o Flight_Route_Management_System
```

---

### 🔹 Run the Executable

```bash
./Flight_Route_Management_System
```

> 🪟 If using Windows, you can also double-click the `.exe` file to run.

---

## 📝 Usage

1. **Edit `flights.txt`**
   Format: `Source Destination Cost Time`

   ```
   DEL BOM 1500 2
   BOM BLR 1800 2
   DEL BLR 3200 4
   ```

2. **Run the program**
   Choose from the menu options to:

   * Display available routes
   * Find shortest path
   * Add/update routes
   * Exit

---

## ⚙️ Scalability & Performance

* 🚀 **Handles Thousands of Routes** without performance drop
* 🧠 **Optimized Data Structures** like adjacency lists and priority queues
* 🔁 Dynamic edge updates without reinitializing the graph
* 🧩 Can be integrated with **JSON/XML parsers**, **GUIs**, or **databases**

---

## 🤝 Contributing

1. Fork the repository
2. Create a new branch: `git checkout -b feature-name`
3. Commit your changes: `git commit -m "Added X feature"`
4. Push to branch: `git push origin feature-name`
5. Create a **Pull Request**

---

## 📜 License

This project is licensed under the **MIT License**.

---

📌 Found this helpful? **Star the repo** ⭐ and share it!

---
