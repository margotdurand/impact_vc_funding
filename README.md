**Overview**

This project examines the impact of venture capital (VC) funding on startup valuations by comparing European and U.S. venture-backed companies.

Using a proprietary dataset of VC-backed firms from 2003 to 2024, the study applies log-log OLS regressions to analyze the relationship between venture funding and post-round valuations. The empirical framework includes controls for company age, number of investors, fund characteristics, as well as industry and year fixed effects.

The project combines firm-level, deal-level, and investor-level information to construct a comprehensive panel dataset for econometric analysis.

**Research Question**

How does venture capital funding influence startup valuations, and does this relationship differ between Europe and the United States?

**Methodology**

The analysis relies on:

Log-log Ordinary Least Squares (OLS) regressions
Fixed effects models
Robustness checks
Instrumental Variable (2SLS) estimations
Control Variables

The regressions control for:

Company age
Number of investors
Fund characteristics
Industry fixed effects
Year fixed effects

**Key Findings**

VC funding has a strong and statistically significant positive effect on post-round startup valuations.
Baseline OLS results show:
β = 0.713
p < 0.001
R² = 0.855

Economically, a 10% increase in venture funding is associated with a 7.1% increase in startup valuation.
The findings support the hypothesis that venture capital acts as a credible market signal, reducing information asymmetry and increasing firm value.

Regional analysis indicates that the effect is initially stronger in the United States than in Europe. However, once firm and fund characteristics are controlled for, the regional difference becomes statistically insignificant.
Instrumental Variable (2SLS) estimations confirm the robustness and likely causal nature of the relationship, with IV estimates suggesting an even stronger elasticity β = 1.160

Overall, the results suggest that venture capital serves both as a financial catalyst and a signaling mechanism that influences startup valuation dynamics.

The study also highlights the importance of Investor reputation, Syndication structures,Venture ecosystem characteristics in shaping valuation outcomes across markets.

**Dataset**

The analysis is based on proprietary datasets obtained from LSEG and Bloomberg.
Due to licensing, privacy, and data usage restrictions, the raw datasets cannot be publicly shared.

**Limitations**

Although the dataset obtained from LSEG is highly reliable, it provides a narrower view of private market activity compared to specialized startup databases such as Crunchbase or PitchBook.

As a result Early-stage funding rounds, Undisclosed valuations,Smaller venture transactions and Pre-seed and non-public startup activity may not be fully captured in the sample.

In addition, databases such as Crunchbase and PitchBook contain richer information on:

Founder experience
Educational background
Industry specialization
Prior funding history
Startup maturity

These variables can significantly influence both the probability of receiving VC funding and post-round valuations. Their absence may limit the model’s ability to fully capture startup heterogeneity and the mechanisms through which VC funding affects firm valuation.

**Disclaimer**

This project is intended for academic and research purposes only. The analysis and conclusions presented are solely those of the author and do not represent the views of any data provider or institution.
