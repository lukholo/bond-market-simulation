# Bond Market Simulator

A hands-on exploration of how bond markets work by building a dynamic simulation from scratch.
This project focuses on intuition, exposure, and experimentation with fixed income concepts such as yield curves, duration, rate shocks, and market behavior.

---

## Project Goal

Build a progressively richer simulation of a bond market:

* Start with basic bond pricing
* Construct a yield curve
* Introduce interest rate dynamics
* Simulate market participants
* Model macroeconomic scenarios
* Track portfolio performance

The emphasis is on understanding *how the system behaves*, not just implementing formulas.

---

## What This Project Explores

* Zero-coupon bond pricing
* Yield-to-maturity mechanics
* Term structure of interest rates
* Yield curve shapes (normal, inverted, flat)
* Interest rate shocks
* Duration intuition
* Market demand effects
* Portfolio mark-to-market dynamics
* Macro-driven rate environments

---

## Project Structure

```
bond-market-sim/
│
├── notebooks/
│   └── bond_market_v0.ipynb
│
├── src/
│   └── bonds.py
│
├── data/
│
├── README.md
└── requirements.txt
```

This structure will evolve as the simulation becomes more sophisticated.

---

## Roadmap

### Phase 1 — Core Engine

* Bond object
* Zero-coupon pricing
* Basic yield inputs

### Phase 2 — Yield Curve

* Multiple maturities
* Curve visualization
* Term structure generation

### Phase 3 — Market Dynamics

* Interest rate shocks
* Curve steepening/inversion
* Time evolution

### Phase 4 — Participants

* Institutional investors
* Central bank behavior
* Demand-driven price changes

### Phase 5 — Portfolio Layer

* Holdings tracking
* Mark-to-market valuation
* Duration exposure

### Phase 6 — Scenario Engine

* Inflation shock
* Recession dynamics
* Policy response simulation

---

## Philosophy

This project treats the bond market as a **system**:

* Prices reflect expectations
* Expectations drive yields
* Yields shape the curve
* The curve signals macro conditions

The simulation is built incrementally so that each layer adds conceptual depth.

---

## Current Status

Version: `v0.1`

* Zero-coupon bond model
* Basic yield curve generation
* Initial visualization

---

## Getting Started

Open the notebook in Google Colab and run cells sequentially.
The simulation builds step-by-step from the core bond engine.

---

## Future Ideas

* Stochastic interest rate paths
* Multiple countries
* Credit spreads
* Auction-based bond issuance
* Liquidity constraints
* Swap curve vs government curve
* Interactive dashboard

---

## Why This Exists

Bond markets are central to:

* Monetary policy
* Inflation expectations
* Economic cycles
* Asset pricing

This project builds intuition through construction rather than abstraction.

---

## License

MIT License (can be updated later)

---

Once you add this, your repo already reads like a **serious quantitative finance project**.
