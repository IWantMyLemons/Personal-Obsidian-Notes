---
share: true
---


Definition:: A mathematical tool for describing associations between elements of [sets](Set.md).

Currently known relations include:
- [Binary Relation](./Binary%20Relation.md) : Given sets $A$ and $B$, a binary relation $R:A\to B$ where $R \subseteq A \times B$
- [Partial Ordering](./Partial%20Ordering.md) : A [Relation](Relation.md) that is reflexive, antisymmetric and transitive

e.g.
$\text{let } a = \{1, 2, 3, 4\}$
$R = \{(a, b)|\text{ a divides b}\}$
then $R = \{(1,1),(1,2),(1,3),(1,4),(2,2),(2,4),(3,3),(4,4)\}$

\* $\text{a divides b}$ means that $\text{b}$ is divisible by $\text{a}$

Relations can be represented by a matrix where
$$
a_{ij} = \begin{cases}
1 \text{ if the ith element of A is related to the jth element}\\
0 \text{ otherwise}
\end{cases}
$$

## Properties
### Reflexive
$(a,a)\in R, \forall a\in A$
Reflexive means that $(a, a) \in R$ exists for all values $a$
In a matrix, this is shown by all members of the diagonal being $1$
$$
\begin{bmatrix}
1& & & \\
 &1& & \\
 & &1& \\
 & & &1\\
\end{bmatrix}
$$
### Irreflexive
$(a,a)\not\in R, \forall a\in A$
Irreflexive means that $(a, a) \not\in R$ for all values $a$
In a matrix, this is shown by all members of the diagonal being $0$
$$
\begin{bmatrix}
0& & & \\
 &0& & \\
 & &0& \\
 & & &0\\
\end{bmatrix}
$$

### Symmetric
$(a,b)\in R\to (b,a)\in R,\forall a,b\in A$
Symmetric means that $(b,a)\in R$ whenever $(a,b)\in R$
In a matrix, this is shown by all elements being symmetrical by the horizontal
$$
\begin{bmatrix}
 &a&b&c\\
a& &d&e\\
b&d& &f\\
c&e&f& \\
\end{bmatrix}
$$

### Antisymmetric
$(a,b)\in R\land (b,a)\in R \to a=b,\forall a,b\in A$
alternatively,
$a \not= B \to (a,b)\not\in R\lor (b,a)\not\in R$
Antisymmetric means that there are no symmetric elements except for the diagonals
In a matrix, this is shown by all elements being symmetrical by the horizontal, $0$s don't count
$$
\begin{bmatrix}
 &b&c&d\\
e& &g&h\\
i&j& &l\\
m&n&o& \\
\end{bmatrix}
$$

### Transitive
$(a,b)\in R \land (b,c)\in R \to (a,c)\in R,\forall a,b,c\in A$
Transitive means that if there is a chain $(a,b)$ and $(b,c)$ then $(a,c)$ also exists
Normally shown with a [Directed Graph](./Directed%20Graph.md)

---

Related :
- [Binary Relation](./Binary%20Relation.md) : Given sets $A$ and $B$, a binary relation $R:A\to B$ where $R \subseteq A \times B$
- [Partial Ordering](./Partial%20Ordering.md) : A [Relation](Relation.md) that is reflexive, antisymmetric and transitive
- [Set](Set.md) : 

Additional reading:
- [Chapter 7: Relations and Partial Orders](./Credenza/Chapter%207:%20Relations%20and%20Partial%20Orders.md)
