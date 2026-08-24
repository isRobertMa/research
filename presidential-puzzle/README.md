# The Presidential Puzzle: the continuum

An empirical revisit of Santa-Clara and Valkanov (2003), *The Presidential Puzzle: Political
Cycles and the Stock Market* (**Journal of Finance** 58(5)), extending the sample to
**January 1934 – December 2023** so that it spans both the 2008 credit crisis and COVID-19.

| | |
|---|---|
| **Paper** | [Ma_Presidential_Puzzle_Continuum.pdf](Ma_Presidential_Puzzle_Continuum.pdf) — 14 pp. |
| **LaTeX source** | [Ma_Presidential_Puzzle_Continuum.tex](Ma_Presidential_Puzzle_Continuum.tex) |
| **Figures** | [`images/`](images/) — the four plots the source includes |
| **R code and data** | [isRobertMa/Presidential_puzzle_continuum](https://github.com/isRobertMa/Presidential_puzzle_continuum) |

The analysis behind this paper — excess returns, t-tests, OLS, ANOVA, ADF tests and ARIMA models,
written in R — lives in its own repository:
**[Presidential_puzzle_continuum](https://github.com/isRobertMa/Presidential_puzzle_continuum)**.
This folder holds the write-up; that one holds the code that produced it, including the script
that generates the four figures in `images/`.

## Rebuilding the PDF

The source is *not* self-contained — it reads the figures from `images/`, so keep that folder
beside the `.tex`:

```
pdflatex Ma_Presidential_Puzzle_Continuum.tex
```

It requires `fourier`, `listings`, `lastpage`, `multirow`, `wrapfig`, and `fancyhdr` in addition
to the usual `amsmath` / `graphicx` set, plus `ucs` for `utf8x` and `utopia` for the Fourier fonts.

---

ECO421, Department of Mathematical & Computational Sciences,
University of Toronto Mississauga. Instructor: Harry G.G. Burke.
