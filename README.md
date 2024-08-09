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

------------------------------------------------------------------------------------------
**Dijkstra's Algorithm Implementation**

**Overview**
---------

This implementation of Dijkstra's algorithm is a Python class that calculates the shortest distances from a source vertex to all other vertices in a weighted graph.

**Usage**
---------

### Class `Dijkstra`

* `__init__(graph)`: Initializes the `Dijkstra` object with a weighted graph represented as an adjacency matrix.
* `dijkstra(src)`: Calculates the shortest distances from the source vertex `src` to all other vertices in the graph.

### Example Usage
-------------

To use this implementation, create an instance of the `Dijkstra` class and pass in the graph matrix as an argument. Then, call the `dijkstra` method with the source vertex as an argument.

```python
graph_matrix = [[0, 3, 0, 4, 0],
                [3, 0, 1, 0, 0],
                [0, 1, 0, 7, 2],
                [4, 0, 7, 0, 5],
                [0, 0, 2, 5, 0]]

dijkstra_obj = Dijkstra(graph_matrix)
shortest_distances = dijkstra_obj.dijkstra(0)

print("Shortest distances from source vertex {}: {}".format(0, shortest_distances))
```

### Output
--------
The output will be a list of shortest distances from the source vertex to all other vertices in the graph. If a vertex is unreachable from the source vertex, the distance will be represented as `inf`.


I hope this helps! Let me know if you have any questions or need further clarification.
