# 📌 Tracking Student Journey: Analyzing Retention and Graduation Rates




# 📌 Overview




This project focuses on analyzing student retention and graduation rates at the University of Connecticut (UConn). The primary goal is to identify key factors influencing student retention and provide data-driven recommendations to enhance student success. By leveraging machine learning, data visualization, and predictive analytics, the study aims to improve retention rates through actionable insights.

# 📊 Datasets Used



The study utilizes multiple datasets containing crucial student attributes related to retention and graduation outcomes. The Retention Dataset tracks student retention across various semesters, providing historical insights into student attrition. The GPA Dataset contains academic performance details, helping us assess how grades influence student retention. The Class-Taking Dataset records student enrollments and grades, offering a broader view of students' academic journeys. The 60-Second Survey Dataset captures qualitative factors such as students' academic confidence, stress levels, and extracurricular involvement, enabling us to analyze the impact of personal and institutional support systems.

# 🛠 Methodology


Our analysis follows the SEMMA (Sample, Explore, Modify, Model, and Assess) Process, ensuring a structured and comprehensive approach to data-driven decision-making. The methodology involves data collection, cleaning, exploratory analysis, machine learning modeling, and final business recommendations.

# 1️⃣ Data Collection & Preprocessing



Data collection and preprocessing involved merging multiple datasets using inner joins to create a single, comprehensive dataset. Given the presence of over 991,849 rows across datasets, redundancy was a key concern. To address this, the data was pivoted and aggregated based on unique student IDs, ensuring each record was unique while maintaining essential attributes. The groupby() function was used to aggregate duplicate records, and columns with over 30% missing values were removed to maintain data quality. Additional feature engineering techniques were applied, creating derived variables that enhanced the dataset's predictive capabilities.

# 2️⃣ Exploratory Data Analysis (EDA) 🔍



Exploratory Data Analysis was performed to identify trends, correlations, and key influencing factors in student retention. Using Seaborn, Matplotlib, and Power BI, we visualized the relationships between financial aid, student engagement, and academic performance. The findings indicated that students without Pell Grants exhibited a 42.73% dropout rate, highlighting the importance of financial aid in retention. Additionally, students engaged in clubs and organizations demonstrated a 64% retention rate, reinforcing the role of extracurricular involvement. Academic stress and confidence levels were also analyzed, revealing a strong correlation between low confidence and increased dropout rates, particularly in the Engineering and Business departments.

# 3️⃣ Machine Learning Models 🤖




To predict student retention, multiple machine learning models were implemented, including Logistic Regression, Random Forest, Decision Trees, and Gradient Boosting (XGBoost). The dataset was split into 80% training and 20% testing to ensure robust model evaluation. Feature scaling was applied to improve model performance. Among all models tested, Gradient Boosting (XGBoost) demonstrated the highest accuracy (88%), making it the final model selected for retention prediction. The Random Forest model performed slightly lower but was still effective, while Logistic Regression and Decision Trees exhibited lower predictive power.



# 💡 Key Insights


The analysis provided significant insights into the major factors influencing student retention. Pell Grants emerged as the most critical factor, with a 26.60% contribution to predictive power, emphasizing the need for financial aid programs. Extracurricular involvement played a substantial role, accounting for 12.74% of the retention rate, while academic confidence contributed 6.01%, demonstrating that student self-belief significantly impacts retention outcomes. Additionally, students enrolled in Engineering and Business programs showed lower retention rates, necessitating targeted interventions to support their academic success.

# 📈 Business Recommendations


To improve retention rates, universities must adopt strategic financial support initiatives, such as introducing on-campus work-study programs for students with Pell Grants. Academic support should be expanded by providing personalized mentorship programs and financial counseling to assist students facing financial burdens. Furthermore, universities should promote student engagement by allocating resources to clubs and organizations, offering incentives for participation, and integrating student involvement into career development programs. Lastly, targeted efforts should be made to enhance retention in high-risk departments like Engineering and Business, including mentorship programs, alumni guidance podcasts, and curriculum refinements.

# 📂 Files in the Repository


This repository contains key files that document the complete analysis and findings. The student_retention_analysis.ipynb file includes all Python scripts used for data preprocessing, model training, and evaluation. The student_retention_dashboard.pbix file contains the Power BI interactive dashboard for visualization. Additionally, the student_retention_presentation.pptx provides a comprehensive presentation of our findings and recommendations.

By leveraging data-driven insights, predictive modeling, and visualization techniques, this project provides a structured roadmap for UConn to enhance student retention and graduation success. 🚀
