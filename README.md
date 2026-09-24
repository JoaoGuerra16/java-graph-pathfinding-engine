# Java Graph & Pathfinding Engine

## 📌 Project Overview
This repository contains a custom Java graph and pathfinding engine. It models a mutable domain as a graph, calculates routes over weighted connections, and exposes the resulting state through a backend API. 

The core architectural focus was to build all Abstract Data Types (ADTs) from scratch, completely bypassing native `java.util.Collection` implementations, to maintain absolute control over memory, traversal, and algorithm behavior.

---

## 🚀 Core Architecture & Features
- **Custom ADT Layer:** Generic, from-scratch implementations of lists, queues, stacks, trees, and heaps.
- **Graph & Network Model:** Adjacency-matrix graph representations with dynamic capacity expansion.
- **Pathfinding & Routing:** BFS, DFS, and shortest-path calculation (Dijkstra-style relaxation) over weighted, directional connections.
- **Data Persistence:** JSON-based hydration of graph topology, entities, and scenario metadata using `json-simple`.
- **Backend API:** Stateful model handling graph mutation, neighbor queries, and route selection.

---

## ⚙️ Tech Stack
- **Language:** Java 17
- **Architecture:** Generic ADT layer, Graph Algorithms, OOP concepts
- **Build System:** Gradle
- **Persistence:** JSON (`json-simple`)
- **Testing:** JUnit Jupiter 5
