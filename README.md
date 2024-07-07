
# Sudoku Solver and Generator

This repository contains a Sudoku solver and generator implemented in C++. The solver can solve a given Sudoku puzzle, and the generator can create new Sudoku puzzles.

## Files

### `sudoku.h`
Header file containing the declarations for the Sudoku solver and generator functions and classes.

### `sudoku_generator.cpp`
Source file that implements the Sudoku puzzle generator. It creates a new Sudoku puzzle with a unique solution.

### `sudoku_solver.cpp`
Source file that implements the Sudoku solver. It solves a given Sudoku puzzle using backtracking.

### `sudoku_solver.exe`
Executable file for the Sudoku solver. Run this file to solve a Sudoku puzzle.

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/Shubham246763/Sudoku-Solver-Generator.git
    cd Sudoku-Solver-Generator
    ```

2. Compile the source files:
    ```sh
    g++ -o sudoku_solver sudoku_solver.cpp
    g++ -o sudoku_generator sudoku_generator.cpp
    ```

3. Alternatively, you can use the provided executable file `sudoku_solver.exe` to solve puzzles.

## Usage

### Sudoku Solver

1. Run the Sudoku solver executable:
    ```sh
    ./sudoku_solver
    ```

2. Input the Sudoku puzzle in the format specified in the code (usually a 9x9 grid).

3. The program will output the solved Sudoku puzzle.

### Sudoku Generator

1. Run the Sudoku generator executable:
    ```sh
    ./sudoku_generator
    ```

2. The program will generate a new Sudoku puzzle and output it.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
.
