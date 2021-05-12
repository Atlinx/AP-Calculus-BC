Tags: #Theorem 

# Second Derivative Test

If $f'(c) = 0$, $f'(x)$ exists near $c$, and $f''(x)$ exists, then,

$$
\large
\begin{aligned}
& f''(c) < 0 \to \text{Relative maximum} \\
& f''(c) > 0 \to \text{Relative minimum} \\
& f''(c) = 0 \to \text{Inconclusive} \\
\end{aligned}
$$

> **NOTE:**
> $f''(c)=0$ is inconclusive because with $f'(c)=0$, we know nothing about what happens to "before" and "after" $f(c)$.

> **NOTE:**
> When the test is inconclusive, you will have to use the first derivative test to figure out the critical value.


## Steps

To find the critical values of a function $f(x)$ on the interval $[a, b]$,

1. Find the points where $f'(x)=0$ and plot them on a number line along with the interval bounds $a$ and $b$. These plotted points are you critical values.

```JSON
+----------+----------+----------+
a          3          4          b
```

2. Then find the sign of $f''(x)$ at those critical values. Make sure to write down which ones have $f''(x) = 0$ as well.

```JSON
f''(x) +          -          0          +
       +----------+----------+----------+
       a          3          4          b
```

4. Points with $f''(x)<0$ are **relative minimums**


```JSON
f''(x) +          -          0          +
       +----------+----------+----------+
       a          3          4          b
	           Rel Min
```

6. Points with $f''(x)>0$ are **relative maximums**

```JSON
f''(x) +          -          +          +
       +----------+----------+----------+
       a          3          4          b
	           Rel Min    Rel Max
```

7. Points with $f''(x)=0$ are **inconclusive**

```JSON
f''(x) +          -          +          +
       +----------+----------+----------+
       a          3          4          b
	           Rel Min    Rel Max
```

8. Calculate $f(x)$ at each critical point to find the **absolute extrema**.

```JSON
f''(x) +          -          +          +
       +----------+----------+----------+
       a          3          4          b
	           Rel Min    Rel Max
f(x)   40         20         26         90
               Abs Min               Abs Max
```