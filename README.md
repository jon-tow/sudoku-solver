# Sudoku Solver
A sudoku solver implemented with backtracking and useful pruning of
solution search space.
Pruning decisions:
  - Most Constrained Square Selecton. Used to select the next sudoku grid cell 
    to fill but under the constraint that said cell is the most constrained of 
    all empty cells.

Note: Looking to implement look ahead pruning.

## Screenshot
![Sudoku Solver](sudoku-solver.png)

## Built with
  * Vanilla-js
  * HTML5
  * CSS3

## Recommended readings on Backtracking
- [Algorithm Design Manual]()
