Purpose and Aims
The aim of this project is to model the dynamics of the French stock market, focusing on LVMH, Air Liquide, and the CAC 40 index, while examining the role of volatility, seasonality effects, and the influence of cryptocurrency assets such as Dogecoin.  
The research investigates:
- How leading French stocks move with the CAC 40 index.
- The relationship between French equities and global volatility (VIX).
- Whether seasonality effects such as the “Monday Effect” hold in the CAC 40.
- How cryptocurrency volatility compares to traditional equity market risk.

Introduction
The French stock market plays a central role in European finance, with the CAC 40 index capturing the performance of its largest and most liquid companies. LVMH and Air Liquide, both among the index’s top ten constituents, represent the luxury and industrial sectors. Alongside domestic factors, global risk sentiment (measured by the VIX) and the rise of volatile cryptocurrencies like Dogecoin shape investor behaviour.  
By combining econometric modelling (ADF, VAR, Granger causality, ARCH/GARCH) with financial data from 2016–2024, this study explores how shocks in volatility, seasonality, and crypto spill over into French markets.

Findings
- Stationarity of Returns: Augmented Dickey-Fuller tests confirmed that daily returns for LVMH, Air Liquide, CAC 40, and VIX are stationary and mean-reverting. Shocks are temporary and do not imply long-term persistent trends.  
- VAR Modelling:
  1. CAC 40 returns significantly affect LVMH and Air Liquide, highlighting the influence of the broader index.  
2. VIX shocks reduce returns across all French equities, but the effect dissipates within a few days.  
3. The VIX itself shows mean reversion, with volatility shocks gradually fading.  
- Impulse Responses: Market shocks last approximately 5–7 days. CAC 40 shocks influence constituent stocks strongly, while volatility shocks from the VIX spill over into French returns in the short term.  
- Granger Causality: LVMH Granger-causes Air Liquide, and there is a feedback loop between Air Liquide and CAC 40. The VIX significantly predicts the CAC 40, but not individual stock returns.  
- Cryptocurrency Volatility: Dogecoin returns display volatility clustering, leptokurtosis, and strong ARCH effects, requiring GARCH modelling. The fitted GARCH (1,1) model captured persistent volatility trends, confirming crypto’s heightened risk compared to equities.  
- Seasonality (Monday Effect): CAC 40 returns showed weak evidence of the Monday Effect (lower average Monday returns). However, these effects were not statistically significant and have diminished in recent years, suggesting market efficiency improvements.

Significance
The results highlight several key insights:  
1. For French equities: Market volatility and shocks transmit quickly but fade within days, confirming the efficiency and resilience of leading CAC 40 companies.  
2. For investors: LVMH and Air Liquide behave differently under volatility, with LVMH showing delayed resilience while Air Liquide reacts more negatively in the short term.  
3. For crypto-assets: Dogecoin demonstrates extreme and persistent volatility, underscoring its speculative nature compared to established equity markets.  
4. For market timing strategies: Traditional anomalies like the Monday Effect appear weaker in recent years, suggesting fewer arbitrage opportunities.  
