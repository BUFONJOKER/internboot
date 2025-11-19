
---

# 📑 Tasks Completed

*(Based on the numbering from the INTERNBOOT “Internship Task for DA_DS” PDF)*

🔗 **Tasks PDF:**
➡️ [INTERNBOOT Internship Task for DA_DS](./INTERNBOOT_internship_task_for_DA_DS.pdf)

---

## 🟦 Task 1 — Beginner Level Task (Part 03)

### **Linear Regression for Sales Prediction**

🔗 **Notebook:**
➡️ [Task1.ipynb](./Task1.ipynb)

**Description:**
Build a simple regression model to predict future sales based on time and promotions.

**Features:**

* Select features like date, promotions, and holidays
* Train/Test split of the dataset
* Build a Linear Regression model

**Tech Stack:**
Python, Pandas, Scikit-learn

**Dataset Link:**
[Store Sales Time Series Forecasting – Kaggle](https://www.kaggle.com/competitions/store-sales-time-series-forecasting)

---

## 🟩 Task 2 — Intermediate Level Task (Part 02)

### **Multiple Regression Model**

🔗 **Notebook:**
➡️ [Task2.ipynb](./Task2.ipynb)

**Description:**
Build a multiple regression model using all engineered features.

**Features:**

* Use variables like promotions, holidays, and store type
* Train a multiple regression model
* Evaluate using RMSE & MAE

**Tech Stack:**
Python, Pandas, Scikit-learn

**Dataset Link:**
[Store Sales Time Series Forecasting – Kaggle](https://www.kaggle.com/competitions/store-sales-time-series-forecasting)

---

## 🟥 Task 3 — Advanced Level Task (Part 03)

### **Model Deployment (Flask / Streamlit)**

🔗 **Notebook (EDA & Model Training):**
➡️ [Task3.ipynb](./Task3.ipynb)

🔗 **Streamlit App:**
➡️ [main.py](./main.py)

**Description:**
Deploy the regression model as a simple web app or dashboard.

**Features:**

* Build a Flask app or Streamlit dashboard
* User inputs store/date → Predict sales
* Display actual vs. predicted sales charts

**Tech Stack:**
Python, Pandas, Scikit-learn, Flask / Streamlit

**Dataset Link:**
[Store Sales Time Series Forecasting – Kaggle](https://www.kaggle.com/competitions/store-sales-time-series-forecasting)

**Deployed App (Streamlit Cloud):**
[https://abdulrehmanjavaid-internboot-dads-task3.streamlit.app/](https://abdulrehmanjavaid-internboot-dads-task3.streamlit.app/)

---

## ⚡ How to Run the Project

**Clone the repository:**

```bash
git clone https://github.com/BUFONJOKER/internboot.git
```

**Create and sync project (using `uv` CLI):**

```bash
uv init internboot
uv sync
```

**Run the Streamlit app:**

```bash
streamlit run main.py
```

---

