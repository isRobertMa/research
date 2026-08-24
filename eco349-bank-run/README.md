# Bank Run: the downfall of First Republic Bank

**Hanshuo Ma** — August 2023. University of Toronto Mississauga, Department of Economics.
ECO349H5 S — Money, Banking & Financial Markets. Instructor: Prof. Yingnan Zhao.

An analysis of the collapse of First Republic Bank, compared against Silicon Valley Bank
through the **Diamond–Dybvig** model of bank runs.

| | |
|---|---|
| **Essay** | [Ma_Bank_Run_First_Republic.pdf](Ma_Bank_Run_First_Republic.pdf) — 9 pp. |
| **Source** | [Ma_Bank_Run_First_Republic.tex](Ma_Bank_Run_First_Republic.tex) |
| **Figures** | [`images/`](images/) |

## Figures

All three are price-history charts composed by the author **using Bloomberg terminal data**:

| File | Content |
|---|---|
| `FRCB_indexes.jpg` | First Republic against the Dow Jones U.S. Banks Index, S&P 500, and KBW NASDAQ Bank Index, standardised |
| `crisis_march_may_2023.jpg` | SIVB, FRCB, SBNY and the two bank indices, 1 March – 15 May 2023 |
| `bank_prices_cpi_fedfunds_2020_2023.jpg` | The same names plus CSGN, against US CPI and the Federal Funds target rate, Aug 2020 – Aug 2023 |

## Rebuilding

```
pdflatex Ma_Bank_Run_First_Republic.tex
```

Keep `images/` beside the `.tex`. The published PDF is the original August 2023 compile, not a
rebuild.

**Note on the source file:** this document was written in an Overleaf project cloned from an
earlier group assignment, so it arrived named `Technical_NDedits.tex` — nothing to do with a
technical report or with anyone's edits. It has been renamed here, and the three figures given
descriptive filenames, with the `\includegraphics` paths updated to match. Nothing else in the
source was touched.
