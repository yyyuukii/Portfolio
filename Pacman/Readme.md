# 👻 Pacman AI Agents

**Course Project – UC Berkeley CS188: Artificial Intelligence**

## Overview

This project implements several AI agents to control Pacman in a grid-based environment.  
The agents use classical search algorithms, adversarial search, and reinforcement learning techniques to navigate the maze, collect food, and avoid ghosts.

The goal of the project is to explore different AI decision-making strategies and understand how search and learning algorithms behave in complex environments.

---

## Key Topics

This project covers several important concepts in artificial intelligence:

- **Search Algorithms**
  - Depth-First Search (DFS)
  - Breadth-First Search (BFS)
  - Uniform Cost Search (UCS)
  - A* Search

- **Adversarial Search**
  - Minimax
  - Alpha-Beta Pruning
  - Expectimax

- **Reinforcement Learning**
  - Q-Learning
  - Value Iteration
  - Feature-based Approximate Q-learning

---

## Environment

The Pacman environment consists of:

- a maze with walls and food pellets
- Pacman (the player agent)
- ghosts (adversarial agents)

Agents must choose actions that maximize long-term rewards while avoiding ghosts.

---

## Implemented Agents

### Search Agent
Uses classical search algorithms to find optimal paths through the maze.

### Minimax Agent
Models the game as an adversarial search problem where ghosts attempt to minimize Pacman’s score.

### Alpha-Beta Agent
Improves the efficiency of minimax using pruning techniques.

### Expectimax Agent
Handles stochastic ghost behavior by modeling their actions as probabilistic outcomes.

### Q-Learning Agent
Learns optimal policies through experience using reinforcement learning.

---

## Learning Outcomes

Through this project I gained experience in:

- implementing classical AI search algorithms
- designing adversarial search agents
- applying reinforcement learning methods
- evaluating agent performance in simulated environments

---

## Note

Due to course policy, the full source code cannot be made publicly available. However, the algorithms and implementation details can be discussed upon request.
