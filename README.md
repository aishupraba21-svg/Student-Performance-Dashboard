📊 Student Performance Analysis
📌 Project Overview

This project analyzes student performance based on various factors such as gender, degree category, and subject scores (Maths, Reading, Writing).
The goal is to uncover insights that help understand academic trends and performance patterns.

🎯 Objectives
Analyze total and average scores across subjects
Compare performance by gender
Evaluate performance across degree categories
Identify top-performing groups
Visualize key trends for better decision-making
📂 Dataset Information

The dataset includes the following columns:

Gender – Male / Female
Degree Category – UG / PG (or other categories)
Maths Score
Reading Score
Writing Score
🛠️ Tools & Technologies
Microsoft Power BI (Data Visualization)
Excel / CSV (Data Source)
DAX (Data Analysis Expressions)
📐 Key DAX Measures
🔹 Total Marks
Total Marks = 
SUMX(
    'StudentData',
    'StudentData'[Maths Score] +
    'StudentData'[Reading Score] +
    'StudentData'[Writing Score]
)
🔹 Average Marks
Average Marks = 
AVERAGE('StudentData'[Maths Score]) +
AVERAGE('StudentData'[Reading Score]) +
AVERAGE('StudentData'[Writing Score])
📊 Dashboard Features
Total Marks by Gender
Total Marks by Degree Category
Gender vs Degree Performance Matrix
Subject-wise Score Distribution
Average Performance Comparison
📈 Insights (Example)
Female students may perform better in reading and writing
Male students may show variation in maths scores
Certain degree categories outperform others overall
📷 Sample Visuals

<img src="images/student performances.png" width="600"/>

🚀 How to Use
Load dataset into Power BI
Create relationships (if needed)
Add DAX measures
Build visuals (charts, tables, slicers)
Analyze insights
📌 Conclusion

This analysis helps identify performance patterns and provides actionable insights for improving student outcomes.

🔗 Future Improvements
Add more features like parent education, test preparation
Include predictive analytics
Build automated reporting

If you want, I can customize this README specifically for:

GitHub upload (with badges & styling)
Your exact dataset columns
Portfolio-ready version to impress recruiters
