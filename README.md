📌 Tracking Student Journey: Analyzing Retention and Graduation Rates



📌 Overview



This project aims to analyze student retention and graduation rates at the University of Connecticut (UConn) using data science, machine learning, and data visualization techniques. The goal is to identify key factors that influence student retention and provide data-driven recommendations to improve graduation rates.




📊 Datasets Used


The study involves multiple datasets containing key student attributes related to retention:

📁 Retention Dataset – Tracks student retention across semesters.



📊 GPA Dataset – Contains student academic performance details.



📚 Class Taking Dataset – Records student enrollments and grades.



📜 60-Second Survey Dataset – Captures students' academic confidence, stress, and engagement.



🛠 Methodology


Our approach follows the SEMMA (Sample, Explore, Modify, Model, and Assess) Process, ensuring structured analysis and reliable insights.

1️⃣ Data Collection & Preprocessing


 🔹Dataset Merging

🔹Combined all datasets using inner join to create a unified dataset.



🔹Used Pandas & NumPy for merging and cleaning data.



🔹 Handling Missing Values & Redundancy

🔹Applied groupby() to aggregate redundant records.


🔹Dropped highly null-value columns (>30%) to maintain data quality.


🔹 Feature Engineering

🔹 Removed unnecessary variables and created new derived features for better model performance.


2️⃣ Exploratory Data Analysis (EDA) 🔍


🔹We performed data visualization & pattern identification using Seaborn, Matplotlib, and Power BI.

🔹 Retention Rate vs Pell Grant 🎓

🔹Students without Pell Grants have lower retention rates (42.73%).


🔹Providing financial aid can significantly improve retention.


🔹 Retention Rate vs Student Engagement 🎭

🔹Students actively participating in clubs & organizations have a 64% retention rate, while non-participating students show a higher dropout rate.


🔹 Retention Rate vs Academic Performance 📖

🔹Low GPA & academic confidence correlates with higher attrition.


🔹Departments with high dropout rates include Engineering, Business, and Liberal Arts.


3️⃣ Machine Learning Models 🤖


🔹We implemented various predictive models to identify key retention factors.



🔹 Model Selection & Training

🔹Split the data: 80% Training & 20% Testing.


🔹Applied feature scaling for optimal model performance.


🔹 Algorithms Used

🔹Logistic Regression
🔹Random Forest
🔹Decision Trees
🔹Gradient Boosting (XGBoost) ✅ (Final Model)


🔹 Performance Metrics 📊

🔹Accuracy, Precision, Recall, and F1-score were used for model evaluation.

🔹XGBoost performed the best with an accuracy of 88%, making it the final model for retention prediction.







💡 Key Insights


📌 Financial aid (Pell Grants) and student engagement have the highest impact on retention.


📌 Business & Engineering students have lower retention rates compared to other departments.


📌 Academic stress and lack of confidence contribute significantly to student dropouts.





📈 Business Recommendations


🚀 Enhance Financial Support: Introduce work-study programs to help students sustain education expenses.


🚀 Encourage Student Participation: Increase club activities & extracurriculars to improve engagement.


🚀 Academic Support for At-Risk Departments: Strengthen mentoring and academic advising programs for struggling students.





📂 Files in the Repository


📌 student_retention_analysis.ipynb – Python script for data analysis & modeling.


📌 student_retention_dashboard.pbix – Power BI interactive dashboard.


📌 student_retention_presentation.pptx – Final project presentation.
