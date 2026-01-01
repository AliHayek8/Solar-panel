🌱 Energy Production Prediction Using Machine Learning

📌 Project Overview
This project focuses on predicting energy production based on weather conditions using Machine Learning techniques.
It demonstrates how environmental factors such as temperature, solar radiation, and humidity influence energy output, helping improve renewable energy forecasting and resource planning.
The project was developed as a Machine Learning course final project at An-Najah National University – Computer Science Department.


Worked by:
Ali Hayek 

Supervisor: Dr. Adnan Salman


🎯 Objectives
Analyze weather data and its impact on energy production.
Apply multiple machine learning models and compare their performance.
Use ensemble methods to improve prediction accuracy.
Highlight the importance of data-driven forecasting in renewable energy systems.



📊 Dataset
Source: Meteostat Library

Features used:

Average daily temperature
Solar radiation
Humidity


🔧 Preprocessing Steps
Handling missing values using imputation.
Extracting date-based features (monthly/seasonal analysis).
Normalizing numerical features for better model performance.


🧠 Machine Learning Models Used
Linear Regression
Decision Tree Regressor
Random Forest Regressor
Voting Regressor
Stacking Regressor


📐 Evaluation Metrics
RMSE (Root Mean Squared Error) – Measures prediction error.
R² Score – Measures how well the model explains variance in energy production.


🏆 Results
The Voting Regressor achieved the best performance, with the lowest RMSE and highest R² score.
Ensemble learning methods proved more robust compared to single models.
Visualizations such as scatter plots and bar charts were used to compare predictions.


⚠️ Challenges & Limitations
Challenges
Presence of outliers affected simpler models like Linear Regression.
Ensemble models were more complex to interpret.
Limitations
Weather data alone may not capture all factors influencing energy production.
Seasonal effects could be improved with more detailed data.


🔮 Future Work
Use hourly weather data for finer-grained predictions.
Explore deep learning models for capturing complex relationships.
Integrate additional data sources related to energy infrastructure.


🛠️ Technologies & Libraries
Python
pandas
NumPy
Matplotlib
scikit-learn
Meteostat


📁 Project Structure (Example)
├── data/
│   └── predicted_energy_tuned.csv
├── notebooks/
│   └── 3rdTry.ipynb
├── report/
│   └── MachineFinalDoc.pdf
├── README.md


📜 License
This project is for educational purposes only.
