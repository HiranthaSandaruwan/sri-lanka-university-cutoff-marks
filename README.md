# Sri Lanka university cut-off marks (Z-scores)

The minimum Z-score for every course at every Sri Lankan state university, for each of the 25 districts, as published by the University Grants Commission (UGC). 2025/2026: 260 course and university rows, from the G.C.E. (A/L) 2025 results after re-scrutiny.

**Search it by district and Z-score on your phone: [hirantha.me/updates/university-cutoff-marks](https://hirantha.me/updates/university-cutoff-marks)**

## Files

| File | Layout |
| --- | --- |
| `data/cutoff-marks-2025-2026.csv` | One row per course, university and district (long) |
| `data/cutoff-marks-2025-2026-by-district.csv` | One row per course and university, a column per district (as in the UGC table) |
| `data/cutoff-marks-2025-2026.json` | Courses with a district-to-Z-score map |

Columns: `course` and `university` (official English names), `all_island_merit` (selection was 100% on all-island merit, no district quota), `aptitude_test` (a practical or aptitude test was required), `district`, `minimum_z_score`, `nqc`.

**NQC** means "No Qualified Candidates": the district quota was already filled, the course filled from higher Z-scores in other districts, or nobody from that district met the requirements. It is not a Z-score of zero: in the long CSV the Z-score is empty and `nqc` is true; in the by-district CSV the cell reads NQC; in JSON it is null.

## Source

University Grants Commission, Sri Lanka: "University Admission - Academic Year 2025/2026, Minimum Z Scores", based on the G.C.E. (A/L) 2025 results after re-scrutiny. Official PDF: https://www.ugc.ac.lk/downloads/admissions/cutoff_2026/COP_2025_2026-ENGLISH_Final.pdf. Transcribed number for number; the counts of figures and NQC cells were checked against the PDF (last checked 2026-10-12). The UGC list is the authority: use it for any decision.

## Licence and credit

[CC BY 4.0](LICENSE). Use it for anything, including commercial work. Please credit it with a link:

```html
University cut-off marks from <a href="https://hirantha.me/updates/university-cutoff-marks">hirantha.me</a>, based on the UGC list
```

Found a mistake? Open an issue or write via [hirantha.me/contact](https://hirantha.me/contact).

_Generated 2026-10-27 from the data behind [hirantha.me](https://hirantha.me)._
