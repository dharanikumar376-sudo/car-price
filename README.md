# 🚗 Car Price Prediction — AIML Mini Project

**Student:** Dharani Kumar  
**Register No.:** 711524BCS036  
**Department:** CSE – Artificial Intelligence & Machine Learning  
**Academic Year:** 2024 – 2028  

---

## 🌐 Live Website

**➡️ [View Live Site](https://dharanikumar376-sudo.github.io/car-price/)**

---

## 📌 Project Overview

An AI-powered web application that predicts the selling price of used cars using Machine Learning. The system is trained on 1,428 real car records from the CarDekho platform and achieves **R² = 0.95** using XGBoost.

---

## 📊 Model Performance

| Model              | R² Score | RMSE (Lakhs) | MAE (Lakhs) |
|--------------------|----------|--------------|-------------|
| **XGBoost** ⭐     | **0.95** | **1.40**     | **0.97**    |
| Gradient Boosting  | 0.93     | 1.70         | 1.18        |
| Random Forest      | 0.91     | 1.90         | 1.31        |
| SVR                | 0.82     | 2.60         | 1.82        |
| Decision Tree      | 0.79     | 3.10         | 2.12        |
| Linear Regression  | 0.72     | 3.80         | 2.64        |

---

## 🔑 Top Features (XGBoost Importance)

1. Max Power — 31%
2. Engine CC — 24%
3. Year of Manufacture — 18%
4. KM Driven — 10%
5. Mileage — 7%

---

## 🛠️ Tech Stack

- **Language:** Python 3.10
- **ML Libraries:** Scikit-learn, XGBoost
- **Data:** Pandas, NumPy
- **Backend:** Flask REST API
- **Frontend:** HTML5, CSS3, Bootstrap 5
- **Dataset:** CarDekho (Kaggle) — 1,428 records

---

## 📁 Repository Structure

```
car-price/
├── index.html                        # Main website (frontend)
├── Car_Price_Prediction_Report.docx  # Full project report (12+ pages)
├── README.md                         # This file
```

---

## 🚀 How to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/dharanikumar376-sudo/car-price.git
   cd car-price
   ```

2. Open `index.html` directly in your browser — no server needed!

---

## 📄 Report

The full 12-page project report (`Car_Price_Prediction_Report.docx`) is included in this repository and covers:
- Abstract & Introduction
- Literature Survey
- Dataset Description
- Methodology & Preprocessing
- Model Building & Evaluation
- Results with charts
- Conclusion & Future Work
- References & Appendix

---

## 📊 Dataset

- **Source:** [CarDekho – Kaggle](https://www.kaggle.com/datasets/nehalbirla/vehicle-dataset-from-cardekho)
- **Records:** 1,428 used car listings
- **Features:** 13 (year, fuel, km driven, engine, max power, mileage, seats, etc.)

---

*AIML Mini Project · Department of CSE · 2024–2028*
