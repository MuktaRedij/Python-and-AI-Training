# 🛳 Titanic Dataset – Exploratory Data Analysis 

This project performs exploratory data analysis (EDA) on the Titanic dataset using Python.  
The goal is to practice reading data, visualizing patterns, and identifying insights using real-world historical data.

---

## 📌 Objective

- Learn how to work with Jupyter Notebook
- Import and explore datasets using Pandas
- Visualize data trends using Matplotlib and Seaborn
- Identify patterns related to survival outcomes

---

## 📁 Dataset

The dataset used is the built-in **Titanic dataset** from the `seaborn` library.

To load it:

```python
import seaborn as sns
df = sns.load_dataset("titanic")
```
## 🧠 Key Steps Performed

- Loaded the dataset into a pandas DataFrame  
- Checked structure, missing values, and data types  
- Visualized survival patterns using bar charts and count plots  
- Compared survival across:
  - Gender  
  - Passenger class  
  - Age patterns  

---

## 📊 Visualizations

The following plots were created:

- ✔ Survival count bar chart (Matplotlib)
- ✔ Survival by gender (Seaborn)
- ✔ Survival by passenger class (Seaborn)

These visualizations help identify the factors influencing passenger survival.

---

## 📎 Insights Summary

Based on the analysis:

- More passengers **did not survive** than survived.
- **Females had significantly higher survival rates** compared to males.
- **First-class passengers survived more frequently** than second and third class.
- The `age` column contains missing values and may require handling in future modeling.

---

## 📦 Tools & Libraries Used

| Library | Purpose |
|--------|---------|
| Pandas | Data loading & manipulation |
| Seaborn | Built-in dataset + visualizations |
| Matplotlib | Plotting graphs |
| Jupyter Notebook | Interactive analysis |

---

## ▶ How to Run

1. Install required libraries:

```bash
pip install pandas seaborn matplotlib
```
2. Open Jupyter Notebook:
```bash
jupyter notebook
```
3. Run the notebook:
```bash
EDA_Titanic.ipynb
```
---
## 👤 Author

**Name:** Mukta Redij  
**Project Type:** - Python and AI Training
