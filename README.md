# Student Performance Analysis

## About the Project

This project analyzes student performance data to understand how different academic and personal factors are associated with exam scores.

The analysis was performed using Python and focuses on data cleaning, exploratory data analysis, and visualization.

## Dataset

The project uses the Student Performance Factors dataset from Kaggle.

The dataset contains information about students such as:
- Hours Studied
- Attendance
- Previous Scores
- Motivation Level
- Parental Involvement
- Access to Resources
- Teacher Quality
- Tutoring Sessions
- Exam Score

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

## Data Cleaning

Missing values in categorical columns were handled using the mode.

One exam score of 101 was identified as a data-quality issue and excluded from score-based analysis.

## Exploratory Data Analysis

The project explores:

- Attendance vs Exam Score
- Hours Studied vs Exam Score
- Motivation Level vs Exam Score
- Parental Involvement vs Exam Score
- Access to Resources vs Exam Score
- Teacher Quality vs Exam Score
- Correlation between numerical features
- Distribution of Exam Scores

## Key Findings

- Attendance showed the strongest linear relationship with Exam Score among the numerical features, with a correlation of approximately 0.58.
- Hours Studied showed a moderate positive correlation with Exam Score of approximately 0.45.
- Students with higher parental involvement had slightly higher average exam scores.
- Higher access to resources was associated with slightly higher average exam scores.
- Most exam scores were concentrated around the mid-to-high 60s.

## Conclusion

The analysis suggests that factors such as attendance and hours studied have noticeable associations with exam performance in this dataset. However, these relationships do not establish causation.

This project was created as a beginner-level data analysis project to practice Python, Pandas, NumPy, and data visualization.

## Project Notebook

The complete analysis and visualizations are available in the Jupyter Notebook included in this repository.
