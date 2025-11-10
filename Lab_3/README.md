# Lab 3 — Pattern Mining (YouTube Comments & Captions)

This lab takes the cleaned CSVs from **Lab 2** (`cleaned_comments.csv`, `cleaned_captions.csv`) and:
- Validates `cleaned_tokens`, drops empties, prints top-20 unigrams.
- Builds transactions (baskets), filters len<3, optional de-dupe, stats + histogram.
- Counts co-occurrence pairs (min count ≥ 3), exports CSV, plots top-20 pairs + unigrams.
- Draws co-occurrence networks with NetworkX.
- Runs Apriori at supports {0.30, 0.20, 0.15, 0.10, 0.05}; filters rules (conf ≥ 0.60, lift ≥ 1.20); plots support vs confidence.
- Variations: stemming vs lemmatization, min token length ≥4, separate vs merged datasets.
- Saves itemsets/rules CSVs and figures in `outputs/` (ignored in git).

## Run
Open `notebooks/477_Lab3_Pattern_Mining.ipynb` and ensure Lab-2 outputs exist at:
`../Lab 2/data_processed/cleaned_comments.csv`
`../Lab 2/data_processed/cleaned_captions.csv`
Run top-to-bottom; generated CSV/PNG files land in `outputs/`.

## Folder map
- `notebooks/` — Jupyter notebook
- `reports/`   — (optional) PDF report
- `outputs/`   — figures, tables, networks, wordclouds (not tracked)
## Folder map
- `notebooks/` — Jupyter notebook
- `reports/`   — PDF report
