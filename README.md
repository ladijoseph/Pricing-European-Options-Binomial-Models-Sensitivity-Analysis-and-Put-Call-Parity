# 📉 Pricing European Options: Binomial Models, Sensitivity Analysis, and Put-Call Parity
## 📌 Overview

This project implements option pricing using the binomial model for European puts and calls, benchmarking results against the Black-Scholes model. It further examines parameter sensitivities and validates put-call parity to confirm arbitrage-free pricing.

## 🛠 Features

Define function european_put() for binomial put option pricing.

Validate convergence to Black-Scholes price with increasing steps.

Sensitivity analysis: test option price against changes in S₀, σ, r, and steps m.

Visualize pricing errors and convergence.

Verify put-call parity both graphically and via code.

---

## 📊 Insights

Binomial pricing converges quickly to Black-Scholes as steps increase.

Option values rise with volatility, time, and risk-free rate; fall with higher spot prices.

Put-call parity ensures arbitrage-free pricing and equivalence of payoff structures.

---

## 🚀 Tools

Python: numpy, scipy, matplotlib

Models: Binomial Option Pricing, Black-Scholes Formula
