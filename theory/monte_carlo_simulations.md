# Monte Carlo Simulations

Guesstimate uses Monte Carlo simulations to perform calculations using probability distributions.

If one wants to find the result of X * Y, where X and Y are random variables, a Monte Carlo simulation repeatedly samples from X and Y and multiplies the sample together. It's a brute force, random process of approximating the true, resulting distribution.

With Guesstimate, a Monte Carlo simulation of approximately 5000 samples is performed for each function with distribution inputs. For many decisions, we think that 5000 samples should be enough resolution for an adequate degree of confidence.
