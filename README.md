# studying_trilliondollar_equation

Schodringer’s Model is built upon the fundamentals of the Geometric Brownian Motion, Black-Scholes Model and the Time dependent Schodringer’s Equation.
It borrows the mathematical tools to implement and replicate its working to predict stock prices in the real time stock-market.

There are numerous researchers that are working in the field pf econophysics, moreover keenly interested in “Quantam Finance”. However, the proposed ideas are still experimental and not extensively in use.

My project is divided into 3 parts to build :
1.Finding the market volatility and drift
2.Normalization of the wave function
3.Using the schodringer’s wave equation


Step 1: Stock price model calculating volatility and Drift (starting point)

In the Black–Scholes framework, the stock price S(t)follows geometric Brownian motion:
dS=μS" " dt+σS" " dW_t

where:
	μ= drift
	σ= volatility
	dW_t= Wiener process (random noise)

	<img width="1195" height="672" alt="Screenshot 2025-12-16 005155" src="https://github.com/user-attachments/assets/294ebbba-67d7-499b-b80c-395eab775b26" />

 Black–Scholes Partial Differential Equation :
For an option price V(S,t), the Black–Scholes PDE is:
▭(∂V/∂t+1/2 σ^2 S^2  (∂^2 V)/(∂S^2 )+rS ∂V/∂S-rV=0)
Where-
r = risk free interest rate
V=constant potential term
S=price of stock

Using the terms of the above Black-Scholes equation the Schodringer’s Market model equation is expressed as followed-
Schrödinger-type equation -
The evolution equation for the wavefunction becomes:
▭((i∂ψ)/∂t=(-1)/2 σ^2  (∂^2 ψ)/(∂x^2 )+μ ∂ψ/∂x+Uψ)

where:
σ^2→ volatility (diffusion strength)[Kinetic of Market]
μ= drift
Ψ=wave function(probability amplitude of the stock price over time)
U→ constant potential term(Market Potential


The movement of stocks also seems to obey the Heisenberg’s uncertainity principle-
“The uncertainty principle (4) can be often seen in finance. For example, at a certain time someone knows nothing but the exact price of a stock. As a result, he certainly does not know the rate of price change at next time and the direction of the price’s movement. In other words, the uncertainty of the trend seems to be infinite” –( A quantum model for the stock market)



