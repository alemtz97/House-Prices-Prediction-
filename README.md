# 🏡House-Prices-Prediction-Advanced Regression Techniques
Kaggle Competition - Advanced Regression Techniques 

This project is a submission for the Kaggle competition **House Prices - Advanced Regression Techniques**. The goal is to build a predictive model that accurately estimates house prices based on various features. 
Using **Python**, I applied advanced regression techniques, feature engineering, and machine learning models to enhance prediction accuracy. The project involved **A/B testing** and iterative model improvements to achieve the best performance.

##  Dataset
The dataset consists of various house attributes, including numerical and categorical features:
- Lot size, square footage, number of bedrooms and bathrooms
- Neighborhood, condition, and quality of materials
- Year built, renovation history, and more

**Source**: [Kaggle Competition Dataset](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques)

##  Approach & Methodology
1. **Data Preprocessing:**
   - Handled missing values using imputation techniques.
   - Converted categorical variables using **one-hot encoding**.
   - Normalized and standardized numerical features.
2. **Feature Engineering:**
   - Created new meaningful features (e.g., total square footage, age of house).
   - Removed multicollinear variables to improve model interpretability.
3. **Model Selection & Training:**
   - Tried multiple models: **Linear Regression, Decision Trees, Random Forest, XGBoost, LightGBM**.
   - Used **hyperparameter tuning** (GridSearchCV, RandomizedSearchCV) to optimize models.
4. **Evaluation & Testing:**
   - Used **Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE)** as performance metrics.
   - Conducted **A/B testing** to compare model effectiveness.
   
## 🚀 Results & Performance
- Best-performing model: **XGBoost with feature selection**
- Achieved **low RMSE** on validation data and ranked in the top percentage on the Kaggle leaderboard.
- Feature importance analysis revealed key factors influencing house prices.

##  Tools & Technologies
- **Python, Pandas, NumPy, Scikit-Learn, XGBoost, LightGBM**
- **Matplotlib & Seaborn** for data visualization
- **Jupyter Notebook** for experimentation

## Repository Structure
```
📁 House-Prices-Prediction
│-- 📜 README.md
│-- 📜 house_prices_notebook.ipynb (Full Jupyter Notebook with analysis & model training)
│-- 📜 kaggle_submission.ipynb (Notebook used for final Kaggle submission)
```

##  How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/House-Prices-Prediction.git
   cd House-Prices-Prediction
   ```
2. Open and run the Jupyter Notebook:
   ```bash
   jupyter notebook house_prices_notebook.ipynb
   ```

##  Acknowledgments
Thanks to **Kaggle** for providing the dataset.
