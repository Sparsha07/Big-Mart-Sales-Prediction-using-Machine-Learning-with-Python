# 🛒 Big Mart Sales Prediction

Predicting product sales at Big Mart outlets using Machine Learning with Python.

## 📂 Dataset

* **Train.csv** → Includes product, outlet features + `Item_Outlet_Sales` (target).
* **Test.csv** → Same features, without target.

Key columns: `Item_Weight`, `Item_Fat_Content`, `Item_MRP`, `Outlet_Type`, `Outlet_Size`, `Outlet_Location_Type`.


## ⚙️ Workflow

1. Data Cleaning & Preprocessing
2. EDA (visualizations & correlations)
3. Model Training → Linear Regression, Decision Tree, Random Forest, XGBoost
4. Model Evaluation → RMSE, R²
5. Predictions on test data

## 🚀 How to Run

```bash
git clone https://github.com/your-username/Big-Mart-Sales-Prediction.git
cd Big-Mart-Sales-Prediction
pip install -r requirements.txt
jupyter notebook BigMart_Sales_Prediction.ipynb

## 📊 Results

* **Best Model:** Random Forest / XGBoost
* **Top Features:** `Item_MRP`, `Outlet_Type`, `Item_Visibility`

## 📜 Tech Stack

Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost

