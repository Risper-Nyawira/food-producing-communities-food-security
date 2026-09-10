# Data Inventory

Project question:

Why can food-producing communities still experience food insecurity?

## Main Data Files

| File | Theme | Use in the project |
|---|---|---|
| `data/raw/faostat_kenya_crop_livestock.csv` | Agricultural production | Production, yield, area harvested, stocks and livestock measures for Kenya crops/livestock |
| `data/raw/Food_Security_Data_E_Africa/Food_Security_Data_E_Africa_NOFLAG.csv` | Food security | Kenya food insecurity, undernourishment, dietary energy supply, import dependency and related food security indicators |
| `data/raw/wfp_food_prices_kenya.csv` | Market dynamics | Food prices by commodity, market, location and date |
| `data/raw/wfp_markets_kenya.csv` | Market geography | Market names, counties/admin areas, latitude and longitude |
| `data/raw/worldbank_kenya_average_precipitation_depth_mm.csv` | Climate | Annual precipitation/rainfall context |
| `data/raw/worldbank_kenya_land_surface_temperature_c.csv` | Climate | Annual temperature context |
| `data/raw/worldbank_kenya_spei.csv` | Climate | Drought/wetness indicator |
| `data/raw/worldbank_kenya_heat_index_35.csv` | Climate | Heat stress indicator |
| `data/raw/worldbank_kenya_socioeconomic_context.csv` | Socioeconomic context | Population, rural population, GDP per capita, inflation, poverty, agricultural employment and food imports |

## Suggested First Analysis

Start with maize as the pilot commodity.

1. Use SQL to create yearly maize production, yield and area harvested.
2. Use SQL to create yearly maize retail price.
3. Join production, prices, climate and food security by year.
4. Use Power BI for dashboarding.
5. Use Python for trends, correlations, lag analysis and simple regression.

## Sources

- FAOSTAT: https://www.fao.org/faostat/
- WFP/HDX Kenya Food Prices: https://data.humdata.org/dataset/wfp-food-prices-for-kenya
- World Bank Indicators API: https://api.worldbank.org/v2/
- World Bank Climate Change Knowledge Portal: https://climateknowledgeportal.worldbank.org/

## Optional Data To Add Later

- County-level food security classification data from IPC or FEWS NET
- Household income/consumption survey data
- County-level poverty data
- Policy/intervention timeline data
- Import/export and trade restriction data

