# International-Medical-AI-Kaggle-Competition

🔥 Calories Burn Prediction using XGBoost
📌 Project Overview

This project focuses on building a machine learning model to predict calories burned during exercise using physiological and activity-related features. The dataset used is the International Medical Dataset with 750,000 records and 9 features.

Using XGBoost Regressor, the model achieved:

✅ R² Score: 0.9961

✅ MAE (Mean Absolute Error): 15.09

✅ MSE (Mean Squared Error): 0.0785

This demonstrates high predictive performance, making the model useful for applications in healthcare, fitness apps, and personal health monitoring.

📊 Dataset Description

The dataset consists of 750,000 rows and 9 columns with features describing physiological attributes and exercise details.

Column Name	Description
ID	Unique identifier for each record
Sex	Gender of the individual (0 = Female, 1 = Male)
Age	Age in years
Height	Height in cm
Weight	Weight in kg
Duration	Duration of exercise (minutes)
Heart_Rate	Heart rate during exercise
Body_Temp	Body temperature in °C
Calories	Target variable (calories burned)
🧠 Model Used

XGBoost Regressor

Optimized for speed and accuracy

Handles large-scale datasets efficiently

Outperformed other models like Linear Regression, Random Forest, and Decision Tree

⚙️ Tech Stack

Language: Python 🐍

Libraries:

pandas, numpy → Data preprocessing

matplotlib, seaborn → Data visualization

scikit-learn → Model evaluation

xgboost → Model training

📈 Results

XGBoost gave the best performance:

R² Score: 0.9961

MAE: 15.09

MSE: 0.0785

📌 The model generalizes well and can be used to predict calorie expenditure for new unseen data.
