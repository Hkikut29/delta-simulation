# Delta Simulation (Black-Scholes Model)

This project explores **Delta sensitivity** of European call options using the Black-Scholes model.  
Delta measures how much the price of an option is expected to move given a $1 change in the underlying stock price.  
Understanding Delta is critical for traders and risk managers because it determines hedge ratios and exposure.

---

## Key Features
- Simulates stock price paths using geometric Brownian motion.  
- Computes option prices across different strike prices, maturities, and volatilities.  
- Calculates **Delta** at each step and visualizes how it evolves as time passes.  
- Includes plots of:
  - Stock price simulations
  - Option price vs. underlying price
  - Delta vs. underlying price / time to expiration

---

## Tools & Libraries
- **Python** (NumPy, Matplotlib, SciPy)  
- **Jupyter Notebook**  

---

## Sample Outputs
- Line charts showing Delta as stock prices change.  
- Heatmaps of Delta across strike prices and maturities.  
- Visual intuition of how option Greeks behave in practice.  

---

## Why This Matters
Delta is one of the most important Greeks used in options trading and portfolio hedging.  
This project demonstrates how to:
- Implement the Black-Scholes formula in Python.  
- Simulate realistic stock price paths.  
- Quantify and visualize risk exposures faced by traders and risk managers.  

---

## How to Run
1. Clone the repository:  
   ```bash
   git clone https://github.com/Hkikut29/delta-simulation.git
   cd delta-simulation
