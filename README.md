# 👋 Hi, I'm Moskong

**Quantitative Developer | Trading Systems Architect (TradFi / DeFi)**
`Python` • `GPU Accelerated Computing` • `Async Systems` • `Market Microstructure`

---

## 🧠 About Me
I am a self-driven quantitative developer and systems architect with a strong focus on building **high-performance execution engines** across FX, Crypto, and DeFi markets. 

My work sits at the intersection of **market microstructure, execution engineering, and risk-aware strategy design**. Rather than optimizing for hype or backtest vanity metrics, I prioritize:
- **Realistic execution assumptions** (Slippage, latency, spread dynamics)
- **Anti-fragile risk frameworks** (Circuit breakers, heartbeat monitoring)
- **Clear decision rules and technical auditing** (Preventing repainting & forward-looking biases)
- **Post-mortem driven system improvement**

Most of my projects originate from *failed ideas*, observed market inefficiencies, and infrastructure pain points encountered during live experimentation.

---

## 🧰 Core Tech Stack
- **Architecture & Trading:** Python (AsyncIO, data pipelines), Docker (reproducible environments)
- **High-Performance Computing:** Numba (CUDA / GPU Acceleration)
- **TradFi Integration:** MetaTrader 5 API (Multi-account FX Execution)
- **Machine Learning & Data:** XGBoost, Pandas, Numpy, Parquet
- **Crypto / DeFi Ecosystem:** Hyperliquid L1 (App-chain DEX), Solana (Raydium), Jupiter SDK, REST & WebSocket APIs

---

## 🚀 Selected Projects

### 🔹 [Quant-Fleet Execution Engine (src16)](https://github.com/moskong-quant/Quant-Fleet-Execution-Engine-src16)
*A production-grade, multi-account quantitative trading system prioritizing architectural stability and latency awareness.*
- **System Architecture:** Engineered a folder-segregated execution model allowing multiple MetaTrader 5 terminals to run in isolation.
- **GPU-Accelerated Backtesting:** Leveraged Numba (CUDA) to process millions of rows of M1 data, reducing grid search times from hours to seconds.
- **Risk Engineering:** Integrated a Global Circuit Breaker (Max Drawdown halt) and hourly Heartbeat monitoring for 24/7 reliability.
- **Technical Auditing:** Resolved the "Repainting Paradox" via strict candle-close verification logic.

### 🔹 [Sniper v3.0: FX Mean Reversion Engine(src9)](https://github.com/moskong-quant/Sniper-v3-Mean-Reversion-GPU)
*A high-performance quantitative trading system for EURUSD utilizing GPU computing and probabilistic AI.*
- **GPU Parallel Computing:** Processed 4,000,000+ rows of M1 data in seconds using Numba/CUDA.
- **Probabilistic Filtering:** XGBoost model acts as a gatekeeper to filter out low-probability trades (>70% confidence required).
- **Execution First:** Applied dynamic volatility-based exits (3.5x TP / 1.5x SL ATR) and a strict 6-minute time barrier.
- **Risk Validated:** Survived 5,000 Monte Carlo simulations to ensure anti-fragility against market regime shifts.

### 🔹 [Harvest Arbitrage Engine (src10)](https://github.com/moskong-quant/Harvest-Arbitrage-Engine-src10)
*An AI-orchestrated R&D project focused on CEX/DEX arbitrage infrastructure.*
- **Architectural Pivot:** Initially explored Solana CLMM binary decoding, but post-mortem analysis revealed an insurmountable latency disadvantage. Strategically pivoted to a latency-aware architecture focusing strictly on Hyperliquid L1 and Binance.
- **Risk Engineering:** Implemented a multi-layered risk framework featuring dynamic circuit breakers, a "Dust Reverter," and "Ghost Book" stale data protection.
- **Outcome:** Exposed real-world constraints like thin liquidity traps and WebSocket latency spikes. Sub-strategies showing negative expectancy after real-world slippage factoring were intentionally terminated—**discipline over bias**.

### 🔹 EMA Trend Crossover (src6_EMA_Trend_Crossover)
*A classic trend-following strategy used as a baseline research framework.*
- Full backtesting pipeline with parameter sensitivity analysis and drawdown evaluation.
- **Purpose:** Establish a robust foundation and validate discipline before pursuing complex strategies.

---

## 📊 Research & Development Philosophy
> *"No trade is better than a bad trade."*
- If costs > expected edge → do not execute.
- Strategies must survive **execution reality**, not just backtests.
- Failure logs are as valuable as profitable runs.

---

## 🎯 Current Focus
Seeking roles where engineering rigor meets financial markets:
- **System Analyst / Trading Systems Architect**
- **Quantitative Developer**
- **Algorithmic Trading Engineer**

*Actively building: High-availability execution fleets, low-latency market monitoring, and cross-market infrastructure.*

---

## 📫 Contact
- **LinkedIn:** [Supayos Phumchaiya](https://www.linkedin.com/in/supayos-phumchaiya-40b4033b0)
- **Email:** [supayos.phum@gmail.com](mailto:supayos.phum@gmail.com)
- **GitHub:** [moskong-quant](https://github.com/moskong-quant)
