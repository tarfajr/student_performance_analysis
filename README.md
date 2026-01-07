# Student Performance Analysis 📊

# Project Overview
This project analyzes student academic performance using Python, SQLite, and data visualization techniques.  
The goal is to identify factors that influence students' total scores and demonstrate a complete data science workflow.

# Dataset Description
The dataset contains student-level academic information including:
- student_id
- weekly_self_study_hours
- attendence_percentage
- class_participation (Low, Medium, High)
- total_score
- grade (A, B, C, etc.)
  
# Tools & Technologies
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- SQLite
- Scikit-learn
- google colab Notebook
- Tableau (optional dashboard)
- Gamma AI (presentation)

# Data Cleaning
- Checked for missing values
- Ensured numeric columns were properly typed
- Encoded categorical variables when necessary
- Selected numeric columns for correlation analysis

# Exploratory Data Analysis (EDA)

# Key Insights
- Weekly self-study hours and attendance percentage show strong positive correlation with total_score.
- Students with higher class participation tend to achieve higher scores.
- Score distribution is slightly skewed towards higher performance levels.

# Visualizations
- Correlation heatmap
- Scatterplot: study hours vs total score
- Boxplot: class participation vs total score
- Histogram: total score distribution

# SQLite Storage
- Dataset stored in SQLite database: student_performance.db
- Table name: students
- Used for structured data storage and querying

Example query:
```sql
SELECT * FROM students LIMIT 5;
