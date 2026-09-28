# A Cleaner Balance Sheet, or Lasting Capacity? Zambia's Copper Test

**Boldwin Mweemba** · Policy Brief · September 2026  
Independent Analyst, Data Analytics and Economic Research, Lusaka, Zambia  
boldwin@aims.edu.gh

---

## Overview

Copper has broken $13,000 per tonne. The Kwacha has appreciated 32% since December 2024. Mineral rents have climbed from 3% to nearly 28% of GDP. By almost every headline number, Zambia's recovery is real.

This policy brief asks a different question: is Zambia converting that tailwind into lasting capacity, or simply building a cleaner balance sheet ahead of the next stress test?

It consolidates five independent data projects on Zambia's economy into one written analysis. Three structural constraints sit at the centre: energy reliability, tax base concentration, and export logistics.

The tailwind is real. The question is whether the decisions being made right now will still look right when it fades.

---



---

## Key Findings

- Copper has broken $13,000 per tonne. The Kwacha appreciated 32% (December 2024 to May 2026). Mineral rents rose from 3% to nearly 28% of GDP. The recovery is real.
- The 2020 Eurobond default and its June 2024 restructuring collapsed debt service to exports from a 12.5% peak to under 3%. That improvement is structural, not just cyclical.
- Energy is the constraint copper prices cannot relax: mine electricity consumption fell 10.6% in 2024, during a hydrological crisis that pushed Lake Kariba to 10% capacity.
- Revenue is concentrated dangerously: large taxpayers carry 79% of the domestic tax base; one mine (Kansanshi) contributed roughly a third of the entire mining sector's government payments in 2023.
- The window to convert this boom into lasting capacity is now, while the tailwind is still blowing.

---

## Related Projects

This brief draws on five independent portfolio projects:

- **Kwacha drivers** — FX reserve decomposition and copper transmission chain
- **Eurobond recovery** —  restructuring analysis
- **Energy constraint** — Kariba reservoir, load shedding, and mine power consumption
- **Tax concentration** — ZRA revenue base analysis (6 independent cuts)


All projects, data, and interactive dashboards: [github.com/BoldwinMax](https://github.com/BoldwinMax)

---

## Compilation

Requires a standard TeX distribution (pdflatex). Figures are generated independently with Python (matplotlib).

```bash
# Generate figures
python figures/gen_fig1.py
python figures/gen_fig2.py
python figures/gen_fig3_v2.py

# Compile PDF (run twice for page references)
pdflatex zambia_copper_linkedin.tex
pdflatex zambia_copper_linkedin.tex
```

---

*Independent analysis. Views are the author's own.*
