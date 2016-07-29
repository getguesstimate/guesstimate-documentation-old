# Distributions

Guesstimate supports a variety of statistical distributions beyond those selectable from confidence intervals. If the input parameters to these distribution functions are deterministic, 5000 samples will be generated at those parameter values. If the inputs are themselves sampled, one sample will be drawn, per input sample.

[Beta](https://en.wikipedia.org/wiki/Beta_distribution)  
`=beta(α, β)`

[Central F](https://en.wikipedia.org/wiki/F-distribution)  
`=centralF(d<sub>1</sub>,d<sub>2</sub>)`

[Cauchy](https://en.wikipedia.org/wiki/Cauchy_distribution)  
`=cauchy(x<sub>0</sub>,γ)`

[Chi-squared](https://en.wikipedia.org/wiki/Chi-squared_distribution)  
`=chisquare(k)`

[Exponential](https://en.wikipedia.org/wiki/Exponential_distribution)  
`=exponential(λ)`

[Inverse-gamma](https://en.wikipedia.org/wiki/Inverse-gamma_distribution)  
`=invgamma(α, β)`

[Gamma](https://en.wikipedia.org/wiki/Gamma_distribution)  
`=gamma(k, θ)`

[Lognormal](https://en.wikipedia.org/wiki/Lognormal_distribution)  
`=lognormal(μ, σ)`

[Normal](https://en.wikipedia.org/wiki/Normal_distribution)  
`=normal(μ, σ)`

[Student's T](https://en.wikipedia.org/wiki/Student%27s_t-distribution)  
`=studentt(ν)`


[Weibull](https://en.wikipedia.org/wiki/Weibull_distribution)  
`=weibull(λ,k)`


[Uniform (continuous)](https://en.wikipedia.org/wiki/Uniform_distribution_(continuous))  
`=uniform(a,b)`


[Bernoulli](https://en.wikipedia.org/wiki/Bernoulli_distribution)  
`=bernoulli(p), =test(p)`


[Binomial](https://en.wikipedia.org/wiki/Binomial_distribution)  
`=binomial(n,p)`

[Negative Binomial](https://en.wikipedia.org/wiki/Negative_binomial_distribution)  
`=negBinomial(r,p)`


[Poisson](https://en.wikipedia.org/wiki/Poisson_distribution)  
`=poisson(λ)`
