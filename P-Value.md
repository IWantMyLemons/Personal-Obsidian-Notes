---
share: true
---


Definition:: Some value used to verify [Null Hypothesis](./Null%20Hypothesis.md)

## How to use
1. Find givens, this usually consists of $\mu$, $\sigma$, $\bar{X}$, $\alpha$
2. Create $H_0$, decide on one-tail (if $\leq$ or $\geq$) or two-tail (if $=$)
3. Calculate $Z_{stat}$ (this is used for P-value)
	$$
	Z_{stat}=\frac{\bar{X}-\mu}{\frac{\sigma}{\sqrt{n}}}
	$$
4. Find P-Value on Z table
	$$
	P(Z=...)=...
	$$
5. Check P-Value against $\alpha$ (confidence level) 



---
Related:
- [Null Hypothesis](./Null%20Hypothesis.md) : $H_0$, is the hypothesis that the data is statistically insignificant

Further Reading:
- [Example](./Example.md)
