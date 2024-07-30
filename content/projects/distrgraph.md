---
title: "Distributed Maze Generator"
date: 2024-07-30T16:46:09+05:30
draft: false
---
![Image](/img/maze.png)
In this project, I undertook implemented distributed versions of well-known graph algorithms such as Prim's, Dijkstra's, Kruskal's, DFS, and BFS specifically tailored for maze generation and solving, using the MPI library in C++.

To achieve parallelization, I employed a strategy for BFS and Dijkstra's algorithms. I introduced the concept of node ownership, assigning specific nodes in the graph to different processors. This allowed for a more balanced distribution of work and enabled efficient parallel processing of the graph.

For the DFS algorithm, I incorporated dynamic load sharing techniques. This involved dynamically redistributing the workload among parallel processes, ensuring that each process had a comparable amount of work to perform. This approach maximized the utilization of available computing resources.


[View the project on GitHub](https://github.com/andTEJAsan/Distributed_Maze_Gen)