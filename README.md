# Sudoku-Solver
My attempt at a sudoku solver using Jupyter Notebook. This uses a brute force technique. It goes through each point and puts number in the position.
It then tests this number for any conflicts in its row, column and block. If there are no conflicts it moves onto the next point. If there is a 
conflict it will try the next number.

Currently the functions all work but I need a backtracking function. The purpose of this function would be to see if a point currently has no solution
and then go to the previous point and see if changing that will fix the problem. If this does not work it will move back another step until it finds a 
solution. I am still trying to get this function to work.
