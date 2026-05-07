# Annual Enterprise Survey Analysis (2011–2024)

A data analysis project exploring financial trends across New Zealand industries using 14 years of enterprise survey data.

---

## Overview

This project cleans, analyses, and visualises the [New Zealand Annual Enterprise Survey](https://www.stats.govt.nz/large-datasets/csv-files-for-download/) published by Stats NZ, covering financial years 2011 to 2024. The goal is to identify revenue trends, top-performing industries, and relationships between sectors over time.

---

## Objectives

- Clean and preprocess raw survey data
- Handle inconsistent and missing values (including suppressed "C" entries)
- Explore revenue trends across industries and years
- Visualise key business insights through charts and heatmaps

---

## Dataset

- **Source:** [Stats NZ – Annual Enterprise Survey](https://www.stats.govt.nz/large-datasets/csv-files-for-download/)
- **File:** `annual-enterprise-survey-2011-2024-financial years.csv`
- **Coverage:** Financial years 2011–2024
- **Classification:** ANZSIC (Australian and New Zealand Standard Industrial Classification)

> Download the CSV from the link above and place it in the same folder as the notebook before running.

---

## Project Structure

```
├── Analysis.ipynb                        # Main analysis notebook
├── annual-enterprise-survey-...csv       # Dataset (download separately)
├── requirements.txt                      # Python dependencies
└── README.md                             # Project documentation
```

---

## Key Findings

- **Financial and Insurance Services** was the highest-revenue industry in both 2011 and 2024.
- **Real Estate and Construction** showed the strongest growth over the 14-year period, with a strong positive correlation between the two sectors.
- Most industries recorded a brief dip in 2013 before resuming growth.
- Overall economic expansion is evident across virtually all sectors from 2011 to 2024.

---

## Visualisations

| Chart | Description |
|-------|-------------|
| Top 10 Industries (2011) | Horizontal bar chart of highest-revenue industries |
| Top 10 Industries (2024) | Horizontal bar chart for comparison |
| 2011 vs 2024 Comparison | Side-by-side bar chart showing revenue growth |
| Industry Share Pie Charts | Percentage contribution of top 10 industries |
| YoY Analysis – Finance (K) | Revenue, absolute change, and % change over time |
| YoY Analysis – Real Estate (L) | Same three-panel view for Real Estate |
| YoY Analysis – Agriculture (A) | Same three-panel view for Agriculture |
| Real Estate vs Construction | Dual line chart with correlation analysis |
| All-Industry Heatmap | Revenue by industry and year (2011–2024) |

---

## Tools & Libraries

- Python 3
- Pandas
- Matplotlib
- Seaborn

---

## How to Run

1. Clone the repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Download the dataset and place the CSV in the project folder
4. Open and run `Analysis.ipynb` in Jupyter Notebook or JupyterLab
