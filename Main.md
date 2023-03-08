the Fourier series for `f(x) = x^2` on the interval `-π<x<π`:

The Fourier series for a periodic function `f(x)` with period `2L` is given by:

```
f(x) = a0/2 + ∑(n=1 to infinity) [an * cos(nπx/L) + bn * sin(nπx/L)]
```

where `a0`, `an`, and `bn` are the Fourier coefficients, which can be calculated using the following formulas:

```
a0 = (1/L) * ∫(-L to L) f(x) dx
an = (1/L) * ∫(-L to L) f(x) cos(nπx/L) dx
bn = (1/L) * ∫(-L to L) f(x) sin(nπx/L) dx
```

For `f(x) = x^2` on the interval `-π<x<π`, we have `L = π`. Therefore, the Fourier coefficients become:

```
a0 = (1/π) * ∫(-π to π) x^2 dx
an = (1/π) * ∫(-π to π) x^2 cos(nx) dx
bn = 0
```

To find `a0`, we integrate `x^2` from `-π` to `π`:

```
a0 = (1/π) * ∫(-π to π) x^2 dx
   = (1/π) * [(1/3)*x^3] from -π to π
   = (1/π) * [(1/3)*π^3 - (1/3)*(-π)^3]
   = π^2/3
```

To find `an`, we integrate `x^2 cos(nx)` from `-π` to `π`:

```
an = (1/π) * ∫(-π to π) x^2 cos(nx) dx
   = (1/π) * [2*x*(sin(nx)/n^2) + 2*n*cos(nx)/(n^3)] from -π to π
   = (1/π) * [(2*π*(sin(nπ)/n^2) + 2*n*cos(nπ)/(n^3)) - (-2*π*(sin(-nπ)/n^2) + 2*n*cos(-nπ)/(n^3))]
```

Since `sin(-nπ) = 0` and `cos(-nπ) = (-1)^n`, this simplifies to:

```
an = (1/π) * [4*(-1)^n/(n^2)]
```

Therefore, the Fourier series for `f(x) = x^2` on the interval `-π<x<π` is:

```
f(x) = π^2/3 + 4/π * ∑(n=1 to infinity) (-1)^n/(n^2) * cos(nx)
```

This series converges to `f(x) = x^2` pointwise for all `x` in the interval `-π<x<π`.
