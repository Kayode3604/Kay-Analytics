# Kay-Analytics
#  Prediction and Visualization of Student Academic Performance Using Machine Learning

##  Project Overview

This project applies machine learning techniques to analyse and predict university students' academic performance using real academic records. The objective is to uncover key performance patterns and develop predictive models that can support early intervention strategies within higher education institutions.

A total of **3,047+ student records** were analysed to identify trends across gender, academic programmes, and study levels.

---

##  Dataset Summary

- **Total Records:** 3,047+ university students  
- **Key Features:**
  - Gender
  - Programme
  - Study Level
  - CGPA (Cumulative Grade Point Average)
  - Academic progression indicators

---

##  Data Preprocessing & Cleaning

Comprehensive data preparation steps were carried out to ensure reliability:

- Removal of duplicate records  
- Outlier detection and treatment  
- Median imputation for missing values  
- Feature preparation for regression and classification modelling  

---

##  Exploratory Data Analysis (EDA)

Visualisations were used to uncover insights such as:

- Distribution of CGPA across students  
- Academic progression trends  
- Gender-based performance comparisons  
- Programme-level performance variations  

EDA findings informed feature engineering and model selection.

---

##  Machine Learning Models

###  Multiple Linear Regression — CGPA Prediction

**Objective:** Predict students' final CGPA  

**Performance Metrics:**
- R² = **0.897**  
- Explains nearly **90% of the variance** in academic performance  
- Evaluated using:
  - Mean Absolute Error (MAE)
  - Root Mean Square Error (RMSE)

---

### 2️ Logistic Regression — At-Risk Student Classification

**Objective:** Identify students at risk of low academic performance (CGPA < 2.5)

**Model Accuracy:** **96.7%**

**Evaluation Metrics:**
- Confusion Matrix
- Precision
- Recall

This model demonstrates strong capability for early detection of academically vulnerable students.

---

##  Key Insights

- Clear performance distribution patterns exist across study levels  
- Gender-based performance differences were observable  
- Academic progression trends strongly influence final CGPA  
- Predictive modelling can effectively support early intervention systems  

---

## Practical Recommendations

Universities can leverage these findings to:

- Implement early-warning systems  
- Design targeted academic support interventions  
- Improve retention strategies using predictive analytics  
- Monitor student progression using continuous performance modelling  

---

##  Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

##  How to Run the Project

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
