# United We Stand

## Project Overview
This project developed a controller for managing micro-organisms on a rectangular grid surrounded by harmful chemical deposits. The goal was to enable these organisms to fuse into a single entity through strategic movements while avoiding obstacles.

## Features
- Micro-organisms can be controlled to move within a grid.
- Fusing of organisms occurs when they occupy contiguous squares.
- Various search algorithms implemented:
  - Breadth-First Search (BFS)
  - Depth-First Search (DFS)
  - Iterative Deepening Search
  - Greedy Search
  - A* Search

## Implementation
- **Grid Generation**: Randomly generates a grid with micro-organism and obstacle placements.
- **Search Function**: Implements different search strategies to determine optimal movement plans.
- **Performance Comparison**: Analyzes and compares algorithms based on:
  - Run-time
  - Memory utilization
  - CPU usage

## Usage
To use this project:
1. Clone the repository.
2. Compile the Java classes.
3. Run the main program with desired parameters.

## Example Input
Grid Format: Width;Height; organismX1,organismY1,...; obstacleX1,obstacleY1,... Strategy: BF, DF, UC, ID, GR1, GR2, AS1, AS2 Visualize: true/false


## Output
The output includes:
- Movement sequence to reach the goal.
- Total cost of the solution.
- Number of nodes expanded during the search.

## Requirements
- Java Development Kit (JDK) version 8 or higher.

## License
This project is licensed under the MIT License.

## Acknowledgments
-Professor Haytham O. Ismail.
