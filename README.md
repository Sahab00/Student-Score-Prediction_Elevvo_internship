# Student-Score-Prediction_Elevvo_internship

A machine learning project focused on predicting students' exam scores based on various academic and lifestyle factors.

---

##  Dataset
- **File Used:** `data_1.csv`
- Contains student-related features like hours studied, tutoring sessions, extracurricular activities, sleep hours, and more.

---

##  Libraries Used
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`


##  Workflow Overview

### 1. Data Preprocessing
- Encoded categorical features using `LabelEncoder`
- Dropped irrelevant or low-correlation columns
- Checked for missing values
- Removed outliers using IQR method (on `Hours_Studied`, `Tutoring_Sessions`, and `Exam_Score`)

### 2. Visualization
- Correlation bar plot to assess feature importance
- Boxplots to detect outliers

<img width="448" height="239" alt="image" src="https://github.com/user-attachments/assets/6dea4797-d25b-44c8-ba4a-28bf56fd9ce8" />

<img width="413" height="239" alt="image" src="https://github.com/user-attachments/assets/b6dbccf6-69f3-4c3d-9278-fc55024373df" />

### 3. Model Building
- Features were split into training and testing sets
- Trained using **Linear Regression**

### 4. Model Evaluation
- Performance metrics: **MAE**, **MSE**, and **RMSE**
- Scatter plots to visualize predicted vs actual exam scores

---

## 🌟 Bonus Work
- Performed feature selection based on correlation with the target
- Performed outlier removal for more accurate model results

---

## 📌 Covered Concepts
- Linear Regression
- Label Encoding
- Data Cleaning & Visualization
- Evaluation Metrics (MAE, MSE, RMSE)

---


