Tags: #Topic 

# Series Representation of an Integral

Since an integral is the area underneath a function, it can be estimated using [[Approximations for Area Under a Curve]]. These approximations use small shapes (usually rectangles) to approximate the area, therefore if we use an infinte number of these small shapes, we will get the exact value of the area under the curve.

Therefore,

$$
\large 
\begin{aligned}
x_i &= \text{offset} + \text{total change} \\
x_i &= a + i\Delta x \\\\

\Delta x &= \frac{\text{total}}{\text{number of steps}} \\
\Delta x &= \frac{b - a}{n} \\\\

\int_a^b f(x) dx &= \lim_{n \to \infty} \sum_{i=1}^n f(x_i) \Delta x \\
&= \lim_{n \to \infty} \sum_{i=1}^n f(a + i \Delta x) \Delta x \\
&= \lim_{n \to \infty} \sum_{i=1}^n f \left( a + i \left( \frac{b - a}{n} \right) \right) \cdot \frac{b - a}{n}
\end{aligned}
$$

## Finding Integral from Series

If you need to find the integral representation of a series, first simplify the the series into summation notation. Then look for the components of an integral in a series format (like $x_i$ and $\Delta x$). Finally solve for $b$, $a$ and the rest of the unknowns using the components.