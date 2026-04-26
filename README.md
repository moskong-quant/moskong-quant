# 👋 Hi, I'm Moskong

**Proprietary FX Trader | Quantitative System Architect**
`Python` • `GPU Accelerated Computing` • `Async Systems` • `Risk-First Engineering`

---

## 🧠 About Me
I am a **Veteran FX Trader evolved into a Quantitative Systems Architect**. After 13 years of navigating global markets and experiencing extreme market regimes (like the AUD/CHF Flash crash and FTX collapse), I transitioned from discretionary trading to fully automated, AI-orchestrated execution.

I don't build systems to chase vanity backtest metrics. I build them to survive. My work sits at the intersection of **market microstructure, execution engineering, and risk-aware strategy design**, prioritizing:
- **Anti-fragile risk frameworks** (Circuit breakers, heartbeat monitoring)
- **Realistic execution assumptions** (Slippage, latency, spread dynamics)
- **Clear decision rules and technical auditing** (Preventing repainting & forward-looking biases)
- **AI-Orchestrated Prototyping** (Rapid development with 100% human oversight on core logic)

Most of my projects originate from *failed ideas*, "Market Scars," and infrastructure pain points encountered during live proprietary trading.

---

## 🧰 Core Tech Stack
- **Architecture & Trading:** Python (Advanced AsyncIO, data pipelines), Docker (reproducible environments)
- **High-Performance Computing:** Numba (CUDA / GPU Acceleration)
- **TradFi Integration:** MetaTrader 5 API (Multi-account FX Execution)
- **Machine Learning & Data:** XGBoost, Pandas, SQL, Parquet
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

## 📊 Research & Development Philosophy: "Market Scars"
> *"No trade is better than a bad trade."*
- If costs > expected edge → do not execute.
- Strategies must survive **execution reality**, not just backtests.
- Failure logs from past liquidations are my most valuable data points for infrastructure improvement.

---

## 🎯 Current Focus
Seeking to transition 13 years of independent market experience into an institutional environment. I aim to leverage my failure-driven development approach and execution rigor to protect and grow enterprise capital. 

Targeting roles where engineering meets financial markets:
- **Proprietary FX Trader**
- **System Analyst / Trading Systems Architect**
- **Quantitative Analyst / Developer**

---

## 📫 Contact
- **LinkedIn:** [Supayos Phumchaiya](https://www.linkedin.com/in/supayos-phumchaiya-40b4033b0)
- **Email:** [supayos.phum@gmail.com](mailto:supayos.phum@gmail.com)
- **GitHub:** [moskong-quant](https://github.com/moskong-quant)
