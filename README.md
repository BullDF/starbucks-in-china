# Starbucks in China: A Spatial Analysis

📄 **[View Full Report (PDF)](report/report.pdf)**

## About

This project analyzes the spatial distribution of Starbucks stores across China using spatial statistics techniques. The study examines 4,166 Starbucks locations as of December 2019, spanning 168 cities in Mainland China.

## Research Questions

1. **Provincial Analysis**: Is there spatial autocorrelation in Starbucks store counts between neighboring provinces? How do socioeconomic factors like GDP and population influence store distribution?

2. **Shanghai Focus**: What spatial patterns exist in Starbucks locations within Shanghai? Can we identify clusters and model the point distribution?

## Data Sources

- Starbucks store locations in China (Kaggle)
- Chinese administrative boundaries (shapefiles)
- Provincial GDP and population data
- Shanghai district demographics

## Methodology

- **Areal Analysis**: Spatial autocorrelation testing, local spatial statistics, and spatial regression models with economic covariates
- **Point Pattern Analysis**: Complete spatial randomness testing, kernel density estimation, clustering algorithms, and point process modeling

## Project Structure

- `code/`: R Markdown analysis files and Python data processing
- `clean_data/`: Processed datasets
- `maps/`: Chinese administrative boundary shapefiles
- `report/`: Final LaTeX report and generated figures

---

*STA465 Spatial Statistics Project, University of Toronto*