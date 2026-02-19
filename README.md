# Black-Scholes Option Pricing

Two ways of pricing European options in Python - the standard analytical solution and a Monte Carlo simulation to validate it.

## What it does
- Prices European call and put options using closed-form Black-Scholes
- Runs a Monte Carlo simulation and compares the output against the analytical price
- Shows how simulation converges to the theoretical price as you increase the number of paths

## Assumptions
Standard Black-Scholes assumptions - constant vol, constant risk-free rate, no dividends, lognormal returns.

## Usage
```bash
python black_scholes.py
```

