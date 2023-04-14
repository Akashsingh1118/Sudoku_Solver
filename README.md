# Sudoku_Solver
Sudoku is a logic-based, combinatorial number-placement puzzle. In classic Sudoku, the objective is to fill a 9 × 9 grid with digits so that each column, each row, and each of the nine 3 × 3 subgrids that compose the grid contain all of the digits from 1 to 9.

# Algorithm
Solver is based upon recursion and backtracking algorithms.
Backtracking is an algorithmic technique for solving problems recursively by trying to build a solution incrementally, one piece at a time, removing those solutions that fail to satisfy the constraints of the problem at any point in time.
In the context of the project, we start by checking whether a particular number can be placed in the current cell ,if yes then we place that number in this cell and we recursively solve for all the other unoccupied cells.Here, at any point if we reach a state which is not going to give the possible outcome , we backtrack and eliminate all the calls which can happen from that particular call. Thus, minimizing the answer set and reducing the time of search.

# Working of the Sudoku Solver
[screen-capture (1).webm](https://user-images.githubusercontent.com/101987244/232132118-f6d7cecf-023d-4f6c-a3bb-8a7ce69b6206.webm)


