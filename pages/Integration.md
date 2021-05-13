Tags: #Topic

# Integration

**Integral** - The operation of summing together of infinitesimal parts to form a whole. An integral by itself represents the area of the curve of the **integrand**.

**Integrand** - The function that is being integrated by an integral.

**Antiderivative** - A function made by reversing the steps to take a derivative.

## Area Under the Curve

An integral represent the the area under a a function's line on a graph.

Areas  **below the x-axis** have **negative** area.
Areas **above the x-axis** have **positive** area.

Since an integral sums up the area of a function over a given interval, this means negative areas **remove area** from positive areas.

To calculate the total area, you would have to use the integral of the absolute value of the function

$$\Large A_\text{total} = \int_a^b|f(x)|dx$$

#### [[Approximations for Area Under a Curve]]

## Fundamental Theorem of Calculus

Abbreviated as "FTC"

> **NOTE:**
> Let capital function letters denote anti-derivatives.
> 
> **Ex.**
> $F(x)$ is the antiderivative of $f(x)$.

If $f(x)$ is continous on $[a,b]$ and $a<x<b$ where
$$\Large F(x) = \int_a^xf(t)dt$$

**Part I**
Then,
$$\Large F'(x) = \frac{d}{dx}\int_a^xf(x)$$

**Part II**
Then,
$$\Large \int_a^bf(x) = F(b) - F(a)$$

## Finding Integrals

The basis of finding integrals is applying the reverse of many derivative rules.

To reverse the [[chain rule]], try using [[U-Substitution]].

### Integration Strategies

- #### [[Integration Tricks]]
- #### [[Reverse Power Rule]]
- #### [[Reverse Logarithmic Rule]]
- #### [[U-Substitution]]
- #### [[Integration by Parts]]
- #### [[Useful Integrals]]

## Integrals

Let $F(x)$ be the antiderivative of $f(x)$.

### Definite

 Integral that is bounded by limits. The limits are indicated at the bottom and top of an integral symbol, respectively.
 
$$\huge \int_a^bf(x)dx$$

To evaluate definite integrals, we first take the antiderivative of the integrand and then, using the part one of **FTC**, we evaluate definite integrals as

$$\Large \int_a^bf(x)dx = F(x)\bigg|_a^b=  F(b) - F(a)$$

The bar after $F(x)$ means "evaluated from $a$ to $b$."

> **NOTE:**
> Integrals evaluated with opposite limits will be negative
> 
> **Ex.**
> $$\Large \int_a^b f(x) dx = -\int_b^a f(x) dx$$
> 
> This makes sense because with flipped limits, you are evaluating the integral "backwards," and would therefore have a opposite sign answer.

##### Absolute Value Integrands

To evaluate a definite integral with an absolute value sign wrapping it's integrand, split the function up into sections based on their sign and then multiply each negative area section by $-1$ to flip it's sign to positive.

> **Ex.**
> Assuming $(a,b)$ is negative and $(b,c)$ is positive for $f(x)$,
> $$\Large \int_a^c|f(x)| = -\int_a^b f(x) + \int_b^c f(x)$$

### Indefinite

The most general antiderivative of a function.

$$\huge \int f(x)dx$$

Indefinite integrals are evaluated as

$$\huge \int f(x)dx = F(x) + C$$

$C$ is is a constant and is necessary due to the [[constant rule]] eliminating constants when taking derivatives. Since we want to reverse the steps of a derivative, there theoretically could have been a constant in the derivative and we wouldn't know. Therefore $C$ represents the possible constants that could appear in the antiderivative. 

### Improper

##### Infinite Integrals

Integrals that are unbounded — meaning it goes to infinity — are improper.

$$\Large \int_a^\infty(x)dx $$

To evaluate an unbounded integral, you would place the integral within a limit — replacing the infinities with a variable that approaches infinity — and then evaluating the integral and then the limit.

$$\Large \int_a^\infty(x)dx = \lim_{t\to\infty} \int_a^tf(x)dx = $$

##### Discontinous Integrands

Integrals are discontinous if they are evaluated over a range that has a discontinuity.

Assume we are evaluting an integral from $a$ to $b$

If there a discontinuity at $x=c$, where $a<c<b$, to evalute the integral you would have to split it up. 

$$\Large \int_a^bf(x)dx = \int_a^cf(x)dx + \int_c^bf(x)dx$$

If the discontinuity is located at one of the bounds, say $x=b$, then you would have to wrap in the integral in a limit that approaches the bounds from inside the bounds.

For example if the upper bound was discontinous, then

$$\Large \int_a^bf(x)dx = \lim_{t\to b^-} \int_a^tf(x)dx$$

And if the lower bound was discontinous, then

$$\Large \int_a^bf(x)dx = \lim_{t\to a^+} \int_t^bf(x)dx$$