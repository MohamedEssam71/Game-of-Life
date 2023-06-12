# Game-of-Life

Implement the Game of Life cellular automaton proposed by John Horton Conway. The Game of Life takes place on a grid of square cells that can be in one of two states: dead or alive. The game follows certain rules, and on each step, cells interact with their adjacent neighbors. The following transactions occur:

- Any live cell with fewer than two live neighbors dies, as if caused by underpopulation.
- Any live cell with two or three live neighbors lives on to the next generation.
- Any live cell with more than three live neighbors dies, as if by overpopulation.
- Any dead cell with exactly three live neighbors becomes a live cell, as if by reproduction.

The status of the game on each iteration should be displayed on the console. You can choose a reasonable size for the grid, such as 20 rows x 50 columns, 30 x 30 columns, or 20 x 20.

## Universe Class

Implement a class called `Universe` with the following functions:

- `initialize(...)`: Generates a starting layout for the game.
- `reset(...)`: Sets all the cells as dead.
- `count_neighbors(...)`: Returns the number of alive neighbors for a given cell.
- `next_generation(...)`: Produces a new state of the game based on the transition rules.
- `display(...)`: Shows the game status on the console. It is recommended to erase the screen and rewrite, as graphics are not needed.
- `run(...)`: Starts the game for a certain number of runs.

You can add more functions if needed.

## How to Play

1. Initialize the game by generating a starting layout.
2. Use the `display` function to show the initial state of the game on the console.
3. Run the game for a certain number of generations using the `run` function.
4. On each iteration, the `next_generation` function will calculate the new state of the game based on the transition rules.
5. After each iteration, use the `display` function to show the updated state of the game on the console.
6. Repeat steps 4 and 5 for the desired number of runs.

Remember, this implementation does not require graphics. The game will be displayed and played on the console.


