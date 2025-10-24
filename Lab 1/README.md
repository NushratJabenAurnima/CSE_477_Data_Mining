# Lab 1 — YouTube Captions & Comments EDA

**Open first:** `reports/Lab_1_Report_146.pdf`  
**Run:** `notebooks/477_lab1_youtube_146.ipynb`

## What this lab does
- Collects **captions** (yt-dlp) and **comments** (YouTube Data API v3).  
- Cleans & deduplicates text; builds datasets for analysis.  
- EDA: length distributions, Type-Token Ratio, top words, hourly activity, length vs. likes.  
- Outputs saved under `data/processed/`.

## How to run (local / Colab)
1. `pip install -r "Lab 1/requirements.txt"`  
2. Create a file named `.env` (next to this README) and add:  
    `YOUTUBE_API_KEY=YOUR_KEY_HERE`  
3. Open `notebooks/477_lab1_youtube_146.ipynb` and run cells top to bottom.

## Folder map
- `notebooks/` → source notebook  
- `data/raw/` → original inputs (captions, raw comments, CSV)  
- `data/processed/` → outputs from notebook (selected/unique comments etc.)  
- `reports/` → final PDF report  

> Note: Never commit real API keys — `.env` is git-ignored.
