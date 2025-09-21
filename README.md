# 🛍️ Mall Customers Data Analysis & KNN Classification

This project performs **Exploratory Data Analysis (EDA)**, **Feature Engineering**, and **Machine Learning modeling** on the popular `Mall_Customers.csv` dataset.  
The goal is to clean and analyze the data, visualize important patterns, and implement a **K-Nearest Neighbors (KNN) classifier** to predict customer segments.

---

## 📌 Project Workflow

1. **Import Libraries**  
   - Pandas, NumPy, Matplotlib, Seaborn for data analysis and visualization  
   - Scikit-learn for preprocessing, model training, and evaluation  

2. **Load Dataset**  
   - Dataset: `Mall_Customers.csv`  

3. **Exploratory Data Analysis (EDA)**  
   - Dataset overview (shape, info, statistics)  
   - Missing values check  
   - Gender distribution  
   - Age distribution  
   - Income vs. Spending Score scatterplot  
   - Correlation heatmap  

4. **Data Cleaning**  
   - Handle duplicates  
   - Encode categorical features (`Gender`)  

5. **Feature Engineering**  
   - Select relevant features: `Age`, `Annual Income (k$)`, `Spending Score (1-100)`  
   - Scale features using **StandardScaler**  

6. **Modeling with KNN**  
   - Train-Test Split (80-20)  
   - Train **K-Nearest Neighbors** classifier  
   - Evaluate performance (Accuracy, Classification Report, Confusion Matrix)  
   - Plot Accuracy vs K values  

---

## 📊 Visualizations

- **Countplot**: Gender distribution  
- **Histogram**: Age distribution  
- **Scatterplot**: Annual Income vs. Spending Score  
- **Heatmap**: Correlations among numeric features  
- **Confusion Matrix**: Model evaluation  
- **Line Plot**: Accuracy vs. K values  

---

## 🚀 Tech Stack

- **Python 3**  
- **Libraries**:  
  - `pandas`  
  - `numpy`  
  - `matplotlib`  
  - `seaborn`  
  - `scikit-learn`  

