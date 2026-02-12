# VaxSent
Twitter Sentiment Analysis of COVID-19 Vaccines

**Interpretation of Temporal Sentiment Analysis**

We applied the best-performing Ridge Logistic Regression model to 228,193 vaccine-related tweets spanning December 2020 to November 2021. The overall predicted sentiment distribution is dominated by Neutral tweets (67.5%), followed by Positive (22.2%) and Negative (10.2%), indicating that the majority of vaccine-related discourse on Twitter was informational or factual in tone rather than explicitly opinionated.

**Temporal Trends.** The monthly sentiment proportion plot and the average sentiment score reveal a clear two-phase pattern:

- **Early optimism (Dec 2020 – Apr 2021):** The average sentiment score peaked at 2.23 in January 2021, coinciding with the initial rollout of COVID-19 vaccines following the FDA's Emergency Use Authorizations for Pfizer (Dec 11, 2020) and Moderna (Dec 18, 2020). Positive tweets reached their highest share during this period (~39% in January), reflecting public enthusiasm and hope surrounding vaccine availability. Tweet volume also surged dramatically from ~2,000 in December 2020 to over 27,000 by March 2021, as vaccines became a central topic of public discourse.

- **Gradual sentiment decline (May – Nov 2021):** Beginning around May 2021, the positive proportion steadily dropped from ~32% to as low as ~13.6% in July, while the neutral proportion rose sharply to 80.3%. The average sentiment score declined from 2.20 in April to a low of 2.04 in October. This shift coincides with several real-world developments: the J&J vaccine pause (April 13, 2021) over blood clot concerns, growing debates over vaccine mandates, the emergence of the Delta variant, and increasing polarization around booster shots. Notably, the negative proportion hit its lowest point (6.1%) in July 2021 — suggesting that the decline in positivity was driven more by a shift toward neutral/informational discourse than by a rise in explicit negativity.

- **Late-period stabilization (Oct – Nov 2021):** A slight rebound in both positive share (20.8%) and average score (2.10) appeared in November 2021, potentially reflecting renewed public attention to booster campaigns and the approaching holiday season.

**Volume Dynamics.** Tweet volume peaked in June 2021 (35,500 tweets), likely driven by widespread vaccine eligibility expansions and mandate announcements, before declining in the latter half of the year as vaccination became more routine and less newsworthy.

**Summary.** Overall, public sentiment toward COVID-19 vaccines on Twitter followed a trajectory of initial optimism during the early vaccine rollout, followed by a gradual shift toward more neutral, information-driven discourse as the vaccination campaign matured and public debate became more complex. The sentiment never fell below the neutral baseline (score = 2.0) in any month, suggesting that despite growing controversy, the overall tone of vaccine-related tweets remained weakly positive throughout the study period.
