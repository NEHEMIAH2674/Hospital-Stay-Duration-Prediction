# Hospital-Stay-Duration-Prediction
Predict the number of days a patient will stay in the hospital based on their demographic, medical, and admission details.

## 📌 Project Overview
This project predicts **patient length of stay (in days)** in a hospital using demographic, medical, and admission-related features.  
By predicting hospital stay duration at admission time, hospitals can:
- Optimize **bed occupancy planning**
- Improve **staff and resource allocation**
- Reduce **patient congestion**

## 📂 Dataset
The dataset contains the following key columns:
- **Demographics:** Name, Age, Gender, Blood Type
- **Medical Information:** Medical Condition, Medication, Test Results
- **Admission Details:** Date_of_Admission, Admission_Type, Hospital, Doctor, Room_Number
- **Financial:** Billing_Amount, Insurance_Provider
- **Outcome:** Duration (in days)

## ⚙️ Workflow
1. **Data Loading & Cleaning** – Handle missing values, correct data types.
2. **Feature Engineering** – Date features, categorical encoding, scaling numeric data.
3. **Model Selection** – Baseline Linear Regression → Random Forest → XGBoost.
4. **Evaluation** – RMSE, MAE, R² Score.
5. **Feature Importance** – Identify top predictors affecting stay duration.

## 🛠️ Tech Stack
- **Python 3.9+**
- **Pandas / NumPy** – Data handling
- **Scikit-learn** – Machine learning
- **Matplotlib / Seaborn** – Visualization

## 🚀 How to Run
```bash
# Clone repo
git clone https://github.com/<your-username>/hospital-stay-duration.git
cd hospital-stay-duration

# Install dependencies
pip install -r requirements.txt

# Run notebook
jupyter notebook hospital_duration_prediction.ipynb
