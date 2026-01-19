# Airline Customer Data Pipeline & Analysis

An end-to-end data project demonstrating a complete ETL pipeline: from raw data extraction and Power Query transformation to Python cleaning and Power BI visualization.

## Project Workflow
1. **Extraction:** Raw airline dataset (`flight.csv`).
2. **Transformation (Power Query):** Initial filtering, data type adjustments, and structural formatting.
3. **Refinement (Python):** * Addressed missing values in the `Age` column using statistical imputation (Mean).
    * Conducted deep cleaning and removed duplicate entries.
    * Renamed technical headers to user-friendly business terms.
4. **Visualization:** Interactive dashboard for analyzing customer demographics and loyalty program tiers.

## Tech Stack
* **ETL:** Power Query (Excel/Power BI)
* **Processing:** Python (Pandas)
* **Visualization:** Power BI (`charts.pbix`)

## Repository Structure
* `data/`: Contains the three stages of data (Raw, Post-PowerQuery, Final-Cleaned).
* `Python_Cleaning.ipynb`: The Python script for final data refinement.
* `charts.pbix`: The final analytical dashboard.




