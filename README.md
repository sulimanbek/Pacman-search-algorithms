# AIN2001 — Assignment 1: Search Algorithms (Pacman)

This repository contains my solutions for **AIN2001 Fall 2023 Assignment 1**, based on the UC Berkeley **CS188 Pacman Search** project.

The goal is to implement classic search algorithms and heuristics to help Pacman navigate mazes and solve increasingly complex search tasks.

## What I Implemented

### In `search.py`
- Depth-First Search (DFS)
- Breadth-First Search (BFS)
- Uniform Cost Search (UCS)
- A* Search (A*)

### In `searchAgents.py`
- `CornersProblem` state representation + successors
- `cornersHeuristic` (consistent heuristic)
- `foodHeuristic` (consistent heuristic)
- `AnyFoodSearchProblem` goal test
- `findPathToClosestDot` for `ClosestDotSearchAgent`

## Project Structure

Typical structure:
- `search/` — Pacman project source code (framework + my changes)
- `layouts/` — Maze layouts
- `test_cases/` — Autograder test cases
- `autograder.py` — Local autograder script

> Files edited: `search.py`, `searchAgents.py`

## Requirements
- Python 3.x

## How to Run

### 1) Run Pacman normally
```bash
cd search
python pacman.py
