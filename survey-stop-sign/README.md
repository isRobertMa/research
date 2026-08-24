# Proportion of UTM drivers who do not stop at a stop sign

**Lufei Liu, Hanshuo Ma, Yixiang Zang, Shuaiqi Chen, Boliang Sun, Tianyue Wang, Yiting Huang**
— December 2022. University of Toronto Mississauga.

An observational survey study estimating how many drivers fail to stop at the sign between
Outer Circle Rd and The Collegeway on the UTM campus, and testing whether that behaviour is
associated with driver gender, age, vehicle type, and number of passengers.

| | |
|---|---|
| **Source** | [UTM_Stop_Sign_Survey.Rmd](UTM_Stop_Sign_Survey.Rmd) |
| **Template** | [svm-latex-ms.tex](svm-latex-ms.tex) |
| **Report PDF** | **not available** — see below |

## Why there is no PDF

The `.Rmd` reads two survey files, `pilot.xlsx` and `complete.xlsx`, holding the group's own
observational data. Neither survives on the author's machine, so the document cannot be knitted
and no compiled copy was kept. The source is published as-is: the sampling design, the analysis,
and the write-up are all readable in it, but it will not render without that data.

## Method

Simple random sampling, chosen over two-stage cluster sampling on feasibility grounds — a
trade-off the paper argues for explicitly rather than assuming. Sample sizes are derived rather
than picked, and the analysis relates non-compliance to the recorded driver and vehicle
covariates.

---

A group project. Placed in the top 3 groups of roughly 250 students.
