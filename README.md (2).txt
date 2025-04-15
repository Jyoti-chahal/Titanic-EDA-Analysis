# 🧠 Task 5: Exploratory Data Analysis (EDA) – Titanic Dataset

## 📌 Objective
The goal of this task was to explore the Titanic dataset and extract meaningful insights through both statistical and visual analysis. This helps in understanding relationships between variables and survival outcomes using Python libraries.

---

## 🛠 Tools Used
- Python
- Google colab
- Pandas
- Matplotlib
- Seaborn

---

## 📂 Files Included
- `train.csv` — The Titanic training dataset used for analysis
- `Titanic_EDA.ipynb - Colab` — Notebook with all analysis and charts
- `README.md` — Description and documentation of the task

---

## 📊 Steps Performed
1. **Data Loading**: Loaded `train.csv` using Pandas
2. **Data Cleaning**: Handled missing values in `Age` and `Embarked`, dropped `Cabin`
3. **Univariate Analysis**: Analyzed individual features like Age, Fare, Sex, Pclass
4. **Bivariate Analysis**: Compared features like Sex, Pclass, Fare, Age with Survived
5. **Multivariate Analysis**: Combined Pclass and Sex vs Survival
6. **Correlation Heatmap**: To identify how features relate numerically
7. **Observations**: Added meaningful insights below each visual
8. **Summary**: Summarized trends and patterns found during EDA

---

## 🔍 Key Insights
- 🚺 **Females** had much higher survival rates than males
- 🎟️ **1st Class** passengers had better survival chances
- 💰 Higher **Fare** → better chances of survival
- 🧒 Younger passengers were more likely to survive
- 🚢 Passengers from **Cherbourg** had the highest survival rate

---

## ✅ How to Run This Project
1. Clone the repository or download the files
2. Open `Titanic_EDA.ipynb` in Jupyter Notebook or Google Colab
3. Run all cells step-by-step to view analysis and graphs

---