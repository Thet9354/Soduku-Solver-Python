### Sudoku Solver GUI

#### Overview:
This Python project leverages the `pygame` library to create a Graphical User Interface (GUI) for automatically solving Sudoku puzzles. The GUI provides an intuitive way for users to input Sudoku puzzles and view the solutions in real-time. The solver utilizes a backtracking algorithm to systematically find valid solutions to Sudoku puzzles.

#### Installation:
Before running the script, make sure to install the `pygame` library:

```bash
pip install pygame
```

#### Usage:
1. Run the Python script.
2. The GUI window will appear, featuring a Sudoku grid where users can input puzzle values.
3. Click on a cell to select it, then use the number keys (1-9) to input values from the keyboard.
4. Press the Enter key to initiate the solving process.
5. The solver will attempt to find a solution for the provided Sudoku puzzle.
6. Once a solution is found, the solved Sudoku grid will be displayed in the GUI.

#### Features:
- **User-Friendly GUI**: The GUI allows users to interactively input Sudoku puzzles and view the solutions.
- **Real-Time Feedback**: Users can see the solving process in real-time as the solver progresses.
- **Backtracking Algorithm**: The solver utilizes a backtracking algorithm to efficiently find valid solutions to Sudoku puzzles.
- **Error Handling**: The GUI provides visual feedback for invalid inputs and prevents users from inputting incorrect values.

#### Example:
- Input an unsolved Sudoku puzzle by clicking on the cells and entering values using the number keys.
- After initiating the solving process, observe how the solver systematically fills in the grid until a solution is found.
- Once solved, the GUI will display the completed Sudoku grid, indicating a successful solution.

#### Notes:
- Ensure that the input Sudoku puzzle adheres to Sudoku rules, i.e., each row, column, and 3x3 subgrid must contain the numbers 1 to 9 without repetition.
- The solver may take longer to find solutions for complex or challenging Sudoku puzzles.
- Users can reset the puzzle or clear individual cells as needed using the GUI controls.

Enjoy using the Sudoku Solver GUI for solving Sudoku puzzles with ease!
