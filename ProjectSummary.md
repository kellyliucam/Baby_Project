# Tourism & Hospitality Industry Analysis

## Introduction

This project analyzes tourism and hospitality metrics across multiple cities and countries on a monthly basis. The goal is to explore patterns in tourist arrivals, length of stay, occupancy rates, and city revenue, as well as to examine how specific factors like hotel ratings influence occupancy.

The original dataset was merged with an AI-generated dataset to improve the analysis and provide additional insights.


## Data & Project Organization

- There are 23 columns and 500 rows in the dataset
- 11 numeric (float64)  
- 9 integer (int64)  
- 4 text/object  
- The dataset is complete with no missing values.

**Project Files:**

- `/data/` folder contains datasets (ignored in `.gitignore`)  
- `/scripts/` folder contains Python scripts 

**Reason for Merging:**
- Part 2 was merged into the main branch because it was more organized and polished.  
- The `.gitignore` file was updated to exclude raw data and unnecessary files, ensuring a clean repository.  
- Commit history contains meaningful messages to track all major changes.


## Analysis

- Calculated averages, maximums, and other descriptive statistics for key metrics.  
- Explored correlations between occupancy rates and hotel ratings.  
- Visualized trends using bar charts, line plots, and scatter plots.


## Insights

- **Tourism Statistics:**  
  - Average tourists per month: 125,263  
  - Average length of stay: 8.67 days  
  - Average occupancy rate: 64.84%  
  - Average city revenue per month: $349,737 USD  
  - Maximum monthly city revenue: $951,466 USD  
  - Las Vegas receives the most tourists per month.  
  - Tourism purposes are evenly split across categories.  
  - Occupancy rate does not strongly correlate with hotel ratings, indicating hotel ratings are **not a reliable predictor of occupancy**.

## Conclusion

- Part 2 improvements improved the project through better organization, clearer analysis, and updated GitHub practices.  
- The final project branch contains all scripts, output, sources, and write-up files.  
