# Airbnb-Project
Data Analysis and Visualization of Airbnb in NYC 
🏡 Airbnb Data Analysis & Price Prediction
📌 Overview
This project focuses on analyzing Airbnb listings data and building regression models to predict listing prices. It involves end-to-end data science steps from data cleaning and exploratory analysis to model selection and performance evaluation using Python.

📂 Dataset
Source: Inside Airbnb (or your provided dataset)

Content: The dataset includes details of Airbnb listings such as location, room type, number of reviews, availability, and price.

Size: ~40,000+ rows with 20+ features

🛠️ Tools & Libraries
Python (Jupyter Notebook)

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

XGBoost

LightGBM

MLP (Neural Networks)

Git & GitHub

🔄 Project Workflow
1. Data Loading and Exploration
Loaded the dataset and explored structure, types, and sample records.

Identified key features such as neighbourhood, room_type, price, minimum_nights, number_of_reviews, etc.

2. Data Cleaning
Removed missing and irrelevant values

Handled outliers in features like price and minimum_nights

Converted categorical variables using one-hot encoding

3. Exploratory Data Analysis (EDA)
Visualized relationships between price and features like:

Room Type

Location (neighbourhood)

Number of Reviews

Availability

Distribution plots and boxplots to understand price trends

4. Feature Engineering
Selected relevant features

Applied normalization for continuous features

Encoded categorical features

Created train/test split for modeling

5. Model Training & Evaluation
🔹 Regression Models
Model	MAE	RMSE	R² Score
Linear Regression	70.24	107.13	0.2108
Ridge Regression	70.24	107.13	0.2108
Lasso Regression	70.25	107.13	0.2108
Decision Tree Regressor	91.08	136.61	-0.283
Random Forest Regressor	75.44	112.92	0.1232
XGBoost Regressor	69.81	104.45	0.2499
MLP Regressor (Neural Net)	70.55	105.76	0.2309

🔸 Best Performer: XGBoost Regressor with RMSE of 104.45 and R² of 0.2499

📈 Key Insights
Room type and location are major drivers of price.

XGBoost and MLP Regressor models showed the best performance.

Simple linear models underperformed due to non-linear relationships.

📌 Future Improvements
Hyperparameter tuning for models

Add clustering for host segmentation

Integrate NLP on descriptions

Deploy model as a web app (e.g., Streamlit)

👤 Author Sreevatsun Janarthanaam
Master of Science in Scientific Instrumentation, Ernst-Abbe-Hochschule Jena, Germany 
📧 sreevatsunj@gmail.com