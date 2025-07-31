#  Smartphone Exploratory Data Analysis (EDA)

## Overview

This project presents a detailed Exploratory Data Analysis (EDA) on a selected dataset of smartphones. It focuses on performance, pricing, and feature trends across different brands, models, and specifications.

The dataset includes hundreds of smartphones and their attributes, such as:
- Brand, Model, Price, Rating
- Processor specs, RAM, Internal storage
- Camera resolution, Fast charging support
- Operating system, screen metrics, and more

---

## Objectives

- Ask meaningful questions to guide data exploration
- Analyze data structure and feature types
- Identify key trends, anomalies, and patterns by brand
- Test hypotheses, such as whether fast charging affects customer ratings
- Detect inconsistencies and missing values in the data

---

##  Key Questions Explored

- Which smartphone brands provide high value in terms of price versus performance?
- Does the availability of fast charging impact user ratings?
- How common is 5G support among mid-range devices?
- Are high-refresh-rate screens linked to higher prices?
- Which processor brand leads in flagship performance?

---

##  Technologies Used

- Python (Pandas, NumPy)
- Seaborn & Matplotlib for data visualization
- Scipy & Statsmodels for hypothesis testing
- Jupyter Notebook for analysis documentation

---

##  Dataset Summary

- Total rows: 1000+ smartphones
- File: `Smartphones_cleaned_dataset.csv`
- Format: CSV, structured tabular data
- Missing values detected in: `rating`, `fast_charging`, `extended_upto`, and a few others

---

##  Sample Insights

- Fast charging above 65W shows a positive correlation with ratings, as tested for statistical significance
- Some brands like *OnePlus* and *Xiaomi* consistently provide performance features at competitive prices
- Resolution inconsistencies were found, such as swapped width and height values in some cases
- Apple's ratings sometimes appear missing despite high price tags, likely due to gaps in the review system


---

##  Data Cleaning Notes

- Removed or flagged duplicate models
- Handled null values for key features
- Standardized boolean flags to binary values

---

##  Next Steps

- Feature engineering for modeling or clustering, such as calculating `pixels_per_inch` and defining price segments
- Price prediction using regression methods
- Creating a dashboard for interactive exploration
- Integrating insights with business strategies or retail analysis


---



