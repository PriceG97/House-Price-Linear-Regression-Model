# House Price Linear Regression Model

This is my first machine learning project: a **linear regression model** that predicts house prices using a publicly available dataset from Kaggle.

## Overview

Using **Scikit-learn**, **NumPy**, and **Pandas**, I:
- Imported and explored the dataset
- Created visualizations using **Matplotlib** to understand relationships between features
- Detected outliers using **Z-scores** with **SciPy**
- Built a **preprocessing pipeline** that encodes categorical features and scales numerical features
- Trained and evaluated a **Linear Regression model**

## Model Performance

- **Mean Absolute Error (MAE)**: `758,727.43`
- **Root Mean Squared Error (RMSE)**: `1,036,228.85`
- **R² Score**: `0.67`

These results suggest that the model explains 67% of the variability in housing prices.

## Dataset

- **Source**: [Kaggle Housing Prices Dataset](https://www.kaggle.com/datasets/yasserh/housing-prices-dataset)
- **Rows**: 545
- **Columns**: 14 features + 1 target (Price)

### Features Used:

- `Price` (Target variable)
- `Area`
- `Bedrooms`
- `Bathrooms`
- `Stories`
- `Mainroad`
- `Guesthouse`
- `Basement`
- `Hot Water Heating`
- `Air Conditioning`
- `Parking`
- `Preferred Area`
- `Furnishing Status`

## Tools & Libraries

- Python
- Jupyter Notebook
- Pandas, NumPy
- Matplotlib
- SciPy
- Scikit-learn

## Improvements to be made

- Remove Outliers
- Engineer new features which better show the relationship between the features and the target
