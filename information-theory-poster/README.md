# Exploring Information Theory

**Luai Al Labadi, Zhirui Chu, Nevena Ciganovic, Hanshuo Ma, Lucas Albert Noritomi-Hartwig,
Jingwen Shi, Ying Xu** — University of Toronto Mississauga.

A research poster on entropy and Kullback–Leibler divergence: their properties, how they are
computed in practice, and where they are applied in statistics.

| | |
|---|---|
| **Poster** | [Information_Theory_Poster.pdf](Information_Theory_Poster.pdf) — single-page conference poster |
| **Source** | [Information_Theory_Poster.tex](Information_Theory_Poster.tex) |
| **Theme** | [beamerposter.sty](beamerposter.sty), [beamerthemeconfposter.sty](beamerthemeconfposter.sty) |

## Rebuilding

```
pdflatex Information_Theory_Poster.tex
```

Both `.sty` files must stay beside the source — `beamerposter` is bundled here rather than taken
from your TeX installation, so the poster renders at the size it was designed for. It also needs
`type1cm`, which supplies the scalable Computer Modern the large headings require.
