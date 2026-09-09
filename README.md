Seasonal Agriculture Performance Analysis

Overview

This project analyzes agricultural performance across three Indian cropping seasons — Kharif, Rabi, and Zaid — to identify seasonal patterns, root causes, and evidence-based recommendations for stakeholders. The analysis is based on 4,000 farm records across 8 states, covering environmental conditions, resource usage, and financial outcomes.

Problem Statement:
Agricultural performance varies across seasons due to differences in environmental conditions, resource availability, and farming practices — but raw data alone doesn't explain how or why. This project investigates seasonal differences in agricultural performance and identifies meaningful patterns, trends, and relationships within the dataset.

Dataset
File: seasonal_agriculture_performance_dataset.csv
Size: 4,000 rows × 28 columns
Coverage: Farm ID, State, District, Crop, Season, farm area, weather/soil conditions, input usage (fertilizer, pesticide, water), yield/production, financials (cost, revenue, profit), and disease/pest risk
Key Finding

Loss rates rise steadily across the season calendar — 42.2% (Kharif) → 51.1% (Rabi) → 64.5% (Zaid). This is driven by declining yield and production (not cost or market price), traced back to Zaid's harsher environmental conditions: lowest rainfall, lowest soil moisture, lowest humidity, and highest temperature — despite farmers using the most irrigation water of any season.

Project Structure
Section	Description
1. Setup & Data Loading	Import libraries, load dataset
2. Explore & Understand	Check structure, category balance, nulls
3. Data Cleaning	Per-season median imputation, integrity checks
4. Economic Analysis	Revenue/cost/profit trends, loss %, boxplot, cost-vs-revenue
5. Yield & Production Analysis	Output trends, rainfall-vs-yield relationship
6. Environmental Root-Cause	Weather/water-use factor trends across seasons
7. State-Level Comparison	Regional loss-rate variation, Punjab vs Gujarat
8. Insights & Recommendations	Data-driven findings and stakeholder recommendations
9. Limitations	Scope and boundaries of the analysis
10. Future Scope	Suggested extensions for deeper analysis

Tools Used
Python — Pandas, NumPy
Visualization — Matplotlib, Seaborn
Environment — Jupyter Notebook

How to Run
Ensure seasonal_agriculture_performance_dataset.csv is in the same directory as the notebook.
Install dependencies:
   pip install pandas matplotlib seaborn
Open Seasonal_Agriculture_Performance_Analysis.ipynb in Jupyter Notebook / JupyterLab / VS Code and run all cells.
Author

Tamanna Yadav
