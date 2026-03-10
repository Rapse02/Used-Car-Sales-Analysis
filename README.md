# Used Car Sales Data Analysis & Visualization

## Project Overview
This repository contains an Exploratory Data Analysis (EDA) focused on a vehicle sales dataset. The primary objective is to audit raw data, perform data cleaning (handling inconsistencies), and extract actionable market insights using statistical visualizations. 

This project explores key automotive market questions, such as the distribution of selling prices and the correlation between a vehicle's mileage (odometer) and its final market value.

## Tech Stack & Libraries
* **Language:** Python 3
* **Data Manipulation:** `pandas`, `numpy`
* **Data Visualization:** `matplotlib`, `seaborn`
* **Environment:** Jupyter Notebook

## Key Features & Methodology
1. **Data Auditing & Cleaning:**
   * Initial assessment of dataset structure (rows, columns, and data types).
   * Data cleaning pipeline to create a reliable dataset (`df_limpio`) for accurate analysis.
2. **Exploratory Data Analysis (EDA) & Visualization:**
   * **Price Distribution:** Created histograms with Kernel Density Estimation (KDE) using `seaborn` to understand the frequency of different price points in the market.
   * **Depreciation Analysis:** Designed scatter plots mapping Selling Price vs. Odometer (Mileage) to visually demonstrate vehicle depreciation trends.
   * Aesthetic configurations applied to charts (e.g., `sns.set_style("whitegrid")`) for clear, executive-level reporting.

## Repository Structure
* `Vehicle_DA.ipynb`: Main Jupyter Notebook containing the full pipeline, from data auditing to the final visualizations.

---
*Created by Jose Emmanuel Mendoza Luna - Data Science Engineering Student*
