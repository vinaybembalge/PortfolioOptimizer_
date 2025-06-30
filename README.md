Portfolio Optimizer

This project is a Python tool that helps **analyze** and **optimize** a stock
portfolio. It uses **historical data** to calculate key financial statistics,
finds the *optimal mix* of stocks to get the best return for the risk taken
(using Modern Portfolio Theory), and then presents the findings through
**visualizations and reports**.


## Visual Overview

```mermaid
flowchart TD
    A0["PortfolioOptimizer Class
"]
    A1["Historical Returns Data
"]
    A2["Statistical Analysis (Expected Returns, Covariance Matrix)
"]
    A3["Portfolio Performance Calculation
"]
    A4["Portfolio Optimization Process
"]
    A5["CAPM Beta Analysis
"]
    A6["Visualization and Reporting
"]
    A0 -- "Loads data" --> A1
    A0 -- "Runs calculation" --> A2
    A0 -- "Runs calculation" --> A5
    A0 -- "Orchestrates" --> A4
    A0 -- "Generates output" --> A6
    A2 -- "Processes" --> A1
    A5 -- "Analyzes" --> A1
    A4 -- "Uses stats from" --> A2
    A3 -- "Calculates using stats from" --> A2
    A4 -- "Calls function" --> A3
    A4 -- "Provides optimal weights to" --> A0
    A6 -- "Uses results from" --> A0
```

## Chapters

1. [PortfolioOptimizer Class
](01_portfoliooptimizer_class_.md)
2. [Historical Returns Data
](02_historical_returns_data_.md)
3. [Statistical Analysis (Expected Returns, Covariance Matrix)
](03_statistical_analysis__expected_returns__covariance_matrix__.md)
4. [Portfolio Performance Calculation
](04_portfolio_performance_calculation_.md)
5. [Portfolio Optimization Process
](05_portfolio_optimization_process_.md)
6. [CAPM Beta Analysis
](06_capm_beta_analysis_.md)
7. [Visualization and Reporting
](07_visualization_and_reporting_.md)

---
