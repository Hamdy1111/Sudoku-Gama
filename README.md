# 4x4 Sudoku Solver Using Tabu Search with GUI

## Overview
This project provides a Python-based solver for 4x4 Sudoku puzzles using the **Tabu Search** algorithm. It features a graphical user interface (GUI) built with **Tkinter**, allowing users to interact with the puzzle, input initial values, and receive hints or complete solutions.

## Key Features
- 🧠 **Tabu Search Metaheuristic**: Avoids local optima by using a memory structure (tabu list) to guide the search.
- 🧩 **Sudoku Solver**: Automatically fills in the Sudoku grid based on input, respecting Sudoku rules.
- 💡 **Hint Function**: Reveals one correct cell at a time to assist the user.
- 🎨 **Interactive GUI**: Allows users to input initial values, request hints, and solve the full puzzle.

## How It Works
- The algorithm begins with a valid board respecting subgrid constraints.
- It iteratively reduces conflicts in rows and columns by swapping values.
- Recent swaps are recorded in a tabu list to avoid cycling.
- The process stops after a fixed number of iterations or when no conflicts remain.

## Usage
1. Clone the repository.
2. Run the Python script:
   ```bash
   python sudoku_tabu_gui.py
