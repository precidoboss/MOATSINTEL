# MOATSINTEL
# 🧠 MOATS INTEL

**Your edge in the Moats ecosystem.**

MOATS INTEL is a real-time intelligence dashboard for the Moats protocol. It tracks moat activity, rewards, wallet rankings, and ecosystem signals to help users make smarter participation decisions.

The platform aggregates moat data and transforms it into actionable insights such as opportunity signals, wallet strategy analysis, and optimal allocation planning.

---

# 🚀 Overview

MOATS INTEL tracks all **11 Moats live**, providing insight into:

* Staked / Locked / Burned positions
* Token price data
* Reward history
* Council Score rankings
* Ecosystem activity signals

Users can plan their strategy using the **Investment Allocator** and identify high-potential moats using the **Signals Engine**.

---

# ⬡ What is a Moat?

A **Moat** is a tokenized vault in the Moats Protocol.

Users participate by depositing a moat's token using one of three mechanisms:

| Action | Multiplier     |
| ------ | -------------- |
| Stake  | **1×**         |
| Lock   | **2.04× – 5×** |
| Burn   | **10×**        |

Each action generates **Moat Points**, which determine ranking and reward allocation.

Points are **isolated per moat**, meaning users must participate in multiple moats to maximize ecosystem rewards.

---

# 🏰 Score System

## Council Score

```
Council Score = Total Points × Diversity Multiplier
```

Diversity Multiplier ranges from:

```
1.0× → 1.5×
```

This score determines:

* governance voting weight
* ecosystem ranking

---

## Fort Score

```
Fort Score = Sum of all Moat Points
```

Your **percentage of the ecosystem’s total Fort Score** determines your share of future airdrops.

---

# ⏳ Lock Multipliers

| Lock Duration | Multiplier |
| ------------- | ---------- |
| 1 Day         | 2.04×      |
| 30 Days       | 2.31×      |
| 90 Days       | 2.73×      |
| 180 Days      | 3.23×      |
| 240 Days      | 3.52×      |
| 365 Days      | 4.00×      |
| 540 Days      | 4.57×      |
| 730 Days      | 5.00×      |

Longer lock durations significantly increase Moat Point rewards.

---

# ⚠️ EEL Penalty Table

If users exit a lock early, the **Early Exit Lock (EEL) penalty** applies.

| Completion | Penalty |
| ---------- | ------- |
| <10%       | 95%     |
| 10%        | 90%     |
| 20%        | 80%     |
| 30%        | 70%     |
| 40–50%     | 60%     |
| 60%        | 50%     |
| 70%        | 40%     |
| 80%        | 30%     |
| 90%        | 20%     |
| >90%       | 10%     |
| 100%       | 0% 🎉   |

---

# ✨ Features

## 💰 Investment Allocator

Enter your **USDC budget** and preferred strategy.

The allocator:

* identifies optimal moats
* calculates token purchase quantities
* estimates Moat Points
* predicts rank and ecosystem share

This uses a **supply-share projection model** to estimate outcomes.

---

## 🔬 Signals Engine

Auto-generated intelligence updated **every 15 seconds**.

Signals include:

* whale accumulation detection
* low-competition moats
* reward momentum shifts
* diversity multiplier opportunities

---

## ⬡ Moat Explorer

Each moat includes a full detail panel:

* **Overview** – total staked / locked / burned
* **Token & Price** – live market data via DexScreener
* **Leaderboard** – ranked wallets with Zephyr usernames
* **Rewards** – distribution and history

---

## 🔎 Wallet Analyzer

Analyze any wallet address to view:

* Council Score
* Fort Score
* ecosystem share percentage
* per-moat rankings
* strategy gap analysis

The system highlights **missing opportunities to increase your score.**

---

## 📡 Activity Feed

A real-time event stream of protocol activity.

Features:

* event type filtering
* time filters (days)
* token amount tracking
* estimated values when precise data is unavailable

This provides a **live view of the ecosystem.**

---

# 🧰 Technology

MOATS INTEL is designed to be lightweight and accessible.

Core stack:

```
HTML
JavaScript
TailwindCSS
Chart.js
Moats API
DexScreener API
```

The application runs entirely in the browser and consumes public data APIs.

---

# 📡 Data Sources

Primary data is retrieved from the **Moats API**.

Endpoints include:

```
/events
/moat-points/all
```

Market pricing is fetched from **DexScreener**.

---

# 🏗 Installation

Clone the repository:

```bash
git clone https://github.com/precidoboss/moatsintel.git
```

Navigate into the project:

```bash
cd moats-intel
```

Open the app:

```
index.html
```

No backend or build tools required.

---

# 🌐 Deployment

MOATS INTEL can be deployed easily using:

* GitHub Pages
* Netlify
* Vercel

Because the app is fully client-side, deployment requires only static hosting.

---

# 🎯 Purpose

MOATS INTEL expands the **Moats ecosystem surface area** by transforming raw protocol data into actionable intelligence.

The goal is to help users:

* discover high-potential moats
* allocate capital efficiently
* track ecosystem activity
* optimize their Council Score strategy

---

# 📜 License

MIT License

---

# 🏆 Built For

Moats Extensions Hackathon
