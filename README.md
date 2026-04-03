# PUBG_Game_winner_prediction
Game Winner Prediction using Machine Learning
# Project Overview

This project focuses on predicting the winning probability (winPlacePerc) of players in a battle royale game using machine learning techniques. The goal is to analyze player behavior and performance metrics to determine what factors contribute most to winning.

# Objectives
- Analyze player statistics and gameplay patterns
- Perform data cleaning and preprocessing
- Engineer meaningful features to improve model performance
- Train and evaluate multiple machine learning models
- Identify key factors influencing winning probability

# Dataset Description

The dataset contains player-level information such as:

- Player attributes (kills, damage dealt, etc.)
- Match-related features (match type, team size)
- Movement metrics (walk distance, ride distance, swim distance)
- Combat stats (kills, headshots, assists)
- Target variable: winPlacePerc (winning placement percentage)

# Tech Stack
- Programming Language: Python
Libraries Used:
- Pandas, NumPy → Data manipulation
- Matplotlib, Seaborn → Data visualization
- Scikit-learn → Machine learning models

# Project Workflow
# 1. Data Preprocessing
- Handled missing values
- Removed unrealistic or inconsistent data points
- Encoded categorical variables
# 2. Exploratory Data Analysis (EDA)
- Analyzed feature distributions
- Identified relationships between features and target variable
- Derived initial insights from player behavior
# 3. Feature Engineering
- Created new meaningful features
- Removed redundant or noisy features
- Improved model input quality
# 4. Model Building
Trained multiple models such as:
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
# 5. Model Evaluation
- Compared models using performance metrics
- Selected the best-performing model based on accuracy and generalization
# Key Insights
- Players with higher kills and damage generally perform better
- Movement (walk distance) is a strong indicator of survival
- Passive players (low movement + low combat) tend to rank lower
- Balanced gameplay (movement + combat) leads to higher winning probability

# Results
- The best-performing model achieved strong predictive accuracy
- Feature importance analysis revealed the most influential factors affecting performance

# Future Improvements
- Hyperparameter tuning for better performance
- Advanced models (XGBoost, LightGBM)
- Deployment using Flask/Streamlit
- Real-time prediction system

## Author

**Anjali Versha**

---

## License

This project is open-source and available under the MIT License.

---

If you like this project, don’t forget to star the repository!
