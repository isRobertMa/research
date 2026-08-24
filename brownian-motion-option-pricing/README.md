# Brownian motion and option pricing

**Arlyn Chavarria Toruno, Hanshuo Ma, Zhirui Chu** — December 2023.
University of Toronto Mississauga.

Derives the Black–Scholes formula from stochastic calculus, then applies it to real data:
a terminal price distribution simulated by geometric Brownian motion over five years of
S&P 500 closes, and an option priced against it.

| | |
|---|---|
| **Report** | [Brownian_Motion_Option_Pricing.pdf](Brownian_Motion_Option_Pricing.pdf) |
| **Source** | [Brownian_Motion_Option_Pricing.Rmd](Brownian_Motion_Option_Pricing.Rmd) |
| **Data** | [spx.csv](spx.csv) — 1,257 trading days of S&P 500 OHLC ending 2023-11-28, exported from Nasdaq |
| **Template** | [svm-latex-ms.tex](svm-latex-ms.tex) — required to knit |

## Contents

Itô's lemma and the stochastic differential equation for geometric Brownian motion; derivation
of the Black–Scholes formula; simulation of the terminal price distribution in R; option pricing
at a chosen strike and expiry.

## Rebuilding

```r
rmarkdown::render("Brownian_Motion_Option_Pricing.Rmd")
```

Needs `svm-latex-ms.tex` in the same directory and a LaTeX installation.

**Note:** the `.Rmd` was last modified 2023-12-05 and the PDF was produced 2023-11-23, so the
source is slightly ahead of the compiled report. Rebuilding may not reproduce the PDF byte for byte.

---

A group project. Graded in the 85th percentile.
