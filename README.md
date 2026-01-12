# FinalExamMarksPrediction
Machine learning dashboard to predict student academic performance using regression models, EDA, and interactive visualization.

## 📌 Project Overview
This project predicts **student academic performance** using Machine Learning.  
It focuses on predicting:

- **Sessional I (S-I)**
- **Sessional II (S-II)**
- **Final Exam Marks**

The project follows a **complete ML lifecycle**:
Data preprocessing → Exploratory Data Analysis → Model training → Evaluation → Interactive Dashboard.

---

## 🧠 Research Questions
1. Can **assignments and quizzes** predict Sessional-I performance?
2. Does **Sessional-I** improve prediction accuracy for Sessional-II?
3. Can **assignments, quizzes, S-I, and S-II** together predict Final Exam marks accurately?

---

## 📂 Dataset Description
- Multiple Excel sheets combined into one dataset
- Assessment components:
  - Assignments (As:1 – As:6)
  - Quizzes (Qz:1 – Qz:8)
  - Sessional-I, Sessional-II, Final Exam
- Engineered features:
  - `Assignment_Avg`
  - `Quiz_Avg`

---

## 🔍 Exploratory Data Analysis (EDA)
- Distribution plots (KDE)
- Correlation heatmaps
- Boxplots for score spread
- Cross-sheet aggregation and analysis

---

## ⚙️ Models Used
| Model | Description |
|-----|------------|
| **Linear Regression** | Baseline multiple regression |
| **Polynomial Regression (Degree 2)** | Captures non-linear relationships |
| **Dummy Regressor** | Mean baseline for comparison |

---

## 📊 Evaluation Metrics
- **MAE (Mean Absolute Error)**
- **RMSE (Root Mean Squared Error)**
- **R² Score**
- **Bootstrap 95% Confidence Interval for MAE**

---

## 📈 Key Results
- Polynomial Regression consistently outperformed Linear Regression
- Adding previous sessionals significantly improved Final Exam prediction
- Models showed strong generalization with low train–test error gap

---

## 🖥️ Interactive Dashboard
Built using **Gradio + Plotly**, the dashboard allows:
- Selecting prediction target (S-I / S-II / Final)
- Comparing model performance
- Visualizing MAE, RMSE, and R² interactively

---

## 🛠️ Tech Stack
- **Python**
- **Pandas, NumPy**
- **Matplotlib, Seaborn**
- **Scikit-learn**
- **Gradio**
- **Plotly**
- **Google Colab**

---

