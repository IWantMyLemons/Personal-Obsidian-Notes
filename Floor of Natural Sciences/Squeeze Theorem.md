---
share: true
---


Definition:: If $f(x) \leq g(x) \leq h(x)$ when $x$ is near $a$ and $\lim_{x\to a}{f(x)}=L=\lim_{x\to a}{h(x)}$ then $\lim_{x\to a}{g(x)}=L$

e.g.
$$
\begin{aligned}
\lim_{x\to0}{x^2\sin\frac1x}&=?\\
\\
\text{it is known that }-1&\leq\sin{\frac1x}\leq1\\
\text{therefore }-x^2&\leq x^2\sin{\frac1x}\leq x^2\\
\\
\lim_{x\to0^+}-x^2&=0\\
\lim_{x\to0^-}x^2&=0\\
\\
\text{by the theorem,}\lim_{x\to0}x^2\sin{\frac1x}&=0\\
\end{aligned}
$$

---
Related:
- [Example](../Meta/Example.md) : An example note

Further Reading:
- [Example](../Meta/Example.md)
