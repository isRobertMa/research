# Literature Review: stakeholder capitalism and ESG

**Hanshuo Ma** — University of Toronto Mississauga, Department of Economics.
ECO440: Corporate Finance. Instructor: Prof. Varouj A. Aivazian.

A critical review of the stakeholder-capitalism model and the implementation of ESG factors,
built around **Brown & Cohen (2023)**.

| | |
|---|---|
| **Review** | [Ma_Literature_Review_Stakeholder_Capitalism.pdf](Ma_Literature_Review_Stakeholder_Capitalism.pdf) — 11 pp. |
| **Source** | [Ma_Literature_Review_Stakeholder_Capitalism.tex](Ma_Literature_Review_Stakeholder_Capitalism.tex) |
| **Bibliography** | [sample.bib](sample.bib) — 13 references |

## Rebuilding

Uses `biblatex`, so it needs the biber pass in the middle:

```
pdflatex Ma_Literature_Review_Stakeholder_Capitalism.tex
biber     Ma_Literature_Review_Stakeholder_Capitalism
pdflatex Ma_Literature_Review_Stakeholder_Capitalism.tex
```

Skipping `biber` leaves every citation rendered as a bold question mark.

**Note on the date:** the source uses `\date{\today}`, so the title page shows whenever it was
last compiled rather than when it was written. The PDF here is the December 2025 build, which is
the closest surviving copy to the submitted version. Recompiling will re-stamp it with the
current date — replace `\today` with a fixed date if that matters to you.
