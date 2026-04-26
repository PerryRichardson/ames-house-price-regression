# Ames House Price Regression

A multiple linear regression model built in Python to predict residential
property sale prices using the Ames, Iowa housing dataset (2930 properties,
2006–2010).

## What this project does

- Loads and inspects the Ames dataset (14 variables, no missing values)
- Explores distributions and variable relationships using histograms,
  scatter plots, and a correlation heatmap
- Builds a multiple linear regression model using two predictors:
  living area (Gr_Liv_Area) and garage size (Garage_Area)
- Evaluates model performance with RMSE and R²
- Visualises prediction errors with an actual vs predicted scatter plot
- Interprets model coefficients in the context of property pricing

## Skills demonstrated

- Python (pandas, numpy, matplotlib, seaborn, scikit-learn)
- Exploratory data analysis
- Multiple linear regression with sklearn
- Model evaluation (RMSE, R²)
- Data visualisation
- Git version control

## Results

| Metric | Value |
|--------|-------|
| R²     | 0.64  |
| RMSE   | ~$51,326 |

The model explains 64% of the variation in sale prices using just two
variables. It performs well for mid-range properties but underestimates
higher-end houses — a known limitation of a two-predictor model.

## Files

- `Linear_Regression_Ames.ipynb` — main notebook
- `ames.csv` — dataset

## Requirements

Python 3, pandas, numpy, matplotlib, seaborn, scikit-learn