# Implementation: Graphs

* A graph is a non-linear data structure that can be looked at as a collection of vertices (or nodes) potentially connected by line segments named edges.


* common terminology used when working with Graphs:

  * Vertex - A vertex, also called a “node”, is a data object that can have zero or more adjacent vertices.

  * Edge - An edge is a connection between two nodes.

  * Neighbor - The neighbors of a node are its adjacent nodes, i.e., are connected via an edge.

  * Degree - The degree of a vertex is the number of edges connected to that vertex.

## Directed vs Undirected

* An Undirected Graph is a graph where each edge is undirected or bi-directional. This means that the undirected graph does not move in any direction.

![directed graph](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-35/resources/assets/UndirectedGraph.PNG)

* Unlike an undirected graph, a Digraph has direction. Each node is directed at another node with a specific requirement of what node should be referenced next.

![undirected graph](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-35/resources/assets/DirectedGraph.PNG)

## Complete vs Connected vs Disconnected

* A complete graph is when all nodes are connected to all other nodes.

![complete graph](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-35/resources/assets/CompleteGraph.PNG)

* 
A connected graph is graph that has all of vertices/nodes have at least one edge.

![connected graph](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-35/resources/assets/ConnectedGraph.PNG)

* A disconnected graph is a graph where some vertices may not have edges.

![disconnected graph](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-35/resources/assets/DisconnectedGraph.PNG)

## Acyclic vs Cyclic

* An acyclic graph is a directed graph without cycles.

A cycle is when a node can be traversed through and potentially end up back at itself.

Here is an example of 3 acyclic graphs:

![acyclic](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-35/resources/assets/threeAcyclic.png)

* A Cyclic graph is a graph that has cycles.
A cycle is defined as a path of a positive length that starts and ends at the same vertex.

Here is an example of a two different cyclic graph:

![a cyclic graph](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-35/resources/assets/cyclic.PNG)

## Graph Representation

* We represent graphs through:

   * Adjacency Matrix
 
   * Adjacency List

* An Adjacency matrix is represented through a 2-dimensional array. If there are n vertices, then we are looking at an n x n Boolean matrix.

* An adjacency list is a collection of linked lists or array that lists all of the other vertices that are connected.

## Weighted Graphs

* A weighted graph is a graph with numbers assigned to its edges. These numbers are called weights.

![weighted graph](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-35/resources/assets/weightGraph.PNG)

---

## refrences

* [Graphs](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-35/resources/graphs.html)
