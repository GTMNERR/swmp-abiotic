# swmp-abiotic
Code and basic products for working with GTMNERR System-Wide Monitoring Program (SWMP) abiotic data (weather, water quality, and nutrient datasets)

Not all files are included in the online repo. Check `.gitignore` for which files are not pushed. Structure is currently as follows:

```
.
├── data/
│   ├── 2001_2020_WQ_MET_NUT_FilesCDMO/
│   └── baseline_mdls_2020.csv
│   └── componentnames.xlsx
│   └── ...
├── R/
│   ├── 00_loadpackages.R
│   └── 01_load_wrangle_LIMS.R
│   └── ...
├── output/
│   └── ...
└── swmp-abiotic.Rproj
```