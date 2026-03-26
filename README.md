# Titanic Data Analysis & Dashboard

## 🚢 Project Objective
Analyze the Titanic dataset to explore passenger survival patterns and create a visual dashboard that tells the story of who survived and why.

---

## 📂 Project Tasks

1. **Load & Explore the Dataset**
   - Loaded Titanic dataset using Pandas
   - Displayed first 10 rows, dataset shape, and summary information
   - Goal: Understand dataset structure and features

2. **Handle Missing Values**
   - Checked missing values using `isnull()`
   - Filled missing values:
     - `Age` → median
     - `Embarked` → most frequent (mode)
   - Goal: Prepare dataset for analysis

3. **Descriptive Statistics**
   - Calculated mean, median, and standard deviation for `Age` and `Fare`
   - Counted survivors and non-survivors
   - Goal: Summarize key statistics

4. **Survival Analysis by Gender**
   - Calculated survival rates for male vs female
   - Visualized using bar plot

5. **Survival Analysis by Passenger Class**
   - Calculated survival rates for 1st, 2nd, and 3rd class
   - Visualized using bar plot

6. **Age Distribution**
   - Plotted age distribution using histogram/KDE
   - Overlayed survived vs non-survived passengers

7. **Fare Distribution by Class**
   - Visualized fares across classes using boxplot/violin plot
   - Highlighted outliers and differences

8. **Correlation Analysis**
   - Computed correlation matrix for `Age`, `Fare`, `SibSp`, `Parch`
   - Visualized using heatmap

9. **Multi-variable Relationship**
   - Created pairplot for `Age`, `Fare`, `SibSp`, `Parch`
   - Colored points by `Survived`

10. **Survival by Class & Gender**
    - Combined `Pclass` and `Sex` to analyze survival
    - Visualized using Seaborn `catplot(kind='bar')`

11. **Mini Dashboard**
    - Combined multiple visualizations into one figure:
      1. Survival by gender (bar plot)
      2. Age distribution (histogram)
      3. Fare by Pclass (boxplot)
      4. Survival by Embarked (bar plot)

---

## 📊 Key Insights

- **Gender:** Females had higher survival rates than males  
- **Class:** 1st class passengers survived more than 2nd and 3rd  
- **Age:** Children and younger passengers had better survival  
- **Fare:** Higher fare paid by 1st class passengers  
- **Embarked:** Survival varied by embarkation port  
- **Family:** Small impact from number of siblings/spouses (SibSp) and parents/children (Parch)

---

## 🛠 Tools & Libraries Used

- **Python 3**  
- **Pandas** – Data manipulation  
- **NumPy** – Numerical calculations  
- **Matplotlib** – Visualization  
- **Seaborn** – Statistical visualization  

---

## 📂 Dataset

- Dataset: [Titanic Dataset CSV](https://www.kaggle.com/datasets/ashishkumarjayswal/titanic-datasets)
- Source: Kaggle

---

## 📌 How to Run

1. Open `titanic_assignment.ipynb` in **Google Colab** or **Jupyter Notebook**  
2. Run all cells sequentially  
3. All plots and analysis will display inline  

---

## 🔗 Author

**Meerab Khan**  
