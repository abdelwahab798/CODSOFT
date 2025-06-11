# Codsoft Internship Projects 🚀

This repository contains the main projects I worked on during my internship at **Codsoft**, where I applied data analysis, visualization, and machine learning techniques to solve real-world problems. Below is a summary of each project, including objectives, techniques used, and model performance.

---

## 📊 1. Advertising Sales Prediction

**Objective:**  
Analyze the impact of different advertising channels (TV, Radio, Newspaper) on product sales and build a predictive model.

**Key Steps:**  
- Performed Exploratory Data Analysis (EDA) to identify the most influential media.  
- Found that **TV advertising** had the strongest correlation with sales.  
- Built a **Linear Regression** model to predict sales.

**Results:**  
- R² Score: `0.91`  
- Mean Squared Error (MSE): `2.41`

---

## 🎬 2. Movie Ratings Analysis & Prediction

**Objective:**  
Clean and analyze movie data, identify trends, and build a model to predict movie ratings based on cast, genre, and other features.

**Key Steps:**  
- Cleaned data and handled missing values.  
- Extracted insights such as:  
  - Most movies produced between 1930–2020 were Drama, Action, and Comedy.  
  - High number of movies doesn’t always mean high average rating.  
- Built a **regression model** using:
  - Features: Votes, Duration, Top 3 Actors, Director, Genre

**Results:**  
- Accuracy: `86.4%`  
- MSE: `0.27`  
- R² Score: `0.86`

---

## 🚢 3. Titanic Survival Prediction

**Objective:**  
Analyze passenger data from the Titanic disaster to predict survival outcomes.

**Key Steps:**  
- Cleaned data and filled missing values.  
- Engineered new features:
  - `FamilySize` = `SibSp + Parch + 1`  
  - `IsAlone` = 1 if passenger was alone, else 0  
  - `AgeGroup` = binned age ranges  
- Built a **Logistic Regression** model to predict survival.

**Results:**  
- Accuracy: `84.3%`  
- R² Score: `0.35`  
- Mean Absolute Error (MAE): `0.16`

---

## 🛠️ Tools & Technologies Used

- Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
- Jupyter Notebook
- Machine Learning Models: Linear Regression, Logistic Regression
- Data Visualization & EDA

---

## 📚 Conclusion

These projects helped me strengthen my skills in data cleaning, feature engineering, model building, and evaluation. I also gained valuable experience turning data into insights that can inform business decisions.



