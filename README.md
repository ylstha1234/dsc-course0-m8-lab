# Data Analysis Jet Airline Safety

# Project Overview
This project analyzes commercial and passenger jet airline accident data from 1948 to 2023 to assist an airline/airplane insurance client in identifying aircraft makes/models with:
1. Low rates of total destruction
2. Low likelihood of fatal or serious injuries in the event of an accident
The goal is to make statistically supported recommendations based on historical safety performance, while also identifying conditions or factors (e.g., phase of flight, weather, engine type) that affect aircraft safety.

# Client Requirements
1. Focus only on professional aircraft still potentially in use (models active post-1983; assume 40-year max lifespan).

2. Provide separate insights for:

   Small aircraft (< 20 passengers)

   Large aircraft (≥ 20 passengers)

3. Only consider makes/models with at least 10 records to ensure statistical robustness.

4. Investigate and highlight at least two contributing variables to safety (e.g., engine count, flight phase, weather).

# Dataset
 
  AvaiationData.CSV file

# Tasks Summary

  Data Loading & Cleaning

  Load CSV into a pandas DataFrame

  Drop or impute missing values

  Filter records from 1983 onward

# Feature Engineering

  Compute total passengers per accident

  Calculate serious/fatal injury rates

  Add binary is_destroyed flag

  Classify aircraft as Small or Large

# Exploratory Data Analysis (EDA)

  Group by Make and compute:

  Mean injury rate

  Mean destruction rate

  Filter to makes with ≥10 records

  Visualize with barplots, violin plots, and stripplots

# Factor Impact Analysis

  Analyze the effect of:

  Phase of Flight (e.g., approach, cruise, climb)

  Engine Count

  Use grouped barplots and distribution plots

# Recommendations

  Identify the top 10 safest makes (separately for small and large aircraft)

  Discuss factors contributing to safety

  Highlight outliers or makes with high risk

# Key Tools & Libraries
  
  Python

  Pandas: Data manipulation and wrangling

  Seaborn/Matplotlib: Visualization

  NumPy: Numerical operations

# Outcomes

  List of aircraft makes/models with strong safety profiles

  Visual and statistical insights into aircraft destruction and injury outcomes

  Factor-based recommendations for safer operations and insurability

# Sample Visuals

  Barplots comparing mean destruction and injury rates

  Violin plots of injury rate distributions

  Grouped barplots analyzing phase of flight and engine impact

# Final Recommendation

This project delivers a data-driven safety profile of jet aircraft to guide decisions related to fleet choices and insurance risk. Aircraft makes with proven structural durability and lower injury likelihood are clearly identified, alongside environmental or operational variables impacting outcomes.

# References

Link: https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses