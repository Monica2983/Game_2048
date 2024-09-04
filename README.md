# Game_2048 in C Programming

## Overview

2048 is an addictive sliding block puzzle game where your goal is to combine tiles with the same number to reach the elusive 2048 tile. The game is played on a 4x4 grid, similar to Sudoku, and involves strategic movement and a bit of mathematical thinking.

### How It Works

- **Tiles & Numbers**: The game starts with two tiles, each numbered either 2 or 4. Every move slides all tiles on the grid in one direction (up, down, left, or right). When two tiles with the same number collide, they merge into one tile with the sum of their numbers.
- **Objective**: Keep merging tiles to create larger numbers until you reach the 2048 tile. However, the game continues beyond 2048, challenging you to achieve even higher scores.
- **Game Over**: The game ends when no more moves are possible, meaning no tiles can be merged and the grid is full.

### Tips & Tricks

1. **Take It Slow**: Rushing often leads to mistakes. Plan your moves carefully, considering how each move will affect the entire board.
2. **Work The Corners**: A popular strategy is to keep your highest tile in one of the corners. This helps organize the board and makes it easier to merge other tiles.

### Features

- **Classic 4x4 Grid**: The traditional 2048 experience with a grid size that's just right for challenging gameplay.
- **Simple Controls**: Easy-to-use keyboard controls (arrows) for intuitive tile sliding.
- **Scoring System**: Track your score as you merge tiles, and aim to surpass your personal best.

### How to Play

1. **Compile the Game**: Use a C compiler to compile the source code.
2. **Start Playing**: Run the compiled program, and use the arrow keys to move the tiles.
3. **Merge & Score**: Keep merging tiles until you reach 2048 or beyond.

### Getting Started

Clone the repository and follow the instructions in the README to get the game up and running on your system.

```bash
git clone https://github.com/yourusername/Game_2048.git
cd Game_2048
gcc -o Game_2048 2048.c   # Compile the source code
./Game_2048               # Run the compiled program

```

### Contributing

If you'd like to contribute, please fork the repository, make your changes, and submit a pull request. All contributions are welcome!

---


