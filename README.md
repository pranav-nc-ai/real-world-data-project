# Real-World Data Project: Retail Sales Analysis and Prediction

## 📌 Project Overview

This project focuses on analyzing retail sales data and building a predictive model to estimate product sales. The goal is to apply data science techniques in a real-world business scenario.

---

## 📂 Dataset

* Dataset: BigMart Sales Data
* Contains information about products, outlets, and sales performance

---

## 🔧 Steps Performed

### 1. Data Loading

* Loaded dataset using pandas

### 2. Data Cleaning

* Handled missing values in `Item_Weight` and `Outlet_Size`
* Standardized categorical values in `Item_Fat_Content`

### 3. Exploratory Data Analysis (EDA)

* Visualized sales distribution
* Analyzed sales by item type and outlet type

### 4. Feature Engineering

* Converted categorical variables using Label Encoding

### 5. Model Building

* Linear Regression Model
* Random Forest Regressor

### 6. Model Evaluation

* Linear Regression R² Score: ~0.52
* Random Forest R² Score: ~0.56

---

## 📊 Key Insights

* Sales vary significantly across outlet types
* Certain item categories perform better
* Random Forest performs better than Linear Regression

---

## 🚀 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib & Seaborn
* Scikit-learn

---

## 📁 Project Structure

```
real-world-data-project/
│
├── data/
│   └── dataset.csv
├── notebooks/
│   └── eda.ipynb
├── src/
├── README.md
├── requirements.txt
```

---

## ✅ Conclusion

This project demonstrates end-to-end data analysis and machine learning workflow, including data cleaning, visualization, and predictive modeling.
