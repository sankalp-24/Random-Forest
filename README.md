# Random-Forest

ABSTRACT : In the last few years, the number of for-hire vehicles operating in NY has grown from 63,000 to more than 100,000. However, while the number of trips in app-based vehicles has increased from 6 million to 17 million a year, taxi trips have fallen from 11 million to 8.5 million. Hence, the NY Yellow Cab organization decided to become more data-centric. Then we have apps like Uber, OLA, Lyft, Gett, etc. how do these apps work After all, that set price is not a random guess.

PROBLEM STATEMENT : Given pickup and dropoff locations, the pickup timestamp, and the passenger count, the objective is to predict the fare of the taxi ride using Random Forest.


APPROACH : To predict taxi fares based on ride features like distance, time, and pickup/drop-off locations.


Tools & Libraries: Python, Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn


Key Steps:
	•	Conducted data cleaning including outlier removal and handling of missing values.
	•	Engineered features like ride distance, day of the week, and hour of pickup from timestamp and location data.
	•	Performed exploratory data analysis (EDA) to understand fare patterns.
	•	Implemented a Random Forest Regressor to model the fare prediction task.
	•	Evaluated the model using metrics like R² Score, Mean Absolute Error (MAE), and Root Mean Squared Error (RMSE).

 
Outcome: Built a robust model capable of predicting taxi fares with high accuracy, demonstrating the value of ensemble models and feature engineering in real-world regression tasks.
