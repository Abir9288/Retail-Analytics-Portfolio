# From Messy Retail Data to Business Insights

This project demonstrates a **complete retail analytics workflow** using Python and real-world messy transaction data. It is designed to showcase **data cleaning, exploratory analysis, feature engineering, customer segmentation, and regression modeling** in a professional, portfolio-ready format.

---

## 🗂 Dataset

The dataset contains online retail transaction data with:

- Product names and brands (some inconsistent)
- Weight information in mixed formats (e.g., "500g", "1 kg", "700")
- Unit price with missing values
- Customer and order IDs
- Country and date information

> **Note:** The dataset is assumed to be in CSV format and is loaded in the notebook.

---

## 🧹 Data Cleaning & Feature Engineering

- Standardized text columns (`ProductName`, `Brand`, `Country`)  
- Converted `Raw_Weight` to numeric `Weight_grams`  
- Handled missing values for `UnitPrice`, `Brand`, and `Weight_grams`  
- Extracted date features: `Year`, `Month`, `Weekday`  
- Created a `Revenue` column for analysis  

---

## 📊 Exploratory Data Analysis (EDA)

- Revenue distribution  
- Top countries by revenue  
- Top brands by revenue  
- Monthly revenue trends  
- Correlation matrix  

These visualizations highlight trends and help identify key business insights.

---

## 👥 Customer Segmentation

- Aggregated customers by total spending and total orders  
- Applied **KMeans clustering** to identify distinct customer segments  
- Visualized spending vs order frequency to guide marketing strategies  

---

## 📈 Regression Modeling (Teaching Example)

- Attempted to predict `UnitPrice` using Linear Regression and Random Forest  
- Performance:  
  - Linear Regression → MAE: 6.79, R²: -0.63  
  - Random Forest → MAE: 5.84, R²: -0.13  
- **Lesson:** Limited features make predicting `UnitPrice` difficult. This demonstrates **real-world data limitations** and the importance of understanding your dataset before modeling.

---

## 🚀 Key Insights

- Revenue is dominated by a few high-value transactions (right-skewed)  
- Top countries and brands drive most of the revenue  
- Customer segments reveal high-value and frequent buyers for targeting  
- Regression modeling illustrates how to approach predictive tasks responsibly  

---

## 🖥 Notebook

You can view and run the full Kaggle notebook here:  
[From Messy Retail Data to Business Insights](https://www.kaggle.com/code/abirmdhasan/from-messy-retail-data-to-business-insights)

---

## 🛠 Technologies Used

- Python 3  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

---

## 📌 How to Use

1. Clone this repository:  
```bash
git clone https://github.com/Abir9288/Retail-Analytics-Portfolio.git

