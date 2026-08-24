# Effect of oven temperature and cooking time on chicken breast internal temperature

**Wenshan Cheng, Natalia Demidova, Zhirui Chu, Lucas Noritomi-Hartwig, Hanshuo Ma,
Matteo Giannone** — April 2023. University of Toronto Mississauga,
Department of Mathematical & Computational Sciences. Instructor: Prof. Luai Al Labadi.

A two-factor designed experiment asking a domestic question with a food-safety answer: what
combination of oven temperature and cooking time reaches the safe internal temperature for
chicken breast while using the least energy and time?

| | |
|---|---|
| **Report** | [Oven_Temperature_Chicken_Experiment.pdf](Oven_Temperature_Chicken_Experiment.pdf) — 10 pp. |
| **Source** | [Technical.tex](Technical.tex) |
| **Figures** | [`Technical/`](Technical/) — boxplot, interaction plot, data summary, and Q–Q plots for the additive and interaction models |

## Method

Factorial design over oven temperature and cooking time, with the resultant internal temperature
as response. Additive and interaction models are fitted and compared, with normal Q–Q plots
checking the residual assumptions behind each.

## Rebuilding

The source reads its figures from `Technical/`, so compile from **this** directory:

```
pdflatex Technical.tex
```

Keep the `Technical/` folder beside the `.tex` — the `\includegraphics` paths are relative and
the document will fall back to draft boxes without it.

**Note:** the PDF here was compiled from this source in August 2026, not submitted in 2023.
It is a faithful build of the group's final `.tex`, but not the original artefact.

---

A group project. Placed in the top 4 groups.
