# House Prices Prediction

This project predicts house sale prices using a dataset from the Kaggle House Prices competition. The goal is to build a regression model that accurately estimates house prices based on various features.

## Project Overview

- Data preprocessing: Handling missing values, encoding categorical variables, and feature engineering  
- Model used: Linear Regression with cross-validation  
- Evaluation metric: Root Mean Squared Error (RMSE)  
- Visualizations: Feature distributions and model performance charts  

## How to Run

1. Load the dataset files (`train.csv` and `test.csv`).  
2. Run the preprocessing steps to clean and prepare the data.  
3. Train the Linear Regression model and evaluate with cross-validation.  
4. Generate predictions for the test set and create the submission file.  

## Results

The model achieved an average cross-validated RMSE of approximately 35,115, indicating reasonable prediction accuracy.

## Files

- `house_prices.ipynb`: Jupyter notebook containing all code and analysis  
- `submission.csv`: Sample submission file with predicted prices  

## Future Improvements

- Try more advanced models like Random Forest or Gradient Boosting  
- Perform more detailed feature engineering and selection  
- Tune hyperparameters for better accuracy  

Feel free to explore, use, and improve this project!
