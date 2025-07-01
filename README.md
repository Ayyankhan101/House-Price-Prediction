# California Housing Price Prediction

## Project Overview

This project aims to predict the median house value in California districts based on various features from the 1990 census data. The goal is to build and evaluate several regression models to determine which one performs best for this task.

The project follows a standard data science workflow:
1.  **Data Loading and Exploration:** Understanding the dataset's structure and statistical properties.
2.  **Data Cleaning:** Handling missing values to ensure data quality.
3.  **Model Building:** Training three different regression models:
    *   Random Forest Regressor
    *   Decision Tree Regressor
    *   Linear Regression
4.  **Model Evaluation:** Comparing the models using Mean Absolute Error (MAE) and Mean Squared Error (MSE) to identify the most accurate one.
5.  **Visualization:** Plotting the results to visually inspect the model's performance.

## How to Run This Project

1.  **Prerequisites:** You need to have Python and the following libraries installed:
    *   pandas
    *   scikit-learn
    *   matplotlib
    *   seaborn

    You can install them using pip:
    ```bash
    pip install pandas scikit-learn matplotlib seaborn
    ```

2.  **Dataset:** The project uses the `housing.csv` dataset, which should be in the same directory as the notebook.

3.  **Execution:** Open the `final project.ipynb` file in a Jupyter Notebook environment and run the cells sequentially.

## Summary of Results

The project evaluates three different models, with the following performance on the validation set:

*   **Random Forest Regressor:**
    *   Mean Absolute Error: 32303.28
    *   Mean Squared Error: 2477670691.14
*   **Decision Tree Regressor:**
    *   Mean Absolute Error: 32303.28
*   **Linear Regression:**
    *   Mean Absolute Error: 50962.33

Based on these results, the **Random Forest Regressor** and **Decision Tree Regressor** perform significantly better than the Linear Regression model, with a much lower error. The Random Forest is generally a more robust choice as it is less prone to overfitting than a single Decision Tree.
