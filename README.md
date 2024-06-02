# Credit risk ccoring for subprime mortgages

This project focuses on developing a credit risk scoring model for subprime mortgages using machine learning techniques. We employ a logistic regression model to predict the likelihood of default and evaluate its performance through ROC and Precision-recall curve analyses. The steps include data preprocessing, exploratory analysis, model training, and evaluation. Insights derived from this project aim to enhance risk management practices in the financial sector.

## Table of contents

1. [Project overview](#project-overview)
2. [Data collection and preparation](#data-collection-and-preparation)
3. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
4. [Model training](#model-training)
5. [Model evaluation](#model-evaluation)
6. [ROC Curve and AUC](#roc-curve-and-auc)
7. [Precision-recall curve](#precision-recall-curve)
8. [Conclusion](#conclusion)
9. [Further considerations](#future-directions)

## Project overview

This project involves building a predictive model to assess credit risk for subprime mortgages. Using a logistic regression model, we predict the probability of loan defaults. Key steps include data preprocessing, exploratory data analysis, model training, evaluation, and performance assessment using ROC and Precision-Recall curves.

## Data collection and preparation

1. **Import libraries**: Import necessary libraries for data manipulation, visualization, and machine learning.
2. **Load data**: Load the dataset from an Excel file.
3. **Data cleaning**:
   - Drop unnecessary columns (e.g., customer ID).
   - Handle missing values by filling them with the mean.
4. **Data splitting**: Split the dataset into training and testing sets.
5. **Feature scaling**: Standardize the features to ensure consistency in model training.

## Exploratory Data Analysis (EDA)

1. **Target variable distribution**: Analyze the distribution of the target variable (default vs. non-default).
2. **Summary statistics**: Calculate mean values grouped by the target variable to understand feature characteristics.

## Model training

1. **Initialize model**: Initialize the logistic regression model.
2. **Train model**: Fit the model to the training data.
3. **Predict**: Use the trained model to predict the target variable for the test data.

## Model evaluation

1. **Confusion matrix**: Display the confusion matrix to evaluate the accuracy of the model.
2. **Accuracy score**: Calculate and print the accuracy score of the model.
3. **Probability predictions**: Generate probability predictions for each class.

## ROC Curve and AUC

1. **Calculate ROC Curve and AUC**: Compute the ROC curve and Area Under the Curve (AUC) score.
2. **Plot ROC Curve**: Visualize the ROC curve to assess model performance.

## Precision-recall curve

1. **Calculate precision-recall curve**: Compute the precision-recall curve and average precision score.
2. **Plot precision-recall curve**: Visualize the precision-recall curve to understand the trade-off between precision and recall.
3. **Optimal F1 Score**: Identify the highest F1 score and corresponding precision and recall values.

## Conclusion

The logistic regression model demonstrates a satisfactory predictive power with an accuracy of approximately 83.33%. The ROC curve analysis with an AUC score of 0.76 indicates a strong ability to distinguish between default and non-default cases. The Precision-Recall curve, with an average precision score of 0.38, highlights the balance between precision and recall.

## Further considerarions

Future work could involve exploring more sophisticated models and feature engineering techniques to enhance predictive accuracy. Implementing these insights in real-world credit risk management scenarios can further improve decision-making processes for mortgage approvals.
