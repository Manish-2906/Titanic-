# 🛳 Titanic Survival Analysis - EDA Project

This project performs an Exploratory Data Analysis (EDA) on the classic Titanic dataset using Python libraries such as Pandas, NumPy, Seaborn, and Matplotlib.

---

## 📂 Dataset

- Source: [Kaggle - Titanic: Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic/data)
- Rows: 891
- Columns: 12
- Target Variable: `Survived` (0 = No, 1 = Yes)

---

## 🧰 Tools & Libraries

- Python
- Pandas, NumPy
- Seaborn, Matplotlib

---

## 🔍 Key EDA Steps

- Explored data types, null values, and duplicates.
- Analyzed univariate features: Sex, Age, Pclass, Fare, Embarked.
- Performed bivariate analysis: Survival rates by gender, class, and age group.
- Created a new feature `IsChild` to assess child survival separately.
- Visualized data using countplots, KDE plots, bar plots with labels, and vertical lines for mean/median.

---

## 📊 Visual Analysis

- **Gender Distribution** and its effect on survival.
- **Passenger Class** comparison for survival and fare.
- **Fare Distribution** with mean and median.
- **Survival Rates by Age** and child vs adult.
- **Embarked Port Distribution**

---

## 📌 Key Insights

- **Women** had a significantly higher survival rate (74%) compared to **men** (19%).
- **1st Class** passengers had the highest survival rate (63%), followed by 2nd (47%) and 3rd (24%).
- **Children under 16** had better survival rates than adults.
- Most passengers boarded from **Southampton (S)**.
- The **Fare** distribution was right-skewed — a few passengers paid very high fares which pulled the mean upward.

---

## ✅ Conclusion

Survival on the Titanic was strongly influenced by **gender**, **class**, and **age**. This EDA highlights how social and economic factors played a major role in survival outcomes.

---

## 📌 Future Improvements

- Handle missing values more robustly (e.g., age imputation by title or class).
- Drop or engineer features from columns like `Cabin` or `Ticket`.
- Extend the project with machine learning classification models.

---


