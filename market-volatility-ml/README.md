# Forecasting US equity market volatility

**Hanshuo Ma** — November 2023. University of Toronto Mississauga.

Forecasts the monthly CBOE Volatility Index (VIX) from the Equity Market Volatility (EMV)
tracker, comparing OLS against three shrinkage estimators, then re-fitting across six
market regimes to test whether one relationship holds over 33 years.

| | |
|---|---|
| **Report** | [Ma_Market_Volatility_Forecasting.pdf](Ma_Market_Volatility_Forecasting.pdf) — 36 pp. |
| **Source** | [Ma_Market_Volatility_Forecasting.Rmd](Ma_Market_Volatility_Forecasting.Rmd) |
| **Data** | [EMV_VIX_Data.xlsx](EMV_VIX_Data.xlsx) |

## Method

| Stage | Approach |
|---|---|
| Baseline | OLS regression of VIX on EMV components |
| Shrinkage | Ridge, LASSO, and Elastic Net, each tuned by cross-validation |
| Segmentation | Refit over six regimes: 1990–98, 1998–2003, 2003–07, 2008–09, 2009–19, 2020–22 |

The segmentation is the point of the exercise. A single model fitted across 33 years averages
over the 2001 downturn, the 2008 credit crisis and the COVID shock as though they were one
regime. Splitting the sample tests whether the fitted relationship is stable or an artefact of
pooling.

## Rebuilding

```r
rmarkdown::render("Ma_Market_Volatility_Forecasting.Rmd")
```

Requires `readxl`, `glmnet`, and `caret`. The report's appendix carries the full code, so the
PDF is readable without running anything.

---

Written as Assignment 2; listed on the CV as *Analysis of Stock Market Implied Volatility using
Data-driven Methodologies*. Graded 95/100.
