---
share: true
---


Definition:: A simplified [Directed Graph](./Directed%20Graph.md) that shows a [Partial Ordering](./Partial%20Ordering.md)

The following shows $\{\{1,2,3,4\}, \leq\}$
![Hasse Diagram-Less Than.png](./Attachments/Hasse%20Diagram-Less%20Than.png)

## Operations
The Maximal of the diagram are the nodes in the top
The Minimal of the diagram are the nodes in the top

The Upper Bound(UB) of an element in the diagram is all the nodes connected above it
The Lower Bound(LB) of an element in the diagram is all the nodes connected above it

If there are multiple bounds, intersect the bounds together 

### Example
![Hasse Diagram Bounds Example.png](./Attachments/Hasse%20Diagram%20Bounds%20Example.png)
$UB\{b\}=\{b,d,e,f,g,h,j\}$
$UB\{c\}=\{c,e,f,j,h\}$
$UB\{b,c\}=\{e,f,j,h\}$
$LB\{a,b,c\}=\{a\}$
$LB\{g,c\}=\{a\}$

---
Related:
- [Partial Ordering](./Partial%20Ordering.md) : A [Relation](Relation.md) that is reflexive, antisymmetric and transitive
- [Relation](./Relation.md) : A mathematical tool for describing associations between elements of [sets](Set.md).
- [Directed Graph](./Directed%20Graph.md) : A graph which shows all relations through arrows
- [Set](Set.md) : 

Further Reading:
- [Chapter 7: Relations and Partial Orders](./Credenza/Chapter%207:%20Relations%20and%20Partial%20Orders.md)
