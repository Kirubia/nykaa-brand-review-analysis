# Nykaa Brand Review Analysis

End-to-end data analysis project on 61,284 beauty product reviews 
from Nykaa's top 11 brands using Python, SQL, and Power BI.

## Tools Used
- Python (Pandas, Matplotlib, Seaborn) — data cleaning and analysis
- SQL (pandasql) — business queries
- Power BI — interactive dashboard
- Git + GitHub — version control

## Key Findings
1. Kay Beauty leads all brands with highest avg rating (4.69) 
   and strongest 5-star ratio
2. Review volume tripled in 2019 — aligns with Nykaa's 
   pre-IPO expansion phase
3. Medium discounts (11–25%) drive more reviews than 
   high discounts — pricing strategy insight
4. 78% of reviews are from Verified Buyers — high trust signal
5. Herbal Essences offers the highest avg discount at 35%

## Project Structure
- `nykaa_analysis.ipynb` — full analysis notebook
- `nykaa_cleaned.xlsx` — cleaned dataset for Power BI
- `nykaa analytics.pbix` — Power BI dashboard
- `chart1_brand_ratings.png` — avg rating by brand
- `chart2_yearly_trend.png` — review growth 2015-2022
- `chart3_rating_distribution.png` — rating distribution
- `chart4_heatmap.png` — brand vs year heatmap
- `chart5_boxplot.png` — rating consistency by brand

## Dataset
Source: Kaggle — Nykaa Top Brands Cosmetics Product Reviews  
61,284 reviews | 11 brands | 2013–2022

## How to Run
1. Clone this repository
2. Install dependencies: `pip install pandas matplotlib seaborn 
   vaderSentiment pandasql openpyxl`
3. Open `nykaa_analysis.ipynb` in Jupyter Notebook
4. Run all cells in order