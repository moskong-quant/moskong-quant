# 👋 Hi, I'm Moskong

**Quantitative Trader | Trading Systems Developer (Crypto / DeFi)**  
Python • Async Systems • Arbitrage • Solana • On-chain Data

---

## 🧠 About Me

I am a self-driven quantitative trader and trading systems developer with a strong focus on **crypto and DeFi markets**.  
My work sits at the intersection of **market microstructure, execution engineering, and risk-aware strategy design**.

Rather than optimizing for hype or backtest vanity metrics, I prioritize:

- Realistic execution assumptions  
- Liquidity & slippage awareness  
- Clear decision rules and failure analysis  
- Post-mortem driven system improvement  

Most of my projects originate from **failed ideas, observed market inefficiencies, and infrastructure pain points** encountered during live experimentation.

---

## 🧰 Core Tech Stack

- **Python** (AsyncIO, data pipelines, strategy logic)
- **Solana / DeFi** (Raydium, on-chain liquidity pools)
- **Arbitrage & Market Neutral Strategies**
- **Jupiter SDK / API** (execution routing)
- **REST & WebSocket APIs**
- **Docker** (reproducible environments)
* **Machine Learning & Data:** XGBoost, Pandas, Numpy
* **High-Performance Computing:** Numba (CUDA/GPU Acceleration)
* **TradFi Integration:** MetaTrader 5 API (FX Execution)
---

## 🚀 Selected Projects

### 🔹 Sniper v3.0: FX Mean Reversion Engine ([Sniper-v3-Mean-Reversion-GPU](https://github.com/moskong-quant/Sniper-v3-Mean-Reversion-GPU))
A high-performance quantitative trading system for EURUSD utilizing GPU computing and probabilistic AI.

* **GPU Parallel Computing:** Processed 4,000,000+ rows of M1 data in seconds using Numba/CUDA.
* **Probabilistic Filtering:** XGBoost model acts as a gatekeeper to filter out low-probability trades (requiring >70% confidence).
* **Execution First:** Applied dynamic volatility-based exits (3.5x TP / 1.5x SL ATR) and a strict 6-minute time barrier.
* **Risk Validated:** Survived 5,000 Monte Carlo simulations to ensure anti-fragility against market regime shifts.
* **Status:** Forward testing on live Cent accounts to measure real-world slippage and execution latency.

### 🔹 EMA Trend Crossover (`src6_EMA_Trend_Crossover`)
A classic trend-following strategy used as a **baseline research framework**.

- Full backtesting pipeline
- Parameter sensitivity analysis
- Risk & drawdown evaluation
- Designed to validate discipline, not curve-fitting

> Purpose: Establish a robust foundation before pursuing complex strategies.

---

### 🔹 Harvest Arbitrage (`src10_Harvest_Arbitrage`)
A multi-layer crypto arbitrage research & monitoring system.

- Spot ↔ Perpetual basis analysis
- Cross-venue price monitoring (CEX / DEX)
- Slippage, liquidity depth, and execution cost awareness
- On-chain price derivation from Raydium pools (Solana)

This project exposed real-world constraints such as:
- Thin liquidity
- Execution latency
- Basis instability
- Infrastructure fragility

> Some sub-strategies were intentionally **terminated** after post-mortem analysis  
> — discipline over bias.

---

## 📊 Research & Development Philosophy

- **No trade is better than a bad trade**
- If costs > expected edge → do not execute
- Strategies must survive *execution reality*, not just backtests
- Failure logs are as valuable as profitable runs

---

## 🎯 Current Focus (Next 6 Months)

- Junior Quantitative Trader  
- Trading Systems Developer  
- Crypto Quant / Research-Oriented Roles  

Actively building:
- Automated execution engines
- Low-latency market monitoring
- Robust arbitrage infrastructure

---

## 📫 Contact

- GitHub: https://github.com/moskong-quant
