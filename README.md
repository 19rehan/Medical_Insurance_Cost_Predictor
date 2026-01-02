# 🏥 Medical Insurance Cost Prediction (ML Project)

This project is a complete end-to-end Data Science pipeline designed to predict medical insurance premiums. It focuses on data quality, statistical normalization, and fairness auditing before training a **Linear Regression** model.

## 🎯 Project Highlights
* **Accuracy:** Achieved an **80% $R^2$ Score**, meaning the model explains 80% of the variance in insurance costs [cite: 2026-01-01].
* **Reliability:** Applied **Log Transformation** to handle skewed data and ensure the model learns effectively [cite: 2026-01-01].
* **Fairness:** Conducted a bias audit to ensure the model treats all genders and regions equally [cite: 2026-01-01].

## 🛠️ Data Science Workflow

### 1. Data Cleaning & Logic
* **Negative Value Correction:** Identified and removed logically impossible data (e.g., negative children counts) to maintain data integrity [cite: 2026-01-01].
* **Outlier Strategy:** Analyzed BMI and Age outliers and decided to keep them as they represent real-world medical risks rather than errors [cite: 2026-01-01].

### 2. Feature Engineering
* **Log Transformation:** Used `np.log1p` on the `charges` column to create a **Normal Distribution**, which is critical for Linear Regression success [cite: 2026-01-01].
* **One-Hot Encoding:** Transformed categorical variables like `sex`, `smoker`, and `region` into binary numbers for mathematical processing [cite: 2026-01-01].

### 3. Model Training & Evaluation
* **Train-Test Split:** Used an 80/20 split to ensure the model was tested on "unseen" data for real-world reliability [cite: 2026-01-01].
* **R-squared Score:** 0.80 [cite: 2026-01-01].
* **Mean Absolute Error (MAE):** 0.26 (Log scale) [cite: 2026-01-01].

## 🚀 Deployment Strategy
This project is built using free, open-source tools [cite: 2025-12-27]. The final model is saved as a `.pkl` file, ready to be deployed on:
* **AWS** / **GCP** / **Azure** [cite: 2025-12-21].

---
🔗 **Github Repository:** [Insert Your Repo Link Here]
