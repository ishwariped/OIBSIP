# Task 5: Sales Prediction Using Python

## Project Overview
This project uses Machine Learning regression algorithms to predict product sales based on advertising expenditure across three media channels: TV, Radio, and Newspaper.

## Dataset
- **Dataset:** Advertising Dataset
- **File:** `advertising.csv`
- **Records:** 200
- **Features:** TV, Radio, Newspaper
- **Target Variable:** Sales

## Technologies Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Project Workflow
1. Loaded and explored the advertising dataset.
2. Checked missing values and descriptive statistics.
3. Created pairplots and individual scatter plots.
4. Generated a correlation heatmap.
5. Split the dataset into training and testing sets.
6. Trained a Linear Regression model.
7. Trained a Random Forest Regressor.
8. Evaluated both models using MAE, RMSE, and R² Score.
9. Created a model comparison chart.
10. Analyzed residuals using a residual plot.
11. Identified advertising channel importance.
12. Tested the best model with a sample advertising budget.

## Model Performance

| Metric | Linear Regression | Random Forest |
|---|---:|---:|
| MAE | 1.2748 | 0.9180 |
| RMSE | 1.7052 | 1.1989 |
| R² Score | 0.9059 | 0.9535 |

## Advertising Channel Importance

| Advertising Channel | Importance |
|---|---:|
| TV | 84.54% |
| Radio | 13.66% |
| Newspaper | 1.80% |

TV advertising had the highest feature importance in the Random Forest model.

## Sample Prediction
For the following advertising budget:
- TV: 200
- Radio: 40
- Newspaper: 50

**Predicted Sales: 21.01**

## Conclusion
The Random Forest Regressor performed better than Linear Regression across all three evaluation metrics, achieving an R² score of 0.9535.

Feature importance analysis showed that TV advertising contributed the most to the model's predictions.

This project demonstrates how Python and Machine Learning can be used for data analysis, regression modeling, and sales prediction.

## How to Run
1. Clone or download this repository.
2. Open the project folder in