# Week 2: Logistics Data Collection, Cleaning, and Preprocessing

## Overview
This project documents a simulated data preprocessing pipeline for logistics-related analysis using Python, pandas, and scikit-learn.

## Dataset reference
- **UCI Online Retail II:** https://archive.ics.uci.edu/dataset/502/online+retail+ii
- This is transactional retail data that can inform demand and inventory analysis. It is not a direct transport-time dataset.

## Workflow
1. Load and inspect the data.
2. Standardize column names and data types.
3. Identify and remove verified exact duplicates.
4. Inspect and handle missing values according to the analysis goal.
5. Investigate invalid values and flag quantity outliers using IQR.
6. Scale numeric features when useful for a chosen model.
7. Create basic features, validate the processed dataset, and export a clean CSV.

## Files
- `Week_2_Logistics_Data_Preprocessing_Report.docx` — assignment report.
- `README_Week_2.md` — project overview.

## Important notes
The code in the report is an illustrative template. Download the dataset, verify its actual column names and file format, then run and adjust the code before claiming that the pipeline was executed. Negative quantities may represent returns and should not be removed without considering the analysis objective. Keep the raw dataset unchanged.

## Tools
- Python
- pandas
- scikit-learn

## Learning outcome
The project explains how data quality affects the reliability of demand analysis, inventory planning, and downstream predictive modelling.
