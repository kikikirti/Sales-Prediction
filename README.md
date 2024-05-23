# Sales Prediction using Python

## Project Overview

This project uses machine learning techniques to predict sales based on advertising expenditure on TV, Radio, and Newspaper.

## Data Source

The data was obtained from the [Sales Prediction Dataset on Kaggle](https://www.kaggle.com/datasets/kiki2k1/codsoft-sales-prediction).

## Data Exploration

The dataset consists of 200 entries, each described by three numerical features and one numerical target variable. Here's a summary of the features:

- **TV**: Represents the advertising budget spent on TV advertising (float).
- **Radio**: Represents the advertising budget spent on radio advertising (float).
- **Newspaper**: Represents the advertising budget spent on newspaper advertising (float).
- **Sales**: Represents the corresponding sales generated (float) (Target variable).

All 200 entries are complete with no missing values, ensuring a clean dataset for model training.

## Model Training

Three machine learning models were employed to predict sales based on advertising budgets:

1. **Linear Regression**: A linear model that estimates the relationship between the dependent variable (sales) and one or more independent variables (TV, Radio, Newspaper).
2. **Ridge Regression**: A linear regression model that includes a regularization term to prevent overfitting.
3. **Lasso Regression**: A linear regression model that includes a regularization term to shrink some coefficients to zero, effectively performing feature selection.

## Evaluation

The performance of each model was evaluated using metrics such as Mean Squared Error (MSE) and R-squared (R²).

## Further Exploration

To enhance the project, the following steps could be undertaken:

- **Feature Engineering**: Creating new features from the existing ones to potentially improve model performance.
- **Model Hyperparameter Tuning**: Adjusting the hyperparameters of the models to achieve better accuracy.
- **Advanced Models**: Exploring more advanced machine learning models like Decision Trees, Random Forests, or Gradient Boosting Machines for potentially better performance.

## Acknowledgements

This project uses the Sales Prediction dataset, which is available from a private dataset on Kaggle.

## License

This project is licensed under the MIT License.
