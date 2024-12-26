# Black-Scholes Model with Monte Carlo Simulation

## ⚙️ Project Overview

This project aims to determine the price of a call option using the Black-Scholes model in conjunction with Monte Carlo simulations. The simulation provides a robust approach for approximating the value of financial derivatives by generating multiple paths for the underlying asset's price. This method is particularly useful when analytical pricing methods are difficult to apply.

## 🥊 American vs. European Options
In this project, we assume that the underlying stock does not pay dividends, and thus we treat American and European call options as equivalent. This assumption simplifies the valuation process, as there is no advantage to early exercise when dividends are not involved. Therefore, the pricing methodology used here applies equally to both American and European options under these conditions.

## 🗝️ Key Features
- Implementation of the Black-Scholes model for option pricing.
- Monte Carlo simulations to estimate the call option price.
- Assumes no dividends are paid by the underlying stock.
- Equivalence between American and European call options due to the no-dividend condition.
