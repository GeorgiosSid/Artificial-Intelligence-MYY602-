# Artificial Intelligence (MYY602) – Projects

This repository contains the programming assignments completed for the **Artificial Intelligence (MYY602)** course at the **University of Ioannina** during the **Spring Semester 2023**.

## Repository Structure
- `exercise_1_labyrinth/`: 
  - Implementation of **Labyrinth Search** using **Uniform Cost Search (UCS)** and **A\*** algorithms.
  - Includes:
    - Source code (`Labyrinth.java`, `Cell.java`, `MinPQ.java`).
    - report (`.pdf`).
- `exercise_2_game/`:
  - Implementation of a **two-player strategic game** using the **Minimax algorithm** (without α-β pruning).
  - Includes:
    - Source code (`Game.java`, `Grid.java`).

## Exercise 1 – Labyrinth Navigation
The task was to implement a pathfinding algorithm for a robot navigating a randomly generated NxN labyrinth:
- Each cell is either free or blocked with a probability `p`.
- The robot moves horizontally, vertically, or diagonally to adjacent cells at a cost of 1.
- A special "teleportation" move is allowed from the bottom-left to top-right cell (or vice-versa) at a cost of 2.
- Both **Uniform Cost Search (UCS)** and **A\*** algorithms are implemented and compared.

The solution prints:
- The labyrinth with the start (S), goal (G), and found path.
- The cost of the path.
- The number of node expansions.
- A full analysis of the heuristic for A\* is included in the report.

## Exercise 2 – Strategic Two-Player Game
The second assignment implements a game where:
- Players (`MAX` and `MIN`) alternately place symbols (X for MAX, O for MIN) on a 4x3 grid.
- The game ends if a winning triplet (`XOX` or `OXO`) is formed horizontally, vertically, or diagonally.
- The player `MAX` uses the **Minimax algorithm** (pure, without α-β pruning) to play optimally.

The program:
- Builds the game tree recursively at each move.
- Makes the optimal move based on the minimax evaluation.
- Describes the rules, evaluation functions, and design in the report.
- 
## Team Members
- Modiotis Athanasios
- Bonitsis Pantelis
- Sidiropoulos Georgios


