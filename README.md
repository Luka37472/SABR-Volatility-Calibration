# SABR Volatility Calibration & Option Pricing

Developed during the early stages of a bidisciplinary Physics and Mathematics BSc, this project implements a quantitative framework to price European options by calibrating the SABR stochastic volatility model using Hagan's asymptotic expansion. The traditional Black-Scholes model relies on the restrictive assumption of constant volatility across all strikes and maturities, which fails to reflect real-world market dynamics. By leveraging the SABR model, this implementation successfully captures the empirical volatility smile and skew, overcoming the limitations of Black-Scholes to provide a more rigorous and accurate approach to derivative pricing.

## Requirements

The following Python libraries are required to execute the mathematical calibration, fetch live market data, and generate the volatility visualizations:

* `numpy`
* `pandas`
* `scipy`
* `matplotlib`
* `yfinance`
