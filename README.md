# Exploratory Data Analysis on Heart Health Dataset
# 📝 Overview
This project performs Exploratory Data Analysis (EDA) on a heart health dataset using Python, pandas, seaborn, and statistical methods. It explores relationships between various health and demographic factors and heart attack occurrence, with a focus on identifying significant variables through statistical tests and visualizations.

# ✨ Features
Data Preprocessing: Handles missing values by removing null entries to ensure clean data for analysis.

Statistical Analysis: Uses Chi-square tests to identify variables significantly associated with heart attacks (p-value ≤ 0.05).

Visualization: Generates a count plot to visualize the distribution of heart attacks across age categories.

Feature Selection: Selects key variables (e.g., Sex, AgeCategory, HadDiabetes) for focused analysis based on domain relevance.

# 💬 How to Use
Mount Google Drive in Colab and load the dataset (Heart.csv).

Run the script to preprocess data, perform Chi-square tests, and generate visualizations.

Review statistical outputs (p-values) and visualizations to understand factors related to heart attacks.

Explore the subset of selected features for deeper insights.

# 🧩 Project Structure
How It Works

Data Loading: Reads the Heart.csv dataset from Google Drive using pandas.

Preprocessing: Drops rows with missing values to create a clean dataset.

Statistical Testing: Performs Chi-square tests for independence between each variable and HadHeartAttack, storing significant variables (p ≤ 0.05).

Feature Subset: Creates a focused DataFrame with key health and demographic variables for analysis.

Visualization: Uses seaborn to plot a count plot of heart attacks by age category.

# ⚠️ Limitations
Missing Data Handling: Simply drops null values, which may reduce dataset size and introduce bias.

Statistical Scope: Relies solely on Chi-square tests, which may not capture complex relationships.

Limited Visualizations: Only includes a single count plot, limiting insights into other variables.

Categorical Focus: Does not fully explore numerical variables (e.g., BMI, SleepHours) in depth.

# 🚀 Future Improvements
Implement advanced imputation techniques (e.g., mean/median or KNN) for missing values.

Incorporate additional statistical tests (e.g., t-tests, ANOVA) for numerical variables.

Expand visualizations (e.g., correlation heatmaps, box plots) for a comprehensive EDA.

Apply machine learning models to predict heart attack risk based on significant variables.
