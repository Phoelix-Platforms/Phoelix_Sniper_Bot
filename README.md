# Phoelix Intraday Bot (Babel 2.5)

<p align="center">
  <strong>The core analytical intelligence engine powering the Phoelix algorithmic trading infrastructure.</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Script%20Version-v6.0-007ACC?style=flat-square" alt="Pine Script Version">
  <img src="https://img.shields.io/badge/Environment-TradingView-2962FF?style=flat-square" alt="TradingView">
</p>

---

## 🎯 Overview

**Phoelix Intraday Bot** is the proprietary analytical engine running natively on TradingView. Built with Pine Script v6, it scans market structures in real time, isolates high-probability intraday trend setups for Gold and US Oil, and instantly fires off structured alert data to the execution pipeline.

---

## ⚡ Core Logic Features

* **Dual-Filter Trend Tracking:** Merges an aggressive tracking engine ("Sniper Line") with a long-term direction matrix ("Anchor Line") to guarantee trade execution only occurs with macro-trend alignment.
* **Intraday Optimization:** Finely tuned for rapid 15-minute chart cycles to capture high-velocity movements in volatile commodity pairs (`XAUUSD`, `USOIL`).
* **Automated Risk Calculations:** Built-in allocation engine that dynamically packages risk variables and asset-specific lot sizes (`tv_gold_lot`, `tv_usoil_lot`) directly into the alert payload.
* **Capital Protection Guard:** Features a hard New York session cutoff matrix to halt trading operations automatically before market close spreads widen.

---

<p align="center">
  &copy; 2026 Phoelix Platforms Ltd. All Rights Reserved.
</p>
