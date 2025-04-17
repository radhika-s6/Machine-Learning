🧠 Predictive Modeling for Car Sale Duration – Auto Trader Hackathon

This repository contains the final presentation from our project “The Implementation of Predictive Modelling to Forecast the Duration of Car Sales”, built for the Auto Trader Hackathon.

Our team, Datacrats, developed a machine learning solution that predicts how long it will take to sell a car listed on Auto Trader. The goal was to empower private sellers and dealerships with data-driven insights while enhancing Auto Trader's platform value.

🚨 Note: The source code is not publicly available due to team repository restrictions. This repo includes the final presentation and a summary of the project’s approach and outcomes.


🔍 Problem Statement

Many car sellers and dealerships struggle with pricing and listing decisions due to a lack of predictive insights. Our challenge was to build a model that can predict the time to sell a car, helping users make informed decisions and optimize sales strategies.


💡 Solution Overview

We implemented a robust pipeline that:
- Preprocesses raw vehicle listing data
- Applies state-of-the-art ensemble models (XGBoost, CatBoost, LightGBM)
- Leverages SHAP and Permutation Importance for interpretability
- Uses Optuna for advanced hyperparameter tuning
- Visualizes feature insights to help stakeholders understand key drivers


👤 My Contributions

- Conducted data preprocessing, feature engineering, and dimensionality reduction
- Researched on the ML models for the project
- Designed and contributed to the final presentation
- Explored future scope in terms of business integration and analytics expansion


🛠️ Tech Stack & Tools

- Languages & Libraries: Python, Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn  
- ML Models: XGBoost, CatBoost, LightGBM  
- Tuning: Optuna  
- Feature Engineering: Regex, TFIDF, SHAP, Permutation Importance  
- GUI: Streamlit (for model interaction – demo not public)


📊 Key Insights

- High-impact features: “First seen date”, “Postcode area”, and “Reviews”
- Gradient Boosted Trees (GBT) models excelled in handling structured data
- Recursive dimensionality reduction improved model efficiency with minimal performance loss
- CatBoost was selected for deployment due to superior evaluation metrics


🧪 Evaluation

- Best Model: CatBoost Regressor
- Metrics:
  - R² Score: High predictive accuracy
  - RMSE & MAE: Minimized error margin
- Visuals: Residual plots, prediction vs actual comparison


📂 Repository Contents

- `Auto_Trader_Final_Presentation.pdf`: Final project slides


🏁 Project Outcome

- Developed a working predictive model with a GUI prototype
- Enabled strategic value for Auto Trader, private sellers, and dealerships
- Proposed future integrations: Dynamic pricing, EV trend analysis, financial insights


🚀 Future Scope

- Demand Forecasting
- Geospatial and Behavioral Analytics
- EV Trends & Sustainability Insights
- Integration with Finance Tools


🧠 Learnings

- GBTs are powerful for structured regression tasks
- Data cleaning & preprocessing can make or break model performance
- SHAP offers excellent model interpretability for stakeholders
- Optuna outperforms traditional grid search for hyperparameter tuning
