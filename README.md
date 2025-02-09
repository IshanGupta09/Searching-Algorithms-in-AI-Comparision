# 🚀 AI Search Algorithms Comparison

## 📌 Project Overview
This project implements and compares various **informed** and **uninformed** search algorithms used in Artificial Intelligence. The goal is to analyze their performance, complexity, and efficiency in solving different search problems.

## 🔍 Implemented Algorithms

### 🔹 **Uninformed Search Algorithms** (Blind Search)
- 📌 **Breadth-First Search (BFS)**
- 📌 **Depth-First Search (DFS)**
- 📌 **Bidirectional Search (BLS)**
- 📌 **Iterative Deepening Depth-First Search (IDDFS)**

### 🔹 **Informed Search Algorithms** (Heuristic-Based Search)
- 🎯 **A* Search**
- 🎯 **Hill Climbing**
- 🎯 **Simulated Annealing**

## 🛠️ Tech Stack
- **Python** 🐍
- **NetworkX** (Graph Manipulation)
- **Matplotlib** (Visualization)
- **Heapq** (Priority Queue Handling)
- **Time Module** (Performance Analysis)

## 📂 Project Structure
```
📁 AI_Search_Algorithms
 ├── 📄 search_algorithms.py      # Core implementations of search algorithms
 ├── 📄 graph.py                  # Graph class with dynamic creation based on input
 ├── 📄 main.py                    # Execution and testing of algorithms
 ├── 📄 requirements.txt           # Required dependencies
 ├── 📄 README.md                  # Project Documentation
```

## 🎯 Features & Highlights
✅ **Graph-Based Implementation**: Dynamically creates graphs based on user preferences (heuristic/non-heuristic, weighted/non-weighted, directed/undirected).

✅ **Performance Analysis**: Compares execution time and efficiency of different algorithms.

✅ **Local Search Optimization**: Simulated Annealing overcomes the limitations of Hill Climbing.

✅ **Algorithm Complexity & Optimality Insights**.

## 🚀 Getting Started
### 🔹 Prerequisites
Ensure you have **Python 3.x** installed along with required dependencies.
```bash
pip install -r requirements.txt
```

### 🔹 Running the Project
To execute the search algorithms, run:
```bash
python main.py
```

## 📊 Results & Observations
- BFS guarantees an optimal solution but can be memory-intensive.
- DFS explores deep but may not always find an optimal path.
- A* provides efficient pathfinding using heuristics.
- Hill Climbing faces local maxima issues, improved by Simulated Annealing.

## 📌 Conclusion
This project enhances the understanding of search strategies, their applications, and efficiency in different problem-solving scenarios. Future improvements could include **real-world dataset integration** and **GUI-based visualization**.

## 🌟 **Contributions & Feedback are Welcome!** 🚀
