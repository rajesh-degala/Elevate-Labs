# House Price Prediction using Linear Regression

## Task Overview
This project builds a Linear Regression model to predict house prices using the California Housing dataset. The task demonstrates data loading, model training, evaluation, and interpretation.

## Dataset
- California Housing Dataset (from scikit-learn)
- Target variable: `MedHouseVal` (continuous numeric house price)

## Tools Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

## Steps Performed
1. Loaded the California housing dataset and converted it into a Pandas DataFrame.
2. Performed basic data inspection using `.head()`, `.info()`, and `.describe()`.
3. Separated input features (X) and target variable (y).
4. Split the data into training (80%) and testing (20%) sets.
5. Trained a Linear Regression model using training data.
6. Predicted house prices on test data.
7. Evaluated the model using MAE and RMSE.
8. Plotted Predicted vs Actual house prices using a scatter plot.
9. Interpreted model coefficients to identify important features.

## Evaluation Metrics
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)

## Results
The Linear Regression model predicts house prices with reasonable accuracy.  
The Predicted vs Actual plot shows how closely predictions match real values.

## Deliverables
- Jupyter Notebook (.ipynb)
- MAE and RMSE report
- Predicted vs Actual scatter plot
