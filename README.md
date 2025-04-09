# 📊 Electronic Sales Prediction Using ML | A Comparative Study

> 🎯 *Accurately forecasting electronic product sales using machine learning models to support inventory planning, pricing, and revenue forecasting.*
---

## 📌 Overview

This project explores and compares **four machine learning regression models** — `Random Forest`, `Support Vector Regression`, `Gradient Boosting`, and `Linear Regression` — to predict the **total sales price of electronic products**.

We aim to assist businesses in making **data-driven sales strategies**, improve **inventory management**, and optimize **financial forecasting**.

---

## 🔍 Key Features

- ✅ Cleaned and preprocessed 20K+ real-world sales records
- 📈 Visualized sales trends and patterns across multiple dimensions
- 🤖 Built and compared multiple ML models using R², MAE, and MSE
- 🥇 Identified **Random Forest** as the best-performing model
- 📦 Saved trained model using `joblib` for real-world deployment

---

## 📂 Project Structure

```
├── Sales_Prediction.ipynb     # Jupyter Notebook (Full Implementation)
├── dataset/                   # Cleaned data used for training/testing
├── model/                     # Saved Random Forest Model
├── report/                    # Research paper style documentation
└── README.md                  # Project Documentation
```

---

## 📊 Algorithms Compared

| Model               | R² Score | MAE (↓) | MSE (↓) |
|--------------------|----------|---------|---------|
| **Random Forest**   | ✅ Highest | 🔽 Lowest | 🔽 Lowest |
| Gradient Boosting  | Moderate | Moderate | Moderate |
| Linear Regression  | Moderate | Moderate | High    |
| SVR                | Lowest   | High     | Highest |

> 💡 **Conclusion:** *Random Forest consistently outperforms others in predictive accuracy and stability for nonlinear sales data.*

---

## 📈 Visual Insights

| Metric | Description |
|--------|-------------|
| 🧾 **Total Price Distribution** – Identify sales volume patterns and outliers |
| 💳 **Payment Preferences** – Optimize customer experience |
| 🎧 **Top Product Types** – Maximize inventory efficiency |
| 👥 **Loyalty Insights** – Explore behavior of repeat customers |

---

## 🧠 How It Works

1. **Data Preprocessing**
   - Remove irrelevant columns, fill missing values
   - Encode categorical features, scale numerical ones

2. **Model Training & Evaluation**
   - Train models on historical sales
   - Evaluate using metrics (R², MAE, MSE)
   - Visualize predicted vs actual results

3. **Deployment-Ready**
   - Save best model using `joblib`
   - Predict new sales based on unit price, quantity, etc.

---

## 🚀 How to Run Locally

```bash
# 1. Clone the repo
git clone https://github.com/your-username/Sales-Prediction-ML.git
cd Sales-Prediction-ML

# 2. Install dependencies
pip install -r requirements.txt

# 3. Launch Jupyter Notebook
jupyter notebook Sales_Prediction.ipynb
```

---

## 📚 Technologies Used

- `Python`
- `Scikit-learn`
- `Pandas`
- `Matplotlib`
- `Seaborn`
- `Joblib`

---

## 👩‍💻 Authors


| Janavi Singh | 
| Sakshi Sinha | 

---

## 🌟 Feedback & Contributions

If you found this project useful or interesting:

✅ Star the repo  
📌 Fork it for your own sales forecasting solutions  
📬 Reach out for collaboration or feedback!

---

Let me know if you'd like a version with badges, emojis minimized, or specific images inserted!
