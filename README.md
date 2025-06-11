# HR-Churn-Prediction-using-Machine-Learning

🔍 Objective This project aims to build a machine learning-based system to predict employee churn in a company. By analyzing historical HR data, the model helps identify key factors driving attrition and enables HR teams to implement targeted retention strategies.

📁 Dataset Overview Source: HR_comma_sep.csv

Records: 14,999 employee entries

Features: Satisfaction level, last evaluation score, number of projects, average monthly hours, promotion status, department, and more

Target: left (binary indicator of whether an employee left the organization)

⚙️ Technologies Used Languages & Libraries: Python, Pandas, NumPy, Matplotlib, Seaborn, scikit-learn

Models: Logistic Regression, Random Forest Classifier

Evaluation Metrics: Accuracy, ROC-AUC, Confusion Matrix, Feature Importance

🧠 Key Steps in the Workflow Data Cleaning & Exploration:

Checked for missing values, duplicates, and outliers

Explored satisfaction levels, workload, and promotion trends among churned employees

Feature Engineering:

Encoded categorical variables

Created new variables from evaluation metrics

Model Building & Evaluation:

Built baseline Logistic Regression and Random Forest models

Used train-test split and cross-validation

Evaluated using ROC-AUC and confusion matrix

Interpretation:

Identified top predictors: low satisfaction, high workload, and lack of promotion

Translated results into actionable insights for HR planning

📊 Key Insights Employees with low satisfaction and high average monthly hours are most likely to leave

Promotion in the last 5 years significantly reduces churn risk

Random Forest outperformed Logistic Regression with an accuracy of 89%

📈 Business Impact This project empowers HR teams to:

Forecast attrition risks

Focus retention programs on at-risk employee groups

Optimize workforce planning through data-backed strategies

📌 Next Steps Deploy the model as a dashboard using Streamlit or Flask

Integrate with real-time HR systems for live attrition monitoring

Expand analysis to include qualitative exit interview feedback
