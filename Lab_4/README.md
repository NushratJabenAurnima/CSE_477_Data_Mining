# Lab 4 — Incremental Pattern Mining & Correlation on YouTube Comments

## Objective
This lab analyzes how frequent words and co-occurring word pairs in YouTube comments evolve over time.
Incremental data arrival is simulated using data chunks, followed by correlation analysis to study
relationships between evolving patterns.

---

## Dataset
- Source file: cleaned_comments.csv ( generated in Lab 2)
- Each row represents a YouTube comment
- cleaned_tokens column contains preprocessed token lists
- Dataset is split into 5 equal chunks to simulate time-based arrival

---

## Tasks Performed
- Loaded and validated the cleaned YouTube comments dataset
- Ensured cleaned_tokens were correctly formatted as lists
- Split the dataset into five equal chunks
- For each chunk:
  - Treated each comment as a transaction
  - Extracted top 10 unigrams
  - Extracted top 10 co-occurring (unordered) word pairs
  - Visualized frequency distributions using bar charts
- Tracked pattern frequency changes across chunks
- Selected meaningful patterns for analysis
- Computed correlation matrices
- Visualized frequency trends over time
- Interpreted correlations and pattern evolution
- Documented limitations of row-based time simulation

---

## How to Run
1. Open the notebook:
   notebooks/477_Lab4_Incremental_Pattern_Mining_and_Correlation.ipynb
2. Ensure cleaned_comments.csv from Lab 2 is available
3. Run all cells sequentially

---

## Deliverables
- Jupyter Notebook:
  477_Lab4_Incremental_Pattern_Mining_and_Correlation.ipynb
- Lab Report (PDF):
  Lab 4 Report (146).pdf

---
