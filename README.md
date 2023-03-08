# Fourier Series of f(x) = x^2

This repository contains the solution for finding the Fourier series expansion of the function f(x) = x^2 over a period of 2π.

## Problem Statement

The objective is to find the Fourier series expansion for the function f(x) = x^2 over a period of 2π.

## Approach

To find the Fourier series of f(x) = x^2, we first need to determine its periodic extension. We know that f(x) = x^2 is an even function, meaning f(-x) = f(x), so we'll extend it periodically using its even symmetry. Therefore, we'll consider f(x) on the interval [-π, π] and extend it periodically with a period of 2π.

Next, we'll use the standard formulae to find the Fourier series coefficients. We'll calculate the Fourier coefficients a0, an, and bn using the following formulas:

```
a0 = (1 / (2 * pi)) * integral(f(x) dx, -pi, pi)
an = (1 / pi) * integral(f(x) * cos(nx) dx, -pi, pi)
bn = (1 / pi) * integral(f(x) * sin(nx) dx, -pi, pi)
```

Finally, we'll plug in the values of a0, an, and bn into the Fourier series equation:

which gives us the Fourier series expansion of x^2.

## Repository Contents

This repository contains the following files:

- `Main.md`
- `Main.tex`
- `Main.pdf`

## Conclusion

In conclusion, the Fourier series expansion of f(x) = x^2 over a period of 2π can be expressed as a sum of sine and cosine functions. This repository serves as a useful resource for anyone who wants to learn more about Fourier series expansions or wants to see an example of how to calculate the Fourier series of a function.
