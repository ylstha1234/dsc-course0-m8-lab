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

4. Investigate and highlight at least two contributing variables to safety (e.g., flight phase, weather).

# Dataset
 
  AvaiationData.CSV file

# Tasks Summary

# Data Loading & Cleaning

1. Load CSV into a pandas DataFrame

2. Drop or impute missing values

3. Filter records from 1983 onward

# Feature Engineering

1. Compute total passengers per accident

2. Calculate serious/fatal injury rates

3. Add binary is_destroyed flag

4. Classify aircraft as Small or Large

# Exploratory Data Analysis (EDA)

1. Group by Make and compute:

2. Mean injury rate

3. Mean destruction rate

4. Filter to makes with ≥10 records

4. Visualize with barplots, violin plots, and stripplots

# Factor Impact Analysis

Analyze the effect of:

1. Phase of Flight (e.g., approach, cruise, climb)

2. Engine Count

3. Use grouped barplots and distribution plots

# Recommendations

1. Identify the top 10 safest makes (separately for small and large aircraft)

2. Discuss factors contributing to safety

3. Highlight outliers or makes with high risk

# Key Tools & Libraries

1. Python

2. Pandas: Data manipulation and wrangling

3. Seaborn/Matplotlib: Visualization

3. NumPy: Numerical operations

# Outcomes

1. List of aircraft makes/models with strong safety profiles

2. Visual and statistical insights into aircraft destruction and injury outcomes

3. Factor-based recommendations for safer operations and insurability

# Final Recommendation

This project delivers a data-driven safety profile of jet aircraft to guide decisions related to fleet choices and insurance risk. Aircraft makes with proven structural durability and lower injury likelihood are clearly identified, alongside environmental or operational variables impacting outcomes.

# References

  Link: https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses