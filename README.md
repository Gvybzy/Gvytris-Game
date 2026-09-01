# GVYTRIS

A neon-themed Tetris game built with Python and Pygame, created as a learning project.

## Description

GVYTRIS is a modern take on the classic Tetris game featuring a cyberpunk-inspired aesthetic with neon colors and smooth gameplay. This project was built to learn game development fundamentals, object-oriented programming, and the Pygame library.

## Features

- **7 Classic Tetrominoes**: I, O, T, S, Z, J, L pieces
- **Next Piece Preview**: See what's coming next
- **Ghost Piece**: Visual guide showing where pieces will land
- **Line Clear Animation**: Satisfying flash effect when clearing lines
- **Hard Drop & Soft Drop**: Instant drop or controlled descent
- **Level Progression**: Speed increases every 10 lines
- **Scoring System**: Points for line clears and hard drops
- **Pause Function**: Take a break anytime
- **Main Menu**: Clean UI with clickable buttons
- **7-Bag Randomizer**: Fair piece distribution (no long droughts)
- **Game Over Detection**: Proper game over screen with stats

## How to Play

### Controls

| Key | Action |
|-----|--------|
| ← → | Move piece left/right |
| ↑ | Rotate piece clockwise |
| ↓ | Soft drop (move down faster) |
| SPACE | Hard drop (instant drop) |
| P | Pause/Resume game |
| R | Restart (after game over) |
| ESC | Return to menu/Quit |

### Objective

Arrange falling tetromino pieces to create complete horizontal lines. Completed lines disappear, earning you points. The game ends when pieces stack up to the top of the board.

### Scoring System

| Action | Points |
|--------|--------|
| 1 Line | 100 |
| 2 Lines | 300 |
| 3 Lines | 500 |
| 4 Lines (Tetris) | 800 |
| Hard Drop | 2 per cell |

### Level System

- Start at Level 1
- Level increases every 10 lines cleared
- Falling speed increases with each level
- Level 1: 1000ms per fall
- Each level: -100ms (minimum 100ms)

## Installation

### Download Executable (No Python Needed)

1. Go to [Releases](https://github.com/Gvybzy/gvytris/releases)
2. Download `Gvytris-v1.0-Windows.zip`
3. Extract the ZIP file
4. Double-click `Gvytris.exe`
5. Play!
