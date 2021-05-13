Tags: #Theorem #FindingIntegrals 

# U-Substitution

A method of integrating that can reverse some uses of the chain rule.

## How to Use

Given,

$$\Large \int \frac{1}{3x + 4}dx$$

1. Choose a term to substitue for $u$.

$$\Large u = 3x + 4$$

2. Implicitly differentiate $u$ with respect to $x$, and solve for $dx$.

$$
\Large
\begin{aligned}
& 1\cdot \frac{du}{dx} = 3 + 0 \\
& \frac{du}{dx} = 3 \\
& dx = \frac{du}{3} \\
\end{aligned}
$$

> **TIP:**
> As a shortcut to solve for $dx$, you can just use the formula,
> 
> $$\Large dx = \frac{du}{u'}$$
> 
> where $u'$ is the derivative of $u$.

> **TIP:**
> When picking a term to substitute $u$ with, try to pick a term whose derivative will cancel out with all the $x$ variables in the integrand.
> 
> Also try to ensure that the resulting integral with $u$ is something that you can integrate.

3. Substitute the term you chose for $u$ with $u$.

$$\Large = \int \frac{1}{u}dx$$

5. Substitute $dx$ with the value you just evaluated containing $du$.

$$
\Large
\begin{aligned}
& = \int \frac{1}{u}\left(\frac{du}{3}\right) \\
& = \int \frac{1}{3u}du \\
\end{aligned}
$$

6. Integrate the integral, whose only variables should now be $u$.

$$\Large = \frac{\ln|u|}{3} + C$$

7. Substitute the term you replaced with $u$ back into the equation.

$$\Large = \frac{\ln|3x+4|}{3} + C$$

> **TIP:**
> You can always verify your solution by taking the derivative of it and seeing if you end up with the original integrand.