# solutions-for-the-option-problems4

1  Price a six month American call option struck at $12 on a non-dividend paying stock whose price is currently $10 using the implicit
finite difference method. Assume a volatility of 18% annualized, 2% annual risk free rate, use 24 time steps, let S max = $95, and set
∆S = 1.
(a) Estimate ∆, Γ, and Θ.
(b) Use the control variate method and the analytic Black-Scholes European formula to adjust your price.
2. Consider the following discrete scenarios for securities A and B.

                  S1  S2   S3
          p(Si) 0.02 0.04 0.94
            A  -1000  0   100
            B     0 -1000 100
What is the 95%-CVaR for A, B, and 1/2*A+1/2*B? Compare these results to the VaR calculations done in class and make a comment on 
subadditivity.
3. Assume the annualized covariance between two stocks is given by
    
    Σ =matrix(0.09 .018 .018 .04)
    
In the following problems, find analytic solutions:
(a) What is the three day 99% VaR for a portfolio long 150 shares of each stock under the assumption of joint normality?
(b) What is the three day 99% VaR for a portfolio long 150 shares of each stock under the assumption that the stocks are jointly 
distributed as a Student t with 5 degrees of freedom?

In the following problems, use Monte Carlo simulations with 10,000 simulations for the state variable:
(a) What is the three day 95% VaR for a portfolio long 150 shares of each stock under the assumption of joint normality? What is the
95% CVaR?
(b) What is the three day 95% VaR for a portfolio long 150 shares of each stock under the assumption that the stocks are jointly
distributed as a Student t with 5 degrees of freedom? What is the 95% CVaR?
(c) Suppose the stock with volatility 30% trades at $40 and the stock with volatility 20% trades at $100 and you are short 150 at the 
money European calls on each stock expiring in six months. What is the two day 99% VaR for each of these straddle portfolios in isolation?
(d) What is the two day 99% VaR for a portfolio long 150 shares of each stock and short 150 at the money European calls on each stock if 
the underlyings are assumed to be jointly normally distributed? Repeat with assumption of joint Student t with 5 degrees of freedom.
