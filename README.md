# 2048 Game in C

A simple terminal-based implementation of the classic 2048 puzzle game, written in pure C.

## Features

- 4×4 grid gameplay in the terminal
- Score tracking
- Undo last move
- Reset the game at any time
- Random tile spawning (2 or 4)

## Controls

| Key | Action |
|-----|--------|
| 1   | Move Up |
| 2   | Move Down |
| 3   | Move Left |
| 4   | Move Right |
| 5   | Undo |
| 6   | Reset |

## How to Build & Run

### Linux / macOS
```bash
gcc -o 2048 2048_Game_C.c
./2048
```

### Windows (MinGW)
```bash
gcc -o 2048.exe 2048_Game_C.c
2048.exe
```

## How to Play

Slide tiles in any direction. When two tiles with the same number collide,
they merge into one. Reach the **2048** tile to win!
The game ends when no moves are left.

## Project Structure
