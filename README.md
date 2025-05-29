# Task-3

used dataset: House Price Prediction Dataset

Import and Preprocess the Dataset:
The dataset is loaded, and any missing values are handled. Only the relevant features (GrLivArea, OverallQual, YearBuilt) and the target (SalePrice) are kept for simplicity. You can apply more advanced preprocessing if needed (e.g., feature scaling or encoding categorical variables).

Split Data into Train-Test Sets:
The data is split into 80% for training and 20% for testing. This ensures that the model is tested on data it hasn’t seen during training.

Fit a Linear Regression Mode:
A linear regression model is created and trained using the training data.

Evaluate the Model:
The model is evaluated using three metrics: MAE (Mean Absolute Error), MSE (Mean Squared Error), and R² (Coefficient of Determination). These metrics help evaluate how well the model is performing.

Plot Regression Line and Interpret Coefficients
A scatter plot of the actual vs predicted values for one feature (GrLivArea) is plotted.
The coefficients of the linear model are printed, showing how each feature influences the target variable (SalePrice).
