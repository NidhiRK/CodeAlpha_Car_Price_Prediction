🚗 Car Price Prediction using Machine Learning
📌 Overview
This project is a Car Price Prediction model built as part of my CodeAlpha internship. The goal is to predict the selling price of a car based on factors such as model year, fuel type, transmission, and ownership history using Machine Learning techniques.

📊 Dataset
The dataset contains the following features:

Car_Name: Name of the car
Year: Manufacturing year
Selling_Price: Price at which the car is sold (Target Variable)
Present_Price: Current market price of the car
Driven_kms: Distance driven in kilometers
Fuel_Type: Type of fuel used (Petrol/Diesel/CNG)
Selling_type: Type of sale (Dealer/Individual)
Transmission: Type of transmission (Manual/Automatic)
Owner: Number of previous owners
🔍 Models Used
Linear Regression
Random Forest Regressor
📈 Results Comparison
Metric  |	Linear Regression	|  Random Forest Regressor |
------- | ------------------| -------------------------|
MAE     |   	1.31	        |       0.98 (Better)      |
MSE	    |     3.55	        |        2.43 (Better)     |
RMSE	  |     1.88          |	      1.56 (Better)      |
R² Score|	    0.85	        |        0.89 (Better)     |
Conclusion:
✅ Random Forest performed significantly better than Linear Regression in all evaluation metrics!

📌 Installation & Usage                                                                                                                                                                 
🔹 Clone the Repository                                                                                                                                                                
git clone https://github.com/NidhiRK/CodeAlpha_Car_Price_Prediction.git                                                                                                                  
cd car-price-prediction                                                                                                                                                                  
🔹 Install Dependencies                                                                                                                                                                 
pip install -r requirements.txt                                                                                                                                                            
🔹 Run the Model                                                                                                                                                                         
python car_price_prediction.py
📊 Visualizations
Actual vs Predicted Prices
Residual Distribution
Feature Importance (Random Forest)
🚀 Next Steps
🔹 Hyperparameter tuning for better performance
🔹 Trying advanced models like XGBoost and LightGBM
🔹 Feature engineering improvements (e.g., extracting car brand, calculating car age)

📢 Connect with Me
🔗 LinkedIn:(https://www.linkedin.com/in/nidhi-kushwaha-1b64b62a1?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)
📧 Email: nidhirk1706@gmail.com

