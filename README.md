# preliminary-exploration

## Exploring, normalizing, and organizing IMPLAN multipliers for JEDI ingestion

Repository containing code for reading in IMPLAN multipliers and getting them in a digestible format for JEDI to use. 

### Authors & contributors

- Brooke Grazda  [GitHub](https://github.com/bgrazda) | [Website](https://bgrazda.github.io/) | [LinkedIn](https://www.linkedin.com/in/brooke-grazda-a02248217/) 
- Marina Kochuten  [GitHub](https://github.com/marinakochuten) | [Website](https://marinakochuten.github.io/) | [LinkedIn](https://www.linkedin.com/in/marina-kochuten-4786b6324/) 
- Liz Peterson  [GitHib](https://github.com/egp4aq) | [Website](https://egp4aq.github.io/) | [LinkedIn](https://www.linkedin.com/in/elizabeth-peterson-85046b204/)

### File contents & structure
```bash
├── data/
│   ├── osw-multipliers-modified/
│   │   ├── osw-multipliers-ccc-earnings_m.csv
│   │   ├── osw-multipliers-ccc-jobs_m.csv
│   │   ├── osw-multipliers-ccc-output_m.csv
│   │   ├── osw-multipliers-ccc-total-value_m.csv
│   │   ├── osw-multipliers-sb-earnings_m.csv
│   │   ├── osw-multipliers-sb-jobs_m.csv
│   │   ├── osw-multipliers-sb-output_m.csv
│   │   ├── osw-multipliers-sb-total-value_m.csv
│   │   ├── osw-multipliers-slo-earnings_m.csv
│   │   ├── osw-multipliers-slo-jobs_m.csv
│   │   ├── osw-multipliers-slo-output_m.csv
│   │   ├── osw-multipliers-slo-total-value_m.csv
│   │   ├── osw-multipliers-ventura-earnings_m.csv
│   │   ├── osw-multipliers-ventura-jobs_m.csv
│   │   ├── osw-multipliers-ventura-output_m.csv
│   │   ├── osw-multipliers-ventura-total-value_m.csv
│   │   ├── sb-pce-norm_m.csv
│   │   ├── slo-pce-norm_m.csv
│   │   ├── ventura-pce-norm_m.csv
│   ├── osw-multipliers-raw/
│   │   ├── osw-multipliers-ccc-earnings.csv
│   │   ├── osw-multipliers-ccc-jobs.csv
│   │   ├── osw-multipliers-ccc-output.csv
│   │   ├── osw-multipliers-ccc-total-value.csv
│   │   ├── osw-multipliers-sb-earnings.csv
│   │   ├── osw-multipliers-sb-jobs.csv
│   │   ├── osw-multipliers-sb-output.csv
│   │   ├── osw-multipliers-sb-total-value.csv
│   │   ├── osw-multipliers-slo-earnings.csv
│   │   ├── osw-multipliers-slo-jobs.csv
│   │   ├── osw-multipliers-slo-output.csv
│   │   ├── osw-multipliers-slo-total-value.csv
│   │   ├── osw-multipliers-ventura-earnings.csv
│   │   ├── osw-multipliers-ventura-jobs.csv
│   │   ├── osw-multipliers-ventura-output.csv
│   │   ├── osw-multipliers-ventura-total-value.csv
│   │   ├── sb-pce-norm.csv
│   │   ├── slo-pce-norm.csv
│   │   ├── ventura-pce-norm.csv
│   ├── osw-pce/
│   │   ├── osw-multipliers-sb-pce.csv
│   │   ├── osw-multipliers-slo-pce.csv
│   │   ├── osw-multipliers-ventura-pce.csv
│   ├── pv-multipliers-modified/
│   │   ├── sb-earnings_m.csv
│   │   ├── sb-jobs_m.csv
│   │   ├── sb-output_m.csv
│   │   ├── sb-pce-norm_m.csv
│   │   ├── sb-value_m.csv
│   │   ├── slo-earnings_m.csv
│   │   ├── slo-jobs_m.csv
│   │   ├── slo-output_m.csv
│   │   ├── slo-pce-norm_m.csv
│   │   ├── slo-value_m.csv
│   │   ├── ventura-earnings_m.csv
│   │   ├── ventura-jobs_m.csv
│   │   ├── ventura-output_m.csv
│   │   ├── ventura-pce-norm_m.csv
│   │   ├── ventura-value_m.csv
│   ├── pv-multipliers-raw/
│   │   ├── sb-earnings.csv
│   │   ├── sb-jobs.csv
│   │   ├── sb-output.csv
│   │   ├── sb-pce-norm.csv
│   │   ├── sb-value.csv
│   │   ├── slo-earnings.csv
│   │   ├── slo-jobs.csv
│   │   ├── slo-output.csv
│   │   ├── slo-pce-norm.csv
│   │   ├── slo-value.csv
│   │   ├── ventura-earnings.csv
│   │   ├── ventura-jobs.csv
│   │   ├── ventura-output.csv
│   │   ├── ventura-pce-norm.csv
│   │   ├── ventura-value.csv
│   └── .DS_Store
├── osw_construction_files/
│   ├── figure-html/
│   │   └── unnamed-chunk-4-1.png
│   ├── libs/
│   │   ├── bootstrap
│   │   │   ├── bootstrap-icons.css
│   │   │   ├── bootstrap-icons.woff
│   │   │   ├── bootstrap.min.css
│   │   │   └── bootstrap.min.js
│   │   ├── clipboard
│   │   │   └── clipboard.min.js
│   │   ├── quarto-html
│   │   │   ├── anchor.min.js
│   │   │   ├── popper.min.js
│   │   │   ├── quarto-syntax-highlighting.css
│   │   │   ├── quarto.js
│   │   │   ├── tippy.css
│   │   │   └── tippy.umd.min.js
├── .DS_Store
├── .gitignore
├── README.md
├── normalize_pces_osw.qmd
├── normalize_pces_pv.qmd
├── osw-reorg.qmd
├── osw_construction.html
├── osw_construction.qmd
├── prelim-explore.qmd
├── pv-reorg.qmd
└── preliminary-exploration.Rproj
```
