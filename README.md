# Monte Carlo Stock Simulation

A simple Python project that simulates possible future stock price paths using **Monte Carlo simulation and Geometric Brownian Motion**.

## What it does

- Simulates 100 possible stock price paths
- Uses expected return and volatility as inputs
- Visualizes how uncertainty affects future prices
- Creates an animated chart and exports it as an MP4


## Key idea

Monte Carlo simulation does not predict one future price. It generates many possible outcomes based on randomness, expected return, and volatility.

## Example parameters

```python id="839kd5"
START_PRICE = 100
EXPECTED_RETURN = 0.08
VOLATILITY = 0.25
TRADING_DAYS = 252
NUM_SIMULATIONS = 100
```

## Next improvements

- Use real stock data with `yfinance`
- Estimate volatility from historical prices
- Add probability of loss and Value at Risk
- Extend the simulation to portfolios
