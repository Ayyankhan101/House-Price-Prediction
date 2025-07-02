 # California Housing Price Prediction
    2 
    3 ## Project Overview
    4 
    5 This project aims to predict the median house value in California districts based on
      various features from the 1990 census data. The goal is to build and evaluate several
      regression models to determine which one performs best for this task.
    6 
    7 The project follows a standard data science workflow:
    8 1.  **Data Loading and Exploration:** Understanding the dataset's structure and
      statistical properties.
    9 2.  **Data Cleaning:** Handling missing values to ensure data quality.
   10 3.  **Model Building:** Training three different regression models:
   11     *   Random Forest Regressor
   12     *   Decision Tree Regressor
   13     *   Linear Regression
   14 4.  **Model Evaluation:** Comparing the models using Mean Absolute Error (MAE) and
      Mean Squared Error (MSE) to identify the most accurate one.
   15 5.  **Visualization:** Plotting the results to visually inspect the model's
      performance.
   16 
   17 ## How to Run This Project
   18 
   19 1.  **Prerequisites:** You need to have Python and the following libraries installed:
   20     *   pandas
   21     *   scikit-learn
   22     *   matplotlib
   23     *   seaborn
   24 
   25     You can install them using pip:

      pip install pandas scikit-learn matplotlib seaborn


    1 
    2 2.  **Dataset:** The project uses the `housing.csv` dataset, which should be in the
      same directory as the notebook.
    3 
    4 3.  **Execution:** Open the `final project.ipynb` file in a Jupyter Notebook
      environment and run the cells sequentially.
    5 
    6 ## Summary of Results
    7 
    8 The project evaluates three different models, with the following performance on the
      validation set:
    9 
   10 *   **Random Forest Regressor:**
   11     *   Mean Absolute Error: 32303.28
   12     *   Mean Squared Error: 2477670691.14
   13 *   **Decision Tree Regressor:**
   14     *   Mean Absolute Error: 32303.28
   15 *   **Linear Regression:**
   16     *   Mean Absolute Error: 50962.33
   17 
   18 Based on these results, the **Random Forest Regressor** and **Decision Tree
      Regressor** perform significantly better than the Linear Regression model, with a much
      lower error. The Random Forest is generally a more robust choice as it is less prone
      to overfitting than a single Decision Tree.
