# Power BI Report

This folder contains the Power BI Desktop project for the COVID-19 Vaccinations Trend Analysis.

## File

`covid19_vaccination_trend_analysis.pbix`

## Analysis Scope

The Power BI project explores global COVID-19 vaccination data during the 2021–2022 analysis period.

The original project examined:

- people vaccinated and fully vaccinated
- total vaccinations
- daily vaccination trends
- vaccinations per hundred
- daily vaccinations per million
- country-level comparisons
- vaccination data sources

## Workflow

The documented project workflow was:

1. Load the country vaccination dataset into Power BI Desktop.
2. Clean and preprocess the dataset.
3. Create charts, graphs, cards, and tables.
4. Analyze vaccination trends and country-level patterns.
5. Summarize observations and recommendations.

## Analytical Limitations

The original project replaced some null values with zero during preprocessing. Missing observations are not necessarily true zero values, so this can influence calculated results.

Some original country-level visuals also use `Sum` aggregation on cumulative vaccination fields. These results should not be interpreted as latest-date vaccination totals.

The project is therefore presented primarily as evidence of Power BI, data preparation, visualization, and exploratory data-analysis skills.
