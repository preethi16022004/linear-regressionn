# linear-regressionn
*Objective* :
Implement and understand Simple and Multiple Linear Regression.

 *Tools You Must Use* :

• Scikit-learn (for modeling)

•Pandas (for handling data)

• Matplotlib (for plotting graphs)

What to Do Step-by-Step:

1. *Import and Preprocess Data* 

•Load a dataset (they suggested House Price Prediction dataset).

•Check for missing values and handle them (fill or remove).

•Select useful features (X = inputs, y = output you want to predict).

2. *Split the Dataset* 

•Split your dataset into training and testing parts.

•Example: train_test_split(X, y, test_size=0.2, random_state=42)

3. *Build a Linear Regression Model* 

•Use sklearn.linear_model.LinearRegression().

•Fit it on your training data using model.fit(X_train, y_train).

4. *Evaluate the Model* 

•Predict on test set: y_pred = model.predict(X_test).

• *Calculate* :

MAE (Mean Absolute Error)

MSE (Mean Squared Error)

R² Score (Coefficient of Determination)

5. *Plot Regression Line* 

•If it’s simple linear regression (1 feature), plot X vs Y with the regression line.

•For multiple regression, plot actual vs predicted values.

6. *Interpret Coefficients* 

•Print model coefficients and intercept.

• *Example* : If coef_ = 3, it means that for every 1 unit increase in X, y increases by 3 units.
