# Diabetes Dataset Analysis and Prediction

This project uses the **Diabetes** dataset from `scikit-learn` to perform data analysis, visualization, and prediction. The code demonstrates how to load the dataset, visualize its features, and apply machine learning models to predict target values.

## Author

Jason Carpenter

## Features

- **Data Exploration**: Load the diabetes dataset and explore its structure, including the shape of the data, target values, and feature names.
- **Visualization**: Generate scatter plots for each feature in the dataset against the target variable to understand the relationships.
- **Prediction Models**: Apply various linear regression models including Linear Regression, ElasticNet, Lasso, and Ridge to predict the target values.

## Libraries Used

- **scikit-learn**: For loading the diabetes dataset and applying machine learning models.
- **pandas**: For data manipulation and exploration.
- **matplotlib**: For plotting and visualizing data.
- **seaborn**: For creating attractive statistical plots.

## Steps in the Code

1. **Loading the Dataset**:
    - The `scikit-learn` library is used to load the diabetes dataset, which includes features related to health diagnostics and a target variable representing a quantitative measure of disease progression.
  
2. **DataFrame Creation**:
    - The data is loaded into a pandas DataFrame for easier manipulation and analysis. The target variable is added as a separate column.

3. **Visualization**:
    - Scatter plots are generated for each feature against the target variable. This helps in visualizing the relationship between each feature and the target, providing insights into the data.

4. **Model Training and Prediction**:
    - The dataset is split into training and test sets. Several linear regression models (`LinearRegression`, `ElasticNet`, `Lasso`, and `Ridge`) are trained on the training data.
    - The models' performance is evaluated using the R² score and Mean Squared Error (MSE). Cross-validation is applied to ensure the models' robustness.

5. **Results**:
    - The coefficients of the features for the linear regression model are displayed.
    - Predicted values are compared with expected values through scatter plots.
    - The models' performance metrics are printed to assess their accuracy.

## How to Run

1. Ensure you have Python installed.
2. Install the required libraries:
    ```bash
    pip install pandas matplotlib seaborn scikit-learn
    ```
3. Run the script to load the dataset, visualize the data, and train the prediction models.

## Summary

This project provides a comprehensive approach to analyzing and predicting diabetes progression using machine learning models. It highlights the use of various tools like `pandas`, `matplotlib`, `seaborn`, and `scikit-learn` to achieve these goals.
