Statistical Distributions Problem Solutions

1. Exponential Distribution

Problem Statement: 

A service receives 3 calls per hour. Find the probability that the next call is received after 15 minutes.

Solution Steps:

1. Convert Time: 
   - 15 minutes = 0.25 hours.

2. Formula: 
   P(X > x) = e^{-\lambda x}
   Where \( \lambda = 3 \).

3. Calculation:
   P(X > 0.25) = e^{-3 \times 0.25} \approx e^{-0.75} \approx 0.4724

Conclusion:
The probability that the next call is received after 15 minutes is approximately 47.24%.

---

2. Normal Distribution

Problem Statement: 

Given a normally distributed variable \( X \) with a mean \( \mu = 100 \) and a standard deviation \( \sigma = 15 \), calculate the probability that \( X \) is less than 110.

Solution Steps:

1. Calculate the Z-score:
   Z = \frac{X - \mu}{\sigma} = \frac{110 - 100}{15} \approx 0.67

2. Use the Z-table:
   - Lookup \( P(Z < 0.67) \approx 0.7486 \).

Conclusion:
The probability that a randomly selected value from this normal distribution is less than 110 is approximately 74.86%.

---

3. Poisson Distribution

Problem Statement: 

A factory finds an average of 2 defects per day. Find the probability of finding exactly 3 defects in one day.

Solution Steps:

1. Formula: 
   P(X = k) = \frac{e^{-\lambda} \lambda^k}{k!}
   Where \( \lambda = 2 \) and \( k = 3 \).

2. Calculation:
   P(X = 3) = \frac{e^{-2} \cdot 2^3}{3!} \approx 0.1804

Conclusion:
The probability of finding exactly 3 defects is approximately 18.04%.

---

4. Binomial Distribution

Problem Statement: 

What is the probability of getting exactly 5 heads in 10 flips of a fair coin (p = 0.5)?

Solution Steps:

1. Formula: 
   P(X = k) = \binom{n}{k} p^k (1-p)^{n-k}
   Where \( n = 10 \), \( k = 5 \), \( p = 0.5 \).

2. Calculation:
   P(X = 5) = \binom{10}{5} (0.5)^5 (0.5)^{5} \approx 0.2461

Conclusion:
The probability of getting exactly 5 heads is approximately 24.61%.

---

5. Triangular Distribution

Problem Statement: 

What is the probability that a variable is less than 3 with \( a = 1 \) and \( b = 5 \)?

Solution Steps:

1. Formula: 
   P(X < x) = \frac{x - a}{b - a}

2. Calculation:
   P(X < 3) = \frac{3 - 1}{5 - 1} = \frac{2}{4} = 0.5

Conclusion:
The probability that a variable is less than 3 is 50%.

---

6. Lognormal Distribution

Problem Statement: 

If a variable \( X \) is lognormally distributed, with \( \mu = 0 \) and \( \sigma = 1 \), calculate \( P(X < 10) \).

Solution Steps:

1. Convert to Z-score:
   Y = \ln(10)

2. Use Z-Score Formula:
   Z = \frac{Y - \mu}{\sigma} = \frac{\ln(10) - 0}{1} \approx 2.3026

3. Lookup in Z-table:
   - \( P(Z < 2.3026) \approx 0.9890 \).

Conclusion:
The probability that \( X < 10 \) is approximately 98.90%.

---

7. Gamma Distribution

Problem Statement: 

If \( k = 2 \) and \( \theta = 3 \), find \( P(X < 6) \).

Solution Steps:

1. Formula: 
   P(X < x) = \frac{1}{\Gamma(k)} \int_0^x \frac{t^{k-1} e^{-\frac{t}{\theta}}}{\theta^k} dt

2. Calculation:
   - Compute the integral for \( x = 6 \).

Conclusion:
Use numerical methods or software to find this probability.

---

8. Beta Distribution

Problem Statement: 

For \( \alpha = 2 \) and \( \beta = 5 \), calculate \( P(X < 0.5) \).

Solution Steps:

1. Formula: 
   P(X < x) = \frac{\int_0^x t^{\alpha-1} (1-t)^{\beta-1} dt}{B(\alpha, \beta)}

2. Calculation:
   - Compute the integral for \( x = 0.5 \).

Conclusion:
Use numerical methods or software to find this probability.

---

9. Weibull Distribution

Problem Statement: 

What is the probability that a product lasts less than 5 years with \( k = 1.5 \) and \( \lambda = 10 \)?

Solution Steps:

1. Formula: 
   P(X < x) = 1 - e^{-\left(\frac{x}{\lambda}\right)^k}

2. Calculation:
   P(X < 5) = 1 - e^{-\left(\frac{5}{10}\right)^{1.5}} \approx 0.293

Conclusion:
The probability that the product lasts less than 5 years is approximately 29.3%.

---

10. Uniform Distribution

Problem Statement: 

What is the probability that a variable is less than 3 in a range from 1 to 5?

Solution Steps:

1. Formula: 
   P(X < x) = \frac{x - a}{b - a}

2. Calculation:
   P(X < 3) = \frac{3 - 1}{5 - 1} = 0.5

Conclusion:
The probability that the variable is less than 3 is 50%.
