# car_price prediction using decision-Tree:
This project predicts the selling price of used cars based on various features such as kilometers driven, age, fuel type, seller type, transmission, and ownership. A Decision Tree Regressor from Scikit-learn is used to model the relationship between car features and their selling prices.

#Features Used:
km_driven – Total kilometers driven by the car
owner – Number of previous owners
car_age – Age of the car in years
fuel – Fuel type (Petrol, Diesel, CNG, etc.)
seller_type – Dealer or Individual
transmission – Manual or Automatic

#How It Works
Data preprocessing: Encode categorical variables using LabelEncoder.
Train-test split: Split dataset into training and testing sets.
Model training: Fit a Decision Tree Regressor to the training data.
Prediction: Predict selling prices for new cars.
Evaluation: Use R² score and Mean Absolute Error (MAE) to evaluate model performance.
Visualization: Compare actual vs predicted prices using scatter plots.

#Technologies Used
Python 3
Pandas, NumPy
Scikit-learn (DecisionTreeRegressor)
Matplotlib, Seaborn
