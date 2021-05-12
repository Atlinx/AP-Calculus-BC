Tags: #Topic 

# Approximations for the Area Under a Curve

Let $f(x)$ be the function we are approximating.

Let $(a,b)$ denote the interval we are interested in approximating

Approximations use a "step" amount normally denoted by $\Delta X$. This determines the widths of the rectangles/trapizoids used in the approximation.

Let $x_a$ and $x_b$ denote the two points that are $\Delta X$ units apart, with $x_a$ located to the left of $x_b$. These two points represent the points surrounding one "step" of the approximation 

## RRAM

Short for "Right Rectangular Approximation Method"

Use rectangles whose rightmost point is located on the function. 

$$
\Large
\begin{aligned}
& h_\text{rectangle} = f(x_b) \\
& A_\text{rectangle} = f(x_b) \cdot \Delta X \\
\end{aligned}
$$

**Underestimates** if $f(x)$ is always decreasing in $(a,b)$.
**Overestimates** if $f(x)$ is always increasing in $(a,b)$.

## LRAM

Short for "Left Rectangular Approximation Method"

Use rectangles whose leftmost point is located on the function.

$$
\Large
\begin{aligned}
& h_\text{rectangle} = f(x_a) \\
& A_\text{rectangle} = f(x_a) \cdot \Delta X \\
\end{aligned}
$$

**Underestimates** if $f(x)$ is always increasing in $(a,b)$.
**Overestimates** if $f(x)$ is always decreasing in $(a,b)$.

## MRAM

Short for "Midpoint Rectangular Approximation Method"

Use rectangles whose height is the height of the point between $x_a$ and $x_b$.

$$
\Large
\begin{aligned}
& h_\text{rectangle} = f\left(\frac{x_a+x_b}{2}\right) \\
& A_\text{rectangle} = f\left(\frac{x_a+x_b}{2}\right) \cdot \Delta X \\
\end{aligned}
$$

## Trapizoidal Approximation Method

Use trapizoids formed by connecting $x_a$ and $x_b$ and using $x_a$ as a one base, $x_b$ as a its second base, and $\Delta X$ as its height.

$$
\Large
\begin{aligned}
& A_\text{trapizoid} = \frac{1}{2} (f(x_a) + f(x_b)) \cdot \Delta X \\
\end{aligned}
$$

**Underestimates** if $f(x)$ is concave down in $(a,b)$.
**Overestimates** if $f(x)$ is concave up in $(a,b)$.