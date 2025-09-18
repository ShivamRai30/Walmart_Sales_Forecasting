# Walmart Sales Forecasting  
![shutterstock_1150637408](https://github.com/user-attachments/assets/56755558-2daf-4ebc-92e0-8fe046800412)

## 📌 Project Overview  
Walmart, a leading retail corporation, operates multiple stores across the U.S. This dataset combines weekly sales data from **45 stores**, along with additional store and holiday information.  
The goal of this project is to **forecast weekly sales** and analyze the **impact of holidays** such as **Christmas, Thanksgiving, Super Bowl, and Labor Day** on store performance.  

---

## 🎯 Business Objective  
- Predict weekly sales for each store and department.  
- Analyze whether sales are influenced by **time-based factors** (seasonality, holidays) and **store-specific factors** (store type, size).  
- Provide insights into **holiday-driven demand spikes** to help Walmart optimize inventory and staffing.  

---

## 📂 Dataset  
The dataset consists of four CSV files:  
- **train.csv** → Weekly sales data (Store, Dept, Date, Weekly_Sales, IsHoliday).  
- **test.csv** → Test set for forecasting.  
- **features.csv** → Additional info such as temperature, fuel price, CPI, unemployment, and holiday flags.  
- **stores.csv** → Metadata about each store (Store type, Size).  

**Size:** ~421k rows in training data.  
**Frequency:** Weekly records.  

---

## 🚀 Project Workflow  
1. **Data Preparation**  
   - Merged datasets and created a consistent training set.  
   - Converted dates, engineered time-based features, and handled missing values.  

2. **Exploratory Data Analysis (EDA)**  
   - Identified sales patterns across stores and departments.  
   - Visualized the impact of holidays and external factors (CPI, unemployment, fuel prices).  

3. **Modeling**  
   - Built baseline regression models (Linear Regression, Random Forest) using scikit-learn.  
   - Evaluated performance with metrics like RMSE and RMSLE.  
   - Compared model results against simple benchmarks.  

4. **Key Insights**  
   - Sales show strong **seasonality**, especially during holiday weeks.  
   - Larger stores record higher sales overall, but holiday effects vary by department.  
   - Departments such as **electronics** and **grocery** are more sensitive to holiday promotions.  

---

## 📊 Tools & Libraries  
- **Python**  
- **Pandas, NumPy** → Data cleaning & preprocessing  
- **Matplotlib, Seaborn** → Data visualization  
- **Scikit-learn** → Machine learning models  

---

## 📈 Results  
- Developed models capable of forecasting weekly sales.  
- Identified significant **holiday-driven sales spikes**.  
- Built a foundation for future improvements (feature engineering, advanced models, time-series validation).  

---

## 🔮 Future Work  
- Add **lag features & rolling averages** for stronger time-series modeling.  
- Experiment with **XGBoost/LightGBM** and deep learning (RNN/LSTM).  
- Implement **time-series-aware cross-validation** for better generalization.  

---

## ▶️ Run the Project  
You can open and run this project in **Google Colab**:  
👉 https://colab.research.google.com/drive/1uS-JHe6-Rt8qybUN3EIyHRw9Pl8IarCo?usp=sharing

---

## 📜 Acknowledgements  
This dataset is based on Walmart sales data provided for forecasting challenges.  
