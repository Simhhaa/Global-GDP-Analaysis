# GDP Dashboard (2020–2025)

An interactive Power BI dashboard that compares GDP across 196 countries from 2020 to 2025.

## Tools
Power BI Desktop, Power Query, DAX, Excel

## Dataset
- `GDP_Excel_Data.xlsx`: 196 countries, GDP for 2020–2025, plus calculated columns
  (average GDP, total GDP, growth, global share, GDP per capita).
- Units are as provided in the source file.

## Dashboard Features
- KPI cards: total countries, average GDP, total GDP
- Average GDP and total GDP by country (ranked bar charts)
- Global share chart (2020–2021)
- GDP growth chart (2020–2025)
- Map of countries coloured by GDP per capita
- Country slicer for filtering all visuals

## Key Insights
- The United States and China lead total GDP, followed by Japan and Germany.
- Guyana shows the highest growth from 2020 to 2025 (about 372%).
- A few countries have missing recent years, which affects their totals.

## Data Notes and Limitations
- 7 countries have blank years (e.g., Afghanistan, Eritrea, Syria), so their totals,
  averages and growth are based on available years only.
- Global share and GDP per capita are taken from the source columns and should be
  validated before further use.
- GDP is not inflation-adjusted.

## Files
- `data/GDP_Excel_Data.xlsx`: source data
- `dashboard/GDP_Dashboard.pbix`: Power BI file
- `screenshots/dashboard.png`: dashboard preview

## Future Improvements
- Unpivot years into a long format and add a Date table
- Add CAGR and YoY growth as DAX measures
- Recalculate global share so it sums to 100%
- Add population data for true GDP per capita
- Publish to Power BI Service and add a live link

## Author
Simhotham Naidu | https://www.linkedin.com/in/simhotham-naidu/ | simhotham@gmail.com