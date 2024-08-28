# Tetris Game

This repository contains the source code for a Tetris game implemented in C++ using the [raylib](https://www.raylib.com/) library. The game features classic Tetris gameplay mechanics, smooth input handling, and engaging graphics, ensuring a fun experience across all platforms.

## Features

- **Game Mechanics**: Classic Tetris gameplay with seven distinct tetrominoes (`I`, `J`, `L`, `O`, `S`, `T`, `Z`), each with unique rotations and movements.
- **Input Handling**: Responsive controls for moving, rotating, and dropping blocks.
- **Graphics Rendering**: Smooth rendering of game blocks and grid using raylib, with custom colors and fonts.
- **Platform Support**: Compatible with Windows, macOS, and Linux, providing a seamless experience on all platforms.
- **Sound Effects and Music**: Background music and sound effects enhance the gaming experience.

## Getting Started

### Prerequisites

To compile and run this project, you need:

- A C++ compiler (GCC, Clang, or MSVC)
- [raylib](https://www.raylib.com/) library installed on your system
- [CMake](https://cmake.org/) (optional, for easier building)

### Building the Project

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/tetris-game.git
    cd tetris-game
    ```

2. Compile the project:

    Using g++:
    ```bash
    g++ -o tetris main.cpp game.cpp grid.cpp block.cpp position.cpp -lraylib -lopengl32 -lgdi32 -lwinmm
    ```

## Controls

- **Left Arrow**: Move the block left
- **Right Arrow**: Move the block right
- **Down Arrow**: Drop the block faster
- **Up Arrow**: Rotate the block
- **Any Key**: Restart the game after a game over

## Code Overview

- `main.cpp`: Handles the game loop, window management, and rendering.
- `game.cpp` and `game.h`: Implements the game logic, including block movement, rotation, and grid management.
- `grid.cpp` and `grid.h`: Manages the Tetris grid, drawing, and row clearing.
- `block.cpp` and `block.h`: Defines the block shapes, rotations, and positions.
- `position.cpp` and `position.h`: Represents the position of blocks on the grid.
- `colors.h`: Contains color definitions used in the game.

