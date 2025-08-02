# SCT_SD_3
Sudoku solver
# 🧠 Sudoku Solver - Python

This project is a simple Python-based **Sudoku Solver** that uses the **Backtracking Algorithm** to automatically solve any valid 9x9 Sudoku puzzle.

## 📌 Features

- Accepts a partially filled 9x9 Sudoku grid
- Fills in missing numbers using backtracking
- Displays the solved puzzle in the terminal

## 💻 How It Works

The algorithm tries numbers (1-9) in each empty cell:
1. Checks if the number follows Sudoku rules (row, column, and 3x3 subgrid)
2. If valid, moves to the next cell
3. If no number fits, it backtracks and tries a different number

## 🧾 Requirements

- Python 3
No additional libraries required.

## ▶️ How to Run

1. Clone or download this repository.
2. Open a terminal or command prompt.
3. Run the Python script:

```bash
 Example Puzzle
Input puzzle (0 represents an empty cell):
python sudoku_solver.py
5 1 7 6 0 0 0 3 4
2 8 9 0 0 4 0 0 0
3 4 6 2 0 5 0 9 0
6 0 2 0 0 0 0 1 0
0 3 8 0 0 6 0 4 7
0 0 0 0 0 0 0 0 0
0 9 0 0 0 0 0 7 8
7 0 3 4 0 0 5 6 0
0 0 0 0 0 0 0 0 0

Output Sample
Solved Sudoku:
5 1 7 6 9 8 2 3 4
2 8 9 1 3 4 7 5 6
3 4 6 2 7 5 8 9 1
6 7 2 8 4 9 3 1 5
1 3 8 5 2 6 9 4 7
9 5 4 7 1 3 6 8 2
4 9 5 3 6 2 1 7 8
7 2 3 4 8 1 5 6 9🙋‍♀️ Author

Mathumitha Balakrishnan
🎓 Computer Science Engineering Student
📬 Email:mathumithabalakrishnan11@gmail.com



