# Journal review: *The Lifetime Costs of Bad Health*

**Hanshuo Ma, Ching Yu Mok** — Winter 2026. ECON 724.

A presentation reviewing **De Nardi, Pashchenko and Porapakkarm**, *The Lifetime Costs of Bad
Health* — a structural life-cycle study of how health shocks translate into lifetime
consumption, earnings and medical spending.

| | |
|---|---|
| **Slides** | [Lifetime_Costs_of_Bad_Health_Review.pdf](Lifetime_Costs_of_Bad_Health_Review.pdf) — 38 slides |
| **Source** | [Lifetime_Costs_of_Bad_Health_Review.tex](Lifetime_Costs_of_Bad_Health_Review.tex) |
| **Figures** | [`images/`](images/) |

## Attribution

This is a **review of someone else's work**, not original research. The figures and tables in
`images/` are reproduced from the reviewed paper for the purpose of discussing it; all credit for
them belongs to De Nardi, Pashchenko and Porapakkarm. The commentary, structure and framing are
the presenters'.

## Rebuilding

```
pdflatex Lifetime_Costs_of_Bad_Health_Review.tex
```

A `beamer` deck compiled in `handout` mode, so `\pause` steps are flattened into single slides.
The source carries `\graphicspath{{images/}}` — added when the figures were moved into their own
folder — so the `\includegraphics` calls still resolve.
