# Data-Analysis-on-UCONN-Student-Data
Tracking Student Journey: Analyzing Retention and Graduation Rates
University of Connecticut (UConn) Capstone Project

📌 Project Overview
The goal of this project is to analyze retention and graduation rates at UConn, identifying key factors that impact student success. By leveraging data analytics, machine learning models, and business intelligence tools, we aim to uncover actionable insights that can improve student retention strategies and enhance graduation rates.

🚀 Problem Statement
UConn, a globally recognized university, faces challenges in student retention and graduation rates. A declining retention rate negatively impacts university rankings, reputation, and student outcomes. This project investigates factors contributing to attrition and develops predictive models to help the institution enhance student engagement, provide targeted support, and improve overall retention rates.

📊 Data Sources & Preprocessing
The project utilized multiple datasets related to student performance, class participation, financial aid, and survey responses. The datasets were merged, cleaned, and preprocessed before analysis.

🗂️ Datasets Used
Student Retention Data - Historical retention trends and student demographics.
GPA Tracking Data - Academic performance trends and GPA progressions.
Class Participation Data - Records of class enrollments and attendance.
60-Second Survey Data - Student engagement and satisfaction survey.
Q-Center Sign-ins & LC Enrollment Data - Student tutoring participation and course enrollments.
🛠️ Data Preprocessing Steps
✔ Handled Missing Values - Columns with >30% missing values were dropped.
✔ Merged Data Using Inner Join - Combined datasets based on student IDs.
✔ Feature Engineering - Extracted new variables from existing datasets.
✔ Data Cleaning & Transformation - Applied groupby functions, pivot tables, and statistical methods.

🔍 Exploratory Data Analysis (EDA)
📌 Key Findings
Pell Grants & Retention: Students without Pell Grants exhibited lower retention rates.
Student Organization Participation: Active club participation increased retention by 64%.
Departmental Retention Trends: Engineering & Business programs showed low retention rates (17%).
Academic Confidence & Retention: Higher confidence correlated with higher retention rates.
🤖 Machine Learning Models
We applied various classification models to predict student retention based on key features.

📈 Model Comparison & Performance
Model	Accuracy	Precision	Recall	F1 Score	Misclassification Rate
Logistic Regression	70%	70%	88%	78%	30%
Decision Tree	77%	81%	81%	81%	23%
Random Forest	85%	89%	88%	88%	15%
Gradient Boosting (XGBoost) 🏆	88%	93%	86%	89%	12%
✅ Final Model: Gradient Boosting (XGBoost)

Achieved the best overall performance across accuracy, precision, recall, and F1-score.
Selected as the final model for predicting student retention.
📌 Feature Importance
The top contributing factors to student retention were:

1️⃣ Pell Grant (26.6%) - Financial aid is the strongest predictor of retention.
2️⃣ Student Organization Participation (12.7%) - Engagement in extracurriculars significantly boosts retention.
3️⃣ Academic Confidence (6.0%) - Students with high confidence levels had a greater likelihood of persisting.

📊 Power BI Dashboard
A fully interactive Power BI dashboard was developed to present key insights, allowing stakeholders to:

Analyze retention trends by Pell Grants, Student Engagement, Academic Confidence, and Departments.
Identify high-risk student groups for targeted interventions.
Monitor real-time student retention statistics.
📢 Business Recommendations
Based on data-driven insights, we propose the following recommendations:

1️⃣ Financial Support & Assistance
✔ Introduce on-campus employment programs for Pell Grant students.
✔ Provide financial literacy workshops & counseling to reduce student stress.

2️⃣ Student Engagement & Retention Strategies
✔ Increase funding for student clubs & extracurriculars.
✔ Implement incentives for student involvement in university organizations.

3️⃣ Departmental Focus & Academic Support
✔ Prioritize retention efforts in Engineering, Business, ACES, and Social Work programs.
✔ Launch mentorship initiatives featuring successful alumni speakers.
