# Titanic Survival Prediction

This repository contains a solution for the Titanic survival prediction problem using machine learning techniques. The goal is to predict whether a passenger survived or not based on features like `Pclass`, `Sex`, `Age`, `Fare`, and others.

## Project Files

- **Kaggle_Titanic_Solution.ipynb**: Jupyter Notebook containing the entire workflow, including data exploration, preprocessing, model building, and evaluation.
- **gender_submission.csv**: The final submission file with survival predictions for the test dataset.

## Approach

1. **Data Preprocessing**:
   - Handling missing values in `Age`, `Fare`, and `Embarked`.
   - Feature engineering (e.g., encoding categorical variables).
   
2. **Models Used**:
   - Logistic Regression
   - Random Forest

3. **Evaluation**:
   - Models were evaluated using metrics like accuracy, precision, and recall.
   - Hyperparameter tuning was performed for the best model.

## Results

- The best model achieved an accuracy of approximately 80% on the test set.
