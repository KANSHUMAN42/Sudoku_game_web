# Sudoku_game_web
This is a web App of sudoku game .It has two button "Get New Puzzle"and "Solve".GetNew Puzzle button generates a new
sudoku puzzle each time ,
And solve function solves the puzzle.
Api is called via http request  and the automatically received json file of puzzle is updated to the board array.
The api called automaticatally generates,grades and validate the puzzle.This is link"https://sugoku.herokuapp.com/"
Later with the help of recursion and back tracking algorithm ,this sudoko is being solved.
It implements function:

SolveSudoku - Called so because it quickly checks horizontally, vertically and in the nine grid box for possible options.
If only one possible solution remains, it adds the value to the square.

Guess - It fills an empty square with a possible, non-conflicting value. If the puzzle is solved (completely filled),
it validates to see if it correct. If not, it goes back and fills the square with another possible value.
It recursively fills in and backtracks until the puzzle is complete
