# Task 3: Car Price Prediction with Machine Learning

## Project Overview
This project uses Machine Learning to predict the selling price of used cars based on various features such as brand, car age, kilometers driven, fuel type, transmission, mileage, engine capacity, and maximum power.

## Objective
To build and evaluate regression models that estimate the selling price of used cars using historical vehicle data.

## Dataset
- **Dataset:** Car Details V3
- **Source:** [Kaggle – Vehicle Dataset from CarDekho](https://www.kaggle.com/datasets/nehalbirla/vehicle-dataset-from-cardekho)
- **Records:** 8,128 before data cleaning
- **Selected file:** `Car details v3.csv`

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Workflow
1. Loaded and explored the car dataset.
2. Checked and removed duplicate records.
3. Handled missing numerical values.
4. Extracted numerical values from mileage, engine, and maximum power columns.
5. Created new features: car age and brand.
6. Performed exploratory data analysis using visualizations.
7. Encoded categorical variables using One-Hot Encoding.
8. Split the dataset into training and testing sets.
9. Trained Linear Regression and Random Forest Regression models.
10. Evaluated both models using MAE, RMSE, and R² Score.
11. Visualized feature importance using the best-performing model.
12. Tested the model with a sample car.

## Model Evaluation Results

| Model | MAE | RMSE | R² Score |
|---|---:|---:|---:|
| Linear Regression | 167801.87 | 298169.09 | 0.5946 |
| Random Forest Regression | 73392.47 | 130599.19 | 0.9222 |

## Best Model
Random Forest Regression performed better than Linear Regression, achieving an R² score of **0.9222** on the test dataset.

## Sample Prediction
The model predicted the selling price of a sample Maruti car as:

**₹5,50,840**

## Conclusion
This project demonstrates how Machine Learning regression algorithms can be used to estimate used-car selling prices. Random Forest Regression provided better results than Linear Regression on the test dataset.

The predictions are estimates based on historical data and may differ from actual market prices.