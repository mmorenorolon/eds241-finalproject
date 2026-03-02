# Replicating the Ecological Impact of High-Speed Rail: A Staggered Difference‑in‑Differences Tutorial

## About

This repository contains the final project materials for Environmental Policy Evaluation (EDS241 / ESM244), replicating the causal inference analysis from:

> Xie, J. & Zhu, M. (2025). Exploring the ecological impacts of high-speed rail on urban avian biodiversity. *Journal of Cleaner Production*, 502, 145351. https://doi.org/10.1016/j.jclepro.2025.145351

The paper examines whether China’s rapid HSR expansion slowed the discovery of new urban bird species. Using a city-year panel of 297 Chinese prefecture-level cities from 2001–2019, the authors employ a **staggered difference-in-differences** design that compares cities receiving HSR service earlier or later to estimate its causal effect on avian biodiversity.

```
├── data/
│   └── xie2025_simulated_panel.csv   # Simulated panel dataset 
│
├── blog-post.wmd
│
└── README.md
```

## Data

This project uses a simulated panel dataset constructed to match the Table 3 summary statistics in Xie & Zhu (2025) and to reproduce the preferred Table 5 specification’s effect size and uncertainty for the HSR treatment variable under city and year fixed effects.

**File:** `data/xie2025_simulated_panel.csv` 

## Authors

- **IXEL	MEDRANO** — [GitHub Profile](https://github.com/IIDonaji)
- **HYLAEA MILLER** — [GitHub Profile](https://github.com/hylaea-miller)
- **MELANNIE	MORENO ROLON** — [GitHub Profile](https://github.com/mmorenorolon)

## References & Acknowledgments
 
Xie, J. & Zhu, M. (2025). Exploring the ecological impacts of high-speed rail on urban avian biodiversity. *Journal of Cleaner Production*, 502, 145351. https://doi.org/10.1016/j.jclepro.2025.145351
  
Environmental Policy Evaluation (EDS241 / ESM244), Bren School of Environmental Science & Management, UC Santa Barbara. https://garberadamc.github.io/W26-Policy-Eval/.



