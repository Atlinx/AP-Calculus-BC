Tags: #Topic 

# Series

**Sequence** - A set of numbers that follows an discernable pattern from one to the next.

The pattern of a sequence is commonly referred to by the way you calculate the $n\text{th}$ term of the series. 

The $n\text{th}$ term of a sequence is commonly written as $a_n$.

**Series** - The summation of a sequence.

**Finite Series** - The summation of a fixed number of terms in a sequence.

**Infinite Series** - The summation of all the terms in a sequence. 

---

**Convergence** - A series that sums to a real number is considered **convergent**.

**Divergence** - A series that sums to infinity is considered **divergent**.

---

## Arithmetic Series

Arithmetic series are the summation of sequence whose next term is the previous term plus some constant.

> **Ex.**
> $$
\large
\begin{aligned}
& 1 + 2 + 3 + 4 + 5 + \ldots \\\\
& 6 + 11 + 16 + 21 + 26 + \ldots \\
\end{aligned}
> $$

$$\Large \sum_{n=0}^\infty b n + c $$

Infinite arithmetic series will always diverge if $a_n \neq 0$.

---

## Geometric Series

Geometric series are the summation of sequence whose next term is the previous term multiplied with some constant.

Geometric series are a type of power series.

> **Ex.**
> $$
\large
\begin{aligned}
& 2 + 4 + 8 + 16 + 32 + \ldots \\\\
& 3 + 9 + 27 + 81 + 243 + \ldots \\
\end{aligned}
> $$

$$\Large \sum_{n=0}^\infty = a_0 r^n$$

If $|r| < 1$, then the geometric series converges.
If $|r|\geq 1$, then the geometric series diverges.

> **NOTE:**
> A geometric series with $r=-1$ will diverge since it will oscillate between $1$ and $0$.
> 
> **Ex.**
> $$\large \sum_{n=0}^\infty (-1)^n = 1 - 1 + 1 - 1 + \ldots$$

If a geometric series converges, then the sum that it the series converges to is

$$\Large S = \frac{a_0}{1-r}$$


---

## Power Series

Power series are geometric series but with a variable that is usually $x$. Power series let us create polynomials.

> **Ex.**
> $$
\begin{aligned}
& 2 + 4x + 8x^2 + 16x^3 + 32x^4 + \ldots \\\\
& 3(x-3) + 9(x-3)^2 + 27(x-2)^3 + \ldots \\
\end{aligned}
> $$

$$\Large \sum_{n=0}^\infty = a_0 (x-c)^n$$

If $|x-c| < R$, then the power series converges.
If $|x-c| > R$, then the power series diverges.

> **NOTE:**
> Wondering where $R$ comes from?
> See [[Convergence]].

$$\Large S = \frac{a_0}{1-(x-c)}$$

> **NOTE:**
> Geometric series are a subset of a power series. This is why a geometric series's convergence, divergence, and sum rules look so similar to that of a power series.

---

## Taylor Series

Taylor series are series that can be used to approximate a function. Taylor series are type of power series.

$$\Large \sum_{n=0}^\infty \frac{ f^{(n)}(c)(x-c)^n }{n!}$$

$c$ is the center of the Taylor series.

A Taylor series always **converges at its center** since plugging in $x=c$ into $(x-c)$ always yields $0$. This means every term in the series except the first is $0$.

#### Finding Talyor Series

To find a Taylor series for a function $f(x)$, repeated take the derivative of $f(x)$ and then plug in the center $c$ for each of the derivatives and use the resulting constant as the coefficient for each term.

$$
\Large
\begin{aligned}
& f(x) = \ldots 		&& f(c) = c_0		\\
& f'(x) = \ldots 		&& f'(c) = c_1		\\
& f''(x) = \ldots 		&& f''(c) = c_2		\\
& f^{(3)}(x) = \ldots 	&& f^{(3)}(c) = c_3	\\
& \ldots				&& \dots			\\
\end{aligned}
$$

$$
\Large
\begin{aligned}
 T_n = \frac{c_0}{0!} & + \frac{c_1(x-c)}{1!} + \frac{c_0(x-c)^2}{2!} \\ 
 & + \frac{c_3x^3}{3!} + \ldots + \frac{c_n(x-c)^n}{0!}
\end{aligned}
$$

#### [[Convergence]]

####  [[Series Error]]

## Maclaurin Series

Maclaurin series are Taylor series that are cented around $0$.

$$\Large \sum_{n=0}^\infty \frac{ f^{(n)}(0)\cdot x^n }{n!}$$