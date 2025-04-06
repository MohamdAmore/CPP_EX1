# CPP_EX1 - Graph Algorithms Project

## 📚 Description

This project implements core graph data structures and algorithms from scratch in C++, including:

- Graph representation using adjacency lists.
- BFS (Breadth-First Search)
- DFS (Depth-First Search)
- Dijkstra’s Shortest Path
- Prim’s Minimum Spanning Tree
- Kruskal’s Minimum Spanning Tree

It also includes custom implementations of data structures like:
- Queue
- Priority Queue
- Union-Find (Disjoint Set)

All code is implemented **without using STL**, based on the course requirements.

---

## 📁 File Structure

| File                  | Description                                 |
|-----------------------|---------------------------------------------|
| `main.cpp`            | Runs and demonstrates graph algorithms.     |
| `tests.cpp`           | Unit tests using doctest.h                  |
| `graph.cpp/hpp`       | Graph class with all operations.            |
| `Algorithms.cpp/hpp`  | BFS, DFS, Dijkstra, Prim, Kruskal.          |
| `Queue.cpp/hpp`       | Basic queue implementation.                 |
| `PriorityQueue.cpp/hpp` | Min-heap based priority queue.           |
| `UnionFind.cpp/hpp`   | Union-Find data structure.                  |
| `doctest.h`           | Header-only testing framework.              |
| `Makefile`            | Automates building, testing, and Valgrind.  |

---

## 🛠️ Build Instructions

Make sure you're using **Linux** or **WSL/Ubuntu**, and have `g++` and `make` installed.

```bash
make Main     # Builds the main program (outputs `program`)
make test     # Builds and runs tests
make valgrind # Runs valgrind memory check on the main program
make clean    # Removes all generated files
```

---

## 🚀 Running the Program

```bash
./program
```

This will output the graph structure and the result of all algorithms.

---

## ✅ Running Tests

```bash
make test
```

All tests are in `tests.cpp`, using the `doctest` framework.

---

## 🧪 Memory Check (Valgrind)

```bash
make valgrind
```

Ensures the program runs without memory leaks or invalid access.

---

## 🔒 Constraints

- STL **is not used**.
- Code is written in **C++17**.
- Tested using **g++ on Ubuntu**.

---


