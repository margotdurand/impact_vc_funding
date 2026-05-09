**Overview**

This project analyzes the impact of venture capital (VC) funding on startup valuations, with a comparison between European and U.S. startups.

Using a proprietary dataset of VC-backed companies from 2003 to 2024, I estimate log-log OLS regressions controlling for company age, number of investors, fund characteristics, as well as industry and year fixed effects. The dataset combines firm-level, deal-level, and investor-level information.

The results show a strong and statistically significant positive relationship between VC funding and post-round valuations (β = 0.713, p < 0.001; R² = 0.855). On average, a 10% increase in VC funding is associated with a 7.1% increase in valuation, supporting the idea that VC participation acts as a credible market signal that reduces information asymmetry and enhances firm value.

Regional estimations indicate that the effect is initially stronger in the U.S. than in Europe, although the difference becomes statistically insignificant once firm and fund characteristics are included. Robustness checks and instrumental variable (2SLS) estimations confirm the relationship, with IV results suggesting an even stronger elasticity (β = 1.160).

Overall, the findings suggest that venture capital acts both as a financial catalyst and as a signaling mechanism influencing startup valuations.

**Dataset**

The analysis relies on proprietary datasets obtained from LSEG and Bloomberg.
Due to licensing and privacy restrictions, the raw data cannot be publicly shared.

**Limitations**

The dataset was primarily obtained from LSEG, which provides a reliable but narrower coverage of private market activity compared to databases such as Crunchbase or PitchBook. As a result, some early-stage rounds, undisclosed valuations, and smaller venture transactions may not be captured.

In addition, variables such as founder experience, education, industry specialization, and prior funding history were not available. Their absence may limit the model’s ability to fully capture startup heterogeneity and the mechanisms through which VC funding affects valuations.

**Disclaimer**

This project is intended for academic and research purposes only. The analysis and conclusions presented are solely those of the author and do not represent the views of any data provider or institution.
