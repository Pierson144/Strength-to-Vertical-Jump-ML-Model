# Strength-to-Vertical-Jump-ML-Model

# Vertical Jump Prediction Using Machine Learning  

## 📌 Project Overview  
This project analyzes the relationship between strength training metrics and vertical jump height using machine learning models. The goal is to determine how weight room performance (e.g., power clean, squats, deadlifts) correlates with an athlete's ability to jump.  

## 🚀 Features & Methodology  
- **Data Preprocessing & Feature Engineering**
  - Created interaction terms such as `Height * Standing Reach` (HxSR)
  - Scaled weight room lifts by body weight for better comparisons  

- **Exploratory Data Analysis (EDA)**
  - Correlation heatmaps to identify the most influential features  
  - Outlier detection using Bonferroni correction  

- **Machine Learning Models Implemented**
  - **Linear Regression** (Baseline Model)  
  - **Random Forest Regressor** (Feature Importance Analysis)  
  - **Gradient Boosting Regressor** (Improved Accuracy)  
  - **Neural Network (TensorFlow/Keras)** (Capturing Non-Linear Relationships)  
  - **SHAP (SHapley Additive exPlanations)** (Understanding Model Predictions)  

- **Key Insights**
  - The **power clean to bodyweight ratio** was the strongest predictor of vertical jump.  
  - Athletes with a **40+ inch vertical** typically had a higher strength-to-bodyweight ratio.  
  - Strength ratios vary depending on **body size**, helping create more realistic training benchmarks.  

## 📊 Visualizations  
- **Optimal Lift Ratios vs. Vertical Jump** (Heatmap for ideal strength benchmarks)  
- **Vertical Jump vs. Strength Metrics** (Scatterplots & Regression Trends)  
- **Average Jump Heights for Dunkers by Standing Reach**  

## 📁 Dataset  
- Collected from **athletes via survey**  
- 315 observations after data cleaning  

## 🛠️ Tools & Technologies  
- **Python (Pandas, NumPy, Seaborn, Matplotlib)**  
- **Machine Learning (Scikit-Learn, TensorFlow/Keras, SHAP)**  
- **Statistical Analysis (Statsmodels, Bonferroni Outlier Detection)**  

## 🔥 Future Improvements  
- Hyperparameter tuning for further optimization  
- Expanding dataset to include sprint speed & flexibility metrics  
- Exploring deep learning with more complex architectures  

## 📜 Author  
Developed by **Pierson Alexander**  
