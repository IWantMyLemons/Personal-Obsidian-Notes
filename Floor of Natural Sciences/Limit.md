---
share: true
---


Definition:: a way of finding the value nearing an [Indeterminant](./Indeterminant.md) point

## Precise definition
$$
\lim_{x\to a}{f(x)}=L
$$
for every number $\epsilon>0$ there is a number $\delta>0$ such that
if $0<|x-a|<\delta$ then $|f(x)-L|<\epsilon$

## Methods
- [Intuitive Limits](./Intuitive%20Limits.md) : Limits by thinking
- [Limit by Direct Substitution](./Limit%20by%20Direct%20Substitution.md) : finding limits by directly inserting the values
- [Limit by Preliminary Algebra](./Limit%20by%20Preliminary%20Algebra.md) : Using algebra to make the question easier

## Directions
approaching values from the right (big to small) is written as
$$
\lim_{x\to e^+}{f(x)}=\text{L}
$$
approaching values from the left (small to big) is written as
$$
\lim_{x\to e^-}{f(x)}=\text{L}
$$
> if unreadable the difference is $e^+$ when approaching from the right and $e^-$ when approaching from the left

A limit exists when you can approach a value from both left and right AND both limits are equal

> While a limit exists, you may also need to watch out for [Continuity](./Continuity.md)

## Limits to infinity
in limits there exists $\infty$ and $-\infty$
$\infty$ happens when we keep getting bigger and bigger numbers trying to approach something
$-\infty$ happens when we keep getting smaller and smaller negative numbers trying to approach something

In finding limits to infinity we may also find the [Vertical Asymptote](./Asymptote.md#vertical-asymptote)

## Practice Questions
![Pasted image 20240207120551.png](../Attachments/Pasted%20image%2020240207120551.png)

> [!help]- 1.Solution
> $$
> \begin{aligned}
> \lim_{x\to-1}{2x^3-4x^2+6}&=-2-3+6\\
> &=1\\
> \end{aligned}
> $$

> [!help]- 2.Solution
> $$
> \begin{aligned}
> \lim_{x\to2}{\frac{x^3-2x+1}{x^2-3x}}&=\frac{8-4+1}{4-6}\\
> &=\frac{5}{-2}\\
> &=-\frac52\\
> \end{aligned}
> $$

> [!help]- 3.Solution
> $$
> \begin{aligned}
> \lim_{x\to2}{\frac{x^2-x-2}{x-2}}&=\frac{(x-2)(x+1)}{x-2}\\
> &=x+1\\
> &=2+1\\
> &=3\\
> \end{aligned}
> $$

> [!help]- 4.Solution
> $$
> \begin{aligned}
> \lim_{x\to\infty}{\frac{x^3-2x^2+1}{2x^3+3x}}&=\frac{\frac{x^3}{x^3}-\frac{2x^2}{x^3}+\frac1{x^3}}{\frac{2x^3}{x^3}+\frac{3x}{x^3}}\\
> &=\frac{1-\frac2x+\frac1{x^3}}{2+\frac3{x^2}}\\
> &=\frac{1-0+0}{2+0}\\
> &=\frac12\\
> \end{aligned}
> $$

> [!help]- 5.Solution
> $$
> \begin{aligned}
> \lim_{x\to\infty}{(x^3-9x^2)}&=x^3(1-\frac9x)\\
> &=\infty\cdot(1-0)\\
> &=\infty\\
> \end{aligned}
> $$

> [!help]- 6.Solution
> $$
> \begin{aligned}
> \lim_{x\to4}{\frac{x-\sqrt{x}-2}{x-4}}&=\frac{(\sqrt x-2)(\sqrt x+1)}{(\sqrt x-2)(\sqrt x+2)}\\
> &=\frac{\sqrt x+1}{\sqrt x+2}\\
> &=\frac{\sqrt 4+1}{\sqrt 4+2}\\
> &=\frac{2+1}{2+2}\\
> &=\frac{3}{4}\\
> \end{aligned}
> $$

> [!help]- 7.Solution
> $$
> \begin{aligned}
> \lim_{x\to\infty}{\frac{x-\sqrt{x}-2}{x-4}}&=\frac{\frac{x}{x}-\frac{\sqrt{x}}{x}-\frac{2}{x}}{\frac{x}{x}-\frac{4}{x}}\\
> &=\frac{1+\frac1{\sqrt x}-\frac2x}{1-\frac4x}\\
> &=1\\
> \end{aligned}
> $$

> [!help]- 8.Solution
> $$
> \begin{aligned}
> \lim_{x\to\infty}{\sqrt{x-1}-\sqrt{x}}&=\frac{\sqrt{x-1}-\sqrt{x}}{1}\\
> &=\frac{(\sqrt{x-1})^2-(\sqrt{x})^2}{\sqrt{x-1}+\sqrt{x}}\\
> &=\frac{(x-1)-x}{\sqrt{x-1}+\sqrt{x}}\\
> &=\frac{-1}{\sqrt{x-1}+\sqrt{x}}\\
> &=\frac{-1}{\infty}\\
> &=0\\
> \end{aligned}
> $$

---
Related:
- [Continuity](./Continuity.md) : Happens when a function's limit equals to it's function result
- [Function Definition](./Function%20Definition.md) : Some functions stop working at some points
- [Limit Laws](./Limit%20Laws.md) : not that bad since most of these just mean you can seperate regular arithmetic from limits
- [Squeeze Theorem](./Squeeze%20Theorem.md) : If $f(x) \leq g(x) \leq h(x)$ when $x$ is near $a$ and $\lim_{x\to a}{f(x)}=L=\lim_{x\to a}{h(x)}$ then $\lim_{x\to a}{g(x)}=L$

Further Reading:
- [Example](../Meta/Example.md)
