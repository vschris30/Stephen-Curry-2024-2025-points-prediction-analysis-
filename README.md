
# 🏀 Analyzing and Predicting Stephen Curry’s Points Scored in the 2024–2025 NBA Season

This project applies Machine Learning to analyze and predict Stephen Curry’s scoring performance during the 2024–2025 NBA season. Using in-game statistics such as minutes played, field goals attempted, and three-point attempts, we explore how these factors influence Curry’s points scored (PTS).

## 📌 Project Highlights

* Cleaned and prepared game log data
* Exploratory Data Analysis (EDA) on Curry’s performance
* Built regression models to predict `PTS`

  * ✅ **Linear Regression** (MSE: 0.64, R²: 0.99)
  * 🌲 **Random Forest Regressor** (MSE: 15.65, R²: 0.71)
* Visual comparisons between actual and predicted scores
* Insights into which stats most influence Curry’s scoring

## 🧠 Models Used

* **Linear Regression** for simple, interpretable predictions
* **Random Forest** for capturing nonlinear patterns

## 📊 Key Findings

* **Linear Regression** outperforms Random Forest with extremely high R²
* Curry’s scoring is strongly influenced by basic stats like `MP`, `FGA`, and `3PA`
* Predictable scoring behavior suggests simpler models are effective

## 🔧 Tools & Libraries

* Python
* Pandas, NumPy, Matplotlib, Seaborn
* Scikit-learn (ML modeling and evaluation)

## 📈 Future Improvements

* Add more seasons for trend analysis
* Include team-level or opponent-level context
* Try deep learning approaches for richer prediction
