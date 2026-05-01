# Quant Developer & Software Engineer

Software Engineer focused on building sovereign infrastructure for quantitative analysis and automated execution in financial markets. My core focus lies in zero-latency systems, time-series data integrity, and the rigorous mathematical validation of trading strategies.

## Core Stack & Architecture

My development and production infrastructure relies on modular architectures, prioritizing absolute environment control and deterministic processing:

*   **Data Ingestion & Storage:** Implementation of asynchronous pipelines via WebSockets for real-time tick capture (L1/L2 Order Book data), persisted in high-performance time-series databases (**TimescaleDB / QuestDB**).
*   **Execution Logic & Modeling:** Development of quantitative models, risk engines, and backtesting frameworks using **Python**, **Java**, and **C**.
*   **Agentic Engineering & AI:** Orchestration of local large language models (Open Weights / DeepSeek) for sentiment analysis, codebase validation, and autonomous research agents.
*   **Infrastructure Ops:** Containerized deployments (**Docker**), sovereign local environment management in **Linux (Ubuntu)**, terminal automation (TMUX), and strict CI/CD pipelines.

##  Quantitative Philosophy

In algorithmic trading system design, I discard visual heuristics in favor of statistical robustness. Every model must be optimized for risk-adjusted returns, constantly evaluating the **Sharpe Ratio**:

$$S_p = \frac{E[R_p - R_f]}{\sigma_p}$$

I operate under the premise that a mathematical edge is only exploitable when the system is designed to perform outside the market's white noise ($\epsilon_t$). This is validated strictly through Walk-Forward Optimization and Combinatorial Purged Cross-Validation.

##  Current Projects

*   **Algorithmic Trading Engine:** Concurrent execution engine that decouples L2 data ingestion, algorithmic signal generation, and dynamic risk management.
*   **Harness Engineering Platform:** Automated testing environment built to validate the resilience of operational strategies against historical drawdowns before they ever touch a live production environment.

---

