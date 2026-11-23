# Task 2: Unemployment Analysis with Python

## Project Overview
This project focuses on analyzing unemployment data in India using Python. Exploratory Data Analysis (EDA) is performed to identify state-wise unemployment patterns, monthly trends, regional differences, and changes during the COVID-19 pandemic.

This project was completed as part of the **Oasis Infobyte Data Science Internship – Task 2**.

## Objectives
- Analyze unemployment rates across Indian states.
- Identify the top 10 states with the highest average unemployment rates.
- Study monthly unemployment trends.
- Compare unemployment trends across Maharashtra, Haryana, and Tamil Nadu.
- Examine correlations between employment indicators.
- Compare unemployment rates before and during the COVID-19 period.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Dataset
The project uses two CSV datasets:
1. `Unemployment in India.csv`
2. `Unemployment_Rate_upto_11_2020.csv`

The datasets contain information about regions, dates, estimated unemployment rates, estimated employment, and labour force participation rates.

## Project Structure
```text
DataScience-Task2-UnemploymentAnalysis/
│
├── unemployment_analysis.ipynb
├── Unemployment in India.csv
├── Unemployment_Rate_upto_11_2020.csv
└── README.md
```

## Analysis Performed
- Data loading and inspection
- Data cleaning and preprocessing
- State-wise average unemployment analysis
- Top 10 states with the highest unemployment rates
- Month-wise unemployment trend analysis
- Three-state unemployment comparison
- Correlation heatmap
- Pre-COVID and COVID-period comparison

## Key Findings
- Tripura recorded the highest average unemployment rate at approximately 28.35%.
- Haryana recorded the second-highest average rate at approximately 26.28%.
- The unemployment rate increased sharply during April and May 2020.
- The average unemployment rate increased from 9.51% before March 2020 to 17.77% from March 2020 onward.
- The analysis revealed differences in unemployment patterns across Indian states.

## Conclusion
The project demonstrates how Python can be used for data cleaning, exploratory data analysis, and visualization. The findings highlight regional variations in unemployment and a substantial increase in unemployment during the COVID-19 period covered by the dataset.

## How to Run the Project
1. Download or clone this repository.
2. Open the project folder in Visual Studio Code.
3. Install the required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```
4. Open `unemployment_analysis.ipynb` in Jupyter Notebook.
5. Run the notebook cells sequentially to view the analysis and visualizations.

## Internship
**Organization:** Oasis Infobyte  
**Track:** Data Science  
**Task:** Task 2 – Unemployment Analysis with Python