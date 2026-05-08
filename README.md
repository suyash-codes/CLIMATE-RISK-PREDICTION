# 🌍 Climate Risk Prediction System

An interactive Machine Learning project that predicts climate and rainfall-related risks using historical rainfall datasets, data visualization, and predictive analytics.

The project combines:

* Data Analysis
* Rainfall Trend Visualization
* Machine Learning Models
* Climate Risk Classification
* Interactive Streamlit Dashboard

---

# 📌 Project Overview

This project analyzes historical rainfall data across different Indian states to identify climate patterns and predict potential environmental risks such as:

* 🌊 Flood Risk
* 🌵 Drought Risk
* ☁️ Normal Climate Conditions

Using machine learning techniques, the system processes rainfall deviation, seasonal trends, and historical climate patterns to generate predictions and insights.

---

# ✨ Features

## 📊 Data Analysis & Visualization

* Rainfall distribution analysis
* Monthly rainfall trends
* Yearly rainfall trend analysis
* Correlation heatmaps
* State-wise rainfall comparison
* Scatter plots and seasonal analysis

## 🤖 Machine Learning

* Random Forest Regressor
* Random Forest Classifier
* Logistic Regression
* Climate risk categorization
* Feature importance analysis
* ROC Curve and confusion matrix evaluation

## 🌐 Interactive Dashboard

* Built using Streamlit
* Interactive visualizations using Plotly
* User input-based rainfall prediction
* Climate risk prediction display
* State and month-wise analysis

---

# 🛠️ Technologies Used

## Programming Language

* Python

## Libraries & Frameworks

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Plotly
* Scikit-learn
* Streamlit
* Streamlit-Lottie
* Pickle

---

# 📂 Dataset Used

The project uses:

```bash
 daily-rainfall-at-state-level.csv
```

Dataset contains:

* State names
* Rainfall data
* Normal rainfall
* Rainfall deviation
* Month and year information

---

# ⚙️ Machine Learning Workflow

## 1️⃣ Data Loading

The rainfall dataset is loaded using Pandas.

## 2️⃣ Data Preprocessing

* Missing value handling
* Feature engineering
* Lag feature creation
* Data cleaning

## 3️⃣ Exploratory Data Analysis

Visual analysis includes:

* Histogram plots
* Heatmaps
* Monthly rainfall trends
* Yearly rainfall trends
* Scatter plots

## 4️⃣ Risk Classification

Climate conditions are categorized as:

| Condition         | Risk Type    |
| ----------------- | ------------ |
| High deviation    | Flood Risk   |
| Very low rainfall | Drought Risk |
| Moderate rainfall | Normal       |

## 5️⃣ Model Training

Models used:

* Random Forest Regressor
* Random Forest Classifier
* Logistic Regression

## 6️⃣ Model Evaluation

Evaluation metrics include:

* Accuracy
* Precision
* Recall
* F1 Score
* RMSE
* ROC Curve
* Confusion Matrix

## 7️⃣ Deployment

The trained model is deployed using Streamlit.

---

# 📁 Project Structure

```bash
CLIMATE-RISK-PREDICTION/
│
├── app.py
├── model.pkl
├── features.pkl
├── daily-rainfall-at-state-level.csv
├── README.md
└── notebooks/
```

---

# ▶️ How to Run the Project

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/suyash-codes/CLIMATE-RISK-PREDICTION.git
cd CLIMATE-RISK-PREDICTION
```

## 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

## 3️⃣ Run the Streamlit Application

```bash
streamlit run app.py
```

---

# 📈 Visualizations Included

The project includes:

* Top rainfall states analysis
* Monthly rainfall seasonality trends
* Yearly rainfall trend plots
* Rainfall distribution histograms
* Correlation matrix heatmaps
* State-wise rainfall heatmaps
* ROC curve visualization
* Feature importance graphs

---

# 🧠 Future Improvements

* Real-time weather API integration
* Deep learning forecasting models
* Multi-state comparison dashboard
* Satellite climate data integration
* Disaster early warning system
* Mobile-friendly deployment

---

# 👨‍💻 Author

### Suyash Singh Gusain
### Tanmay Madan
### Saara Ahmed
### Titas Mahato

GitHub: https://github.com/suyash-codes

