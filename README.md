**Cardiac Arrest Data Analysis (Heart Disease Detection)**  
This project involves exploratory data analysis (EDA) on a cardiac arrest dataset to uncover patterns and insights related to heart disease. The goal is to understand which features are most associated with heart disease, using visualization and statistical techniques. 

Dataset Overview  
* Total Records: 1,025  
* Features: 14 (including target variable)  
* Target Variable: target  
   1. indicates presence of heart disease
   2. 0 indicates absence of heart disease
  
Key Features:  

  | Feature    | Description                                 |
| ---------- | ------------------------------------------- |
| `age`      | Age of the patient                          |
| `sex`      | Gender (0 = Female, 1 = Male)               |
| `cp`       | Chest pain type                             |
| `trestbps` | Resting blood pressure                      |
| `chol`     | Serum cholesterol in mg/dl                  |
| `fbs`      | Fasting blood sugar > 120 mg/dl             |
| `restecg`  | Resting ECG results                         |
| `thalach`  | Max heart rate achieved                     |
| `exang`    | Exercise induced angina                     |
| `oldpeak`  | ST depression after exercise                |
| `slope`    | Slope of the ST segment                     |
| `ca`       | No. of major vessels colored by fluoroscopy |
| `thal`     | Thalassemia type                            |  

**📊 Analysis Performed**  
Basic Statistical Analysis:  
* Central tendency (mean, median)
* Outlier detection
* No missing values found

Visualizations:
* Distribution Plots: Age, Cholesterol, Max Heart Rate
* Correlation Heatmap: Relationships among features
* Boxplots & Countplots: Compare values across target (heart disease presence)

Key Insights  
* Max Heart Rate (thalach) shows strong negative correlation with heart disease.
* Chest Pain Type (cp) positively correlates with heart disease risk.
* Exercise-Induced Angina (exang) is a strong risk factor.
* Cholesterol has a wide range and noticeable outliers.

Technologies Used:Python,Pandas,Matplotlib,Seaborn,Google Colab (Jupyter Notebook)  















