# Monte Carlo Simulations

Guesstimate uses [Monte Carlo](https://en.wikipedia.org/wiki/Monte_Carlo_method) techniques to produce our results. The
Monte Carlo method involves repeatedly sampling the underlying probability distributions of a random variable and
performing all calculations involving that random variable many times, with those sampled values. The Monte Carlo method
is a brute force, random process of approximating the true, resulting distribution.

For example, if you wanted to compute the value of $$X \times Y$$, where $$X$$ and $$Y$$ are random variables (such as
Guesstimate cells whose inputs are ranges, or data streams), then using the Monte Carlo method you would compute many
sample values for $$X$$ and many sample values for $$Y$$, then multiply those samples together pairwise to produce the
output distribution for $$X \times Y$$.

Within Guesstimate, 5000 samples are performed per stochastic expression. 5000 is enough to be useful for most
estimates, but not enough to slow the system down. In the future, this amount may be variable depending on the need and
circumstances.
