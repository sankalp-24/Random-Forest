🚖 NY Taxi Fare Prediction – Random Forest Regression

📌 Abstract

In recent years, the number of for-hire vehicles in New York has surged from 63,000 to over 100,000. App-based ride services like Uber, Lyft, OLA, and Gett have seen trip volumes increase from 6 million to 17 million annually, while traditional taxi trips have declined from 11 million to 8.5 million.
The NY Yellow Cab organization decided to adopt a data-centric approach to remain competitive. Predicting taxi fares accurately is essential for pricing strategies, customer satisfaction, and operational efficiency.

🎯 Problem Statement

Given pickup and drop-off locations, pickup timestamp, and passenger count, predict the taxi fare using historical trip data.

⸻

⚙ Approach

Developed a Random Forest Regression model to predict taxi fares based on ride characteristics like distance, pickup/drop-off points, and time-related features.

Tools & Libraries:
Python | Pandas | NumPy | Seaborn | Matplotlib | Scikit-learn

⸻

🔑 Key Steps
	•	🧹 Data Cleaning – Removed outliers and handled missing values to ensure dataset integrity.
	•	🛠 Feature Engineering – Derived features like ride distance (from coordinates), day of the week, and hour of pickup from timestamp data.
	•	📊 Exploratory Data Analysis (EDA) – Analyzed fare patterns across time, location, and passenger count.
	•	🌲 Model Building – Implemented a Random Forest Regressor for robust fare predictions.
	•	📉 Model Evaluation – Assessed performance with R² Score, MAE, and RMSE.

⸻

🏆 Outcome

Built a highly accurate fare prediction model, showcasing the power of ensemble learning and feature engineering in real-world regression problems.
This solution can help taxi operators and ride-hailing platforms optimize pricing and improve transparency for customers.
