# Dynamic-Asset-Allocation-and-Crisis-Management-Using-Deep-Reinforcement-Learing
In this project we have calculated the optimal asset allocation for each day (dynamically) with minimised risk and maximised profit using Deep Reinforcement Learning

Developed a model utilizing the Deep Deterministic Policy Gradient (DDPG) Algorithm, i.e. Q-learning with Off-Policy Gradient to optimize portfolio construction that is a continuous space, by dynamically allocating assets based on daily volatility, aiding in mitigating financial crises.

Trained two deep neural networks (DNNs) and constructed a custom Trading Environment incorporating various constraints and investor risk metrics. One DNN interact with this environment to determine optimal asset allocations for portfolio formation, the other acts like a critic to evaluate the weight performance that should maximize the Q-function.

Implemented Ornstein-Uhlenbeck noise decay to encourage exploration of the Trading Environment initially, transitioning gradually towards exploitation.

Incorporated an Exponential Moving Average baseline for rewards as a performance benchmark to enhance reward optimization.

Achieved these results (Testing Period : Aug 2022 to March 2024) :-

1. Cumulative Return - 55.18%
2. CAGR - 20.16%
3. Sharpe - 2.4
4. Annual Volatility - 11.65%
5. Sortino - 3.37
6. Calmar Ratio - 2.22
7. Ulcer Index - 0.03
8. Kelly Criterion - 19.42%
9. Daily Value at Risk (VaR) - (-1.1%)
10. Expected Shortfall (cVaR) - (-1.1%)
11. Max Drawdown - (-9.06%)
12. Average Drawdown - (-1.81%)

When benchmark - Nifty 50, Beta - 0.81 and Alpha - 0.15 and Treynor Ratio - 68.53%