Telecommunications Stock Analysis

Project Overview

I analyzed historical stock market data for three major telecommunications companies—AT&T, T-Mobile, and Verizon—to evaluate their performance from an investment perspective.

I collected and cleaned historical market data, analyzed stock price and trading volume trends, investigated volatility and seasonality, evaluated dividend behavior and P/E ratios, and explored relationships between key financial metrics.

The analysis focused on answering a central question:

Based on historical market performance, which of these three telecommunications companies presents the strongest potential investment opportunity?

Based on the available data, I identified AT&T as the strongest overall option, primarily because of its comparatively lower volatility, liquidity, and consistent dividend payments. However, historical stock performance alone is not sufficient for an investment decision, and company financial statements and broader market conditions should also be considered.

Tools & Skills

* Python
* Pandas
* APIs
* Data cleaning and transformation
* Exploratory Data Analysis (EDA)
* Statistical analysis
* Data visualization
* Financial and investment analysis
* Correlation analysis
* Time-series and seasonal analysis

⸻

Data Collection

I obtained historical stock data from the NASDAQ website using its API.

After retrieving the data, I cleaned and structured the datasets so the three companies could be compared across common financial measures.

⸻

1. Historical Trading Volume

I first examined how trading volume fluctuated throughout each company’s available history.

Daily trading volume represents the number of shares traded during a given trading day. Examining volume can provide insight into a stock’s liquidity and unusual periods of market activity.

Finding

Verizon experienced a significant spike in trading volume in early 2014.

I investigated the outlier rather than treating it as normal trading behavior.

Investigating Verizon’s 2014 Outlier

The spike occurs around the end of February and beginning of March 2014. During this period, Verizon completed its acquisition of Vodafone’s stake in Verizon Wireless.

Because this was an unusual corporate event involving substantial financing and market activity, I treated the spike as an event-specific outlier rather than evidence of Verizon’s typical trading behavior.

⸻

2. Historical Stock Price

I analyzed how each company’s stock price changed throughout its available history.

T-Mobile’s available dataset covered a shorter period than the other companies, so I narrowed the comparison to the most recent ten years to make the analysis more comparable.

Finding

T-Mobile demonstrated substantially greater price fluctuations, while AT&T and Verizon showed comparatively more stable historical price behavior.

For an investor prioritizing stability, the lower volatility of AT&T and Verizon could make them more attractive based on this measure.

⸻

3. Recent Trading Volume & Liquidity

I analyzed recent daily trading volume to compare the relative liquidity of the three stocks.

Higher trading volume generally indicates greater liquidity, meaning investors can typically enter or exit positions more easily.

Finding

AT&T demonstrated higher trading volume within the analyzed period, suggesting greater liquidity relative to the other companies.

⸻

4. Recent Stock Price & Volatility

I then narrowed the analysis to more recent stock-price behavior.

Finding

T-Mobile continued to demonstrate greater price fluctuations even within the shorter timeframe.

AT&T and Verizon exhibited comparatively lower volatility, making their historical performance more consistent within the period analyzed.

⸻

5. Dividend Analysis

I evaluated dividend history to determine which companies provided the most consistent shareholder distributions.

Finding

AT&T and Verizon demonstrated more consistent dividend payments during the analyzed period.

T-Mobile’s historical dividend behavior was substantially different, with the available data showing a large distribution in 2013 rather than the same recurring pattern.

For an investor prioritizing consistent income, AT&T and Verizon therefore appeared stronger based on historical dividend behavior.

Dividend history alone, however, does not establish the financial health of a company. Earnings, cash flow, payout ratios, debt, and other financial measures would need to be considered before making an investment decision.

⸻

6. Seasonal Analysis

I investigated whether stock performance demonstrated meaningful seasonal patterns across quarters.

The goal was to determine whether particular periods of the year consistently produced stronger or weaker stock performance.

AT&T

AT&T’s second quarter showed comparatively stronger performance across portions of the dataset and somewhat less fluctuation.

T-Mobile

T-Mobile showed less fluctuation during portions of the first quarter, although its overall percentage changes remained substantial.

Verizon

Verizon did not demonstrate an obvious recurring quarterly pattern.

Finding

Overall, I did not identify a sufficiently consistent seasonal pattern to support a short-term investment strategy based solely on quarter of the year.

⸻

7. Price & Volume Correlation

I examined the relationship between stock price and trading volume for each company.

AT&T

AT&T demonstrated a more noticeable relationship between price and volume than the other companies within the analyzed data.

T-Mobile

T-Mobile demonstrated a weak relationship between trading volume and stock price.

Verizon

Verizon also demonstrated a relatively weak relationship, with several notable outliers.

Finding

Trading volume alone did not consistently explain stock-price movement across the three companies, suggesting that additional market and company-specific factors would need to be considered.

⸻

8. P/E Ratio Analysis

Finally, I examined recent price-to-earnings (P/E) ratios.

Changes in P/E ratios can result from movements in either stock price or earnings per share (EPS).

For AT&T and Verizon, periods of declining EPS combined with relatively stable or increasing stock prices contributed to changes in their P/E ratios.

This reinforced the importance of evaluating underlying earnings alongside market-price performance rather than interpreting stock price independently.

⸻

Overall Findings

Across the dimensions I analyzed:

* AT&T demonstrated strong liquidity, comparatively stable pricing, and consistent dividend payments.
* Verizon also demonstrated relatively stable pricing and consistent dividends, although its historical data contained notable event-driven volume outliers.
* T-Mobile demonstrated greater price volatility and a less consistent historical dividend pattern within the available dataset.

Based on these factors, AT&T emerged as the strongest potential investment candidate within the scope of this analysis.

This conclusion is based solely on the historical data and metrics analyzed in this project and should not be interpreted as financial advice.

⸻

What I Demonstrated

Through this project, I:

* Retrieved financial data programmatically through an API
* Cleaned and transformed raw datasets for analysis
* Conducted exploratory and statistical analysis
* Identified and investigated anomalous data rather than automatically excluding it
* Compared companies across multiple financial measures
* Analyzed historical and seasonal trends
* Evaluated correlations between financial variables
* Created visualizations to communicate findings
* Translated quantitative results into an investment-oriented recommendation

The project demonstrates my ability to take a broad business question, identify relevant measures, investigate the data, and communicate a defensible conclusion.
