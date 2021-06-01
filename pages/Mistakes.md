Tags: #Topic 

# Mistakes

## Extrema

> **NOTE:**
> You should know that existence of [[Second Derivative Test]] because even though the [[First Derivative Test]] is guaranteed to work, College Board still expects you to know how to use second derivative test.

## Continuity

> **NOTE:**
> Watch out for asymptotes!
> 
> **Ex.**
> What value of $k$ makes this function continuous? 
> $$
\Large
f(x) =
\begin{cases} 
  k^3 + x 			& x < 3 \\
  \dfrac{16}{k^2-x}	& x \ge 3 \\
\end{cases}
> $$
> 
> Keep in mind that $k^2$ must be $<3$, or else the second part $f(x)$ will have an **vertical asymptote due to the denominator**.
> 
> $(k^3 + 3)(k^2 - 3)-16=0$ is the function that holds the possible zeroes. 
> 
> We can find the zeroes using a calculator by graphing $y = (k^3 + 3)(k^2 - 3)-16$ and identifying where $y=0$.

## Trig Functions and Limits

> **NOTE:**
> $\tan^{-1}(x)$ and $\cot^{-1}(x)$ are the only trig functions that can handle limits of $x\to\infty$.
> 
> Make sure to not panic when seeing a trig function in an infinity limit.

## Using U-Substitution

> **NOTE:**
> If a function seems hard to integrate, try u-sub!
> 
> **Ex.**
> $$
\Large
\begin{aligned}
\int \frac{e^x - 1}{e^x - x}dx \\
\end{aligned}
>$$
>$$
\Large
\begin{aligned}
u &= e^x - x \\
dx &= \frac{du}{e^x - 1}
\end{aligned}
>$$
>$$
\Large
\begin{aligned}
&= \int \frac{\bcancel{e^x - 1}}{u} \left( \frac{du}{\bcancel{e^x - 1}} \right) \\
&= \int \frac{1}{u} du \\
&= ln|u| + C \\
&= ln|e^x-x| + C \\
\end{aligned}
>$$

## Derivative of First-Derivative Parametric Equation

Given

$$\Large \frac{dx}{dt} = \ldots \qquad \frac{dy}{dt} = \ldots$$

you must find $$\Large  \frac{d^2y}{dx^2}$$

You **CANNOT** do

$$\Large  \frac{d}{dt} \left[ \frac{dy}{dt}  \right] \div \frac{d}{dt} \left[ \frac{dx}{dt}  \right] = \frac{d^2y}{dx^2}$$

since 

$$\large \frac{d}{dt} \left[ \frac{dy}{dt}  \right] \div \frac{d}{dt} \left[ \frac{dx}{dt}  \right] = \frac{d^2y}{d^2x} \neq \frac{d^2y}{dx^2}$$

> **NOTE:**
> Look at the denominator. Notice how this produces $d^2x$ in the denominator, which is not the same as $dx^2$.

Instead, you must do

$$\Large \frac{d}{dx} \left[ \frac{dy}{dt} \div \frac{dx}{dt} \right] = \frac{d^2y}{dx^2}$$

Therefore you can only do the "division combination" strategy of combining parametric equations **BEFORE** taking the derivative of the combined terms.