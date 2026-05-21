# 🩺 Medical Data Visualizer

This project is part of the FreeCodeCamp Data Analysis with Python Certification.

The project analyzes medical examination data and visualizes relationships between health factors and cardiovascular disease using Python libraries like Pandas, Matplotlib, and Seaborn.

---

## 📌 Features

- Added an `overweight` column using BMI calculation
- Normalized cholesterol and glucose values
- Created categorical plots using Seaborn `catplot()`
- Cleaned incorrect medical data
- Generated a correlation heatmap
- Visualized health-related patterns in patients

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 📂 Dataset

The dataset contains medical examination records including:

- Age
- Height
- Weight
- Blood pressure
- Cholesterol
- Glucose
- Smoking habits
- Alcohol intake
- Physical activity
- Cardiovascular disease status

---

## 📊 Visualizations

### 1. Categorical Plot

Shows counts of good and bad health outcomes for:
- Cholesterol
- Glucose
- Smoking
- Alcohol consumption
- Physical activity
- Overweight status

Separated by:
- `cardio = 0`
- `cardio = 1`

---

### 2. Correlation Heatmap

Displays correlations between medical variables after cleaning invalid data.