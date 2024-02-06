---
share: true
---


Definition:: a way of representing [Time Complexity](./Time%20Complexity.md), such as $O(n\log{n})$

Big O notation is shown as the formula of time based on input, stripped of constants and lower order quadratics

![Time complexity comparison.png](../Attachments/Time%20complexity%20comparison.png)

Bubble Sort has $O(n^2)$ time complexity (blue line)n
Linear Search has $O(n)$ time complexity (red line)

generally, time complexities are
- Constant : $O(1)$
- Linear : $O(n)$
- Logarithmic : $O(\log{n})$
- Polynomial : $O(n),O(n^2),O(n^3)$
- Exponential : $O(2^n)$

time complexities can also be mixed, such as mergesort's $O(n\log{n})$
> $O(n(\log{n})^k)$ is called quasilinear

---
Related:
- [Example](../Meta/Example.md) : An example note

Further Reading:
- [Example](../Meta/Example.md)
