<div align="center">
  
# Conway's Game of Life

**A Python implementation of the classic cellular automaton zero-player game.**

Simulates life. Evolves patterns. Zero unrestricted actions.

![Python](https://img.shields.io/badge/PYTHON-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pygame](https://img.shields.io/badge/PYGAME-2.x-5C3EE8?style=for-the-badge&logo=python&logoColor=white)
![Git](https://img.shields.io/badge/GIT-LATEST-F05032?style=for-the-badge&logo=git&logoColor=white)

</div>

<br>

## 📖 About The Project

This is an interactive implementation of **Conway's Game of Life**, a famous cellular automaton devised by the British mathematician John Horton Conway in 1970. It is a zero-player game, meaning its evolution is determined by its initial state, requiring no further input. 

This project goes a step further by allowing the user to pause, edit the board, adjust the simulation speed, and randomly generate life!

<div align="center">
  <img src="Game%20of%20Life%20Demo.png" alt="Game of Life Screenshot" width="800">
</div>

## ✨ Features

- **Classic Simulation**: Accurately follows all the classic rules of Conway's Game of Life.
- **Interactive Grid**: Click to toggle individual cells to create your own custom patterns.
- **Dynamic Speed Control**: Speed up or slow down the simulation in real-time.
- **Random Generation**: Instantly populate the grid with a random state to see what evolves.
- **Clear & Reset**: Wipe the board clean to start fresh.

## 🎮 Controls & User Input

You have full control over the simulation using your mouse and keyboard:

| Action | Control | Description |
| :--- | :--- | :--- |
| **Start Simulation** | `ENTER` | Unpauses and starts the Game of Life simulation. |
| **Pause Simulation** | `SPACE` | Freezes the current state of the simulation. |
| **Toggle Cell** | `Mouse Click` | Click any cell to manually toggle it alive or dead. |
| **Increase Speed** | `F` | Increases the simulation FPS (Frames Per Second). |
| **Decrease Speed** | `S` | Decreases the simulation FPS (minimum 2 FPS). |
| **Random Fill** | `R` | Fills the grid with a random configuration of live/dead cells. |
| **Clear Grid** | `C` | Kills all cells, leaving a blank canvas. |

## 🛠️ Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/HiteshDokku/Game-of-Life.git
   cd Game-of-Life
   ```

2. **Install the required dependencies:**
   Make sure you have Python installed, then install Pygame:
   ```bash
   pip install pygame
   ```

3. **Run the simulation:**
   ```bash
   python main.py
   ```

## 📜 The Rules of Life
The universe of the Game of Life is a two-dimensional orthogonal grid of square cells. Every cell interacts with its eight neighbors, following these simple rules:
1. **Underpopulation:** Any live cell with fewer than two live neighbors dies.
2. **Survival:** Any live cell with two or three live neighbors lives on to the next generation.
3. **Overpopulation:** Any live cell with more than three live neighbors dies.
4. **Reproduction:** Any dead cell with exactly three live neighbors becomes a live cell.
