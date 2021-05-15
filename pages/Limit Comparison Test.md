Tags: #Theorem #ConvergenceTests #Memorize 

# Limit Comparison Test

Given a series with the $n\text{th}$ term of $a_n$, and another series with the $n\text{th}$ term of $b_n$ with known convergence,

$$
\Large
\begin{aligned}
& \lim_{x\to\infty} \left| \frac{a_n}{b_n} \right| = L \\\\

& L = \infty \to \text{diverges if } b_n \text{ diverges} \\
& L = 0 \to \text{converges if } b_n \text{ converges} \\\\

& 0 < L < \infty	\\
	& \quad \to \text{converges if } b_n \text{ converges} \\
	& \quad \to \text{diverges if }b_n \text{ diverges} \\
\end{aligned}
$$

> **NOTE:**
> The $L = \infty$ and $L = 0$ parts of the test come from a hidden [[Direct Comparison Test]]. 
> 
> If $L = \infty$, then $a_n$ must be $> b_n$ to have the limit approach $\infty$. If $\sum b_n$ is also divergent, then $a_n$ must be grow faster than the infinite sum of the divergent $\sum b_n$ series, therefore $\sum a_n$ must also be divergent.
> 
> If $L = 0$, then $a_n$ must be $< b_n$ to have the limit approach $0$. If $\sum b_n$ is also convergent, then $a_n$ must approach $0$ and therefore $\sum a_n$ must be convergent.