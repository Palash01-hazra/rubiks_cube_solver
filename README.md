# 🧩 Rubik’s Cube Solver

A command-line C++ program that solves the 3×3 Rubik’s Cube using multiple search algorithms:

- 🧠 BFS (Breadth-First Search)
- 🔍 DFS (Depth-First Search)
- 🔁 IDDFS (Iterative Deepening DFS)
- 🚀 Korf’s IDA* (Iterative Deepening A* with heuristic optimization)

---

## 🔗 GitHub Repository

[👉 GitHub Repo](https://github.com/Palash01-hazra/rubiks_cube_solver)

---

## 🚀 Features

- Solve any 3x3 Rubik's Cube configuration.
- Choose from multiple solving strategies.
- Pattern database support for optimal IDA* performance.
- Terminal output showing step-by-step solutions.

---

## 🧪 Algorithms Used

| Algorithm    | Description |
|--------------|-------------|
| **BFS**      | Guarantees shortest solution path, but consumes more memory. |
| **DFS**      | Explores deep paths quickly, not guaranteed to be optimal. |
| **IDDFS**    | Combines DFS depth with optimality of BFS. |
| **Korf’s IDA\*** | Best performance using heuristics + pattern databases. |

---

## 🛠 Installation

### 📥 Clone the Repository

```bash
git clone https://github.com/Palash01-hazra/rubiks_cube_solver.git
cd rubiks_cube_solver
