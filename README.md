#  Bike Sharing Demand Prediction

A machine learning project to predict **hourly bike rental demand** using the **Capital Bikeshare (hour.csv)** dataset.  
All code is executed in **Google Colab**, and the notebook is uploaded directly to GitHub.

---

##  Dataset
Kaggle: https://www.kaggle.com/datasets/marklvl/bike-sharing-dataset  
File used: **hour.csv**

## Main features:
- Time features: season, month, hour, weekday  
- Weather features: temp, humidity, windspeed  
- Target: `cnt` (total rentals)

## Objective
Predict hourly bike rental demand using time + weather conditions.

## EDA (Completed)
Rentals by Weekday
sns.barplot(x='weekday', y='cnt', data=df)


Insight: Weekdays have higher demand due to office-hour usage.

## Model

Model used: Random Forest Regressor

## Evaluation:

RMSE

R² Score

The model captures demand patterns effectively.

## Tools Used

Google Colab

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

## How to Run

Open notebook in Google Colab

Upload hour.csv

Run all cells

## Author

Jahnavi Bandaru
