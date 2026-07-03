# Statistical Plots & Distribution Analysis

## Project Overview
This project performs statistical distribution analysis on a customer sales dataset using Python. It visualizes the data with histograms, KDE plots, and boxplots, compares distributions across regions, detects outliers, and measures skewness and spread.

## Dataset
The dataset contains 50 customer records with the following attributes:
- Cust_ID
- Region
- Age
- Sales

## Objectives
- Draw Histograms to inspect data distribution.
- Draw KDE (Kernel Density Estimation) plots.
- Create Boxplots to identify outliers.
- Compare Sales distribution across different Regions.
- Detect outliers using the IQR method.
- Calculate skewness and standard deviation.
- Export plots as PNG images.
- Provide statistical interpretation.

## Technologies Used
- Python
- Pandas
- Matplotlib
- Seaborn

## How to Run
1. Install the required libraries:
pip install pandas matplotlib seaborn
2.Place `customer_data.csv` in the project folder.
3. Run the Python notebook or script.

## Output
The project generates:
- Histogram of Sales
- KDE Plot of Age
- Sales Boxplot
- Sales Distribution by Region
- Age Distribution by Region
- Outlier Detection Report
- Skewness and Standard Deviation
- Saved plot images in PNG format

## Conclusion
The project demonstrates how statistical visualization techniques can be used to understand data distribution, compare groups, identify outliers, and analyze the spread and skewness of numerical data. These insights help in making better data-driven decisions.
