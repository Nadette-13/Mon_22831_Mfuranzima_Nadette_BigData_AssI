# Uber Fares Dataset Analysis

**Student Name:** Mfuranzima Nadette  
**Student ID:** 22831  
**Course:** Introduction to Big Data Analytics (INSY 8413)  
**Instructor:** Eric Maniraguha  
**Assignment:** Assignment I – Uber Fares Dataset Analysis  

---

## Project Overview

This project analyzes the Uber Fares Dataset from Kaggle to uncover insights about fare patterns, ride volumes, and temporal trends in New York City. The analysis includes data cleaning, feature engineering, exploratory data analysis (EDA), and visualization.

---

## Data Preparation & Feature Engineering

- Loaded the raw dataset into Python using Pandas.
- Performed data cleaning by handling missing values and correcting data types.
- Created new features such as Hour, Day, Month, Weekday, and Peak/Off-peak time indicators.
- Exported the cleaned dataset as `uber_cleaned.csv` for further analysis.

---

## Exploratory Data Analysis (EDA) and Visualizations

Since Power BI and Excel faced technical issues on my system, I used Python libraries Matplotlib and Seaborn to generate key visualizations:

- **Number of Rides by Hour:** Shows peak ride times throughout the day.  
- **Number of Rides by Weekday:** Displays ride distribution across the week.  
- **Peak vs Off-Peak Rides:** Categorizes rides based on time to highlight busy periods.

Screenshots of these visualizations are included in the `/images` folder.

---

## Issues Faced & Solutions

- Experienced repeated errors ("Class Not Registered") when attempting to load data into Power BI Desktop.  
- Excel charts also failed to load data correctly on my system.  
- As a workaround, completed all data cleaning, analysis, and visualization using Python (Google Colab).  
- Visualizations generated in Python serve as effective alternatives to Power BI charts.  
- Detailed process and insights are fully documented to ensure project completeness.

---

## Visualizations

### Rides by Hour  
![Rides by Hour](number_of_rides_by_hour)

### Rides by Weekday  
![Rides by Weekday](rides_by_weekday)

### Peak vs Off-Peak Rides  
![Peak vs Off-Peak](peak_Offpeak)

---
## Fare Amount Distribution (Histogram)

This histogram shows how fare amounts are distributed across the dataset. It helps identify pricing trends, outliers, and common fare ranges.

![Fare Amount Distribution](Fare_Amount_Distribution(Histogram))
## Fare Amount Distribution with Mean and Mode

This chart visualizes how Uber fares are distributed across the dataset and highlights the statistical mean and mode, which help identify central pricing trends.

![Fare Amount - Mean and Mode](e2025-07-25 at 11.20.52_fd47fdac)



## Dataset

Cleaned dataset used for analysis:  
[data/uber_cleaned.csv](uber_cleaned.csv)

---

## Conclusions and Recommendations

- Uber ride volumes peak during morning (7–9 AM) and evening (4–7 PM) rush hours.  
- Weekdays generally have higher ride counts compared to weekends, with Tuesday and Friday being the busiest days.  
- Understanding these patterns can help optimize driver allocation and pricing strategies.

---

## Repository Structure

