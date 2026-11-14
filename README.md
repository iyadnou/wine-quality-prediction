# Wine Quality Prediction

Predicts wine quality scores from physicochemical properties (acidity, sugar, alcohol, etc.).

This is a small machine learning project I made while learning Python and data science.

## What it does

- Explores the data and removes duplicate rows
- Trains a **Linear Regression** model (with `StandardScaler` in a pipeline)
- Trains a **Random Forest Regressor**
- Compares the models with MAE, RMSE and R²

## Results

| Model | MAE | RMSE | R² |
|---|---|---|---|
| Linear Regression | 0.50 | 0.66 | 0.392 |
| **Random Forest** | **0.47** | **0.62** | **0.462** |

The Random Forest performed better than Linear Regression.

## Files

- `Wine_Quality.ipynb`
- `data.csv`

## Run it

```
pip install pandas scikit-learn jupyter
jupyter notebook Wine_Quality.ipynb
```
