# 🚢 Titanic Dataset - Exploratory Data Analysis (EDA)

This project performs data cleaning and exploratory data analysis (EDA) on the famous [Titanic dataset](https://www.kaggle.com/competitions/titanic/data), which contains information about the passengers aboard the Titanic and whether they survived.

---

## 📁 Dataset

- **Source:** Kaggle ([Titanic - Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic))
- **Files Used:**
  - `train.csv`: Used for all cleaning and visualization

---

## 🛠️ Tools & Libraries

- Python
- Pandas
- Seaborn
- Matplotlib
- Jupyter Notebook

---

## 🔍 Objectives

- Clean the dataset (handle missing values, drop irrelevant columns).
- Perform EDA to identify trends and relationships between features and survival.
- Visualize:
  - Survival counts
  - Survival by gender
  - Survival by class
  - Age distribution
  - Survival by port of embarkation

---

## 🧼 Data Cleaning

- Filled missing values in `Age` with the median.
- Filled missing values in `Embarked` with the mode.
- Dropped the `Cabin` column due to excessive missing data.

---

## 📊 Key Visualizations

- **Survival Count**: How many survived vs. didn't.
- **Survival by Sex**: Comparison of survival between male and female passengers.
- **Survival by Class**: Survival rate across 1st, 2nd, and 3rd class.
- **Age Distribution**: Histogram of passenger ages.
- **Survival by Embarked**: Survival rate based on port of embarkation.

---

## 📎 How to Run

1. Clone this repository or download the `.ipynb` notebook.
2. Make sure you have `train.csv` in the same directory.
3. Install required libraries (if not installed):
   ```bash
   pip install pandas matplotlib seaborn
