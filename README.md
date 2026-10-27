# CodeAlpha_RetailSalesAnalysis

Exploratory Data Analysis (Task 2) and Data Visualization (Task 3) on a 1,000-transaction retail sales dataset (Jan 2023 – Jan 2024).

**Tools:** Python, pandas, Matplotlib, Seaborn, SciPy

## Key findings
- **Clean data:** no missing values, duplicates, or calculation errors.
- **Balanced categories:** Electronics 34.4%, Clothing 34.1%, Beauty 31.5% of revenue.
- **Price tier drives revenue:** items at 300 and 500 are ~40% of orders but 88% of revenue.
- **Seasonality:** peak in May, dip in September; Saturday is the strongest weekday.
- **Demographics:** gender, age, and category show no statistically significant effect on order value (Mann-Whitney, Spearman, Chi-square, Kruskal-Wallis, all p > 0.05).

## Recommendation
Prioritise high-price products and peak months (May, October, December); investigate the September dip.

## Run it
```
pip install pandas matplotlib seaborn scipy
jupyter notebook analysis.ipynb
```
Charts are saved to `/charts`.
