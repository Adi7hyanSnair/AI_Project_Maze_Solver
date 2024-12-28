# Multi-Agent Maze Solver

This project demonstrates a multi-agent maze solver implemented in Python using Pygame. 
It employs Conflict-Based Search (CBS) to optimize the pathfinding process 
while resolving conflicts among multiple agents. The algorithm uses A* search as a low-level pathfinding strategy.


## Features

- Dynamic Maze: Generate random mazes with walls that can be modified during runtime.
- Multi-Agent Support: Add multiple agents with unique start positions and paths.
- Conflict Resolution: Use CBS to resolve conflicts between agents' paths dynamically.
- Interactive Controls: Easily set start points, goals, and modify walls in the maze.


## Prerequisites

- Python 3.7 or higher
- Pygame library


## Controls

- Left Mouse Button: Add walls.
- Right Mouse Button: Remove walls.
- Keyboard:
  - S: Set start points for agents.
  - E: Set the goal position.
  - SPACE: Start the pathfinding process.
  - R: Reset the maze and generate a new random maze.


## How It Works

### Algorithms Used

#### A* Search:
- Heuristic-based algorithm for finding the shortest path.
- Uses the Manhattan distance as the heuristic.
  
#### Conflict-Based Search:
- Handles path conflicts between agents by adding constraints.
- Re-plans individual agent paths to resolve conflicts.
  
#### Core Components
- Random Maze Generator: Creates a grid-based maze with a specified density of walls.
- Visualization: Real-time visualization of the agents’ movements and conflicts.


## Contributors

- ##### Adith Anish [AM.SC.U4AIE23103]
- ##### Adithyan S [AM.SC.U4AIE23104]
- ##### Mohamed Hani [AM.SC.U4AIE23130]
- ##### Sravan Chandrakanth [AM.SC.U4AIE23152]


Feel free to contribute by submitting issues or pull requests!

