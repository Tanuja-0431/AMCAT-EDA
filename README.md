# AMCAT-EDA
# Project Overview

This project aims to perform Exploratory Data Analysis (EDA) on a dataset containing employment outcomes of engineering graduates, focusing on analyzing and visualizing key trends and patterns related to salary, gender, and specialization. The primary goal is to discover insights that can guide business decisions and better understand the factors influencing salary outcomes for fresh graduates.

## Key Objectives

*   Conduct data cleaning and manipulation to prepare the dataset for analysis.
*   Perform univariate and bivariate analysis to identify patterns in the dataset.
*   Test hypotheses related to gender, specialization, and salary.
*   Provide actionable insights and conclusions based on the findings.
*   Summarize key research questions and results.

# Dataset

The dataset used in this project includes the following key features:

*   Salary: The salary of fresh graduates.
*   Gender: The gender of the graduates.
*   Specialization: The academic specialization of the graduates.
*   10percentage, 12percentage: The percentages obtained in 10th and 12th grades.
*   collegeGPA: College grade point average.
*   GraduationYear: Year of graduation.
*   Various skill scores: Scores in English, Logical, Quantitative, Domain-specific knowledge, and technical fields such as Computer Science and Mechanical Engineering.

# Project Structure

The project is structured as follows:

1.  **Data Collection:** The dataset is collected from a reliable source (Aspiring Minds) and loaded into a Jupyter Notebook.
2.  **Data Cleaning:** Handling missing values, removing irrelevant columns or duplicate rows, normalizing categorical columns and handling outliers in numerical columns.
3.  **Data Exploration :**
    *   Univariate Analysis: Distribution of individual features such as salary, GPA, gender, and more.
    *   Bivariate Analysis: Exploring relationships between variables, such as salary and specialization or gender and salary.
    *   Outlier Detection: Identifying and handling outliers using box plots and histograms.
  
4.  **Conclusions:** Summarizing the key insights and recommendations based on the analysis.
5.    additional model development too , using SHAP and save the model 

# Research Questions

The following research questions will guide our analysis:

1.  Does the preference for specialization vary based on gender?
2.  Is there a significant relationship between GPA and salary?
3.  What are the factors most correlated with higher salaries for fresh graduates?

# Technical Stack

The technical stack used in this project includes:

*   Python 3.x
*   Pandas for data manipulation
*   Matplotlib & Seaborn for data visualization
*   Jupyter Notebook for interactive analysis

# Visualizations

Various visualizations were used to uncover insights:

*   Histograms to observe distributions of numerical data like salary
*   Box plots to compare salary distributions by gender and specialization
*   Count plots to visualize the distribution of categorical variables
*   Pair plots to explore relationships between numerical variables
