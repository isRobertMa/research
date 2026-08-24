# Introduction to Brownian motion and its application for modeling stock and option prices

**Arlyn Chavarria Toruno, Hanshuo Ma, Zhirui Chu** — December 2023.
University of Toronto Mississauga.

Brownian motion and its properties, the Markov property, Itô calculus, and geometric Brownian
motion applied to the Black–Scholes model — worked through to a terminal price distribution
simulated over five years of S&P 500 closes and an option priced against it.

| | |
|---|---|
| **Report** | [Brownian_Motion_Option_Pricing.pdf](Brownian_Motion_Option_Pricing.pdf) |
| **Source** | [Brownian_Motion_Option_Pricing.Rmd](Brownian_Motion_Option_Pricing.Rmd) |
| **Data** | [spx.csv](spx.csv) — 1,257 trading days of S&P 500 OHLC ending 2023-11-28, exported from Nasdaq |
| **Template** | [svm-latex-ms.tex](svm-latex-ms.tex) — required to knit |

The PDF and the `.Rmd` are both dated 2023-12-05, so the published report matches its source.

## Rebuilding

```r
rmarkdown::render("Brownian_Motion_Option_Pricing.Rmd")
```

Needs `svm-latex-ms.tex` in the same directory and a LaTeX installation.
