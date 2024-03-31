# README

## Binomial Tree Model for Option Pricing

This exercise, set within a derivatives class, develops code to implement the binomial tree model for option pricing.

### Key Features
- Establishes essential parameters for the binomial model, including risk-neutral probability ($q$), risk-free interest rate ($r$), time increment ($\delta$), number of time steps ($T$), and factors for stock price movements ($U$ and $D$).
- Constructs the binomial tree to represent potential future stock prices, showcasing the different paths the stock price might take and their impact on option valuation.
- Defines and applies a European call and put option's payoff function at the tree's terminal nodes, with backward induction used to calculate option prices at earlier nodes.
- Calculates the delta values at each node, indicating the units of the underlying asset to buy or sell to hedge the option's risk.

### Development Environment
- **Python libraries:** `numpy`, `matplotlib`
- **Parameters:** `q`, `r`, `delta`, `T`, `gamma`, `S0`, `U`, `D`, `K`
- **Functions:** Payoff function `H(S, K)`, stock price matrix population `populateS(S0, U, D, T, S)`

### Visualization
- Utilizes `matplotlib` to plot the binomial tree, displaying option prices and delta values at each node for clear, visual representation of the model's outcomes.

### Execution
- Ensure all dependencies are installed.
- Run the script in a Python environment to observe the binomial tree construction, option pricing, and hedging strategy visualization.
