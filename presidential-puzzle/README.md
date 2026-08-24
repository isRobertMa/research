# The Presidential Puzzle: the continuum

An empirical revisit of Santa-Clara and Valkanov (2003), *The Presidential Puzzle: Political
Cycles and the Stock Market* (**Journal of Finance** 58(5)), extending the sample to
**January 1934 – December 2023** so that it spans both the 2008 credit crisis and COVID-19.

| | |
|---|---|
| **Paper** | [Ma_Presidential_Puzzle_Continuum.pdf](Ma_Presidential_Puzzle_Continuum.pdf) — 14 pp. |
| **LaTeX source** | [Ma_Presidential_Puzzle_Continuum.tex](Ma_Presidential_Puzzle_Continuum.tex) |
| **Figures** | [`images/`](images/) — the four plots the source includes |
| **Data** | [Presidential_Party_by_Month.csv](Presidential_Party_by_Month.csv) |

## Data

`Presidential_Party_by_Month.csv` is the party-by-month coding used throughout: one row per month
from 1934-01 to 2023-12, with `Party` = `0` for Democrat and `1` for Republican.

The return series themselves are **not** included, because they are licensed:

- **3MTB** — 3-Month Treasury Bill Secondary Market Rate, from
  [FRED](https://fred.stlouisfed.org/series/TB3MS) (public)
- **VWP / EWP** — CRSP value-weighted and equal-weighted portfolios of the S&P 500 universe
  (CRSP US Stock & Indexes, INDO 1000510 and 1000511) — **licensed, obtain via CRSP**

Excess returns are formed against the T-bill benchmark: `Value Excess = VWP − 3MTB` and
`Equal Excess = EWP − 3MTB`.

## Rebuilding the PDF

The source is *not* self-contained — it reads the figures from `images/`, so keep that folder
beside the `.tex`:

```
pdflatex Ma_Presidential_Puzzle_Continuum.tex
```

It requires `fourier`, `listings`, `lastpage`, `multirow`, `wrapfig`, and `fancyhdr` in addition
to the usual `amsmath` / `graphicx` set.

---

ECO421, Department of Mathematical & Computational Sciences,
University of Toronto Mississauga. Instructor: Harry G.G. Burke.
