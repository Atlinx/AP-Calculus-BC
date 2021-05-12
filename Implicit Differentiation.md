Tags: #Topic #FindingDerivatives 

# Implicit Differentiation

Assume that a function is differentiable. That is, we assume that every point on the function has a slope.

This lets us differentiate functions that use both $x$ and $y$.

## How to Perform

1. Decide which variable to differentiate with respect to. Lets call this variable, $y$

3. Take derivative of each term. Let $v$ be the variable in a term.

	1. If the $v$ **is** $y$, then differentiate as normal.
	
	3. If the $v$ **is not** $y$, then
	
		1. Differentiate as normal.
		
		3. Multiply by the differentiated result by $\dfrac{dv}{dy}$ 

Step 2.1.2 works because,

$$
\Large
\begin{aligned}
& \frac{d}{dx} y \\
& = \frac{d}{dx} \cdot \frac{dy}{dy} y \\
& = \frac{d}{dx} \cdot \left( \frac{dy}{d} \cdot \frac{d}{dy} \right) y \\
& = \left( \frac{d}{dx} \cdot \frac{dy}{d} \right) \cdot \frac{d}{dy} [y] \\
& = \frac{dy}{dx} \cdot \frac{d}{dy}[y]
\end{aligned}
$$

