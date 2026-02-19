# Can Day Trading Really Be Profitable? 
-Analysis and Optimization
Based on the paper by Carlo Zarattini and Andrew Aziz.
The project is structured into three main phases:

**Phase 1**: Replication
The first phase focused on the replication of the paper's original methodology. By replicating the study, I successfully obtained the same results as the authors, establishing a solid baseline for further work.

**Phase 2**: Improvements
In the second phase, I explored different solutions to improve the strategy presented in the paper. The enhancements included:
- Implementing additional filters for entry signals.
- Utilizing more efficient financial instruments.
- Conducting slippage simulations based on real market data to ensure more realistic performance expectations.

**Phase 3**: Results
The final phase consists of a presentation of the results obtained. The performance analysis was conducted by accounting for slippage simulations, commissions, and key market metrics such as the Sharpe Ratio. This phase also included the application of the strategy across different assets to evaluate its robustness.

**Technical Implementation & Data Sources**
- Data Sourcing: Market data for simulations were retrieved via the IBKR API and purchased from Databento to ensure high-fidelity backtesting.
- Data Management: Utilized SQL for efficient data manipulation and large-scale dataset handling.
- Simulation: Developed the simulation framework using Python to execute backtests and validate the strategy.

**Future Development**
This project represents a starting point for developing more complex initiatives, building upon the core skills and quantitative methodologies acquired throughout this study.
