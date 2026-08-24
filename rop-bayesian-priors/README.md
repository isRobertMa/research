# Enhancing Bayesian Analyses: adjusting improper priors with cross-validation

**STA399Y5Y — Research Opportunity Program, Summer 2024.**
University of Toronto Mississauga. Supervisor: Prof. Luai Al Labadi.

| | |
|---|---|
| **Slides** | [ROP_Enhancing_Bayesian_Analyses.pdf](ROP_Enhancing_Bayesian_Analyses.pdf) — 144 slides |

## Hanshuo Ma's contribution

This is a **group presentation**. The sections presented by Hanshuo Ma are:

- **Single-Parameter Model**
- **Multi-Parameter Model**
- **Jeffreys' Prior**
- **Posterior Predictive Model**

The remaining sections — including the introduction, the conjugate and uninformative prior
material, and the cross-validation methods — were presented by other members of the group.
The full outline is on slide 2.

## What the study does

An improper prior cannot be used directly for prediction, because it does not integrate to a
proper distribution. The methodology here recovers a usable prior by splitting the sample:

1. Combine the improper prior $\pi(\theta)$ with a first subsample $y_1,\dots,y_l$ to obtain
   a posterior $\pi(\theta \mid y_1,\dots,y_l)$.
2. Treat that posterior as a new, proper prior $\pi^{*}(\theta)$, and update it against the
   held-out subsample $y_1^{*},\dots,y_m^{*}$.

The deck works this through single- and multi-parameter models, Jeffreys' prior and its
extensions to the multiparameter, multivariate and reference-prior cases, then k-fold and
leave-one-out cross-validation, with MCMC applications throughout.
