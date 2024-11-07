**01- Non-Ensemble (ANN model)**

**How to Run:**

1- Load the MATLAB environment and ensure all required toolboxes are available.

2- Copy the code from 01- Non-Ensemble (ANN model).txt into a new script or function in MATLAB.

3- Prepare your input data as a matrix x1 with appropriate dimensions (Qx7 for Q samples).

4- Call the function myNeuralNetworkFunction(x1) to get the output.

5- Ensure the Train.xlsx and Test.xlsx data are preprocessed according to the model’s requirements.

**Expected Results:** The function outputs a Qx1 matrix representing the predictions.

**02- Non-Ensemble (GEP model)**

**How to Run:**

1- Ensure Python is installed with required libraries (e.g., NumPy).

2-Copy the code from 02- Non-Ensemble (GEP model).py into a Python script.

3- Prepare your input as a data list d matching the required input format.

4- Run the script and call the gepModel(d) function with your input data.

5- Make sure Train.xlsx and Test.xlsx data are formatted for proper extraction.

**Expected Results**: The function returns the model's prediction as a float value.

**03- Non-Ensemble (SVR model)**

**How to Run:**

1- Open the Jupyter Notebook 03- Non-Ensemble (SVR model).ipynb.

2- Run each cell sequentially to load data, train the model, and make predictions.

3- Ensure the Train.xlsx and Test.xlsx files are read correctly using pandas.

**Expected Results**: The notebook outputs performance metrics and predictions from the trained and Tested SVR model.

**04- Ensemble (RF model)**

**How to Run:**

1- Open the Jupyter Notebook 04- Ensemble (RF model).ipynb.

2- Execute each cell step-by-step to read the data, train the Random Forest model, and evaluate its performance.

3- Ensure data loading and preprocessing steps match the input format required by the notebook.

**Expected Results**: The model displays performance metrics such as R^2 and outputs predictions.

**05- Ensemble (AdaBoost model)**

**How to Run:**

1- Open the Jupyter Notebook 05- Ensemble (AdaBoost model).ipynb.

2- Run the cells sequentially for data loading, training, and testing the model.

3- Use Train.xlsx and Test.xlsx as the input datasets.

**Expected Results**: The notebook should output the trained model’s performance metrics and predictions.

**06- Ensemble (XGBoost model)**

**How to Run:**

1- Open the Jupyter Notebook 06- Ensemble (XGBoost model).ipynb.

2- Execute each cell for loading data, training, and generating results.

3- Ensure the Joblib from (XGBoost model).joblib file is available if needed for model loading or inference.

**Expected Results**: The notebook outputs model performance metrics and predictions.


**Note: **Ensure all dependencies (e.g., Python packages like xgboost, scikit-learn, pandas, matplotlib) are installed and up to date. Use pip install <package> to install any missing libraries.

These instructions should guide you to run the code successfully and obtain the reported results for each model.
