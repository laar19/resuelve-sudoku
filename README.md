# Solve sudoku

<img src="https://img.shields.io/badge/GPL-v3-green"/>

Implementation of a genetic algorithm, using the **DEAP** framework, to solve a sudoku with 17 known numbers.
The **fitness** function is proposed as a minimization problem, it consists in evaluating that the numbers are not repeated in the rows, columns or sectors, otherwise, the fitness is increased in one unit, so the ideal fitness for a solved sudoku is **0.0**.   
### Unfortunately the algorithm stagnates in local minimums and does not reach the solution.   
## Any contribution or suggestion will be very helpful
