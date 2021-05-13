Tags: #Topic 

# Differential Equations

**Differential Equation** - An equations that relates a function to one or more of its derivatives

> **Ex.**
> $$
\Large
\begin{aligned}
& \frac{dy}{dx} = y^2 + 34 \\
& \frac{d^2y}{dx^2} + \frac{dy}{dx} - 52 = y \\
\end{aligned}
> $$

First-order differential equations (ie. $\dfrac{dy}{dx} = y \ldots$) can be represented graphically by using [[Slope Fields]].

The solutions to a differential equations is a set of possible functions for that function.

> **Ex.**
> $$\Large \frac{d^2y}{dx^2} + 2\frac{dy}{dx} = 3y$$
> 
> Could have these equations as possible solutions:
> 
> $$
\Large
\begin{aligned}
& y=e^{-3x} \\
& y=e^{x} \\
\end{aligned}
> $$

## Seperable Differential Equations

1. Given some differential equation of $x$ and $y$ containing only first-order derivatives, try and seperate all the $y$ variables to one side and all the $x$ variables to the other side.

> **Ex.**
> $$
\Large 
\begin{aligned}
& \frac{dy}{dx} = 3xy^2 \\
& dy = 3xy^2dx \\
& \frac{dy}{y^2} = 3xdx \\
\end{aligned}
> $$

3. If this is possible, then you can solve for a generation solution for the differential equation by integrating both sides

> **Ex.**
> $$
\Large 
\begin{aligned}
& \int \frac{1}{y^2}dy = \int 3xdx \\
& \frac{y^{-3}}{-3} = 3\cdot\frac{x^2}{2} + C\\
& -\frac{1}{3y^3} = \frac{3x^2}{2} + C\\
\end{aligned}
> $$

3. If you want a specific solution, then you must solve for $y$.