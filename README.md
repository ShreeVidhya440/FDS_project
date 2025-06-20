# Used Car Price Prediction 
The dataset you've provided "used_car_price_dataset_extended.csv" is about used cars and their selling prices, along with detailed attributes describing each car.
Each row represents a used car listing, and the dataset contains columns (features) that help describe the car’s condition, specs, and background, all of which can influence its selling price.
# Prediction Model
To predict the resale price (in USD) of a used car based on various features of the vehicle.
Plotting predicted vs actual prices is a way to evaluate the performance of a regression model.
-> A scatter plot where each point represents a prediction.
-> The red dashed line shows perfect prediction (i.e., y = y_pred).
-> If most points lie close to this line, the model performs well.
-> The R² score tells you how well the model explains the variability in the target.
-> Mean Absolute Error (MAE) gives an average difference in USD between predicted and actual prices.
-> "predict_price()" function allows to input car details manually (like year, mileage, brand, etc.) and returns a predicted price from the machine learning model.
