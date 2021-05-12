Tags: #Theorem

# First Derivative Test

If $f'(c)$ exists and $f'(x)$ exists around $x=c$, then

$$
\large
\begin{aligned}
& f'(c) \text{ changes from} + \text{to } - \to \text{Relative maximum} \\
& f'(c) \text{ changes from} - \text{to } + \to \text{Relative minimum} \\
& f'(c) \text{ does not change sign} \to \text{Saddle point)}\\
\end{aligned}
$$

## Steps

To find the critical values of a function $f(x)$ on the interval $[a, b]$,

1. Find the points where $f'(x)=0$ and plot them on a number line along with the interval bounds $a$ and $b$. These plotted points are you critical values.

```JSON
+----------+----------+----------+
a          1          3          b
```

2. Then find the sign of $f'(x)$ between these critical values.

```JSON
f'(x)       +          -          +
      +----------+----------+----------+
      a          1          3          b
```

4. Points where the sign changes from $-$ to $+$ are **relative minimums**


```JSON
f'(x)       +          -          +
      +----------+----------+----------+
      a          1          3          b
	                     Rel Min
```

6. Points where the sign changes from $+$ to $-$ are **relative maximums**

```JSON
f'(x)       +          -          +
      +----------+----------+----------+
      a          1          3          b
	          Rel Max    Rel Min
```

8. Calculate $f(x)$ at each critical point to find the **absolute extrema**.

```JSON
f'(x)          +          -          +
         +----------+----------+----------+
         a          1          3          b
	             Rel Max    Rel Min
f(x)     30         40         19         23
      Abs Max               Abs Min
```
