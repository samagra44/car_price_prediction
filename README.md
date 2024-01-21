# Car Price Prediction Web App

### Overview

The Car Price Prediction Web App is a comprehensive project that involves predicting car prices based on various attributes. The primary goal is to provide users with a reliable tool for estimating the selling price of cars, leveraging machine learning techniques. The project encompasses data preprocessing, model development, and web application deployment.

### Dataset

The dataset used in this project contains essential information about cars, including features such as Car_Name, Year, Selling_Price, Present_Price, Kms_Driven, Fuel_Type, Seller_Type, Transmission, and Owner. Each entry represents a specific car with associated attributes.

### Machine Learning Model

#### Random Forest Regressor

The machine learning model utilized for predicting car prices is the Random Forest Regressor. This ensemble learning algorithm excels in capturing complex relationships within the data, making it well-suited for regression tasks. The model is trained on historical data to learn the patterns and correlations between car attributes and selling prices.

#### Hyperparameter Tuning

To enhance the model's performance, RandomizedSearchCV is employed for hyperparameter tuning. This process involves systematically searching through a range of hyperparameter values to find the combination that maximizes predictive accuracy. The tuned model demonstrates improved results, as indicated by metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE).The achieved performance metrics are as follows:

MAE: 0.874067912087912    
MSE: 3.969051762230773    
RMSE: 1.9922479168594387    

#### Feature Importance

The ExtraTree Regressor is employed to identify the most influential features in determining car prices. This analysis provides valuable insights into the factors that significantly impact the selling price of cars.

![pic3](https://github.com/samagra44/car_price_prediction/assets/77968722/49240d35-1103-4e7a-b1e5-cded5efc7cde)

![pic1](https://github.com/samagra44/car_price_prediction/assets/77968722/bfb371db-6d72-49ee-a0a5-20b7a3cc7b84)

![pic2](https://github.com/samagra44/car_price_prediction/assets/77968722/21282ebb-b075-4d89-9d48-c68a3e884d0d)

![pic4](https://github.com/samagra44/car_price_prediction/assets/77968722/8ac4c058-aa72-4303-8a52-571e0f6e5140)


### Web Application

#### Flask Framework

The web application is developed using Flask, a lightweight and flexible Python web framework. Flask enables the seamless integration of the trained machine learning model into a user-friendly interface. Users can input relevant details about a car, and the application provides an instant prediction of the car's selling price.

#### User Interface

The user interface is designed to be intuitive and easy to navigate. Users are prompted to enter information such as the car's name, year of manufacture, fuel type, and other relevant details. Upon submission, the application processes the input through the trained model and displays the predicted selling price.

### Conclusion

The Car Price Prediction Web App combines the power of machine learning with a user-friendly web interface to provide a valuable tool for car buyers and sellers. The project encompasses various aspects, including model training, hyperparameter tuning, feature importance analysis, and web application development, resulting in an integrated solution for estimating car prices. Users can leverage this application to make informed decisions in the car-buying and selling process.

# Output:

![Document - Brave 2024-01-21 12-59-14](https://github.com/samagra44/car_price_prediction/assets/77968722/52ac2e7c-47ee-4425-8246-854840352f77)

