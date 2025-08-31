# Netflix Dataset Analysis - Data Preparation for Power BI

## Project Overview
This project analyzes Netflix content data (November 2019) using Python for data preparation and Power BI for visualization.

## Dataset
- **Source:** Netflix titles dataset (November 2019)
- **Records:** 5,410 titles after cleaning
- **Content:** Movies and TV shows with metadata

## Data Cleaning Process
- Handled missing values in country, rating, and date_added columns
- Removed 427 entries with missing country data (7.32%)
- Converted date_added to proper datetime format
- Maintained data integrity for director/cast missing values

## Files
- `netflix_data_preparation.ipynb` - Data cleaning and preparation notebook
- `netflix_cleaned_for_powerbi.csv` - Cleaned dataset ready for Power BI
- Original analysis in Python with Power BI implementation guidelines

## Key Insights
- Content distribution: Movies vs TV Shows
- Geographic content analysis by country
- Content rating categories
- Timeline analysis of content additions

## Tools Used
- **Python:** pandas, matplotlib for data preparation
- **Power BI:** For interactive visualizations and dashboards
- **Jupyter Notebook:** For data exploration and cleaning

## How to Use
1. Clone this repository
2. Open `netflix_data_preparation.ipynb` to see data cleaning process
3. Import `netflix_cleaned_for_powerbi.csv` into Power BI for visualization
