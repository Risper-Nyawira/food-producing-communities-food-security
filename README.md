# Food-Producing Communities and Food Security in Kenya

## Research question

Why can food-producing communities still experience food insecurity?

## Project summary

This project brings together annual maize production, yield, cultivated area, maize retail prices, climate indicators, and national food insecurity data for Kenya. It tests the idea that producing food is necessary, but does not by itself guarantee that households can afford, access, or consistently obtain a nutritious diet.

## Tools used

- SQL and SQLite for preparing the annual analysis table
- Power BI for interactive dashboarding
- Python (pandas, matplotlib, seaborn) for data checks, trend charts, and correlations

## Main finding

National maize production continued throughout the period, yet the prevalence of moderate or severe food insecurity rose from 50.7% for the 2014-2016 rolling period to 72.8% for 2021-2023. This supports the conclusion that food production alone is not enough. Affordability, price volatility, climate stress, incomes, storage, market access, and how food is distributed also matter.

## Project structure

- `data/raw` contains the original downloads and is not uploaded to GitHub.
- `data/processed` contains the cleaned annual analysis dataset and Power BI dashboard.
- `sql` contains the SQLite database and DB Browser project file.
- `notebooks` contains the Python analysis notebook.
- `outputs` contains Python charts and summary tables.
- `docs` contains data notes and the conclusions and recommendations.

## Reproduce the Python analysis

1. Open Anaconda Navigator and launch Jupyter Notebook.
2. Open `notebooks/01_food_producing_communities_analysis.ipynb`.
3. Choose `Kernel` then `Restart Kernel and Run All Cells`.
4. The notebook reads `data/processed/maize_food_security_analysis_fixed.csv` and saves charts and tables in `outputs`.

## Important limitation

The food-insecurity measure is a three-year moving average and only has eight observations in this dataset. The analysis can show useful patterns and context, but it cannot prove that a single factor caused food insecurity.
