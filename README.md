# House Price Prediction

## Project Overview
This project predicts house sale prices using machine learning and the Kaggle House Prices dataset.

## Technologies Used
- Python
- Pandas and NumPy
- Scikit-learn
- XGBoost
- Jupyter Notebook

## Workflow
1. Explored and preprocessed the dataset.
2. Handled missing values and encoded categorical features.
3. Trained Random Forest, Gradient Boosting, and XGBoost models.
4. Compared model performance using validation RMSLE.
5. Selected XGBoost and generated predictions for the test dataset.

## Best Model
**XGBoost Regressor**

- Validation RMSLE: 0.13474
- Validation MAE: 15,469.43
- Validation RMSE: 24,902.31

## Dataset
[Kaggle House Prices Competition](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques)

Download `train.csv` and `test.csv` from Kaggle and place them in the project folder before running the notebook.

## How to Run
1. Install the required Python libraries.
2. Open `price_prediction.ipynb` in Jupyter Notebook.
3. Run the cells in order.

## Author
Sudhir Pratap