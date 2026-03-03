# FAANG Stock Market Analysis (Interactive Dashboard creation using Power BI)

## Project Objective
The objective of this project is to analyze decades of historical price, volume, and volatility data for FAANG stocks (Facebook, Amazon, Apple, Netflix, Google). This interactive dashboard allows financial analysts and investors to evaluate long-term market trends, assess risk vs. return, and track technical trading signals.

## Dataset used
- <a href="[Insert Link to your CSV/Excel file here]">FAANG Historical Stock Dataset</a>

## Questions (KPIs)
- What is the long-term stock price trend and total trading volume for each company?
- Which company yields the highest average daily return?
- How do the companies compare in terms of Risk vs. Return (Volatility)?
- How often do bullish/bearish market signals (Golden Cross vs. Death Cross) occur?
- What is the historical win rate (Up Days vs. Down Days)?
- Which company dominates the volume market share?
## Dashboard Screenshots

**1. Overview**
![Overview](https://github.com/grshruthi2002/Faang_dashboard_powerbi/blob/main/screenshot1_FAANG%20Stock%20Dashboard%20%E2%80%94%20Overview.png?raw=true)

**2. Returns**
![Returns](https://github.com/grshruthi2002/Faang_dashboard_powerbi/blob/main/screenshot2_FAANG%20Stock%20Dashboard%20%E2%80%94%20Returns.png?raw=true)

**3. Volatility**
![Volatility](https://github.com/grshruthi2002/Faang_dashboard_powerbi/blob/main/screenshot3_FAANG%20Stock%20Dashboard%20%E2%80%94%20Volatility.png?raw=true)

**4. Moving Averages**
![Moving Averages](https://github.com/grshruthi2002/Faang_dashboard_powerbi/blob/main/screenshot4_FAANG%20Stock%20Dashboard%20%E2%80%94%20Moving%20Averages.png?raw=true)

**5. Company Comparison**
![Company Comparison](https://github.com/grshruthi2002/Faang_dashboard_powerbi/blob/main/screenshot5_FAANG%20Stock%20Dashboard%20%E2%80%94%20Company%20Comparison.png?raw=true)

## Process
- Verified raw market data for missing values, anomalies, and consistent date formatting.
- Developed a complex Power BI data model, utilizing DAX to calculate advanced financial metrics including Simple Moving Averages (SMA 50 & SMA 200), Volatility, and Risk-Adjusted Returns.
- Designed a multi-page interactive layout categorizing insights logically: Overview, Returns, Volatility, Moving Averages, and Company Comparison.
- Merged all visualizations and applied dynamic slicers (Year, Company) to allow for granular filtering and cross-company auditing.

## Project Insight
- **Volume Dominance:** Apple overwhelmingly dominates the Total Trading Volume market share (~93.9%) among the FAANG group.
- **Risk vs. Return:** Netflix and Amazon yield the highest Average Daily Returns (0.20% and 0.19%), but this comes with the highest Average Volatility (Risk). 
- **Market Signals:** Historical data leans heavily bullish, with Golden Cross (SMA 50 > SMA 200) days making up 67.74% of the recorded crossover periods.
- **Win Rate:** Trading days are nearly evenly split over time, with 51.5% Negative (Down) days and 48.5% Positive (Up) days overall.
- **Growth:** Amazon shows the most significant absolute price growth since its IPO compared to the other tech giants.

## Final Conclusion:
To optimize investment strategies within the FAANG portfolio, investors seeking high growth should target Amazon and Netflix, provided they have the risk tolerance for the associated volatility. Conversely, Apple offers massive market liquidity and stability. Furthermore, traders should leverage the built-in Moving Average indicators (SMA 50/200), as historical data shows Golden Cross momentum historically outnumbers Death Crosses 2-to-1, providing strong, data-backed entry signals for long-term holds.
