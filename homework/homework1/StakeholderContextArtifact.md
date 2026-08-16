# Stakeholder Memo -- Unemployment and Stock Market Returns
**Stakeholder:** Portfolio Manager 
## Problem
Does the U.S. unemployment rate provide useful information about subsequent stock market return?
## Stakeholder & User
Portfolio managers are the primary stakeholders/users of the output, since they evaluate factors that may provide information about future stock market performance when makeing investment decisions. For similar reasons, individual investors would be secondary stakeholders/users. The output would be used as one factor when evaluating current economic conditions and potential subsequent stock market returns.
## Useful Answer & Decision
Immediately, the output is predictive, since it attempts to use unemployment to determine subsequent stock market returns. The primary metric will be the correlation between the unemployment rate and subsequent stock market returns, measured overa  defined period following reports on unemployment. The final artifact would be a data analysis showing whether unemployment provides useful information for evaluating future stock market performance.
## Assumptions & Constraints
- Data availability: Unemployment data will be sourced from the publicly available monthly reports from the U.S. Bureau of Labor Statistics (BLS). Stock market data will be sourced from Python library yfinance, or some other source that provides historical price data needed to calculate susequent returns.
- Capacity: The analysis will be limited to the historical data provided by the BLS.
- Latency: The unemployment data is released monthly, so the analysis is restricted by the timing of these releases. Additional time will be required to collect and process the unemployment and stock market data after each release.
- Compliance: This project will use publicly available data, not private or personally identifiable information, so compliance requirements should be limited.
## Known Unknowns / Risks
- Confounding factors: The stock market is influenced by many different factors simultaneously, including economic, political, and financial. Thus, it may be unclear whether observed changes in stock market returns can majorly be attributed to the reports on the unemployment rate or to other simultaneously-occuring factors.
- Concurrent information: Geopolitical news, other economic reports, or financial events may be released around the same time as the unemployment report, making it difficult to isolate the unemployment rate's influence on subsequent stock market returns.
- Testing/monitoring: The analysis will examine the relationship between unemployment and subsequent returns over a defined period, and it will compare results across many different time periods to determine whether the relationship is consistent.
## Lifecycle Mapping
- Define and understand the problem → Problem Framing & Scoping (Stage 01) → This section of the README
- ...
## Repo Plan
data/, src/, notebooks/, docs/ ; cadence for updates