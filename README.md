<<<<<<< HEAD
# 🧠 Zara Sales Prediction (2024–2025)

## 👨‍💻 Author
**Name:** Dilkash  
**Location:** Budapest, Hungary 🇭🇺  
**Focus Areas:** Data Science | Full-Stack Development | AI Agentic Systems  

---

## 🧩 Project Overview
This project analyzes **Zara’s 2024–2025 sales data** to understand and predict product sales volume based on pricing, seasonality, promotion, material, and brand.  
The dataset was cleaned, explored, and modeled using Python in **Jupyter Notebook**.  

The goal was to:
- Perform end-to-end **Exploratory Data Analysis (EDA)**
- Build **machine learning models** (Linear Regression & Decision Tree)
- Evaluate performance using **R² and RMSE metrics**
- Visualize predictions and gain business insights

---

## 📂 Project Structure

📁 Zara_Sales_Project/
├── 📓 Zara_Sales_Prediction.ipynb ← main notebook
├── 📊 Cleaned_Zara_Data.csv ← cleaned dataset
├
│ 
└── 🧾 README.md


---

## 🧹 Data Preparation & Cleaning
1. **Loaded dataset** (`.xlsx`) using `pandas.read_excel()`
2. **Checked missing values** — found a few in `name` and `description`
   - Filled with `"Unknown Product"` or `"No description available"`
3. **Removed outliers** in price using IQR (Interquartile Range)
4. **Converted categorical variables** using `pd.get_dummies()`
5. **Final dataset shape:** ~19,600 rows × 16 features

---

## 📊 Exploratory Data Analysis (EDA)
- Analyzed **price distribution** using boxplots and histograms
- Compared **sales volume vs product category**
- Explored **seasonal patterns** and **promotion effects**
- Detected correlations between numeric variables

---

## 🤖 Machine Learning Models

### 1️⃣ Linear Regression
- R² Score: **0.9008**  
- RMSE: **93.16**

✅ Captured clear linear relationships between price, promotion, and sales.  
Performed best overall — accurate and stable.

### 2️⃣ Decision Tree Regressor
- R² Score: **0.8967**

✅ Captured non-linear relationships  
Slightly lower performance but interpretable.

---

## 📈 Model Comparison Visualization

### Linear Regression
![Linear Regression Prediction](images/Linear_Regression_Sales_Prediction.png)

### Decision Tree
![Decision Tree Prediction](images/Decision_Tree_Sales_Prediction.png)

---

## 💡 Insights & Interpretation
- **Price** and **Promotion** were the strongest predictors of sales.
- **Seasonality** and **Material** also affected demand patterns.
- Zara’s sales patterns are **largely linear**, meaning traditional models like Linear Regression work very well.
- Data is **predictable and clean**, indicating consistent business operations.

---

## 🏁 Conclusion
- **Best Model:** Linear Regression (R² = 0.90)
- **Business Insight:** Zara can use this model to forecast sales, optimize pricing, and plan promotions.
- **Next Step:** Extend with Random Forest or Gradient Boosting for deeper prediction capabilities.

---

## ⚙️ Technologies Used
- **Python (Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn)**
- **Jupyter Notebook**
- **Excel / CSV data files**
- **GitHub for version control**

---

## 🌍 Future Improvements
- Include **Random Forest & XGBoost** for advanced modeling
- Perform **Feature Importance Analysis**
- Build a **Streamlit dashboard** for interactive predictions

---

## 🧠 Keywords
`Data Science` · `Zara` · `Sales Forecasting` · `Linear Regression` · `Decision Tree` · `Machine Learning` · `EDA` · `Python`

---

## 💬 Acknowledgement
Guided learning and mentoring by **ChatGPT (OpenAI)** 🤝  
Project created as part of continuous growth in **Data Science & Machine Learning.**
=======
# zara-sales-prediction-2024-2025
End-to-end data science project predicting Zara product sales (2024–2025) using Python, EDA, and Machine Learning (Linear Regression &amp; Decision Tree).
>>>>>>> 0b161954f8930e1d3b56ffe9ee3fd770ca645297
