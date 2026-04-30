# ✈️ Turbofan Engine RUL Prediction (Predictive Maintenance)

## 📌 Problem Statement

Predict the **Remaining Useful Life (RUL)** of turbofan engines using sensor data.  
This helps enable **predictive maintenance** and reduces unexpected failures.

---

## 📊 Dataset

- NASA Turbofan Engine Degradation Dataset (C-MAPSS)
- Includes multiple operating conditions and fault modes

---

## ⚙️ Project Pipeline

1. Data Loading & Cleaning
2. Feature Engineering
3. RUL Calculation
4. Model Training
5. Model Evaluation

---

## 🤖 Models Used

- Random Forest (Basic & Full Data)
- Neural Network (ANN)
- Convolutional Neural Network (CNN)

---

## 🏆 Best Model

**CNN Model**

- Captures temporal patterns in sensor data
- Achieves best performance among all models

---

## 📁 Project Structure

.
├── RUL_RF_Basic.ipynb
├── RUL_RF_FullData.ipynb
├── RUL_NN_FullData.ipynb
├── RUL_CNN_Final.ipynb
├── README.md
└── .gitignore

---

## 🚀 How to Run

```bash
pip install -r requirements.txt
jupyter notebook
```
