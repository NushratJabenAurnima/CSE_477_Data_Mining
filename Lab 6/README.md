# Lab 6 – Text Mining with YouTube Data

## Overview
This lab presents a comparative text mining analysis of YouTube video captions and user comments. The goal is to examine how creator-generated content differs from audience-generated responses in terms of language structure, thematic focus, and sentiment.

## Data Description
The analysis is based on two cleaned datasets generated in earlier stages of the project:
- cleaned_comments.csv
- cleaned_captions.csv

Each dataset contains a `cleaned_tokens` column with normalized and tokenized text. These tokens were reconstructed into continuous text to enable TF–IDF vectorization, n-gram extraction, and sentiment analysis.

Captions represent structured and instructional content produced by the creator, while comments capture spontaneous audience reactions that are often informal and metadata-heavy.

## Analytical Approach
The workflow follows a structured text mining pipeline:
- TF–IDF keyword extraction to identify dominant terms in captions and comments
- Keyword overlap analysis to compare shared and unique themes
- Bigram TF–IDF analysis to capture short phrase-level patterns
- Sentiment analysis to assess emotional tone across both datasets
- Interpretation of results in relation to earlier analyses such as co-occurrence mining and clustering

## Key Findings
The results reveal a clear distinction between captions and comments. Captions are linguistically coherent and task-oriented, emphasizing instructional and technical language. In contrast, comments are dominated by reactions, platform-specific tokens, and repeated URL fragments, leading to sparse and less structured patterns. Keyword overlap and bigram analyses show minimal meaningful similarity between the two datasets, while sentiment analysis indicates an overall neutral tone driven by informational and non-emotive content.
