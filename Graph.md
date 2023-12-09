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
Bingus : **:3**

## Cool Math ~~Games~~ Facts
$$
2m = \sum_{v=V}\deg(v)
$$
m is edges

---
Related:
- [Example](./Example.md) : An example note

Further Reading:
- [Example](./Example.md)
