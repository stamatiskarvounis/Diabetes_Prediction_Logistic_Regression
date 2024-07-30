# Diabetes Prediction Model: Logistic Regression Analysis

This project focuses on building a binary logistic regression model to predict diabetes based on blood test results from an Iraqi university hospital in 2020. The dataset includes variables such as age, gender, urea, creatinine, cholesterol, triglycerides, and others. The goal was to diagnose diabetes by analyzing these variables and predicting the likelihood of a patient being diabetic.

# Key Steps and Methodology

## Exploratory Data Analysis (EDA):
- Conducted data cleaning and preprocessing, removing irrelevant fields and handling outliers.
- Transformed categorical variables into numerical formats for model compatibility.
- Utilized descriptive statistics and visualizations to understand data distributions and relationships.
- 
## Feature Engineering and Selection:
- Created new variables and converted continuous variables into categorical ones.
- Identified key features correlated with diabetes status using correlation analysis.
- 
## Model Building:
- Split the data into training and test sets.
- Developed logistic regression models using selected features (HbA1c, BMI, age, urea, cholesterol, and triglycerides).
- Evaluated model performance using accuracy, precision, recall, F1-score, and confusion matrices.

## Model Evaluation:
- Model 1, which included all selected features, outperformed Model 2, demonstrating better accuracy and lower rates of false positives and negatives.
- Testing on Prediabetic Cases:
- Applied the final model to cases labeled as prediabetic to estimate the probability of these cases being diabetic.

## Results and Findings:
The model provided accurate predictions, with a high probability (50.7%) of diagnosing prediabetic cases as diabetic, indicating its potential utility in clinical settings.

## Technologies and Tools Used
- Programming Language: Python
- Libraries: pandas, scikit-learn, matplotlib, seaborn
- Data Analysis and Visualization: Jupyter Notebook


The project highlights the effectiveness of logistic regression in medical diagnostics and provides a foundation for further enhancements, such as incorporating additional data or refining the model for better accuracy.
