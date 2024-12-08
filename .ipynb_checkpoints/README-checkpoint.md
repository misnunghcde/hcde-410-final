# hcde-410-final
# README: Correlation Analysis Between Birth Rate, Happiness Index, and Economic Indicators in South Korea

## Project Overview
This project investigates the relationships between fertility rates, happiness indices, and economic indicators, specifically focusing on South Korea. The analysis uses international datasets to identify patterns and outliers, contextualizing South Korea’s unique demographic challenges within global trends. Key research questions focus on whether non-marital birth rates correlate with overall fertility rates and how broader societal factors influence these metrics.

## Dataset Details

1. **Fertility Rate Data**
   - **Source**: World Bank Fertility Rate Data
   - **URL**: https://data.worldbank.org/indicator/SP.DYN.TFRT.IN
   - **Description**: Annual fertility rate data indicating the average number of children born to a woman during her reproductive years.
   - **License**: Most datasets from the World Bank are licensed under the Creative Commons Attribution 4.0 International License (CC BY 4.0). This license allows users to copy, adapt, distribute, and use the data for any purpose, provided proper attribution is given. Some datasets may have additional licensing conditions that must be followed. More details can be found at: https://datacatalog.worldbank.org/public-licenses

2. **Happiness Index Data**
   - **Source**: World Happiness Report Data
   - **URL**: https://worldhappiness.report/data/
   - **Description**: Annual data capturing life satisfaction and related metrics, such as GDP per capita and healthy life expectancy.
   - **License**: Data is publicly accessible with attribution required. Visualizations such as dashboards and maps are licensed under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License (CC BY-NC-SA 4.0). Full license details at: https://creativecommons.org/licenses/by-nc-sa/4.0/

3. **Non-Marital Birth Rate Data**
   - **Source**: OECD Family Database - Share of Births Outside Marriage
   - **URL**: https://www.oecd.org/en/data/datasets/oecd-family-database.html
   - **Description**: National-level data on the share of births occurring outside of marriage.
   - **License**: Open for use under OECD’s specific Terms and Conditions. The OECD encourages using their data to develop software applications and requires users to adhere to their terms when using datasets and APIs. More details at: https://www.oecd.org/termsandconditions/

## Methodology
- **Data Cleaning and Integration**: Datasets were cleaned, standardized, and merged using consistent country names and time ranges (2010–2020).
- **Analysis Techniques**: 
  - Correlation analysis to examine relationships between fertility rates and societal indicators.
  - Double-axis bar graphs for simultaneous visualization of fertility rates and non-marital birth rates across countries.
- **Visualization Libraries**: Matplotlib and Pandas were used to generate visual insights.

## Findings
- South Korea exhibits both the lowest fertility rate globally and a significantly low percentage of non-marital births.
- A weak positive correlation (0.10913) between non-marital birth rates and fertility rates globally challenges assumptions about their direct relationship.
- Broader societal factors, including economic stress and rigid cultural norms, significantly influence South Korea’s demographic crisis.

## Limitations and Future Directions
- **Data Gaps**: Missing data for certain years or countries may have impacted the completeness of the analysis.
- **Contextual Sensitivity**: Insights from international datasets may not directly translate to actionable solutions for South Korea due to unique socio-cultural contexts.
- **Recommendations**: To address South Korea's demographic challenges holistically, future research should integrate qualitative studies and focus on interdisciplinary approaches.

## Reproducibility
- All code, data, and visualizations are contained within the Jupyter Notebook in this repository.
- Supplementary datasets used for analysis are provided in CSV format.

## License
This project is licensed under the MIT License. The datasets follow their respective licenses as mentioned above. Users must ensure compliance with these licenses when utilizing the datasets, including:

- **World Bank License**: Most data is under the CC BY 4.0 license, which allows broad usage provided proper attribution is given. Additional conditions may apply to specific datasets. More details can be found at: https://datacatalog.worldbank.org/public-licenses
- **OECD Terms**: Data can be used under OECD’s terms, encouraging the development of applications while requiring adherence to specific usage guidelines. See more at: https://www.oecd.org/termsandconditions/
- **World Happiness Report License**: Visualizations and data are under CC BY-NC-SA 4.0, which restricts commercial use and requires attribution. Full details at: https://creativecommons.org/licenses/by-nc-sa/4.0/.

- This part was helped by AI.