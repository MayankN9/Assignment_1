# 🩺 Diabetes Prediction - Exploratory Data Analysis (EDA)

This project performs **Exploratory Data Analysis (EDA)** on the Pima Indian Diabetes dataset, which contains medical information of women and their diabetes diagnosis. The goal is to uncover factors most associated with diabetes.

---

## 📁 Dataset

- **File**: `diabetes.csv`
- **Source**: UCI Machine Learning Repository
- **Features**:
  - `Pregnancies`
  - `Glucose`
  - `BloodPressure`
  - `SkinThickness`
  - `Insulin`
  - `BMI`
  - `DiabetesPedigreeFunction`
  - `Age`
  - `Outcome` (0 = No Diabetes, 1 = Diabetes)

---

## 📊 EDA Steps

1. **Loading & Understanding the Dataset**
2. **Data Cleaning**
   - Replaced zero values in key columns with medians
3. **Univariate Analysis**
   - Histograms for all features
4. **Bivariate Analysis**
   - Boxplots to compare diabetic vs non-diabetic groups
5. **Correlation Matrix**
   - Heatmap of feature relationships
6. **Inferential Statistics**
   - t-tests to find statistically significant differences

---

## 🔍 Key Insights

- **Plasma Glucose** and **BMI** are the strongest indicators of diabetes.
- **Age**, **Pregnancies**, and **Insulin** also show statistically significant impact.
- Higher values in these features correlate with positive diabetes diagnoses.

---

## 📂 Files in this Repository

| File Name              | Description                              |
|------------------------|------------------------------------------|
| `diabetes.csv`         | Original dataset                         |
| `diabetes_eda.py`      | Python script performing full EDA        |
| `diabetes_cleaned.csv` | Cleaned dataset with invalids handled    |
| `hist_*.png`           | Histograms of individual features        |
| `boxplot_*.png`        | Boxplots comparing Outcome               |
| `correlation_heatmap.png` | Correlation heatmap of all features   |

---

## 📌 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/diabetes-eda.git
   cd diabetes-eda
