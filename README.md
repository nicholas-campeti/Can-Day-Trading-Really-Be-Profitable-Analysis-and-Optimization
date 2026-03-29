*Can Day Trading Really Be Profitable? -Analysis and Optimization*

This project investigates the practical viability of intraday trading strategies, focusing on the quantitative framework established by Zarattini and Aziz. The study bridges the gap between academic skepticism and anecdotal success by implementing a high-fidelity simulation environment to test the Opening Range Breakout (ORB) strategy.

**Project Objectives**

Rigorous Validation: Full-scale replication of the original findings by Zarattini and Aziz, enriched with dynamic slippage simulations.

Robustness Enhancement: Addressing "real-world" market frictions (liquidity constraints, execution costs) that typically erode theoretical returns.

Cross-Asset Analysis: Evaluating strategy performance across a diverse range of financial instruments over a multi-year horizon.

**Methodology & Research Stages**

The research is developed through three progressive stages:
Baseline Replication: Establishing a statistical baseline of the original methodology while accounting for high-fidelity liquidity constraints.

Strategy Optimization: Integration of advanced entry filters and selection of high-efficiency instruments.

Empirical Backtesting: A comprehensive campaign across multiple assets to evaluate the strategy's robustness under various market regimes.

**Dataset & Backtesting Horizon**

Period: January 4, 2016 – October 31, 2025 (nearly a decade of market evolution).

Resolution: 5-minute intraday candles.

Data Sources: Market data gathered via IBKR API and premium datasets from Databento.

**Tech Stack & Infrastructure**

Engine: Custom-built Python simulation engine.

Architecture: SQL-based data management for large-scale backtesting.

Execution Model: Advanced modeling of commission structures and dynamic slippage simulations to ensure realistic performance metrics (Sharpe Ratio, Max Drawdown).
