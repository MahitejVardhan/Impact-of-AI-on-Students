Impact of AI on Students — Data Analytics Project
Project Overview

Artificial Intelligence has become an increasingly important component of students' academic activities. From assignment assistance and debugging support to concept learning and research, AI tools are influencing learning behaviors and study patterns.

This project analyzes the relationship between AI usage and its impact on:

Academic performance
Study behavior
AI dependency
Mental well-being
Knowledge retention

The analysis was conducted using Exploratory Data Analysis (EDA), feature engineering, and dashboard storytelling techniques to understand whether AI acts as a learning support system or replaces traditional learning practices.

Problem Statement

As AI adoption continues to increase among students, several important questions arise:

Does AI improve academic performance?
Does increased AI usage reduce traditional study habits?
Are students becoming dependent on AI tools?
Does dependency contribute to burnout?
Does AI influence long-term knowledge retention?

This project attempts to answer these questions through a data-driven analytical approach.

Dataset

Dataset Source:
Kaggle Dataset: AI Impact on Students

Dataset Link:
https://www.kaggle.com/datasets/laveshjadon/ai-impact-on-students

Dataset Information
Total Records: 50,000
Total Features: 16
Main Variables
Major_Category
Weekly_GenAI_Hours
Pre_Semester_GPA
Post_Semester_GPA
Traditional_Study_Hours
Perceived_AI_Dependency
Skill_Retention_Score
Burnout_Risk_Level
Prompt_Engineering_Skill
Primary_Use_Case
Objectives
AI Adoption
Identify which student groups use AI the most
Understand major use cases of AI
Academic Performance
Evaluate whether AI improves GPA
Measure changes in GPA after AI usage
Study Habits
Analyze the impact of AI on traditional study behavior
Determine whether AI acts as a supplement or replacement
Mental Well-being
Examine the relationship between AI dependency and burnout
Learning Outcomes
Assess the impact of AI on skill retention
Project Workflow
1. Data Cleaning

Tasks performed:

Removed unnecessary variables
Handled missing values
Treated outliers
Verified data consistency
2. Feature Engineering

Created additional variables for analysis:

GPA Change
GPA_Change = Post_Semester_GPA - Pre_Semester_GPA
AI Usage Categories
Low
Moderate
High
Extreme
3. Exploratory Data Analysis (EDA)

Analysis included:

Distribution Analysis
Correlation Analysis
Group-wise Analysis
Relationship Analysis
Comparative Analysis

<img width="2000" height="1100" alt="newplot (2)" src="https://github.com/user-attachments/assets/dbe537d8-068f-4d5f-aca8-051c058038c7" />


4. Dashboard Development

An interactive dashboard was developed using a storytelling approach:

AI Adoption → Study Behavior → Academic Performance → Mental Health

Dashboard Components:

KPI Cards
Major-wise AI Usage
GPA Comparison
GPA Change Distribution
AI vs Traditional Study Relationship
Primary AI Use Cases
Burnout Analysis
Skill Retention Analysis
Key Findings
AI Usage

Students spend an average of approximately 8.43 hours per week using AI tools.

Academic Performance

Average GPA showed a positive increase after AI adoption.

Major Analysis

Students from STEM disciplines demonstrated the highest AI usage.

Study Behavior

Higher AI usage showed a tendency toward reduced traditional study hours.

AI Dependency

Students displayed moderate levels of dependency on AI tools.

Burnout Risk

Higher AI dependency appeared to be associated with increased burnout levels.

Skill Retention

Students maintained relatively strong skill retention scores despite AI usage.

Primary AI Use Cases

Students mainly used AI for:

Debugging and Troubleshooting
Copywriting and Drafting
Idea Generation
Summarization
Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Plotly
Jupyter Notebook
Dashboard Preview

Add your dashboard image inside the repository and use:

![Dashboard](Dashboard/dashboard.png)
Repository Structure
Impact-of-AI-on-Students/

├── Dataset/
│   └── ai_impact_students.csv
│
├── Notebook/
│   └── AI_Impact_Analysis.ipynb
│
├── Dashboard/
│   └── dashboard.png
│
├── README.md
│
└── requirements.txt
Future Scope

Potential future improvements include:

Building predictive models for burnout risk
Developing classification models
Performing student segmentation through clustering
Deploying the dashboard as an interactive web application

Author

Bantaram Mahitej Vardhan


Feedback and suggestions are welcome.
