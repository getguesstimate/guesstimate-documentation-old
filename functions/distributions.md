# Distributions

Guesstimate supports a variety of statistical distributions beyond those selectable from confidence intervals. If the
input parameters to these distribution functions are deterministic, 5000 samples will be generated at those parameter
values. If the inputs are themselves sampled, one sample will be drawn, per input sample.

| Distribution Name | Use Cases | Syntax |
| ----------------- | --------- | ------ |
| [Beta](https://en.wikipedia.org/wiki/Beta_distribution) | Estimating Proporitions or Percentages | `=beta`$$(\alpha, \beta)$$ |
| [Central F](https://en.wikipedia.org/wiki/F-distribution) | Testing the Variance of Observed Samples | `=centralF`$$(d_1, d_2)$$ |
| [Cauchy](https://en.wikipedia.org/wiki/Cauchy_distribution) | The x-intercept of a ray with uniformly distributed angle | `=cauchy`$$(x_0, \gamma)$$ |
| [Chi-squared](https://en.wikipedia.org/wiki/Chi-squared_distribution) | The sum of the squares of normal random variables | `=chisquare`$$(k)$$ |
| [Exponential](https://en.wikipedia.org/wiki/Exponential_distribution) | The waiting time until the occurence of a rare event with a specified rate. | `=exponential`$$(\lambda)$$ |
| [Gamma](https://en.wikipedia.org/wiki/Gamma_distribution) | A generalization of the sum of exponential random variables | `=gamma`$$(k, \theta)$$ |
| [Inverse-gamma](https://en.wikipedia.org/wiki/Inverse-gamma_distribution) | The reciprocal of a gamma random variable | `=invgamma`$$(\alpha, \beta)$$ |
| [Lognormal](https://en.wikipedia.org/wiki/Lognormal_distribution) | The product of many positive, independent random variables | `=lognormal`$$(\mu, \sigma)$$ |
| [Normal](https://en.wikipedia.org/wiki/Normal_distribution) | The sum of many independent random variables | `=normal`$$(\mu, \sigma)$$ |
| [Student's T](https://en.wikipedia.org/wiki/Student%27s_t-distribution) | An estimator for the difference between the true mean and the mean of N independent samples of a random variable, for small N. | `=studentt`$$(\nu)$$ |
| [Weibull](https://en.wikipedia.org/wiki/Weibull_distribution) | The lifetime of a component for which failure rate is proportional to time | `=weibull`$$(\lambda, k)$$ |
| [Uniform (continuous)](https://en.wikipedia.org/wiki/Uniform_distribution_(continuous) | An estimate where all equally sized uniforms have the same likelihood | `=uniform`$$(a,b)$$ |
| [Bernoulli](https://en.wikipedia.org/wiki/Bernoulli_distribution) | The value 1 (success) with probability $$p$$, and 0 (failure) otherwise. Used for accounting for discrete trials. | `=bernoulli`$$(p)$$, `=test`$$(p)$$ |
| [Binomial](https://en.wikipedia.org/wiki/Binomial_distribution) | The sum of $$n$$ independent Bernoulli distributions with parameter $$p$$ | `=binomial`$$(n,p)$$ |
| [Negative Binomial](https://en.wikipedia.org/wiki/Negative_binomial_distribution) | The number of success before $$r$$ failures is reached in a series of Bernoulli trials with parameter $$p$$ | `=negBinomial`$$(r,p)$$ |
| [Poisson](https://en.wikipedia.org/wiki/Poisson_distribution) | The number of events occurring in a fixed interval, with known average rate $$\lambda$$, if events occur independently. | `=poisson`$$(\lambda)$$ |
