Tags: #Topic 

# Polar Equations

Polar equations are functions graphed on the polar coordinate plane.

![](attachments/polar_coordinates.png)

Polar equations often follow the format of 
$$\Large r(\theta)=\ldots$$

## Parametric Polar Equations

Polar equations can also be rewritten to use the cartesian coordinate system. However since cartesian coordinates use $x$ and $y$, we need to split $r(\theta)$ into two parts.

$$
\Large
\begin{aligned}
& x = r(\theta)\cos(\theta) \\
& y = r(\theta)\sin(\theta) \\
\end{aligned}
$$

This converted set of $x$ and $y$ equations are parametric equations since they change depending on the variable $\theta$.

## Area of Polar Equation

The area of a polar equation is normally the area from the orign ($r = 0$) to $r(\theta)$.

This area can be calculated using

$$\Large A = \int_a^b \frac{1}{2} r(\theta)^2 d\theta$$

> **NOTE:**
> This is derived from the area of a sector, which is 
> 
> $$\Large A_\text{sector} = \frac{\theta}{2\pi} \pi r^2 = \frac{\theta}{2}r^2$$

## Area Using Multiple Polar Equations

Divide the polar equations into sectors and integrate of each of the sectors separately to get the different sectors' areas. You can then sum up these sector areas to get the total area.

$$\large A = \int_a^b \frac{1}{2} \left( r_1(\theta)^2 - r_2(\theta)^2 \right) d\theta + \int_b^c \frac{1}{2} \left( r_2(\theta)^2 - r_3(\theta)^2 \right) d\theta + \ldots$$