Sudoku Solver Game:
What my Project will and will not do :
Functional Requirements: 
Input Processing: 
There should be 9*9 grid as input for user, with some cells containing digits from 1 to 9 and other cells designated as empty. 
 Validation: 
 There should be validation in any number placement by checking if that number is present in the same rows, same column, or same Sub-Grid, if it is then remove that number and check that whole process with other numbers from 1 to 9 until valid condition is met. 
Output: 
If completion has been successful until end of the grid, then there must be an output with a single valid 9*9 sudoku grid with all empty cells filled. 
Unsolvable puzzle handling: 
 If the solver determines that no valid solution exist for the given input, then it must notify the user that your given input is invalid, remove it and put any valid number. 
Non-Functional Requirements: 
Speed: 
The solver should find a valid solution and display the valid solution within a reasonable time, typically a few seconds even for difficult puzzles. 
Efficiency: 
The algorithm logic should be optimized to reduce computational complexity. Performance should be improved by using efficient valid techniques even in a worst case.  
         
           User interface features: 
UI must be easy to understand and use, with clear labelling. 
Grid display: 
A user- friendly graphical interface must display a 9*9 Grid, clearly highlighting a 3*3 Sub-Grids. 
Interactive input: 
The user should be able to interact with the grid to enter numbers into the empty cells, initial puzzle numbers should be non-editable. 
Solver action: 
A button or menu option should trigger the solver to find the solution for the current grid. 
Hint functionality: 
The application should provide an optional hint, such as showing the possible valid numbers for a selected cell. 
Input validation: 
System should immediately highlight incorrect user entries. 
Difficulty selection: 
System should generate new, random puzzles based on different difficulty levels (e.g. easy, medium, high). 
Usability: 
UI should be easy to understand for any user, system must provide clear feedback, indicating when it is solving, finding solution, or even if solution doesn’t exist. 
Reliability: 
The solver must always produce a correct solution, system must be able to handle unexpected or invalid input without crashing. 
Portability: 
System should run on multiple operating systems such as windows, linux, macOS. Maintainability: 
The codebase should be structured logically, with separations between the user interface, the solving algorithm, and the valid solution. And design should allow for future extensions, such as if we want to increase or decrease grid size, or different other variations like if we want to change sudoku rules (e. g, Diagonal Sudoku). 
# SUDOKU-SOLVER-GAME-GITHUB-TASK
