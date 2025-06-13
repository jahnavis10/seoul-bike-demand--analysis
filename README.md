🚴‍♀️ Seoul Bike Sharing Demand Prediction

📌 Overview
This project focuses on predicting hourly demand for the Seoul Bike Sharing system using weather, date, and time-related features. By analyzing trends and building machine learning models, we aim to support better inventory management and smarter bike distribution strategies.

📁 Dataset
The dataset includes:
* Hourly rental data for bikes in Seoul
* Weather indicators: temperature, humidity, rainfall, snowfall, wind speed
* Time-based info: date, hour, seasons, holidays, functioning days
* Target variable: Rented Bike Count

🔍 Problem Statement
To ensure optimal allocation of bikes across the city, it is crucial to predict demand accurately. This project explores which factors affect bike usage the most and develops a machine learning model to forecast hourly rental counts.

🧪 Workflow
* Data Exploration
* Understand data structure and types
* Visualize rental patterns by time and weather
* Data Cleaning & Preprocessing
* Handle missing values and outliers
* Feature engineering (hour, weekday, season)
* Encode categorical variables
* Exploratory Data Analysis (EDA)
* Analyze correlation between weather and rentals
* Identify peak rental times
* Understand effects of holidays and seasons

Results
Temperature, Hour, Functioning Day are key predictors

📈 Key Insights
* Bike demand peaks during commuting hours (7–9 AM, 5–7 PM).
* Demand drops significantly during heavy rainfall or snowfall.
* Weekends and holidays show different usage patterns.
* Demand is higher in Spring and Autumn seasons

💻 Tools Used
* Python
* Pandas, NumPy, Seaborn, Matplotlib
* Scikit-learn, XGBoost
* Jupyter Notebook

✅ Conclusion
The model can effectively predict hourly bike rental demand based on environmental and time features. This helps optimize resource allocation and improve urban mobility.

📎 Project Structure
SeoulBikeProject/
│
├── SeoulBikeProject.ipynb      # Jupyter notebook with full analysis
├── README.md                   # Project documentation
