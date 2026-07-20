# cross-asset-electricity-preanalysis
Preanalysis part of my bachelor thesis @ TUM.

## France daily data

French system-load and generation forecasts (`data/prevision_conso_*.xls`, `data/PrevisionProduction_*.xls`) are merged into `data/FR.csv`:

```bash
.venv/bin/python build_fr_daily.py
```

Run the **France CSV Export** cells in `analysis.ipynb` (after the Germany export) to write `output/FR_model_1_base.csv` … `output/FR_model_5.csv`.
