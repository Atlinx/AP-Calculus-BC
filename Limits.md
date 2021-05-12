Tags: #Topic

# Limits

**Limit** - The value that a function approaches as it's input approaches some value.

$$\huge\lim_{x\to c}f(x) = L$$

This reads as "The limit of $f(x)$ as $x$ approaches $c$ is $L$

## Solving for Limits

### Direct Substitution

You can solve for a limit using by plugging in the value the limit approaches into the function.

> **Ex.**
> 
> $$
\Large
\begin{aligned}
&\lim_{x\to 5} x^2 - 3x \\
& = 5^2 - 3\cdot5 \\
& = 25 - 15 \\
& = 10 \\
\end{aligned}
> $$

### Race to Infinity

For limits that involve infinity, whether by having the limit approach infinity (ie. $\lim\limits_{x\to \infty}x$) or by having an infinity appear within the limit (ie. $\lim\limits_{x\to0}\frac{1}{x}$), you can use the race to infinity to evaluate it.

**Term Group** (Not an official term) - Group of numbers that only use addition or subtraction.

> **Ex.**
> $\large (123 - 93x^2), \quad (34x - 293), \quad \text{etc.}$  

To use the race to infinity, identify the fastest scaling terms in each term group and cancel out the rest of the terms in each group.

#### Scaling Speed of Terms from Slowest to Fastest

1. **L**ogarithmnic
2. **R**oots
3. **P**olynomials
4. **E**xponents
5. **F**actorials
6. $X^X$

> **TIP:**
> You can use the mnemonic "Lerp Effects" to memorize the first letters of the chart, which together form "LRP EFX".

## Existence

For a limit to exist, the function must approach the same value from both the left and right hand side. That is,

$$\huge\lim_{x\to c^-}f(x) = \lim_{x\to c^+}f(x) = L$$

where $L$ is a real number

## Does Not Exist

Limits do not exist if there is a discontinuity or if the limit approaches infinity. 

See [[continuity]] for more information about discontinuities.

> **NOTE**
> For a given real number $c$,
> 
> $$\huge\frac{c}{\infty} = 0 \text{ and } \huge\frac{\infty}{c} = \infty$$

## Indeterminate

Limits are indeterminate if they are,

$$\huge\frac{0}{0}, \frac{\infty}{\infty}, \infty - \infty, 0^0, 1^\infty, \infty^0, 0 \cdot \infty$$

If a limit is in the indeterminate form of $\displaystyle 	\frac{0}{0}$ or $\displaystyle \frac{\infty}{\infty}$ , you can use [[L'Hopital's Rule]] to solve for the limit.

## Compound Limits

Given $f(x)$ and $g(x)$, if $\lim\limits_{x\to c} f(x)$ exists and $\lim\limits_{x\to c} g(x)$, then a limit of a funciton that uses only $f(x)$ and $g(x)$ as variables exists.

## Special Limits

$$
\Large
\begin{aligned}
& \lim_{x\to 0} \frac{\sin(x)}{x} = \lim_{x\to 0} \frac{x}{\sin(x)} = 1 \\\\
& \lim_{x\to 0} \frac{\cos(x) - 1}{x} = \lim_{x\to 0} \frac{\cos(x) - 1}{x} = 0 \\\\
& \lim_{x\to \infty} (1 + \frac{1}{x})^x = \lim_{x\to 0} (1 + x)^{\frac{1}{x}} = e \\\\
& \lim_{x\to 0} \frac{e^x - 1}{x} = 1 \\
\end{aligned}
$$