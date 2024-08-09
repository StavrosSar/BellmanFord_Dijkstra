Path planning algorithms
Bellman Ford and Dijkstra
Here is a possible README format for your GitHub repository:

**Bellman-Ford Algorithm Implementation in Python**

**Overview**
-----------

This repository contains a Python implementation of the Bellman-Ford algorithm, a well-known algorithm for finding the shortest path from a single source node to all other nodes in a weighted graph.

**Features**
---------

* Supports directed graphs with weighted edges
* Can handle negative weight cycles
* Visualizes the graph using NetworkX and Matplotlib

**Example Graph**
----------------

The example graph used in this implementation is a 6-node graph with weighted edges:
```
example_graph = [
    ['X', 4, 'X', 2, 'X', 'X'],
    ['X', 'X', 15, -6, 4, 'X'],
    ['X', 'X', 'X', 'X', 'X', 1],
    ['X', 'X', 'X', 'X', 2, 'X'],
    ['X', 'X', 'X', 'X', 'X', 17],
    ['X', 'X', 'X', 'X', 'X', 'X']
]
```
Choose a source node (default is 0) and run the script to see the results.

