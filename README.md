# Inflation Pass-Through to Retail Demand in Singapore

## Business Question
Does inflation stimulate real business activity in the short run, or does it ultimately hurt firm growth once cost pressures materialize?

## Industry
Consumer & Retail (FMCG, Supermarkets)

## Time Frame
November 2017 – October 2025  
(Pre-inflation vs post-inflation comparison)

---

## Data
- Consumer Price Index (CPI): Singapore Department of Statistics (SingStat)
- Retail Sales Index (RSI): Singapore Department of Statistics (SingStat)

All variables are transformed into growth rates where appropriate.

---

## Methodology
- Ordinary Least Squares (OLS) regression
- Current and lagged inflation variables (0, 3, 6 months)
- Time-series analysis

---

## Economic Concepts
- Inflation pass-through
- Demand elasticity
- Marginal revenue
- Cost-push inflation
- Lagged policy transmission

---

## Economic Background

### 1. Inflation Dynamics in Singapore
Post-2021 inflation in Singapore was primarily driven by **imported inflation and cost-push pressures** in a highly open economy. This was reinforced by post-pandemic demand recovery and labor market tightness.

- Wage-setting dynamics consistent with the Phillips Curve:
  - Low unemployment after reopening
  - Rising nominal wages
- Monetary Authority of Singapore (MAS) combats inflation by allowing the Singapore dollar to appreciate, lowering imported costs.
- Inflation-reducing effects materialize with a **lag** due to gradual price and wage adjustments.

### 2. Pre- vs Post-Inflation Comparison
- Retail demand dynamics before and after the inflation surge
- Exchange rate appreciation and inflation moderation (visualized in figures)

---

## Empirical Results

### Key Findings
- **Positive short-term effect of inflation on retail demand**
- **Delayed contractionary effect after cost pressures materialize**
- Inflation shocks dissipate over longer horizons

### Interpretation
- A one-unit increase in **current inflation** significantly increases RSI growth.
- Inflation lagged by **three months** has a significant **negative** effect on retail demand.
- Inflation lagged by **six months** shows no statistically meaningful impact.

This suggests that inflation initially boosts retail sales through demand-side pressures, where nominal income growth temporarily outpaces firms’ cost adjustments. However, over time, rising production costs, declining real purchasing power, and policy tightening reverse these gains.

From a microeconomic perspective:
- Demand for essential retail goods is relatively **inelastic in the short run**
- Over time, consumers adjust behavior, making demand more **price elastic**
- Firms benefit temporarily from higher prices but face declining margins and demand in the medium term

---

## Business Implications
- Short-term inflation-driven revenue gains are **not sustainable**
- Firms should anticipate delayed cost pressures when pricing aggressively
- Policymakers and businesses should monitor:
  - Monetary policy transmission
  - Exchange rate movements
  - Lagged inflation effects on real demand

---

## Limitations
- Simplified model structure:
  - Does not explicitly control for interest rates, monetary policy stance, or external demand
- Aggregate data:
  - Cannot capture firm-level heterogeneity
- Endogeneity concerns:
  - Inflation and demand may influence each other simultaneously
  - Results should be interpreted as **associational**, not causal

---

## Files
- `inflation-retail-github.ipynb` – Complete Jupyter notebook with code
- `data/` – Folder containing datasets used in the analysis  
- `figures/` – Folder with all charts and visualizations generated from the notebook  
- `inflation-retail-demand.docx` – Written report summarizing methodology, figures, results, and business insights

