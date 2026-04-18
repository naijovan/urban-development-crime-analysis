# Impact of Urban Development Factors on City Crime Rates

## Project Overview
This project investigates how urban development factors such as population density, night time light intensity, and CCTV density affect crime rates across cities worldwide. Multiple global datasets were cleaned, integrated, and enriched using geospatial techniques to support statistical and spatial analysis.

## Research Question
How do urban developmental factors affect the crime rate in a city

## Tech Stack
Python, Google Colab, pandas, NumPy, matplotlib, scipy, geopandas, pyproj, shapely, sqlite3

## Methodology

### Data Preparation
- Cleaned and standardised city and country fields across datasets
- Handled inconsistencies using case insensitive matching and trimming

### Feature Engineering
- Derived population density using population and area data
- Enriched missing city level data through dataset integration

### Data Integration
- Merged datasets using shared attributes
- Applied coordinate based fuzzy joins using latitude and longitude
- Improved data completeness and enabled city level analysis across more than 180 countries

### Analysis
- Conducted exploratory statistical and spatial analysis
- Evaluated relationships between urban development factors and crime rates

## Key Highlights
- Built an end to end data pipeline for multi source data integration
- Applied geospatial enrichment to improve dataset usability
- Generated insights on relationships between infrastructure and crime

## Repository Structure
- urban_development_crime_analysis.ipynb main notebook
- README.md project documentation

## How to Run
1. Open the notebook in Google Colab  
2. Upload or connect datasets  
3. Run cells sequentially  

## Authors
Jovan Nai
Xu Xia
Mabel Lee
