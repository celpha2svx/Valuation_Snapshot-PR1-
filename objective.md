# Project 1: Dangote Cement — Relative Valuation Snapshot

**Date:** October 2026

## Problem Statement
Estimate whether Dangote Cement (ticker: DANGCEM, Nigerian Exchange) is cheap, 
fair, or expensive relative to three industry peers, as of October 2026, based 
on six publicly available financial ratios.

## Decision Rule
Compute six ratios for Dangote and three peers:
- P/E, EV/EBITDA, P/B, ROE, Debt/Equity, Revenue Growth (3-yr CAGR)

Compare Dangote's ratios to the **median** of the peers:
- If Dangote is >10% below peer median on the majority of ratios → **cheap**
- If Dangote is >10% above peer median on the majority of ratios → **expensive**
- If Dangote is within ±10% of peer median → **fair**

## Falsifiable Conditions
I will admit my conclusion is invalid if:

1. **Stale data:** The financial data I pull is more than 12 months old.
2. **Incomparable peers:** At least two of my three peers operate under a 
   fundamentally different business model (e.g., distribution-only vs. 
   integrated producer).
3. **Documented reason for the gap:** A recent, publicly disclosed event 
   (acquisition, FX shock, regulatory change, divestiture) explains the 
   ratio difference. In that case, the gap is not a mispricing signal.