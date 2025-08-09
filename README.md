# M2-BTC-SP500-Liquidity-Analysis

## Project Overview
This project investigates the relationship between global liquidity, represented by the **M2 money supply**, and the performance of two major assets:
1. **Bitcoin (BTC)** – as a representative of high-risk digital assets  
2. **S&P 500 Index** – as a representative of traditional financial markets  

The analysis uses **weekly data from January 2022 to present** and applies **cross-correlation** techniques to explore potential lead-lag effects between liquidity changes and asset price movements.

---

## Motivation
According to the **Quantity Theory of Money**, asset prices tend to follow long-term changes in the money supply.  
This project aims to empirically test whether shifts in global liquidity (M2) can be observed in Bitcoin and S&P 500 price trends — and if so, how long it takes for these effects to materialize.

---

## Key Variables
- **M2 Global Money Supply** – proxy for global liquidity  
- **BTC Price Changes** – cryptocurrency market performance  
- **S&P 500 Price Changes** – traditional equity market performance  

---

## Methodology
1. **Data Collection**  
   - M2 data from [FRED Economic Data](https://fred.stlouisfed.org/)  
   - BTC and S&P 500 prices via [Yahoo Finance](https://finance.yahoo.com/) API  

2. **Data Preprocessing**  
   - Weekly frequency alignment  
   - Percentage change calculations  

3. **Exploratory Data Analysis (EDA)**  
   - Trend comparison between M2, BTC, and S&P 500  
   - Visual correlation patterns  

4. **Cross-Correlation Analysis**  
   - Lag range: -20 to +20 weeks  
   - Identify lead or lag relationships between liquidity and asset prices  

---

## Results
- **BTC vs M2** → Highest correlation at **+11 weeks lag** (M2 leads BTC)  
- **S&P 500 vs M2** → Highest correlation at **+9 weeks lag** (M2 leads S&P 500)  
- Findings partially align with the Quantity Theory of Money, but liquidity is not the sole driver of asset price changes.

---

## Conclusion
Liquidity changes can serve as a potential **leading indicator** for both BTC and S&P 500, with a time lag of approximately 2–3 months.  
However, correlation does not imply direct causation — other macroeconomic factors, policy changes, and geopolitical events must also be considered.


## Repository Structure
