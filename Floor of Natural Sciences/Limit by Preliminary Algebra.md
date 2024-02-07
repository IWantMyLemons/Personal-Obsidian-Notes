---
share: true
---


Definition:: Using algebra to make the question easier

e.g.
$$
\lim_{x\to1}{\frac{x^3-1}{x-1}}=?
$$
If we tried using [Limit by Direct Substitution](./Limit%20by%20Direct%20Substitution.md) we would've gotten indeterminate $\frac00$
$$
\begin{aligned}
\lim_{x\to1}{\frac{x^3-1}{x-1}}&=\frac{1^3-1}{1-1}\\
&=\frac00
\end{aligned}
$$
We first use alg
$$
\begin{aligned}
\lim_{x\to1}{\frac{x^3-1}{x-1}}&=\frac{(x-1)(x^2+x+1)}{x-1}\\
&=x^2+x+1\\
\end{aligned}
$$
then using [Limit by Direct Substitution](./Limit%20by%20Direct%20Substitution.md):
$$
\begin{aligned}
\lim_{x\to1}x^2+x+1 &= 1^2+1+1\\
&=3\\
\end{aligned}
$$


---
Related:
- [Example](../Meta/Example.md) : An example note

Further Reading:
- [Example](../Meta/Example.md)
