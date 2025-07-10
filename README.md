# a-level-resources
Projects for using Flock XR to introduce A-level Computer Science concepts

## [Pathfinding Game](https://flipcomputing.github.io/a-level-resources/pathfinding.html)

The goal of this game is to find the shortest path between two nodes of a graph. The starting node is shown in the orange, and the target node is shown in purple. You can choose your path by walking to the orange node to highlight it, and then walking to each node on your chosen path in order, until you reach the purple node.

This project is intended to be used to show students an example use of Dijkstra's shortest path algorithm. Initially, the user tries to find the shortest path themselves, but when they have finished their path, they are shown the actual shortest path, as calculated using Dijkstra's algorithm, and are shown the weights assigned to each node by the algorithm.

At the start of the lesson the students could be told to try to find the shortest path from the orange node to the purple node. They could be asked to generate their own ideas on how to work out the shortest path. After this, the program will show them the solution, which it calculates using Dijkstra's algorithm, and then the students can be taught how Dijkstra's algorithm works and found the shortest path.

The json file for the project can be found [here](https://github.com/flipcomputing/a-level-resources/blob/main/pathfinding.json)

## [Maze Visualisation](https://flipcomputing.github.io/a-level-resources/maze.html)

The purpose of this project is visualise breadth-first search and depth-first search in the scenario of solving a maze. First, a maze is created using Prim's algorithm, by randomly assigning a weight to each wall, and then picking the accessible walls with the least values that don't create cycles until it can no longer turn walls into paths. Then, it spawns a target in yellow. Next, it demonstrates a breadth-first search, placing red markers in order on each tile visited during its search for the target. Finally, it shows a depth-first search, this time placing cyan markers on the tiles.

This project is intended to be used when teaching these search algorithms to illustrate how they both work. This visualisation clearly depicts the differences in these approaches, so it should help students understand the difference between them. Additionally, at the end, the program displays the number of tiles used by each algorithm.

The json file for the project can be found [here](https://github.com/flipcomputing/a-level-resources/blob/main/maze.json)