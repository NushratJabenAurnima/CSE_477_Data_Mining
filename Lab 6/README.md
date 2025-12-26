# Lab 6 – Text Mining with YouTube Data

## Objective
The objective of this lab is to apply text mining techniques to YouTube comments and captions using TF–IDF, bigram analysis, and sentiment analysis. The goal is to compare creator-intended themes in captions with audience-driven discussions found in comments.

## Dataset
This lab uses cleaned datasets produced in earlier labs:
- cleaned_comments.csv
- cleaned_captions.csv

Both datasets include a `cleaned_tokens` column, which is reconstructed into text for analysis.

## Tools and Libraries
- Python
- pandas
- scikit-learn
- matplotlib
- matplotlib-venn
- TextBlob / VADER

## Methodology
1. Load cleaned comments and captions datasets
2. Reconstruct text from token lists
3. Apply TF–IDF to extract important keywords
4. Compare keyword overlap between comments and captions
5. Perform TF–IDF bigram analysis
6. Conduct sentiment analysis and visualize sentiment distributions
7. Relate findings to techniques used in previous labs

## Folder Structure
Lab 6/
├── README.md
├── notebooks/
│   └── CSE477_Lab6_TextMining_Jaben.ipynb
└── reports/
    └── Lab6_Report.pdf


