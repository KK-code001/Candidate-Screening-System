AI-Driven Resume Screening Dataset (2026)
Project Overview
This project explores an AI-driven recruitment simulation using a synthetic dataset from Kaggle. The dataset represents a modern, 2026-era hiring process where automated systems evaluate candidates based on their resumes, skills, and professional backgrounds. The primary goal is to understand how these automated decisions are made and to identify the key factors that lead to a candidate being Selected or Rejected.

Dataset Features
The dataset provides a structured look at candidate profiles with the following key attributes:

Years of Experience: Total professional experience in years.

Education Level: Highest degree attained (Bachelors, Masters, PhD, etc.).

Skills Match Score (0–100): A percentage indicating how well the candidate's skills align with the job description.

Resume length (0–100): A score reflecting the overall quality and formatting of the resume as parsed by an AI.

Project count: How many relevant did candidate made.

Github activity: annual github contributions of a candidate.

AI Screening Result: The final decision made by the system (Selected or Rejected).

Project Objectives
1. Exploratory Data Analysis (EDA)
Perform statistical analysis to understand the average experience and scores of candidates.

Visualize the distribution of "Selected" vs. "Rejected" candidates across different industries.

Identify trends in salary expectations based on education level and job titles.

2. Data Visualization
Create Heatmaps to find correlations between "Skills Match Score" and the final selection.

Use Bar Charts to compare hiring rates across different industries.

Develop Box Plots to see how experience impacts salary expectations.

3. Basic Machine Learning
Clean and preprocess the data for modeling.

Implement a Logistic Regression or Decision Tree model to predict the AI Screening Result.

Evaluate the model's performance using accuracy scores and confusion matrices.

Technologies & Tools
Language: Python

Libraries: * Pandas for data manipulation.

NumPy for numerical operations.

Matplotlib & Seaborn for data visualization.

Scikit-Learn for basic machine learning.

Environment: Jupyter Notebook / Kaggle Kernels.

Future Plans (Advanced Enhancements)
Bias Detection: Investigate if the AI system shows any unconscious bias toward specific education levels or location types.

Advanced Modeling: Implement more robust algorithms like Random Forest or XGBoost to improve the precision of screening predictions.

Salary Regression: Build a regression model to accurately predict a candidate's salary expectation based on their specific skill set.

Feature Engineering: Create new features, such as a "Experience-to-Skill" ratio, to gain deeper insights into candidate potential.
