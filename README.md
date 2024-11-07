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
