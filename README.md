# Sudoku Game

This Python script allows users to play Sudoku using a graphical user interface (GUI) built with Tkinter. Sudoku is a popular logic-based puzzle game where the objective is to fill a 9x9 grid with digits so that each column, each row, and each of the nine 3x3 subgrids contains all of the digits from 1 to 9.


### Features:

- **User-friendly Sudoku Interface**: This game provides a user-friendly interface for playing Sudoku puzzles generated by the code.
- **Interactive Puzzle Solver**: The game offers the functionality to input a custom Sudoku puzzle and obtain its solution.
- **Timer**: A timer keeps track of the time taken to solve the puzzle.
- **Leaderboard**: Records the time taken by each player to complete the puzzle and displays the leaderboard.

## How to Play:

1. **Player Registration**:
   - When the script is executed, it prompts the player to register by entering their name.
   - The player is required to enter their name in a text entry field provided by the GUI.
   - Once the name is entered, the player clicks the "Submit" button to proceed.

2. **Sudoku Game Interface**:
   - After registration, the Sudoku game interface opens.
   - The interface displays options for the player:
     - Play Game: Starts a new Sudoku game.
     - Instructions: Provides instructions on how to play Sudoku.
     - Leaderboard: Displays the top players' times.
     - Sudoku Solver: Solves the Sudoku puzzle automatically.
     - Exit: Closes the game.

3. **Playing the Game**:
   - Clicking the "Play Game" button generates a new Sudoku puzzle.
   - The player is presented with a 9x9 grid with some cells pre-filled.
   - The player can click on any empty cell and enter a number from 1 to 9 using the keyboard.
   - After entering a number, the player can click the "Check" button to verify their solution.
   - Correctly filled cells are highlighted in green, while incorrect cells are highlighted in red.
   - If the player fills all cells correctly, a congratulatory message is displayed, and the player's time is recorded.

4. **Instructions**:
   - Clicking the "Instructions" button opens a new window with instructions on how to play Sudoku.
   - The instructions explain the rules of Sudoku and how to use the GUI interface to play the game.

5. **Leaderboard**:
   - Clicking the "Leaderboard" button displays the top players' times in a separate window.
   - The leaderboard shows the names of the players along with their completion times in minutes.

6. **Sudoku Solver**:
   - Clicking the "Sudoku Solver" button solves the Sudoku puzzle automatically.
   - The solver algorithm fills in the empty cells with the correct numbers.
   - Once the puzzle is solved, the solution is displayed to the player.

7. **Exiting the Game**:
   - Clicking the "Exit" button closes the Sudoku game interface and terminates the script.

## Dependencies:

- Python 3.x
- Tkinter library for GUI
- Pillow (PIL Fork) for image handling (`pip install Pillow`)
- openpyxl for Excel interaction (`pip install openpyxl`)

## Contributing:

Contributions to this project are welcome. If you have any suggestions, bug fixes, or feature enhancements, feel free to submit a pull request. 
