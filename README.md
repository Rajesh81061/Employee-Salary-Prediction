# 🧑‍💼 Employee Salary Prediction Using Machine Learning

This project aims to build a machine learning model that predicts employee salaries based on various features like age, gender, education level, job title, and experience. It also includes a Streamlit-based web application for real-time predictions.

---

## 📊 Problem Statement

Organizations often struggle to set fair and competitive salaries across various roles and experience levels. This project helps address that by developing a machine learning model to predict employee salaries, aiding HR in decision-making and budget planning.

---

## 🔧 Technologies and Libraries Used

- **Python 3.8+**
- **Pandas, NumPy** – Data manipulation and analysis
- **Matplotlib, Seaborn, Plotly** – Visualization
- **Scikit-learn** – Machine Learning models
- **XGBoost** – Advanced boosting algorithm
- **Streamlit** – Web app deployment
- **Pyngrok** – Public sharing via Google Colab (optional)

---

## ⚙️ Project Workflow

### 1. Data Collection
- Loaded a dataset with attributes: Age, Gender, Education Level, Job Title, Years of Experience, and Salary.

### 2. Data Preprocessing
- Removed duplicates and cleaned data.
- Encoded categorical variables (`Gender`, `Education Level`, `Job Title`).
- Scaled numerical features using `StandardScaler`.
- Split into training and testing sets.

### 3. Model Building
- Trained the following regression models:
  - Linear Regression
  - Decision Tree Regressor
  - Random Forest Regressor
  - Gradient Boosting Regressor
  - K-Nearest Neighbors
  - Support Vector Regressor (SVR)
  - XGBoost Regressor

### 4. Model Evaluation
- Evaluated all models using:
  - R² Score
  - Mean Squared Error (MSE)
- Selected the best-performing model.

### 5. Web Interface (Streamlit)
- Developed a user-friendly interface where users can input employee data and receive predicted salary instantly.

### 6. Deployment (Optional via Colab)
- Streamlit app deployed in **Google Colab** using **pyngrok** for public access.

---

## 🚀 How to Run the Project

### 👉 Locally (VS Code or Jupyter)
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/employee-salary-prediction.git
   cd employee-salary-prediction
