# Research

Papers and projects by **Hanshuo Ma** — PhD student in Economics, McGill University.

This repository holds the writing: papers, their LaTeX or R Markdown sources, and the figures
needed to rebuild them. Standalone analysis code lives in its own repositories, linked below.

| Project | Field | Year |
|---|---|---|
| [Dynamic Bayesian Persuasion with Partial Commitment](Ma_Dynamic_Bayesian_Persuasion_Partial_Commitment.pdf) | Information design | 2026 |
| [The Presidential Puzzle: the continuum](presidential-puzzle/) | Empirical finance | 2024 |
| [Forecasting US equity market volatility](market-volatility-ml/) | Statistical learning | 2023 |
| [Brownian motion and option pricing](brownian-motion-option-pricing/) | Stochastic calculus | 2023 |
| [Oven temperature and chicken breast](experimental-design-chicken/) | Experimental design | 2023 |
| [UTM drivers and a stop sign](survey-stop-sign/) | Survey sampling | 2022 |

---

## Dynamic Bayesian Persuasion with Partial Commitment

How much credibility does honest disclosure from a central bank actually need?
A dynamic information design model in which a sender's commitment power is partial,
applied to central bank FX communication.

| | |
|---|---|
| **Paper** | [Ma_Dynamic_Bayesian_Persuasion_Partial_Commitment.pdf](Ma_Dynamic_Bayesian_Persuasion_Partial_Commitment.pdf) — final submitted version, 19 pp., July 2026 |
| **Slides** | [Presentation (13 slides)](Ma_Dynamic_Bayesian_Persuasion_Slides.pdf) |
| **Extended manuscript** | [LaTeX source](Ma_Dynamic_Bayesian_Persuasion_Extended_Manuscript.tex) — a longer development of the same project, work in progress |

The paper is the version submitted for ECON 701. The extended manuscript is a separate, longer
treatment of the same material, still being revised, and is provided as LaTeX source only —
it is not the source of the paper above.

*ECON 701, Department of Economics, McMaster University. Instructor: Prof. Gajendran Raveendranathan.*

## [The Presidential Puzzle: the continuum](presidential-puzzle/)

An empirical revisit of Santa-Clara and Valkanov (2003), extending the sample to 1934–2023 so
that it spans the 2008 credit crisis and COVID-19. The R analysis behind it —
t-tests, OLS, ANOVA, ADF tests and ARIMA — lives in
**[Presidential_puzzle_continuum](https://github.com/isRobertMa/Presidential_puzzle_continuum)**.

*ECO421, University of Toronto Mississauga.*

## [Forecasting US equity market volatility](market-volatility-ml/)

Predicting the VIX from the Equity Market Volatility tracker: OLS against Ridge, LASSO and
Elastic Net with cross-validated tuning, then refitted across six market regimes to test whether
one relationship holds over 33 years.

*University of Toronto Mississauga, 2023. Graded 95/100.*

## [Brownian motion and option pricing](brownian-motion-option-pricing/)

The Black–Scholes formula derived from Itô's lemma, then applied — a terminal price distribution
simulated by geometric Brownian motion over five years of S&P 500 closes.

*With Arlyn Chavarria Toruno and Zhirui Chu. University of Toronto Mississauga, 2023.*

## [Oven temperature and chicken breast](experimental-design-chicken/)

A two-factor designed experiment: which combination of oven temperature and cooking time reaches
a safe internal temperature using the least energy and time?

*With Wenshan Cheng, Natalia Demidova, Zhirui Chu, Lucas Noritomi-Hartwig and Matteo Giannone.
STA305, University of Toronto Mississauga, 2023.*

## [UTM drivers and a stop sign](survey-stop-sign/)

An observational survey estimating non-compliance at a campus stop sign and its association with
driver and vehicle characteristics. Source only — the survey data did not survive.

*With Lufei Liu, Yixiang Zang, Shuaiqi Chen, Boliang Sun, Tianyue Wang and Yiting Huang.
STA304, University of Toronto Mississauga, 2022.*
