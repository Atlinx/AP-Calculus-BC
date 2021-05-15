Tags: #Topic 

# Series Error

Error is used to describe the difference in a result produced by a finite series and the actual series. 

$$\Large \text{Error} = |S - S_n|$$

For Taylor series, error is the difference in the value of an estimation and the actual value of the function that the Taylor series is estimating. 

Given that a Taylor series $T_n$ is an estimation of $f(x)$,

$$\Large \text{Error} = |f(x) - T_n|$$

## Error Bounding

The error bound of a finite series is the most amount of error that could have occured for an estimation made by the finite series.

$$\Large \text{Error}_{S_n} = |S - S_n| \leq \text{Max Error}$$

### Alternating Series Error Bound

If a series $S_n$ is alternating and has an $n\text{th}$ term that is  decreasing in absolute value and approaching $0$, then

$$\Large \text{Error}_{S_n} \leq |a_{n+1}|$$

### Lagrange Error Bound

This is an error bound that applies to Taylor series.

Given a Taylor series $T_n$ that is estimating $f(x)$,

$$\Large \text{Error}_{T_n} \leq \left| \frac{f^{(n+1)} (z) \cdot (x-c)^{n+1}}{(n+1)!} \right|$$

where $z$ is value between $x$ and $c$ that produces that maximum $f(x)$ value.