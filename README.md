# Exploring High-Dimensional Tic-Tac-Toe
Authors: Camden Weber, Daniel Mendelevitch, Niket Patel, Elaine Fan, and Thomas Park

## Project Overview
This project investigates the game theory behind Tic-Tac-Toe and its extensions into higher dimensions. The study uses algorithms like MiniMax and Monte Carlo Tree Search (MCTS) to explore optimal strategies and improve computational efficiency in solving high-dimensional Tic-Tac-Toe games.

## Abstract
This study explores the game theory behind Tic-Tac-Toe and its variations in higher dimensions. We use the MiniMax algorithm to create an optimal agent for the standard 3×3 Tic-Tac-Toe and extend this approach to higher dimensions using evaluation functions. We observe that higher-dimensional boards tend to result in more draws and provide analytical reasoning behind this phenomenon. We introduce the longest-chain board evaluation function, which generalizes well to larger boards. Additionally, we evaluate this function for 3D boards and explore methods to improve computational efficiency, such as Alpha-Beta pruning and Monte Carlo Tree Search (MCTS).

## Problem Statement
Optimal game-playing poses a significant challenge for humans due to the complexity and vast number of possible states in games like Tic-Tac-Toe. While the 3×3 board is solved, extending the game to 3×3×3 or larger boards complicates optimal play due to the exponential increase in possible states. This project investigates various game-playing algorithms and their effectiveness in solving high-dimensional Tic-Tac-Toe. We aim to determine the best-performing algorithms, their computational efficiency, and scalability as the board size and dimensions increase.

## Mathematical Model
MiniMax - The MiniMax algorithm is a decision rule used for minimizing the possible loss for a worst-case scenario. In this project, we implement MiniMax to explore optimal strategies for Tic-Tac-Toe.


## What we investigated
N × N Tic-Tac-Toe
Random Agent Behavior in N × N Tic-Tac-Toe
We analyze the behavior of a random agent in N × N Tic-Tac-Toe to establish a baseline for performance.

MiniMax for N × N Tic-Tac-Toe
We apply the MiniMax algorithm to N × N boards and evaluate its performance.

N × N × N Tic-Tac-Toe
Random Agent Behavior in N × N × N Tic-Tac-Toe
We extend our analysis to 3D Tic-Tac-Toe, examining the performance of a random agent.

MiniMax for N × N × N Tic-Tac-Toe
We implement and evaluate the MiniMax algorithm for 3D boards.

## Improvements
Monte Carlo Tree Search - We explore the use of Monte Carlo Tree Search (MCTS) as an alternative to MiniMax and evaluate its performance.

Alpha-Beta Pruning - We implement Alpha-Beta pruning to improve the efficiency of the MiniMax algorithm and reduce computational complexity.

## Conclusion
Our study demonstrates the effectiveness of MiniMax in solving high-dimensional Tic-Tac-Toe and highlights the benefits of evaluation functions and pruning techniques in improving computational efficiency. While MCTS underperforms relative to MiniMax, it offers insights into alternative approaches for complex game-solving tasks.

