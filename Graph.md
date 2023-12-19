---
share: true
---


Definition:: A discrete structure consisting of vertices and edges

A graph $G=(V, E)$ consists of $V$ vertices and $E$ edges
Sometimes graphs don't have arrows, therefor it's connection is bidirectional

## Terminology
Simple Graph : graph where no two edges connect to the same vertice
Multigraph : graph where some edges connect to the same vertice
Loops : edge that connects from and to the same vertice
Pseudograph : graph with some loops
Adjacent : vertices connected by one edge
Incident : the edge that connects adjacents
Neighborhood($V$) : vertices connected to vertice $V$ 
Degree : amount of connections to a vertice (loops count for 2 degrees)
Pendant : degree == 1
Isolated : degree == 0
In-Degree : amount of connections pointing into the vertice (written as $\deg^-()$)
Out-Degree : amount of connections pointing out of the vertice (written as $\deg^+()$)
Cycle : graph where all vertices are degree 2
Wheel : Cycle + 1 vertice connecting everything
Subgraph : Graph where every element is contained in it's parent graph
Bipartide : Graph where exists Vertex set $V_1$ and $V_2$ where they share no vertices
Adjacency Matrix : write it down as
$$
\begin{bmatrix}
0&1&0\\
0&1&0\\
0&0&0
\end{bmatrix}
$$
where there is a connection from b to a and from b to b
Isomorphic : If the shapes of 2 graphs are the same
Path : A set of vertices that go in a path, you may not cross the same edge twice
Circuit : Path that starts and ends on the same vertice
Connected : When there is a path to and from every vertice when undirected
Strongly Connected : When there is a path to and from every vertice
Weakly Connected : When there is a path between every vertice
Euler's Circuit : Circuit that contains every edge of g
Euler's Path : Path that contains every edge of g
Hamilton Circuit : Circuit that contains every vertice of g
Hamilton Path : Path that contains every vertice of g
Chromatic Number : Least colors needed to color graph
Bipartide Graph : Union of 2 disjoint sets / Chromatic Number == 2 / no odd-sided polygons
Tree : Undirected graph without circuits
Forest : Collections of trees
Branch : Tree node with some connections
Leaf : Tree node with no more nodes afterwards / Degree == 1
Subtree : Tree in tree

## How to find Chromatic Number
1. Count degrees of all nodes
2. Order them by degree, then alphabetically
3. Color them in that order, one color at a time using multiple passes

## Cool Math ~~Games~~ Facts
$$
2m = \sum_{v=V}\deg(v)
$$
$m$ is edges

A Euler's Path but not a Euler's Circuit exists if there is exactly 2 odd degree vertices, in this case the path must start and end on the odd degree vertices


---
Related:
- [Example](./Example.md) : An example note

Further Reading:
- [Example](./Example.md)
