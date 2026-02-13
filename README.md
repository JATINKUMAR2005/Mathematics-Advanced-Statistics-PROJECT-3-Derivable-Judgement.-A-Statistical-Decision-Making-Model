# 📊 Statistical Data Analysis & Hypothesis Testing using Python

## 📌 Project Overview
This project focuses on applying **inferential statistics, hypothesis testing, and data analysis techniques** using Python on a healthcare-related dataset. The objective is to analyze relationships between health indicators such as age, BMI, smoking habits, glucose levels, and disease conditions (e.g., diabetes, hypertension) and to interpret results using statistical tests and visualizations.

The project is divided into two major parts:
- **Part A:** Theoretical foundation of statistical concepts
- **Part B:** Practical data analysis and hypothesis testing using Python

---

## 🎯 Objectives
- Understand and apply inferential statistics concepts
- Formulate and test statistical hypotheses
- Calculate confidence intervals and interpret results
- Perform statistical tests such as t-test, z-test, chi-square test, and ANOVA
- Analyze relationships using covariance and correlation
- Visualize statistical findings using graphs
- Draw meaningful conclusions from data

---

## 🧾 Dataset Description
The dataset represents synthetic health records and contains the following key attributes:

| Column Name | Description |
|------------|-------------|
| record_id | Unique identifier for each record |
| age | Age of the individual |
| age_group | Age category (18–25, 26–35, etc.) |
| weight | Weight of the individual |
| gender | Gender (Male, Female, Other) |
| region | Geographic region |
| smoking_status | Smoking habit |
| bmi | Body Mass Index |
| blood_pressure | Systolic blood pressure |
| glucose_level | Fasting glucose level |
| cholesterol_level | Cholesterol level |
| diabetes | Diabetes status (True/False) |
| hypertension | Hypertension status (True/False) |
| visit_date | Date of medical visit |

---

## 🛠️ Tools & Technologies Used
- **Python 3**
- **Jupyter Notebook**
- **Libraries:**
  - NumPy
  - Pandas
  - SciPy
  - Matplotlib
  - Seaborn

---

## 📘 Part A – Theoretical Foundation
This section covers short notes and explanations of key statistical concepts:
- Inferential Statistics
- Hypothesis Testing
- Confidence Interval & Critical Value
- p-value
- Type I and Type II Errors
- z-test, t-test, Chi-square test, ANOVA
- Covariance
- Correlation

These concepts form the theoretical basis for the practical analysis performed in Part B.

---

## 📗 Part B – Data Analysis & Testing Tasks

### 1️⃣ Hypothesis Formulation
- **H₀:** Smoking has no effect on diabetes prevalence  
- **H₁:** Smoking affects diabetes prevalence  

Additional hypotheses are formulated to compare BMI, age groups, and disease conditions.

---

### 2️⃣ Confidence Interval Calculation
Confidence intervals are calculated for numerical variables such as age and BMI to estimate population parameters with a defined confidence level (95%).

---

### 3️⃣ Critical Value & p-value
Critical values and p-values are computed to determine the statistical significance of test results and to decide whether to reject or fail to reject the null hypothesis.

---

### 4️⃣ Mean Comparison Tests (z-test / t-test)
- Used to compare mean BMI between diabetic and non-diabetic groups
- Selection of test depends on sample size and variance assumptions

---

### 5️⃣ Chi-Square Test of Independence
- Applied to categorical variables such as smoking status and diabetes
- Determines whether a significant association exists between variables

---

### 6️⃣ ANOVA Test
- Used to check whether glucose levels significantly differ across age groups
- Helps identify variations among more than two groups

---

### 7️⃣ Covariance & Correlation Analysis
- Covariance measures the direction of relationship between age and BMI
- Correlation quantifies the strength and direction of the relationship

---

### 8️⃣ Data Visualization
The following statistical graphs are used:
- Histogram (Age distribution)
- Box plots (BMI vs Diabetes, Glucose vs Age Groups)
- Count plots (Smoking vs Diabetes)
- Scatter plots (Age vs BMI)
- Regression plots (Correlation analysis)
- Heatmap (Correlation matrix)

Visualizations support statistical findings and improve interpretability.

---

## 📊 Results & Interpretation
- Statistical tests indicate significant relationships between certain health indicators
- BMI and diabetes show meaningful differences
- Smoking status demonstrates association with diabetes prevalence
- Age and BMI show a positive correlation
- Graphical analysis supports hypothesis test results

Each test includes a clear **Accept/Reject H₀** decision based on p-values.

---

## ✅ Conclusion
This project successfully demonstrates the application of statistical methods to real-world health data. By combining theory, computation, and visualization, it provides a structured approach to data-driven decision-making and statistical inference.

---

## 🚀 How to Run the Project
1. Clone the repository
2. Ensure the dataset CSV file is in the project directory
3. Open the Jupyter Notebook
4. Run cells sequentially from top to bottom

---

## 📌 Future Enhancements
- Add regression analysis
- Include machine learning models for prediction
- Expand dataset with real-world data
- Automate report generation

---

## 👨‍💻 Author
**Jatin.K**  
Data Analysis | Statistics | Machine Learning Enthusiast  

---

## 📝 License
This project is for **educational and academic use only**.
