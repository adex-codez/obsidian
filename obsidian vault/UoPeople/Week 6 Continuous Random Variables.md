
Chapter objectives
- Recognize and understand continuous probability density function in general.
- Recognize the uniform probability distribution and apply it appropriately
- Recognize the exponential probability distribution and apply it appropriately.

## Properties of Continuous Probability Distributions

The graph of a continuous probability distribution is a curve, The area under the curve is the probability.
The curve is called the probability density function(pdf). f(x) is the symbol that is used to represent the curve. f(x) is the function that corresponds to the graph. We use the density function f(x) to draw the graph of the probability distribution.

Area under the curve is given by another function which is the cumulative distribution function(cdf). The cumulative distribution function is used to evaluate the probability as area.

The following are the properties of continuous probability distributions:
- The outcomes are not counted they are measured.
- The entire area under the curve and above the x-axis is equal to one.
- Probability is found for the intervals of x values rather than individual x values
- P(c < x < d) is the probability that the random variable X is between the intervals of the value of c and d. P(c < x  < d) is the area under the curve, above the x-axis, the right of c and left of d.
- P(x = c) = 0. The probability that x takes on any single individual value is 0. The area below the curve, above the x-axis and between  x = c and x = c has no width, and therefore no area. since the probability is the same as the area. the probability is also zero.
- P(c < x  < d) is the same as P(c <= x <= d) because the probability is equal to the area.

For continuous probability distributions, PROBABILITY = AREA 

### Continuous Probability Functions

Area = base(height)
where height = f(x), 

### The Uniform Distribution

The uniform distribution is a continuous probability distribution and is concerned with events that are likely to occur. When solving uniform distribution we should check if the data is inclusive or exclusive of endpoints.

The notation for the uniform distribution is X ~ U(a,b), where a is the lowest value while b is the highest value.
The probability density function f(x) = 1 / b - a for P(a <= x <= b).

mean = µ = a + b / 2
standard deviation = σ = b - a / sqrt(12)

### The Exponential Distribution

The exponential distribution is often concerned with the amount of time until a specific event occurs.

m, the decay parameter 

m = 1 / µ
standard deviation = σ = µ.

The notation for the exponential distribution is X ~ Exp(m)

The probability density function is f(x) = me^-mx. The number e = 2.71828182846...

The curve is:
f(x) = 0.25e ^ -0.25x where x is at least zero and m = 0.25.

for example f(5) = 0.25e^ - (0.25) (5).

The cumulative probability function gives the area under the curve.
P(x < x) = 1 - e^-mx
P(x > x) = e^-mx

The formula for the percentile of k is K = ln(1 - AreaToTheLeft) / -m

P(x < k) = (k - 0) * 1/40
0.85 = k * 1/40
0.85  = k / 40
k = 0.85 * 40
k = 34