
# Sudoku Solver

This is a small Python project where I tried to make a program that can solve a 9x9 Sudoku puzzle. I mainly did it to understand how backtracking works and to practice working with 2D lists in Python.

## How it works

The puzzle is stored as a list of lists.  
Zeroes represent empty spaces.

The solver:

- finds the next empty cell
- tries numbers from 1 to 9
- checks if the number follows the Sudoku rules
- if it’s not valid, it tries a different one
- if nothing works, it backtracks to previous cells

If the puzzle can be solved, it fills in the whole board.
