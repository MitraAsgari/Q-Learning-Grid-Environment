# Q-Learning Grid Environment

This project demonstrates the implementation of a Q-Learning algorithm to solve a grid-based environment problem. The environment consists of a 4x4 grid where an agent learns to navigate from the starting position to the goal position by receiving rewards or penalties based on its actions.

## Overview

- **Environment**: A 4x4 grid where the agent starts at the top-left corner and aims to reach the bottom-right corner.
- **Actions**: The agent can move in four directions: up, down, left, and right.
- **Reward Structure**: The agent receives a penalty of -1 for each step taken, and a reward of 0 when it reaches the goal.

## Files

- `main.py`: Contains the implementation of the Grid Environment, Q-Learning Agent, and the training procedure.
- `README.md`: This file, provides an overview and instructions for the project.

## Dependencies

To run the code, you need to install the following Python libraries:

- `numpy`: For numerical operations
- `matplotlib`: For plotting graphs

You can install the required libraries using `pip`:

  ```bash
    pip install numpy matplotlib

