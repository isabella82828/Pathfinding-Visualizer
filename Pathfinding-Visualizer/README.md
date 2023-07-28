# Pathfinding Visualizer
A pathfinding visualizer made in Python and Pygame. 


## Features
* Visualizes popular pathfinding algorithms such as Dijkstra's and A*.
* Visualizes popular maze generation algorithms like Recursive division and Prim's algorithm.
* Step-by-step animation of the search process, allowing you to see how the algorithms work.


## Supported Algorithms
The following pathfinding algorithms are currently supported in this visualizer:

1. Depth First Search (DFS): A traversal-based algorithm that goes as far as possible along each branch before backtracking. Not commonly used for pathfinding.
2. Breadth First Search (BFS): A traversal-based algorithm that explores all neighbors of a node before moving on to the next level. Guaranteed to find the shortest path in unweighted graphs.
3. Greedy Best First Search: A heuristic search algorithm that prioritizes visiting nodes closest to the goal. Not guaranteed to find the shortest path, but often faster.
4. A* Search: A heuristic search algorithm that combines the strengths of BFS and greedy best first search. Efficient for many types of graphs.
5. Dijkstra's Search: A shortest path algorithm that uses a priority queue to prioritize visiting nodes with the smallest known cost. Guaranteed to find the shortest path in weighted graphs.

## Usage
- Run `python3 run.pyw` if on Linux or Mac
- Run `python run.pyw` if on Windows

